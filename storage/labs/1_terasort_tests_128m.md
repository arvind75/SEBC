///
time /opt/cloudera/parcels/CDH/bin/hadoop jar /opt/cloudera/parcels/CDH/jars/hadoop-examples.jar terasort  /benchmark/teragen_128m /benchmark/terasort
16/09/20 21:39:21 INFO terasort.TeraSort: starting
16/09/20 21:39:22 INFO input.FileInputFormat: Total input paths to process : 2
Spent 166ms computing base-splits.
Spent 3ms computing TeraScheduler splits.
Computing input splits took 170ms
Sampling 10 splits of 76
Making 8 from 100000 sampled records
Computing parititions took 733ms
Spent 906ms computing partitions.
16/09/20 21:39:23 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-13-184.us-west-2.compute.internal/172.31.13.184:8032
16/09/20 21:39:24 INFO mapreduce.JobSubmitter: number of splits:76
16/09/20 21:39:24 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1474407042043_0006
16/09/20 21:39:24 INFO impl.YarnClientImpl: Submitted application application_1474407042043_0006
16/09/20 21:39:24 INFO mapreduce.Job: The url to track the job: http://ip-172-31-13-184.us-west-2.compute.internal:8088/proxy/application_1474407042043_0006/
16/09/20 21:39:24 INFO mapreduce.Job: Running job: job_1474407042043_0006
16/09/20 21:39:32 INFO mapreduce.Job: Job job_1474407042043_0006 running in uber mode : false
16/09/20 21:39:32 INFO mapreduce.Job:  map 0% reduce 0%
16/09/20 21:39:46 INFO mapreduce.Job:  map 8% reduce 0%
16/09/20 21:39:47 INFO mapreduce.Job:  map 9% reduce 0%
16/09/20 21:39:48 INFO mapreduce.Job:  map 15% reduce 0%
16/09/20 21:39:51 INFO mapreduce.Job:  map 16% reduce 0%
16/09/20 21:39:52 INFO mapreduce.Job:  map 17% reduce 0%
16/09/20 21:40:00 INFO mapreduce.Job:  map 21% reduce 0%
16/09/20 21:40:01 INFO mapreduce.Job:  map 23% reduce 0%
16/09/20 21:40:02 INFO mapreduce.Job:  map 27% reduce 0%
16/09/20 21:40:03 INFO mapreduce.Job:  map 29% reduce 0%
16/09/20 21:40:06 INFO mapreduce.Job:  map 30% reduce 0%
16/09/20 21:40:07 INFO mapreduce.Job:  map 32% reduce 0%
16/09/20 21:40:10 INFO mapreduce.Job:  map 34% reduce 0%
16/09/20 21:40:13 INFO mapreduce.Job:  map 35% reduce 0%
16/09/20 21:40:15 INFO mapreduce.Job:  map 38% reduce 0%
16/09/20 21:40:16 INFO mapreduce.Job:  map 41% reduce 0%
16/09/20 21:40:17 INFO mapreduce.Job:  map 44% reduce 0%
16/09/20 21:40:18 INFO mapreduce.Job:  map 46% reduce 0%
16/09/20 21:40:25 INFO mapreduce.Job:  map 47% reduce 0%
16/09/20 21:40:26 INFO mapreduce.Job:  map 50% reduce 0%
16/09/20 21:40:29 INFO mapreduce.Job:  map 53% reduce 0%
16/09/20 21:40:30 INFO mapreduce.Job:  map 56% reduce 0%
16/09/20 21:40:31 INFO mapreduce.Job:  map 59% reduce 0%
16/09/20 21:40:32 INFO mapreduce.Job:  map 62% reduce 0%
16/09/20 21:40:33 INFO mapreduce.Job:  map 63% reduce 0%
16/09/20 21:40:42 INFO mapreduce.Job:  map 64% reduce 0%
16/09/20 21:40:44 INFO mapreduce.Job:  map 66% reduce 0%
16/09/20 21:40:45 INFO mapreduce.Job:  map 72% reduce 0%
16/09/20 21:40:46 INFO mapreduce.Job:  map 75% reduce 0%
16/09/20 21:40:47 INFO mapreduce.Job:  map 79% reduce 0%
16/09/20 21:40:48 INFO mapreduce.Job:  map 80% reduce 0%
16/09/20 21:40:56 INFO mapreduce.Job:  map 81% reduce 0%
16/09/20 21:40:58 INFO mapreduce.Job:  map 82% reduce 0%
16/09/20 21:40:59 INFO mapreduce.Job:  map 84% reduce 0%
16/09/20 21:41:00 INFO mapreduce.Job:  map 86% reduce 0%
16/09/20 21:41:01 INFO mapreduce.Job:  map 89% reduce 0%
16/09/20 21:41:02 INFO mapreduce.Job:  map 92% reduce 0%
16/09/20 21:41:03 INFO mapreduce.Job:  map 94% reduce 0%
16/09/20 21:41:04 INFO mapreduce.Job:  map 96% reduce 0%
16/09/20 21:41:07 INFO mapreduce.Job:  map 97% reduce 0%
16/09/20 21:41:12 INFO mapreduce.Job:  map 97% reduce 3%
16/09/20 21:41:14 INFO mapreduce.Job:  map 99% reduce 5%
16/09/20 21:41:15 INFO mapreduce.Job:  map 100% reduce 9%
16/09/20 21:41:16 INFO mapreduce.Job:  map 100% reduce 14%
16/09/20 21:41:17 INFO mapreduce.Job:  map 100% reduce 18%
16/09/20 21:41:18 INFO mapreduce.Job:  map 100% reduce 20%
16/09/20 21:41:19 INFO mapreduce.Job:  map 100% reduce 23%
16/09/20 21:41:20 INFO mapreduce.Job:  map 100% reduce 25%
16/09/20 21:41:21 INFO mapreduce.Job:  map 100% reduce 28%
16/09/20 21:41:22 INFO mapreduce.Job:  map 100% reduce 32%
16/09/20 21:41:23 INFO mapreduce.Job:  map 100% reduce 36%
16/09/20 21:41:24 INFO mapreduce.Job:  map 100% reduce 43%
16/09/20 21:41:25 INFO mapreduce.Job:  map 100% reduce 57%
16/09/20 21:41:26 INFO mapreduce.Job:  map 100% reduce 62%
16/09/20 21:41:27 INFO mapreduce.Job:  map 100% reduce 63%
16/09/20 21:41:28 INFO mapreduce.Job:  map 100% reduce 68%
16/09/20 21:41:29 INFO mapreduce.Job:  map 100% reduce 70%
16/09/20 21:41:31 INFO mapreduce.Job:  map 100% reduce 73%
16/09/20 21:41:32 INFO mapreduce.Job:  map 100% reduce 75%
16/09/20 21:41:34 INFO mapreduce.Job:  map 100% reduce 78%
16/09/20 21:41:35 INFO mapreduce.Job:  map 100% reduce 79%
16/09/20 21:41:36 INFO mapreduce.Job:  map 100% reduce 80%
16/09/20 21:41:37 INFO mapreduce.Job:  map 100% reduce 83%
16/09/20 21:41:39 INFO mapreduce.Job:  map 100% reduce 84%
16/09/20 21:41:40 INFO mapreduce.Job:  map 100% reduce 88%
16/09/20 21:41:42 INFO mapreduce.Job:  map 100% reduce 89%
16/09/20 21:41:43 INFO mapreduce.Job:  map 100% reduce 92%
16/09/20 21:41:45 INFO mapreduce.Job:  map 100% reduce 94%
16/09/20 21:41:46 INFO mapreduce.Job:  map 100% reduce 96%
16/09/20 21:41:48 INFO mapreduce.Job:  map 100% reduce 97%
16/09/20 21:41:51 INFO mapreduce.Job:  map 100% reduce 98%
16/09/20 21:41:52 INFO mapreduce.Job:  map 100% reduce 99%
16/09/20 21:41:54 INFO mapreduce.Job:  map 100% reduce 100%
16/09/20 21:41:55 INFO mapreduce.Job: Job job_1474407042043_0006 completed successfully
16/09/20 21:41:56 INFO mapreduce.Job: Counters: 50
        File System Counters
                FILE: Number of bytes read=4482324758
                FILE: Number of bytes written=8896058773
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=10000009120
                HDFS: Number of bytes written=10000000000
                HDFS: Number of read operations=252
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=16
        Job Counters
                Launched map tasks=76
                Launched reduce tasks=8
                Data-local map tasks=75
                Rack-local map tasks=1
                Total time spent by all maps in occupied slots (ms)=1128662
                Total time spent by all reduces in occupied slots (ms)=363001
                Total time spent by all map tasks (ms)=1128662
                Total time spent by all reduce tasks (ms)=363001
                Total vcore-seconds taken by all map tasks=1128662
                Total vcore-seconds taken by all reduce tasks=363001
                Total megabyte-seconds taken by all map tasks=1155749888
                Total megabyte-seconds taken by all reduce tasks=371713024
        Map-Reduce Framework
                Map input records=100000000
                Map output records=100000000
                Map output bytes=10200000000
                Map output materialized bytes=4403335497
                Input split bytes=9120
                Combine input records=0
                Combine output records=0
                Reduce input groups=100000000
                Reduce shuffle bytes=4403335497
                Reduce input records=100000000
                Reduce output records=100000000
                Spilled Records=200000000
                Shuffled Maps =608
                Failed Shuffles=0
                Merged Map outputs=608
                GC time elapsed (ms)=22416
                CPU time spent (ms)=990630
                Physical memory (bytes) snapshot=48519565312
                Virtual memory (bytes) snapshot=131624628224
                Total committed heap usage (bytes)=57680592896
        Shuffle Errors
                BAD_ID=0
                CONNECTION=0
                IO_ERROR=0
                WRONG_LENGTH=0
                WRONG_MAP=0
                WRONG_REDUCE=0
        File Input Format Counters
                Bytes Read=10000000000
        File Output Format Counters
                Bytes Written=10000000000
16/09/20 21:41:56 INFO terasort.TeraSort: done

real    2m36.004s
user    0m7.606s
sys     0m0.887s


///