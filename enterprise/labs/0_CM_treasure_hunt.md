* 1) Ubertask is for small jobs that you want to run locally and not to distribute it to the cluster
* 2) All the place where we integrate the service with LDAP for external authentication - HUE, Navigator, CM, Kerberos Administration in CM
* 3) All (HIVE, HDFS, YARN, HUE, IMPALA, HBASE, OOZIE)
* 4) CM Agents are upgraded when cloudera manager is upgraded.
* 5) select total_cpu_user_rate_across_hue_servers + total_cpu_system_rate_across_hue_servers 
* 6) HIVESERVER2, HIVEMETASTORE,WEBHAT SERVER, GATEWAY
* 7) Before integrating with Kerberos, 
** Set up a working KDC. Cloudera Manager supports MIT KDC and Active Directory.
** The KDC should be configured to have non-zero ticket lifetime and renewal lifetime. CDH will not work properly if tickets are not renewable.
** OpenLdap client libraries should be installed on the Cloudera Manager Server host if you want to use Active Directory. Also, Kerberos client libraries should be installed on ALL hosts.
** Cloudera Manager needs an account that has permissions to create other accounts in the KDC.