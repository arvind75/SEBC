```


time hadoop jar /opt/cloudera/parcels/CDH/jars/hadoop-examples.jar terasort  /user/christie/tgen64 /user/christie/tgen64 /user/christie/tsort
16/09/23 11:42:38 INFO terasort.TeraSort: starting
16/09/23 11:42:40 INFO hdfs.DFSClient: Created token for christie: HDFS_DELEGATION_TOKEN owner=christie@ARVIND75.NYC, renewer=yarn, realUser=, issueDate=1474645360140, maxDate=1475250160140, sequenceNumber=1, masterKeyId=2 on 172.31.33.102:8020
16/09/23 11:42:40 INFO security.TokenCache: Got dt for hdfs://ip-172-31-33-102.us-west-2.compute.internal:8020; Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.33.102:8020, Ident: (token for christie: HDFS_DELEGATION_TOKEN owner=christie@ARVIND75.NYC, renewer=yarn, realUser=, issueDate=1474645360140, maxDate=1475250160140, sequenceNumber=1, masterKeyId=2)
16/09/23 11:42:40 INFO input.FileInputFormat: Total input paths to process : 2
Spent 411ms computing base-splits.
Spent 3ms computing TeraScheduler splits.
Computing input splits took 415ms
Sampling 10 splits of 78
Making 8 from 100000 sampled records
Computing parititions took 1068ms
Spent 1486ms computing partitions.
16/09/23 11:42:41 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-40-208.us-west-2.compute.internal/172.31.40.208:8032
16/09/23 11:42:41 INFO mapreduce.JobSubmitter: number of splits:78
16/09/23 11:42:42 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1474645281490_0001
16/09/23 11:42:42 INFO mapreduce.JobSubmitter: Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.33.102:8020, Ident: (token for christie: HDFS_DELEGATION_TOKEN owner=christie@ARVIND75.NYC, renewer=yarn, realUser=, issueDate=1474645360140, maxDate=1475250160140, sequenceNumber=1, masterKeyId=2)
16/09/23 11:42:43 INFO impl.YarnClientImpl: Submitted application application_1474645281490_0001
16/09/23 11:42:43 INFO mapreduce.Job: The url to track the job: http://ip-172-31-40-208.us-west-2.compute.internal:8088/proxy/application_1474645281490_0001/
16/09/23 11:42:43 INFO mapreduce.Job: Running job: job_1474645281490_0001
16/09/23 11:42:53 INFO mapreduce.Job: Job job_1474645281490_0001 running in uber mode : false
16/09/23 11:42:53 INFO mapreduce.Job:  map 0% reduce 0%
16/09/23 11:43:07 INFO mapreduce.Job:  map 4% reduce 0%
16/09/23 11:43:12 INFO mapreduce.Job:  map 5% reduce 0%
16/09/23 11:43:13 INFO mapreduce.Job:  map 8% reduce 0%
16/09/23 11:43:16 INFO mapreduce.Job:  map 9% reduce 0%
16/09/23 11:43:17 INFO mapreduce.Job:  map 18% reduce 0%
16/09/23 11:43:19 INFO mapreduce.Job:  map 22% reduce 0%
16/09/23 11:43:25 INFO mapreduce.Job:  map 26% reduce 0%
16/09/23 11:43:32 INFO mapreduce.Job:  map 37% reduce 0%
16/09/23 11:43:33 INFO mapreduce.Job:  map 40% reduce 0%
16/09/23 11:43:36 INFO mapreduce.Job:  map 41% reduce 0%
16/09/23 11:43:37 INFO mapreduce.Job:  map 42% reduce 0%
16/09/23 11:43:38 INFO mapreduce.Job:  map 44% reduce 0%
16/09/23 11:43:44 INFO mapreduce.Job:  map 45% reduce 0%
16/09/23 11:43:45 INFO mapreduce.Job:  map 47% reduce 0%
16/09/23 11:43:48 INFO mapreduce.Job:  map 59% reduce 0%
16/09/23 11:43:49 INFO mapreduce.Job:  map 60% reduce 0%
16/09/23 11:43:50 INFO mapreduce.Job:  map 62% reduce 0%
16/09/23 11:43:55 INFO mapreduce.Job:  map 63% reduce 0%
16/09/23 11:43:56 INFO mapreduce.Job:  map 64% reduce 0%
16/09/23 11:43:57 INFO mapreduce.Job:  map 65% reduce 0%
16/09/23 11:44:02 INFO mapreduce.Job:  map 67% reduce 0%
16/09/23 11:44:03 INFO mapreduce.Job:  map 69% reduce 0%
16/09/23 11:44:04 INFO mapreduce.Job:  map 71% reduce 0%
16/09/23 11:44:05 INFO mapreduce.Job:  map 79% reduce 0%
16/09/23 11:44:08 INFO mapreduce.Job:  map 81% reduce 0%
16/09/23 11:44:09 INFO mapreduce.Job:  map 82% reduce 0%
16/09/23 11:44:10 INFO mapreduce.Job:  map 83% reduce 0%
16/09/23 11:44:13 INFO mapreduce.Job:  map 85% reduce 0%
16/09/23 11:44:14 INFO mapreduce.Job:  map 86% reduce 0%
16/09/23 11:44:15 INFO mapreduce.Job:  map 87% reduce 0%
16/09/23 11:44:19 INFO mapreduce.Job:  map 90% reduce 0%
16/09/23 11:44:20 INFO mapreduce.Job:  map 91% reduce 0%
16/09/23 11:44:21 INFO mapreduce.Job:  map 95% reduce 0%
16/09/23 11:44:22 INFO mapreduce.Job:  map 99% reduce 0%
16/09/23 11:44:23 INFO mapreduce.Job:  map 99% reduce 7%
16/09/23 11:44:26 INFO mapreduce.Job:  map 99% reduce 8%
16/09/23 11:44:27 INFO mapreduce.Job:  map 99% reduce 15%
16/09/23 11:44:30 INFO mapreduce.Job:  map 99% reduce 16%
16/09/23 11:44:31 INFO mapreduce.Job:  map 99% reduce 20%
16/09/23 11:44:32 INFO mapreduce.Job:  map 100% reduce 20%
16/09/23 11:44:33 INFO mapreduce.Job:  map 100% reduce 21%
16/09/23 11:44:34 INFO mapreduce.Job:  map 100% reduce 27%
16/09/23 11:44:35 INFO mapreduce.Job:  map 100% reduce 33%
16/09/23 11:44:36 INFO mapreduce.Job:  map 100% reduce 40%
16/09/23 11:44:37 INFO mapreduce.Job:  map 100% reduce 47%
16/09/23 11:44:38 INFO mapreduce.Job:  map 100% reduce 52%
16/09/23 11:44:39 INFO mapreduce.Job:  map 100% reduce 54%
16/09/23 11:44:40 INFO mapreduce.Job:  map 100% reduce 58%
16/09/23 11:44:41 INFO mapreduce.Job:  map 100% reduce 59%
16/09/23 11:44:42 INFO mapreduce.Job:  map 100% reduce 65%
16/09/23 11:44:43 INFO mapreduce.Job:  map 100% reduce 71%
16/09/23 11:44:44 INFO mapreduce.Job:  map 100% reduce 72%
16/09/23 11:44:45 INFO mapreduce.Job:  map 100% reduce 76%
16/09/23 11:44:46 INFO mapreduce.Job:  map 100% reduce 78%
16/09/23 11:44:47 INFO mapreduce.Job:  map 100% reduce 79%
16/09/23 11:44:48 INFO mapreduce.Job:  map 100% reduce 82%
16/09/23 11:44:49 INFO mapreduce.Job:  map 100% reduce 83%
16/09/23 11:44:51 INFO mapreduce.Job:  map 100% reduce 84%
16/09/23 11:44:52 INFO mapreduce.Job:  map 100% reduce 86%
16/09/23 11:44:54 INFO mapreduce.Job:  map 100% reduce 88%
16/09/23 11:44:55 INFO mapreduce.Job:  map 100% reduce 90%
16/09/23 11:44:58 INFO mapreduce.Job:  map 100% reduce 91%
16/09/23 11:45:13 INFO mapreduce.Job:  map 100% reduce 96%
16/09/23 11:45:19 INFO mapreduce.Job:  map 100% reduce 98%
16/09/23 11:45:46 INFO mapreduce.Job:  map 100% reduce 100%
16/09/23 11:45:47 INFO mapreduce.Job: Job job_1474645281490_0001 completed successfully
16/09/23 11:45:47 INFO mapreduce.Job: Counters: 50
        File System Counters
                FILE: Number of bytes read=2286766558
                FILE: Number of bytes written=4541749833
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=5120012012
                HDFS: Number of bytes written=5120000000
                HDFS: Number of read operations=258
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=16
        Job Counters
                Launched map tasks=78
                Launched reduce tasks=8
                Data-local map tasks=77
                Rack-local map tasks=1
                Total time spent by all maps in occupied slots (ms)=1062225
                Total time spent by all reduces in occupied slots (ms)=484166
                Total time spent by all map tasks (ms)=1062225
                Total time spent by all reduce tasks (ms)=484166
                Total vcore-seconds taken by all map tasks=1062225
                Total vcore-seconds taken by all reduce tasks=484166
                Total megabyte-seconds taken by all map tasks=1087718400
                Total megabyte-seconds taken by all reduce tasks=495785984
        Map-Reduce Framework
                Map input records=51200000
                Map output records=51200000
                Map output bytes=5222400000
                Map output materialized bytes=2244499631
                Input split bytes=12012
                Combine input records=0
                Combine output records=0
                Reduce input groups=51200000
                Reduce shuffle bytes=2244499631
                Reduce input records=51200000
                Reduce output records=51200000
                Spilled Records=102400000
                Shuffled Maps =624
                Failed Shuffles=0
                Merged Map outputs=624
                GC time elapsed (ms)=20165
                CPU time spent (ms)=631700
                Physical memory (bytes) snapshot=46334619648
                Virtual memory (bytes) snapshot=134395318272
                Total committed heap usage (bytes)=52726071296
        Shuffle Errors
                BAD_ID=0
                CONNECTION=0
                IO_ERROR=0
                WRONG_LENGTH=0
                WRONG_MAP=0
                WRONG_REDUCE=0
        File Input Format Counters
                Bytes Read=5120000000
        File Output Format Counters
                Bytes Written=5120000000
16/09/23 11:45:47 INFO terasort.TeraSort: done

real    3m10.665s
user    0m8.832s
sys     0m1.033s
ip-172-31-40-208@christie:/home/christie >
