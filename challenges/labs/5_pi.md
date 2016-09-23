```
ip-172-31-40-208@weiner:/home/weiner >hadoop jar /opt/cloudera/parcels/CDH/lib/hadoop-mapreduce/hadoop-mapreduce-examples.jar pi 10 100
Number of Maps  = 10
Samples per Map = 100
Wrote input for Map #0
Wrote input for Map #1
Wrote input for Map #2
Wrote input for Map #3
Wrote input for Map #4
Wrote input for Map #5
Wrote input for Map #6
Wrote input for Map #7
Wrote input for Map #8
Wrote input for Map #9
Starting Job
16/09/23 11:47:25 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-40-208.us-west-2.compute.internal/172.31.40.208:8032
16/09/23 11:47:26 INFO hdfs.DFSClient: Created token for weiner: HDFS_DELEGATION_TOKEN owner=weiner@ARVIND75.NYC, renewer=yarn, realUser=, issueDate=1474645646241, maxDate=1475250446241, sequenceNumber=2, masterKeyId=2 on 172.31.33.102:8020
16/09/23 11:47:26 INFO security.TokenCache: Got dt for hdfs://ip-172-31-33-102.us-west-2.compute.internal:8020; Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.33.102:8020, Ident: (token for weiner: HDFS_DELEGATION_TOKEN owner=weiner@ARVIND75.NYC, renewer=yarn, realUser=, issueDate=1474645646241, maxDate=1475250446241, sequenceNumber=2, masterKeyId=2)
16/09/23 11:47:26 INFO input.FileInputFormat: Total input paths to process : 10
16/09/23 11:47:26 INFO mapreduce.JobSubmitter: number of splits:10
16/09/23 11:47:26 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1474645281490_0002
16/09/23 11:47:26 INFO mapreduce.JobSubmitter: Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.33.102:8020, Ident: (token for weiner: HDFS_DELEGATION_TOKEN owner=weiner@ARVIND75.NYC, renewer=yarn, realUser=, issueDate=1474645646241, maxDate=1475250446241, sequenceNumber=2, masterKeyId=2)
16/09/23 11:47:27 INFO impl.YarnClientImpl: Submitted application application_1474645281490_0002
16/09/23 11:47:27 INFO mapreduce.Job: The url to track the job: http://ip-172-31-40-208.us-west-2.compute.internal:8088/proxy/application_1474645281490_0002/
16/09/23 11:47:27 INFO mapreduce.Job: Running job: job_1474645281490_0002
16/09/23 11:47:36 INFO mapreduce.Job: Job job_1474645281490_0002 running in uber mode : false
16/09/23 11:47:36 INFO mapreduce.Job:  map 0% reduce 0%
16/09/23 11:47:44 INFO mapreduce.Job:  map 20% reduce 0%
16/09/23 11:47:47 INFO mapreduce.Job:  map 40% reduce 0%
16/09/23 11:47:50 INFO mapreduce.Job:  map 100% reduce 0%
16/09/23 11:47:57 INFO mapreduce.Job:  map 100% reduce 100%
16/09/23 11:47:57 INFO mapreduce.Job: Job job_1474645281490_0002 completed successfully
16/09/23 11:47:57 INFO mapreduce.Job: Counters: 50
        File System Counters
                FILE: Number of bytes read=91
                FILE: Number of bytes written=1332201
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=2990
                HDFS: Number of bytes written=215
                HDFS: Number of read operations=43
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=3
        Job Counters
                Launched map tasks=10
                Launched reduce tasks=1
                Data-local map tasks=9
                Rack-local map tasks=1
                Total time spent by all maps in occupied slots (ms)=102388
                Total time spent by all reduces in occupied slots (ms)=3993
                Total time spent by all map tasks (ms)=102388
                Total time spent by all reduce tasks (ms)=3993
                Total vcore-seconds taken by all map tasks=102388
                Total vcore-seconds taken by all reduce tasks=3993
                Total megabyte-seconds taken by all map tasks=104845312
                Total megabyte-seconds taken by all reduce tasks=4088832
        Map-Reduce Framework
                Map input records=10
                Map output records=20
                Map output bytes=180
                Map output materialized bytes=340
                Input split bytes=1810
                Combine input records=0
                Combine output records=0
                Reduce input groups=2
                Reduce shuffle bytes=340
                Reduce input records=20
                Reduce output records=0
                Spilled Records=40
                Shuffled Maps =10
                Failed Shuffles=0
                Merged Map outputs=10
                GC time elapsed (ms)=443
                CPU time spent (ms)=8820
                Physical memory (bytes) snapshot=4753682432
                Virtual memory (bytes) snapshot=17281458176
                Total committed heap usage (bytes)=5445779456
        Shuffle Errors
                BAD_ID=0
                CONNECTION=0
                IO_ERROR=0
                WRONG_LENGTH=0
                WRONG_MAP=0
                WRONG_REDUCE=0
        File Input Format Counters
                Bytes Read=1180
        File Output Format Counters
                Bytes Written=97
Job Finished in 31.783 seconds
Estimated value of Pi is 3.14800000000000000000
```
