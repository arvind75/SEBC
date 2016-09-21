<p>/etc/default >curl  --insecure -u arvind75:cloudera "http://172.31.3.236:7180/api/v2/cm/deployment"
{
  "timestamp" : "2016-09-21T17:32:18.631Z",
  "clusters" : [ {
    "name" : "arvind75",
    "version" : "CDH5",
    "services" : [ {
      "name" : "hive",
      "type" : "HIVE",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "HIVEMETASTORE",
          "items" : [ {
            "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "hive<em>metastore</em>java<em>heapsize",
            "value" : "1521483776"
          }, {
            "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          } ]
        }, {
          "roleType" : "HIVESERVER2",
          "items" : [ {
            "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "hiveserver2<em>downloaded</em>resources<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "hiveserver2</em>exec<em>local</em>scratch<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "hiveserver2</em>java<em>heapsize",
            "value" : "2485125120"
          }, {
            "name" : "hiveserver2</em>spark<em>driver</em>memory",
            "value" : "966367641"
          }, {
            "name" : "hiveserver2<em>spark</em>executor<em>cores",
            "value" : "4"
          }, {
            "name" : "hiveserver2</em>spark<em>executor</em>memory",
            "value" : "2746063257"
          }, {
            "name" : "hiveserver2<em>spark</em>yarn<em>driver</em>memory<em>overhead",
            "value" : "102"
          }, {
            "name" : "hiveserver2</em>spark<em>yarn</em>executor<em>memory</em>overhead",
            "value" : "462"
          }, {
            "name" : "log<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          } ]
        }, {
          "roleType" : "WEBHCAT",
          "items" : [ {
            "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          } ]
        } ],
        "items" : [ {
          "name" : "hive<em>metastore</em>database<em>host",
          "value" : "ip-172-31-3-236.us-west-2.compute.internal"
        }, {
          "name" : "hive</em>metastore<em>database</em>name",
          "value" : "hive"
        }, {
          "name" : "hive<em>metastore</em>database<em>password",
          "value" : "hive</em>password"
        }, {
          "name" : "mapreduce<em>yarn</em>service",
          "value" : "yarn"
        }, {
          "name" : "zookeeper<em>service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "hive-GATEWAY-00e6ad869b94416fda600601ca9a26a3",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-1b85fee9b91287fbb726bb23bd20fb9e",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "i-0cdec7e9fd3c6d7a2"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-20465ca0226a76231505957a301a8e07",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "i-07d8b09bd07f7c4fe"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-23106fb589586818a37e9c07eb3233d1",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "i-0e787aefb35b3b594"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-4068bedd0a784c6e1f05b8e1dcf989b2",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "i-06bb02d87a313ec25"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-GATEWAY-f90b2f5a95253112e45830cab6f6a631",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "i-06227a5eda43d6c09"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hive-HIVEMETASTORE-00e6ad869b94416fda600601ca9a26a3",
        "type" : "HIVEMETASTORE",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "ep47wqagmdcwhwfet0rou8mps"
          } ]
        }
      }, {
        "name" : "hive-HIVESERVER2-00e6ad869b94416fda600601ca9a26a3",
        "type" : "HIVESERVER2",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "6oom749wnaonezdtj3zg7jnrd"
          } ]
        }
      }, {
        "name" : "hive-HIVESERVER2-23106fb589586818a37e9c07eb3233d1",
        "type" : "HIVESERVER2",
        "hostRef" : {
          "hostId" : "i-0e787aefb35b3b594"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "an0uajl6alin7j5sfc0yml4yw"
          } ]
        }
      }, {
        "name" : "hive-WEBHCAT-00e6ad869b94416fda600601ca9a26a3",
        "type" : "WEBHCAT",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ {
            "name" : "hive</em>webhcat<em>secret</em>key",
            "value" : "qd8t7owD01BNEfhIVOq7I5QVcOj30J"
          }, {
            "name" : "role<em>jceks</em>password",
            "value" : "42ejc23ia0bg1c473u1c427cx"
          } ]
        }
      } ],
      "displayName" : "Hive"
    }, {
      "name" : "zookeeper",
      "type" : "ZOOKEEPER",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "SERVER",
          "items" : [ {
            "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "zookeeper</em>server<em>data</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "zookeeper<em>server</em>data<em>log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "zookeeper<em>server</em>java<em>heapsize",
            "value" : "1006632960"
          } ]
        } ],
        "items" : [ ]
      },
      "roles" : [ {
        "name" : "zookeeper-SERVER-00e6ad869b94416fda600601ca9a26a3",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "8578njtospg5l6h5s25wm4rpq"
          }, {
            "name" : "serverId",
            "value" : "2"
          } ]
        }
      }, {
        "name" : "zookeeper-SERVER-20465ca0226a76231505957a301a8e07",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "i-07d8b09bd07f7c4fe"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "87cep0mrqr2sooarrsyeccxl6"
          }, {
            "name" : "serverId",
            "value" : "3"
          } ]
        }
      }, {
        "name" : "zookeeper-SERVER-4068bedd0a784c6e1f05b8e1dcf989b2",
        "type" : "SERVER",
        "hostRef" : {
          "hostId" : "i-06bb02d87a313ec25"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "1ulgc5jxcp30fe9uuediln70n"
          }, {
            "name" : "serverId",
            "value" : "1"
          } ]
        }
      } ],
      "displayName" : "ZooKeeper"
    }, {
      "name" : "hue",
      "type" : "HUE",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "HUE</em>LOAD<em>BALANCER",
          "items" : [ {
            "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          } ]
        }, {
          "roleType" : "HUE<em>SERVER",
          "items" : [ {
            "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          } ]
        }, {
          "roleType" : "KT<em>RENEWER",
          "items" : [ {
            "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          } ]
        } ],
        "items" : [ {
          "name" : "database<em>host",
          "value" : "ip-172-31-3-236.us-west-2.compute.internal"
        }, {
          "name" : "database</em>password",
          "value" : "hue<em>password"
        }, {
          "name" : "database</em>type",
          "value" : "mysql"
        }, {
          "name" : "hive<em>service",
          "value" : "hive"
        }, {
          "name" : "hue</em>webhdfs",
          "value" : "hdfs-HTTPFS-20465ca0226a76231505957a301a8e07"
        }, {
          "name" : "oozie<em>service",
          "value" : "oozie"
        }, {
          "name" : "zookeeper</em>service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "hue-HUE<em>SERVER-00e6ad869b94416fda600601ca9a26a3",
        "type" : "HUE</em>SERVER",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ {
            "name" : "role<em>jceks</em>password",
            "value" : "ef9ng53bwdxgly9fghfonjjjf"
          }, {
            "name" : "secret<em>key",
            "value" : "150h67tehuxDYHyN0Uuxhf6POvDlL4"
          } ]
        }
      } ],
      "displayName" : "Hue"
    }, {
      "name" : "oozie",
      "type" : "OOZIE",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "OOZIE</em>SERVER",
          "items" : [ {
            "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "oozie</em>database<em>host",
            "value" : "ip-172-31-3-236.us-west-2.compute.internal"
          }, {
            "name" : "oozie</em>database<em>password",
            "value" : "oozie</em>password"
          }, {
            "name" : "oozie<em>database</em>type",
            "value" : "mysql"
          }, {
            "name" : "oozie<em>database</em>user",
            "value" : "oozie"
          } ]
        } ],
        "items" : [ {
          "name" : "hive<em>service",
          "value" : "hive"
        }, {
          "name" : "mapreduce</em>yarn<em>service",
          "value" : "yarn"
        }, {
          "name" : "zookeeper</em>service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "oozie-OOZIE<em>SERVER-00e6ad869b94416fda600601ca9a26a3",
        "type" : "OOZIE</em>SERVER",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ {
            "name" : "role<em>jceks</em>password",
            "value" : "eax2drvl3irvwrtvkpqa1pt90"
          } ]
        }
      } ],
      "displayName" : "Oozie"
    }, {
      "name" : "yarn",
      "type" : "YARN",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "GATEWAY",
          "items" : [ {
            "name" : "mapred<em>reduce</em>tasks",
            "value" : "8"
          }, {
            "name" : "mapred<em>submit</em>replication",
            "value" : "2"
          } ]
        }, {
          "roleType" : "JOBHISTORY",
          "items" : [ {
            "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          } ]
        }, {
          "roleType" : "NODEMANAGER",
          "items" : [ {
            "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "nodemanager<em>local</em>data<em>directories</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "nodemanager</em>log<em>directories</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "nodemanager</em>recovery<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "rm</em>cpu<em>shares",
            "value" : "1500"
          }, {
            "name" : "rm</em>io<em>weight",
            "value" : "750"
          }, {
            "name" : "yarn</em>nodemanager<em>heartbeat</em>interval<em>ms",
            "value" : "100"
          }, {
            "name" : "yarn</em>nodemanager<em>local</em>dirs",
            "value" : "/data01/yarn/nm"
          }, {
            "name" : "yarn<em>nodemanager</em>log<em>dirs",
            "value" : "/data01/yarn/container-logs"
          }, {
            "name" : "yarn</em>nodemanager<em>resource</em>cpu<em>vcores",
            "value" : "3"
          }, {
            "name" : "yarn</em>nodemanager<em>resource</em>memory<em>mb",
            "value" : "5147"
          } ]
        }, {
          "roleType" : "RESOURCEMANAGER",
          "items" : [ {
            "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "yarn<em>scheduler</em>maximum<em>allocation</em>mb",
            "value" : "5147"
          }, {
            "name" : "yarn<em>scheduler</em>maximum<em>allocation</em>vcores",
            "value" : "3"
          } ]
        } ],
        "items" : [ {
          "name" : "hdfs<em>service",
          "value" : "hdfs"
        }, {
          "name" : "rm</em>dirty",
          "value" : "false"
        }, {
          "name" : "rm<em>last</em>allocation<em>percentage",
          "value" : "75"
        }, {
          "name" : "yarn</em>service<em>cgroups",
          "value" : "false"
        }, {
          "name" : "yarn</em>service<em>lce</em>always",
          "value" : "false"
        }, {
          "name" : "zk<em>authorization</em>secret<em>key",
          "value" : "zoQDA0z6fGVemyZKNTyhdNa2uulYzt"
        }, {
          "name" : "zookeeper</em>service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "yarn-JOBHISTORY-00e6ad869b94416fda600601ca9a26a3",
        "type" : "JOBHISTORY",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ {
            "name" : "role<em>jceks</em>password",
            "value" : "4osd5rn6cb502f3gaqwlhol2w"
          } ]
        }
      }, {
        "name" : "yarn-NODEMANAGER-1b85fee9b91287fbb726bb23bd20fb9e",
        "type" : "NODEMANAGER",
        "hostRef" : {
          "hostId" : "i-0cdec7e9fd3c6d7a2"
        },
        "config" : {
          "items" : [ {
            "name" : "role<em>jceks</em>password",
            "value" : "d6ihaoyq0cd26l64l73x3fpoe"
          } ]
        }
      }, {
        "name" : "yarn-NODEMANAGER-23106fb589586818a37e9c07eb3233d1",
        "type" : "NODEMANAGER",
        "hostRef" : {
          "hostId" : "i-0e787aefb35b3b594"
        },
        "config" : {
          "items" : [ {
            "name" : "role<em>jceks</em>password",
            "value" : "5rsgcmd3r7u0xzmekzomdd0yu"
          } ]
        }
      }, {
        "name" : "yarn-NODEMANAGER-4068bedd0a784c6e1f05b8e1dcf989b2",
        "type" : "NODEMANAGER",
        "hostRef" : {
          "hostId" : "i-06bb02d87a313ec25"
        },
        "config" : {
          "items" : [ {
            "name" : "role<em>jceks</em>password",
            "value" : "8hmmd76yh90yo0k9b5ayn2vlf"
          } ]
        }
      }, {
        "name" : "yarn-NODEMANAGER-f90b2f5a95253112e45830cab6f6a631",
        "type" : "NODEMANAGER",
        "hostRef" : {
          "hostId" : "i-06227a5eda43d6c09"
        },
        "config" : {
          "items" : [ {
            "name" : "role<em>jceks</em>password",
            "value" : "39r64ip5lmfygqlcwhk1zlc0c"
          } ]
        }
      }, {
        "name" : "yarn-RESOURCEMANAGER-00e6ad869b94416fda600601ca9a26a3",
        "type" : "RESOURCEMANAGER",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ {
            "name" : "rm<em>id",
            "value" : "61"
          }, {
            "name" : "role</em>jceks<em>password",
            "value" : "e3o1qqi4m356unh6y7fddc279"
          } ]
        }
      } ],
      "displayName" : "YARN (MR2 Included)"
    }, {
      "name" : "hdfs",
      "type" : "HDFS",
      "config" : {
        "roleTypeConfigs" : [ {
          "roleType" : "BALANCER",
          "items" : [ {
            "name" : "balancer</em>java<em>heapsize",
            "value" : "1006632960"
          } ]
        }, {
          "roleType" : "DATANODE",
          "items" : [ {
            "name" : "datanode</em>data<em>directories</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "datanode</em>java<em>heapsize",
            "value" : "1073741824"
          }, {
            "name" : "dfs</em>data<em>dir</em>list",
            "value" : "/data01/dfs/dn"
          }, {
            "name" : "dfs<em>datanode</em>du<em>reserved",
            "value" : "2113784627"
          }, {
            "name" : "dfs</em>datanode<em>max</em>locked<em>memory",
            "value" : "4294967296"
          }, {
            "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "max<em>log</em>backup<em>index",
            "value" : "5"
          }, {
            "name" : "max</em>log<em>size",
            "value" : "10"
          }, {
            "name" : "rm</em>cpu<em>shares",
            "value" : "500"
          }, {
            "name" : "rm</em>io<em>weight",
            "value" : "250"
          } ]
        }, {
          "roleType" : "FAILOVERCONTROLLER",
          "items" : [ {
            "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "max<em>log</em>backup<em>index",
            "value" : "5"
          }, {
            "name" : "max</em>log<em>size",
            "value" : "10"
          } ]
        }, {
          "roleType" : "GATEWAY",
          "items" : [ {
            "name" : "dfs</em>client<em>use</em>trash",
            "value" : "true"
          } ]
        }, {
          "roleType" : "HTTPFS",
          "items" : [ {
            "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "max</em>log<em>backup</em>index",
            "value" : "5"
          }, {
            "name" : "max<em>log</em>size",
            "value" : "10"
          } ]
        }, {
          "roleType" : "JOURNALNODE",
          "items" : [ {
            "name" : "dfs<em>journalnode</em>edits<em>dir",
            "value" : "/data01/jn"
          }, {
            "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "journalnode</em>edits<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "max<em>log</em>backup<em>index",
            "value" : "5"
          }, {
            "name" : "max</em>log<em>size",
            "value" : "10"
          } ]
        }, {
          "roleType" : "NAMENODE",
          "items" : [ {
            "name" : "dfs</em>name<em>dir</em>list",
            "value" : "/data01/dfs/nn"
          }, {
            "name" : "dfs<em>namenode</em>servicerpc<em>address",
            "value" : "8022"
          }, {
            "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "max<em>log</em>backup<em>index",
            "value" : "5"
          }, {
            "name" : "max</em>log<em>size",
            "value" : "10"
          }, {
            "name" : "namenode</em>data<em>directories</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "namenode</em>java<em>heapsize",
            "value" : "1073741824"
          }, {
            "name" : "role</em>config<em>suppression</em>namenode<em>java</em>heapsize<em>minimum</em>validator",
            "value" : "true"
          } ]
        }, {
          "roleType" : "NFSGATEWAY",
          "items" : [ {
            "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "max</em>log<em>backup</em>index",
            "value" : "5"
          }, {
            "name" : "max<em>log</em>size",
            "value" : "10"
          }, {
            "name" : "nfsgateway<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          } ]
        }, {
          "roleType" : "SECONDARYNAMENODE",
          "items" : [ {
            "name" : "fs<em>checkpoint</em>dir<em>list",
            "value" : "/data01/dfs/snn"
          }, {
            "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          }, {
            "name" : "max<em>log</em>backup<em>index",
            "value" : "5"
          }, {
            "name" : "max</em>log<em>size",
            "value" : "10"
          }, {
            "name" : "secondary</em>namenode<em>java</em>heapsize",
            "value" : "1073741824"
          }, {
            "name" : "secondarynamenode<em>checkpoint</em>directories<em>free</em>space<em>absolute</em>thresholds",
            "value" : "{\"warning\":1073741824,\"critical\":536870912}"
          } ]
        } ],
        "items" : [ {
          "name" : "dfs<em>ha</em>fencing<em>cloudera</em>manager<em>secret</em>key",
          "value" : "QzxHCdhUv95MsGJUk5aP8wlWZyPa0o"
        }, {
          "name" : "dfs<em>ha</em>fencing<em>methods",
          "value" : "shell(true)"
        }, {
          "name" : "fc</em>authorization<em>secret</em>key",
          "value" : "PnqfTOWwm94QNeU3PT07N4Dk3HimzU"
        }, {
          "name" : "http<em>auth</em>signature<em>secret",
          "value" : "g5VgXe3IQElbfFK206AEtBarx1ZhMO"
        }, {
          "name" : "navigator</em>audit<em>log</em>max<em>file</em>size",
          "value" : "50"
        }, {
          "name" : "rm<em>dirty",
          "value" : "false"
        }, {
          "name" : "rm</em>last<em>allocation</em>percentage",
          "value" : "25"
        }, {
          "name" : "zookeeper<em>service",
          "value" : "zookeeper"
        } ]
      },
      "roles" : [ {
        "name" : "hdfs-BALANCER-20465ca0226a76231505957a301a8e07",
        "type" : "BALANCER",
        "hostRef" : {
          "hostId" : "i-07d8b09bd07f7c4fe"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hdfs-DATANODE-1b85fee9b91287fbb726bb23bd20fb9e",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "i-0cdec7e9fd3c6d7a2"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "1g4l2oc4lyqi4sc5kcegbexfe"
          } ]
        }
      }, {
        "name" : "hdfs-DATANODE-23106fb589586818a37e9c07eb3233d1",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "i-0e787aefb35b3b594"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "bujec4a3ijifye2rrx4qmrl6g"
          } ]
        }
      }, {
        "name" : "hdfs-DATANODE-4068bedd0a784c6e1f05b8e1dcf989b2",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "i-06bb02d87a313ec25"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "3lkoxg5nycjghqpdfgp36twuu"
          } ]
        }
      }, {
        "name" : "hdfs-DATANODE-f90b2f5a95253112e45830cab6f6a631",
        "type" : "DATANODE",
        "hostRef" : {
          "hostId" : "i-06227a5eda43d6c09"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "a86q76cfw4cpdtxl9qe1k9b5p"
          } ]
        }
      }, {
        "name" : "hdfs-FAILOVERCONTROLLER-00e6ad869b94416fda600601ca9a26a3",
        "type" : "FAILOVERCONTROLLER",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "dtonelexsjkqa9mkj6a3gflze"
          } ]
        }
      }, {
        "name" : "hdfs-FAILOVERCONTROLLER-20465ca0226a76231505957a301a8e07",
        "type" : "FAILOVERCONTROLLER",
        "hostRef" : {
          "hostId" : "i-07d8b09bd07f7c4fe"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "17oqk6emti8osri640fhq5u76"
          } ]
        }
      }, {
        "name" : "hdfs-GATEWAY-00e6ad869b94416fda600601ca9a26a3",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hdfs-GATEWAY-1b85fee9b91287fbb726bb23bd20fb9e",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "i-0cdec7e9fd3c6d7a2"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hdfs-GATEWAY-20465ca0226a76231505957a301a8e07",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "i-07d8b09bd07f7c4fe"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hdfs-GATEWAY-23106fb589586818a37e9c07eb3233d1",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "i-0e787aefb35b3b594"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hdfs-GATEWAY-4068bedd0a784c6e1f05b8e1dcf989b2",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "i-06bb02d87a313ec25"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hdfs-GATEWAY-f90b2f5a95253112e45830cab6f6a631",
        "type" : "GATEWAY",
        "hostRef" : {
          "hostId" : "i-06227a5eda43d6c09"
        },
        "config" : {
          "items" : [ ]
        }
      }, {
        "name" : "hdfs-HTTPFS-20465ca0226a76231505957a301a8e07",
        "type" : "HTTPFS",
        "hostRef" : {
          "hostId" : "i-07d8b09bd07f7c4fe"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "7n53jwmha9frys0exnehx5289"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-00e6ad869b94416fda600601ca9a26a3",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "2b9hdna08vsufnortpvft2ome"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-20465ca0226a76231505957a301a8e07",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "i-07d8b09bd07f7c4fe"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "cg6xkw2t8ih69evoeucdj4njj"
          } ]
        }
      }, {
        "name" : "hdfs-JOURNALNODE-4068bedd0a784c6e1f05b8e1dcf989b2",
        "type" : "JOURNALNODE",
        "hostRef" : {
          "hostId" : "i-06bb02d87a313ec25"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "a3mx6j6ed2umxxko23sw3u766"
          } ]
        }
      }, {
        "name" : "hdfs-NAMENODE-00e6ad869b94416fda600601ca9a26a3",
        "type" : "NAMENODE",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ {
            "name" : "autofailover</em>enabled",
            "value" : "true"
          }, {
            "name" : "dfs<em>federation</em>namenode<em>nameservice",
            "value" : "nameservice1"
          }, {
            "name" : "dfs</em>namenode<em>quorum</em>journal<em>name",
            "value" : "nameservice1"
          }, {
            "name" : "namenode</em>id",
            "value" : "77"
          }, {
            "name" : "role<em>jceks</em>password",
            "value" : "2hka0x65ioavfk0tdf5zm8ife"
          } ]
        }
      }, {
        "name" : "hdfs-NAMENODE-20465ca0226a76231505957a301a8e07",
        "type" : "NAMENODE",
        "hostRef" : {
          "hostId" : "i-07d8b09bd07f7c4fe"
        },
        "config" : {
          "items" : [ {
            "name" : "autofailover<em>enabled",
            "value" : "true"
          }, {
            "name" : "dfs</em>federation<em>namenode</em>nameservice",
            "value" : "nameservice1"
          }, {
            "name" : "dfs<em>namenode</em>quorum<em>journal</em>name",
            "value" : "nameservice1"
          }, {
            "name" : "namenode<em>id",
            "value" : "65"
          }, {
            "name" : "role</em>jceks<em>password",
            "value" : "4gc03t4jjlgxgvnu9jbdcatpx"
          } ]
        }
      }, {
        "name" : "hdfs-NFSGATEWAY-00e6ad869b94416fda600601ca9a26a3",
        "type" : "NFSGATEWAY",
        "hostRef" : {
          "hostId" : "i-030ba7e9fb9905c4a"
        },
        "config" : {
          "items" : [ {
            "name" : "role</em>jceks<em>password",
            "value" : "2798m5yj2l7jgqdxahsmogkq8"
          } ]
        }
      } ],
      "displayName" : "HDFS"
    } ]
  } ],
  "hosts" : [ {
    "hostId" : "i-0e787aefb35b3b594",
    "ipAddress" : "172.31.1.76",
    "hostname" : "ip-172-31-1-76.us-west-2.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "i-0cdec7e9fd3c6d7a2",
    "ipAddress" : "172.31.1.77",
    "hostname" : "ip-172-31-1-77.us-west-2.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "i-06227a5eda43d6c09",
    "ipAddress" : "172.31.1.78",
    "hostname" : "ip-172-31-1-78.us-west-2.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "i-06bb02d87a313ec25",
    "ipAddress" : "172.31.1.79",
    "hostname" : "ip-172-31-1-79.us-west-2.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "i-030ba7e9fb9905c4a",
    "ipAddress" : "172.31.13.184",
    "hostname" : "ip-172-31-13-184.us-west-2.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  }, {
    "hostId" : "i-07d8b09bd07f7c4fe",
    "ipAddress" : "172.31.3.236",
    "hostname" : "ip-172-31-3-236.us-west-2.compute.internal",
    "rackId" : "/default",
    "config" : {
      "items" : [ ]
    }
  } ],
  "users" : [ {
    "name" : "<strong>cloudera</em>internal<em>user</strong>mgmt-EVENTSERVER-20465ca0226a76231505957a301a8e07",
    "roles" : [ "ROLE</em>USER" ],
    "pwHash" : "0b169ef23160454422bc7407442242d3b3d10915f5fcf1e91d402494d0cddcb8",
    "pwSalt" : -6987964884420949147,
    "pwLogin" : true
  }, {
    "name" : "<strong>cloudera<em>internal</em>user</strong>mgmt-HOSTMONITOR-20465ca0226a76231505957a301a8e07",
    "roles" : [ "ROLE<em>USER" ],
    "pwHash" : "d32839fff8904f3cf6000633df3773c595619723a7079bef9e17f4c657d63bae",
    "pwSalt" : -6282278702152043403,
    "pwLogin" : true
  }, {
    "name" : "<strong>cloudera</em>internal<em>user</strong>mgmt-REPORTSMANAGER-20465ca0226a76231505957a301a8e07",
    "roles" : [ "ROLE</em>USER" ],
    "pwHash" : "feb7d1e54d28f3f880b9f54e1bc391abe04fda4b712f99714556f5e66a7bb161",
    "pwSalt" : 5863429181474268157,
    "pwLogin" : true
  }, {
    "name" : "<strong>cloudera<em>internal</em>user</strong>mgmt-SERVICEMONITOR-20465ca0226a76231505957a301a8e07",
    "roles" : [ "ROLE<em>USER" ],
    "pwHash" : "809a7b8a9e78c22536dfc9ae1da05bd0e25d3c8cd813465ccf4852ca624e0267",
    "pwSalt" : -3346630642994893644,
    "pwLogin" : true
  }, {
    "name" : "admin",
    "roles" : [ "ROLE</em>LIMITED" ],
    "pwHash" : "67d87352b7a7e8b06d4914b378e840963b4301669dfdee8b9814841d0a0ac230",
    "pwSalt" : 4152759654975312896,
    "pwLogin" : true
  }, {
    "name" : "arvind",
    "roles" : [ "ROLE<em>ADMIN" ],
    "pwHash" : "3a60c01049db98408957f8b9bf88c0e8ecaf71f0039c9f567d65d0ccf09a606a",
    "pwSalt" : 7404372168610525719,
    "pwLogin" : true
  }, {
    "name" : "arvind75",
    "roles" : [ "ROLE</em>ADMIN" ],
    "pwHash" : "9ec51d6c5763cbd41874a32c52c2d834bcdaebb802e59fcf047927f3ec168ef9",
    "pwSalt" : 1686886305382661018,
    "pwLogin" : true
  }, {
    "name" : "minotaur",
    "roles" : [ "ROLE<em>CONFIGURATOR" ],
    "pwHash" : "e258a5f9b9cbf45289a184cec9c1fc113809d07777f1031cc94e4325e15694fa",
    "pwSalt" : 249356702777589302,
    "pwLogin" : true
  }, {
    "name" : "security",
    "roles" : [ "ROLE</em>KEY<em>ADMIN" ],
    "pwHash" : "99ebdd4272d3de72fec4fdea71ed3ce4739c683238f66acbaa9cb2a535cad8c4",
    "pwSalt" : -9151195600242854365,
    "pwLogin" : true
  } ],
  "versionInfo" : {
    "version" : "5.8.1",
    "buildUser" : "jenkins",
    "buildTimestamp" : "20160722-1141",
    "gitHash" : "a0886a893750079a4dc7f902be22d6f6e63b85a1",
    "snapshot" : false
  },
  "managementService" : {
    "name" : "mgmt",
    "type" : "MGMT",
    "config" : {
      "roleTypeConfigs" : [ {
        "roleType" : "ACTIVITYMONITOR",
        "items" : [ {
          "name" : "firehose</em>heapsize",
          "value" : "268435456"
        }, {
          "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "log<em>directory</em>free<em>space</em>absolute<em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        } ]
      }, {
        "roleType" : "ALERTPUBLISHER",
        "items" : [ {
          "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        } ]
      }, {
        "roleType" : "EVENTSERVER",
        "items" : [ {
          "name" : "event<em>server</em>heapsize",
          "value" : "1006632960"
        }, {
          "name" : "eventserver<em>index</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "log<em>directory</em>free<em>space</em>absolute<em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        } ]
      }, {
        "roleType" : "HOSTMONITOR",
        "items" : [ {
          "name" : "firehose</em>heapsize",
          "value" : "268435456"
        }, {
          "name" : "firehose<em>non</em>java<em>memory</em>bytes",
          "value" : "805306368"
        }, {
          "name" : "firehose<em>storage</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "log<em>directory</em>free<em>space</em>absolute<em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "role</em>config<em>suppression</em>firehose<em>heap</em>size<em>validator",
          "value" : "true"
        }, {
          "name" : "role</em>config<em>suppression</em>firehose<em>non</em>java<em>memory</em>validator",
          "value" : "true"
        } ]
      }, {
        "roleType" : "NAVIGATOR",
        "items" : [ {
          "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "log<em>directory</em>free<em>space</em>absolute<em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        } ]
      }, {
        "roleType" : "NAVIGATORMETASERVER",
        "items" : [ {
          "name" : "heap</em>dump<em>directory</em>free<em>space</em>absolute<em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "log</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "navigatormetaserver<em>audit</em>event<em>log</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "navigatormetaserver<em>data</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        } ]
      }, {
        "roleType" : "REPORTSMANAGER",
        "items" : [ {
          "name" : "headlamp<em>database</em>host",
          "value" : "ip-172-31-3-236.us-west-2.compute.internal"
        }, {
          "name" : "headlamp<em>database</em>name",
          "value" : "rman"
        }, {
          "name" : "headlamp<em>database</em>password",
          "value" : "rman<em>password"
        }, {
          "name" : "headlamp</em>database<em>user",
          "value" : "rman"
        }, {
          "name" : "headlamp</em>heapsize",
          "value" : "1006632960"
        }, {
          "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "log<em>directory</em>free<em>space</em>absolute<em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "reportsmanager</em>scratch<em>directory</em>free<em>space</em>absolute<em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        } ]
      }, {
        "roleType" : "SERVICEMONITOR",
        "items" : [ {
          "name" : "firehose</em>heapsize",
          "value" : "268435456"
        }, {
          "name" : "firehose<em>non</em>java<em>memory</em>bytes",
          "value" : "805306368"
        }, {
          "name" : "firehose<em>storage</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "heap<em>dump</em>directory<em>free</em>space<em>absolute</em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "log<em>directory</em>free<em>space</em>absolute<em>thresholds",
          "value" : "{\"warning\":1073741824,\"critical\":536870912}"
        }, {
          "name" : "role</em>config<em>suppression</em>firehose<em>heap</em>size<em>validator",
          "value" : "true"
        }, {
          "name" : "role</em>config<em>suppression</em>firehose<em>non</em>java<em>memory</em>validator",
          "value" : "true"
        } ]
      } ],
      "items" : [ {
        "name" : "mgmt<em>command</em>storage<em>directory</em>free<em>space</em>absolute<em>thresholds",
        "value" : "{\"warning\":1073741824,\"critical\":536870912}"
      }, {
        "name" : "mgmt</em>embedded<em>database</em>free<em>space</em>absolute<em>thresholds",
        "value" : "{\"warning\":1073741824,\"critical\":536870912}"
      } ]
    },
    "roles" : [ {
      "name" : "mgmt-ALERTPUBLISHER-20465ca0226a76231505957a301a8e07",
      "type" : "ALERTPUBLISHER",
      "hostRef" : {
        "hostId" : "i-07d8b09bd07f7c4fe"
      },
      "config" : {
        "items" : [ {
          "name" : "role</em>jceks<em>password",
          "value" : "dgloegz8itq508btzelrxrmfg"
        } ]
      }
    }, {
      "name" : "mgmt-EVENTSERVER-20465ca0226a76231505957a301a8e07",
      "type" : "EVENTSERVER",
      "hostRef" : {
        "hostId" : "i-07d8b09bd07f7c4fe"
      },
      "config" : {
        "items" : [ {
          "name" : "role</em>jceks<em>password",
          "value" : "eakua0chxn5bqjop3abm948my"
        } ]
      }
    }, {
      "name" : "mgmt-HOSTMONITOR-20465ca0226a76231505957a301a8e07",
      "type" : "HOSTMONITOR",
      "hostRef" : {
        "hostId" : "i-07d8b09bd07f7c4fe"
      },
      "config" : {
        "items" : [ {
          "name" : "role</em>jceks<em>password",
          "value" : "5eo3yrb61fn2fz1ooe8tqywb9"
        } ]
      }
    }, {
      "name" : "mgmt-REPORTSMANAGER-20465ca0226a76231505957a301a8e07",
      "type" : "REPORTSMANAGER",
      "hostRef" : {
        "hostId" : "i-07d8b09bd07f7c4fe"
      },
      "config" : {
        "items" : [ {
          "name" : "role</em>jceks<em>password",
          "value" : "eic2ag99843h2gku9k2nj3g5b"
        } ]
      }
    }, {
      "name" : "mgmt-SERVICEMONITOR-20465ca0226a76231505957a301a8e07",
      "type" : "SERVICEMONITOR",
      "hostRef" : {
        "hostId" : "i-07d8b09bd07f7c4fe"
      },
      "config" : {
        "items" : [ {
          "name" : "role</em>jceks<em>password",
          "value" : "dchr67jolyuhjspgjzlp1j9zx"
        } ]
      }
    } ],
    "displayName" : "Cloudera Management Service"
  },
  "managerSettings" : {
    "items" : [ {
      "name" : "CLUSTER</em>STATS<em>START",
      "value" : "10/27/2012 12:20"
    }, {
      "name" : "PUBLIC</em>CLOUD<em>STATUS",
      "value" : "ON</em>PUBLIC<em>CLOUD"
    }, {
      "name" : "REMOTE</em>PARCEL<em>REPO</em>URLS",
      "value" : "https://archive.cloudera.com/cdh5/parcels/{latest_supported}/,https://archive.cloudera.com/cdh5/parcels/5.7.2,https://archive.cloudera.com/cdh4/parcels/latest/,https://archive.cloudera.com/impala/parcels/latest/,https://archive.cloudera.com/search/parcels/latest/,https://archive.cloudera.com/accumulo/parcels/1.4/,https://archive.cloudera.com/accumulo-c5/parcels/latest/,https://archive.cloudera.com/kafka/parcels/latest/,https://archive.cloudera.com/navigator-keytrustee5/parcels/latest/,https://archive.cloudera.com/spark/parcels/latest/,https://archive.cloudera.com/sqoop-connectors/parcels/latest/"
    } ]
  }
}</p>

