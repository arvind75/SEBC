```


hadoop jar /opt/cloudera/parcels/CDH/jars/hadoop-examples.jar teragen -Ddfs.block.size=64M 51200000  /user/christie/tgen64



real    2m58.111s
user    0m6.271s
sys     0m0.811s



ip-172-31-40-208@christie:/home/christie >hdfs dfs -ls /user/christie/tgen64
Found 3 items
-rw-r--r--   3 christie bridges          0 2016-09-23 10:54 /user/christie/tgen64/_SUCCESS
-rw-r--r--   3 christie bridges 2560000000 2016-09-23 10:54 /user/christie/tgen64/part-m-00000
-rw-r--r--   3 christie bridges 2560000000 2016-09-23 10:54 /user/christie/tgen64/part-m-00001


ip-172-31-40-208@christie:/home/christie >hadoop fsck /user/christie/tgen64
DEPRECATED: Use of this script to execute hdfs command is deprecated.
Instead use the hdfs command for it.

Connecting to namenode via http://ip-172-31-33-102.us-west-2.compute.internal:50070
FSCK started by christie (auth:SIMPLE) from /172.31.40.208 for path /user/christie/tgen64 at Fri Sep 23 10:57:21 EDT 2016
...Status: HEALTHY
 Total size:    5120000000 B
 Total dirs:    1
 Total files:   3
 Total symlinks:                0
 Total blocks (validated):      78 (avg. block size 65641025 B)
 Minimally replicated blocks:   78 (100.0 %)
 Over-replicated blocks:        0 (0.0 %)
 Under-replicated blocks:       0 (0.0 %)
 Mis-replicated blocks:         0 (0.0 %)
 Default replication factor:    3
 Average block replication:     3.0
 Corrupt blocks:                0
 Missing replicas:              0 (0.0 %)
 Number of data-nodes:          4
 Number of racks:               1
FSCK ended at Fri Sep 23 10:57:21 EDT 2016 in 6 milliseconds


