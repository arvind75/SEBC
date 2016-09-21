**curl  --insecure -u arvind75:cloudera "http://172.31.3.236:7180/api/v12/clusters/arvind75/services/hive/"
///
{
  "name" : "hive",
  "type" : "HIVE",
  "clusterRef" : {
    "clusterName" : "cluster"
  },
  "serviceUrl" : "http://ip-172-31-3-236.us-west-2.compute.internal:7180/cmf/serviceRedirect/hive",
  "roleInstancesUrl" : "http://ip-172-31-3-236.us-west-2.compute.internal:7180/cmf/serviceRedirect/hive/instances",
  "serviceState" : "STARTED",
  "healthSummary" : "GOOD",
  "healthChecks" : [ {
    "name" : "HIVE_HIVEMETASTORES_HEALTHY",
    "summary" : "GOOD",
    "suppressed" : false
  }, {
    "name" : "HIVE_HIVESERVER2S_HEALTHY",
    "summary" : "GOOD",
    "suppressed" : false
  }, {
    "name" : "HIVE_WEBHCATS_HEALTHY",
    "summary" : "GOOD",
    "suppressed" : false
  } ],
  "configStalenessStatus" : "FRESH",
  "clientConfigStalenessStatus" : "FRESH",
  "maintenanceMode" : false,
  "maintenanceOwners" : [ ],
  "displayName" : "Hive",
  "entityStatus" : "GOOD_HEALTH"

///

** curl  -X POST -u arvind75:cloudera "http://172.31.3.236:7180/api/v12/clusters/arvind75/services/hive/commands/stop"
///
{
  "id" : 579,
  "name" : "Stop",
  "startTime" : "2016-09-21T19:51:44.463Z",
  "active" : true,
  "serviceRef" : {
    "clusterName" : "cluster",
    "serviceName" : "hive"
  }
}
///

** curl  -X POST -u arvind75:cloudera "http://172.31.3.236:7180/api/v12/clusters/arvind75/services/hive/commands/start"
///
{
  "id" : 585,
  "name" : "Start",
  "startTime" : "2016-09-21T19:52:53.339Z",
  "active" : true,
  "serviceRef" : {
    "clusterName" : "cluster",
    "serviceName" : "hive"
  }
///