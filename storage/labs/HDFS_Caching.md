hdfs cacheadmin -addPool teragenpool

hdfs cacheadmin -addDirective -path /benchmark/teragen_128m -pool teragenpool -replication 1



///time /opt/cloudera/parcels/CDH/bin/hadoop jar /opt/cloudera/parcels/CDH/jars/hadoop-examples.jar terasort  /benchmark/teragen_128m /benchmark/terasort
16/09/20 21:58:17 INFO terasort.TeraSort: starting
16/09/20 21:58:19 INFO input.FileInputFormat: Total input paths to process : 2
Spent 175ms computing base-splits.
Spent 3ms computing TeraScheduler splits.
Computing input splits took 180ms
Sampling 10 splits of 76
Making 8 from 100000 sampled records
Computing parititions took 6268ms
Spent 6449ms computing partitions.
16/09/20 21:58:25 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-13-184.us-west-2.compute.internal/172.31.13.184:8032
16/09/20 21:58:26 INFO mapreduce.JobSubmitter: number of splits:76
16/09/20 21:58:26 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1474407042043_0007
16/09/20 21:58:26 INFO impl.YarnClientImpl: Submitted application application_1474407042043_0007
16/09/20 21:58:26 INFO mapreduce.Job: The url to track the job: http://ip-172-31-13-184.us-west-2.compute.internal:8088/proxy/application_1474407042043_0007/
16/09/20 21:58:26 INFO mapreduce.Job: Running job: job_1474407042043_0007
16/09/20 21:58:33 INFO mapreduce.Job: Job job_1474407042043_0007 running in uber mode : false
16/09/20 21:58:33 INFO mapreduce.Job:  map 0% reduce 0%
16/09/20 21:58:47 INFO mapreduce.Job:  map 2% reduce 0%
16/09/20 21:58:48 INFO mapreduce.Job:  map 8% reduce 0%
16/09/20 21:58:49 INFO mapreduce.Job:  map 9% reduce 0%
16/09/20 21:58:50 INFO mapreduce.Job:  map 15% reduce 0%
16/09/20 21:58:53 INFO mapreduce.Job:  map 17% reduce 0%
16/09/20 21:59:01 INFO mapreduce.Job:  map 18% reduce 0%
16/09/20 21:59:02 INFO mapreduce.Job:  map 21% reduce 0%
16/09/20 21:59:03 INFO mapreduce.Job:  map 25% reduce 0%
16/09/20 21:59:04 INFO mapreduce.Job:  map 27% reduce 0%
16/09/20 21:59:05 INFO mapreduce.Job:  map 29% reduce 0%
16/09/20 21:59:08 INFO mapreduce.Job:  map 31% reduce 0%
16/09/20 21:59:09 INFO mapreduce.Job:  map 32% reduce 0%
16/09/20 21:59:11 INFO mapreduce.Job:  map 33% reduce 0%
16/09/20 21:59:12 INFO mapreduce.Job:  map 34% reduce 0%
16/09/20 21:59:16 INFO mapreduce.Job:  map 35% reduce 0%
16/09/20 21:59:17 INFO mapreduce.Job:  map 39% reduce 0%
16/09/20 21:59:18 INFO mapreduce.Job:  map 40% reduce 0%
16/09/20 21:59:19 INFO mapreduce.Job:  map 44% reduce 0%
16/09/20 21:59:20 INFO mapreduce.Job:  map 46% reduce 0%
16/09/20 21:59:27 INFO mapreduce.Job:  map 48% reduce 0%
16/09/20 21:59:28 INFO mapreduce.Job:  map 50% reduce 0%
16/09/20 21:59:31 INFO mapreduce.Job:  map 53% reduce 0%
16/09/20 21:59:32 INFO mapreduce.Job:  map 56% reduce 0%
16/09/20 21:59:33 INFO mapreduce.Job:  map 58% reduce 0%
16/09/20 21:59:34 INFO mapreduce.Job:  map 61% reduce 0%
16/09/20 21:59:35 INFO mapreduce.Job:  map 63% reduce 0%
16/09/20 21:59:46 INFO mapreduce.Job:  map 68% reduce 0%
16/09/20 21:59:47 INFO mapreduce.Job:  map 71% reduce 0%
16/09/20 21:59:48 INFO mapreduce.Job:  map 73% reduce 0%
16/09/20 21:59:49 INFO mapreduce.Job:  map 74% reduce 0%
16/09/20 21:59:51 INFO mapreduce.Job:  map 80% reduce 0%
16/09/20 22:00:03 INFO mapreduce.Job:  map 88% reduce 0%
16/09/20 22:00:04 INFO mapreduce.Job:  map 89% reduce 0%
16/09/20 22:00:05 INFO mapreduce.Job:  map 96% reduce 0%
16/09/20 22:00:09 INFO mapreduce.Job:  map 97% reduce 0%
16/09/20 22:00:16 INFO mapreduce.Job:  map 97% reduce 2%
16/09/20 22:00:17 INFO mapreduce.Job:  map 100% reduce 3%
16/09/20 22:00:18 INFO mapreduce.Job:  map 100% reduce 10%
16/09/20 22:00:19 INFO mapreduce.Job:  map 100% reduce 16%
16/09/20 22:00:20 INFO mapreduce.Job:  map 100% reduce 17%
16/09/20 22:00:21 INFO mapreduce.Job:  map 100% reduce 23%
16/09/20 22:00:22 INFO mapreduce.Job:  map 100% reduce 25%
16/09/20 22:00:24 INFO mapreduce.Job:  map 100% reduce 26%
16/09/20 22:00:26 INFO mapreduce.Job:  map 100% reduce 35%
16/09/20 22:00:27 INFO mapreduce.Job:  map 100% reduce 36%
16/09/20 22:00:28 INFO mapreduce.Job:  map 100% reduce 40%
16/09/20 22:00:29 INFO mapreduce.Job:  map 100% reduce 42%
16/09/20 22:00:30 INFO mapreduce.Job:  map 100% reduce 46%
16/09/20 22:00:31 INFO mapreduce.Job:  map 100% reduce 56%
16/09/20 22:00:32 INFO mapreduce.Job:  map 100% reduce 61%
16/09/20 22:00:34 INFO mapreduce.Job:  map 100% reduce 69%
16/09/20 22:00:35 INFO mapreduce.Job:  map 100% reduce 72%
16/09/20 22:00:37 INFO mapreduce.Job:  map 100% reduce 74%
16/09/20 22:00:38 INFO mapreduce.Job:  map 100% reduce 77%
16/09/20 22:00:40 INFO mapreduce.Job:  map 100% reduce 79%
16/09/20 22:00:41 INFO mapreduce.Job:  map 100% reduce 81%
16/09/20 22:00:43 INFO mapreduce.Job:  map 100% reduce 83%
16/09/20 22:00:44 INFO mapreduce.Job:  map 100% reduce 84%
16/09/20 22:00:46 INFO mapreduce.Job:  map 100% reduce 85%
16/09/20 22:00:47 INFO mapreduce.Job:  map 100% reduce 86%
16/09/20 22:00:49 INFO mapreduce.Job:  map 100% reduce 88%
16/09/20 22:00:50 INFO mapreduce.Job:  map 100% reduce 89%
16/09/20 22:00:52 INFO mapreduce.Job:  map 100% reduce 91%
16/09/20 22:00:53 INFO mapreduce.Job:  map 100% reduce 92%
16/09/20 22:00:55 INFO mapreduce.Job:  map 100% reduce 94%
16/09/20 22:00:56 INFO mapreduce.Job:  map 100% reduce 95%
16/09/20 22:00:58 INFO mapreduce.Job:  map 100% reduce 97%
16/09/20 22:01:01 INFO mapreduce.Job:  map 100% reduce 99%
16/09/20 22:01:03 INFO mapreduce.Job:  map 100% reduce 100%
16/09/20 22:01:03 INFO mapreduce.Job: Job job_1474407042043_0007 completed successfully
16/09/20 22:01:03 INFO mapreduce.Job: Counters: 49
        File System Counters
                FILE: Number of bytes read=4483251960
                FILE: Number of bytes written=8896985975
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
                Data-local map tasks=76
                Total time spent by all maps in occupied slots (ms)=1142092
                Total time spent by all reduces in occupied slots (ms)=391484
                Total time spent by all map tasks (ms)=1142092
                Total time spent by all reduce tasks (ms)=391484
                Total vcore-seconds taken by all map tasks=1142092
                Total vcore-seconds taken by all reduce tasks=391484
                Total megabyte-seconds taken by all map tasks=1169502208
                Total megabyte-seconds taken by all reduce tasks=400879616
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
                GC time elapsed (ms)=22618
                CPU time spent (ms)=1000650
                Physical memory (bytes) snapshot=48467509248
                Virtual memory (bytes) snapshot=131735199744
                Total committed heap usage (bytes)=57762381824
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
16/09/20 22:01:03 INFO terasort.TeraSort: done

real    2m46.789s
user    0m7.922s
sys     0m0.825s
///