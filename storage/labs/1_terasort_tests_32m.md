///

hdfs@ip-172-31-13-184:/var/lib/hadoop-hdfs >time /opt/cloudera/parcels/CDH/bin/hadoop jar /opt/cloudera/parcels/CDH/jars/hadoop-examples.jar terasort  /benchmark/teragen_32m /benchmark/terasort
16/09/20 21:29:13 INFO terasort.TeraSort: starting
16/09/20 21:29:15 INFO input.FileInputFormat: Total input paths to process : 2
Spent 236ms computing base-splits.
Spent 6ms computing TeraScheduler splits.
Computing input splits took 243ms
Sampling 10 splits of 298
Making 8 from 100000 sampled records
Computing parititions took 978ms
Spent 1223ms computing partitions.
16/09/20 21:29:16 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-13-184.us-west-2.compute.internal/172.31.13.184:8032
16/09/20 21:29:16 INFO mapreduce.JobSubmitter: number of splits:298
16/09/20 21:29:17 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1474407042043_0004
16/09/20 21:29:17 INFO impl.YarnClientImpl: Submitted application application_1474407042043_0004
16/09/20 21:29:17 INFO mapreduce.Job: The url to track the job: http://ip-172-31-13-184.us-west-2.compute.internal:8088/proxy/application_1474407042043_0004/
16/09/20 21:29:17 INFO mapreduce.Job: Running job: job_1474407042043_0004
16/09/20 21:29:24 INFO mapreduce.Job: Job job_1474407042043_0004 running in uber mode : false
16/09/20 21:29:24 INFO mapreduce.Job:  map 0% reduce 0%
16/09/20 21:29:35 INFO mapreduce.Job:  map 2% reduce 0%
16/09/20 21:29:36 INFO mapreduce.Job:  map 3% reduce 0%
16/09/20 21:29:38 INFO mapreduce.Job:  map 4% reduce 0%
16/09/20 21:29:46 INFO mapreduce.Job:  map 6% reduce 0%
16/09/20 21:29:47 INFO mapreduce.Job:  map 7% reduce 0%
16/09/20 21:29:52 INFO mapreduce.Job:  map 9% reduce 0%
16/09/20 21:29:56 INFO mapreduce.Job:  map 10% reduce 0%
16/09/20 21:29:57 INFO mapreduce.Job:  map 11% reduce 0%
16/09/20 21:29:58 INFO mapreduce.Job:  map 12% reduce 0%
16/09/20 21:30:05 INFO mapreduce.Job:  map 13% reduce 0%
16/09/20 21:30:06 INFO mapreduce.Job:  map 14% reduce 0%
16/09/20 21:30:07 INFO mapreduce.Job:  map 15% reduce 0%
16/09/20 21:30:09 INFO mapreduce.Job:  map 16% reduce 0%
16/09/20 21:30:15 INFO mapreduce.Job:  map 17% reduce 0%
16/09/20 21:30:18 INFO mapreduce.Job:  map 19% reduce 0%
16/09/20 21:30:20 INFO mapreduce.Job:  map 20% reduce 0%
16/09/20 21:30:25 INFO mapreduce.Job:  map 21% reduce 0%
16/09/20 21:30:28 INFO mapreduce.Job:  map 22% reduce 0%
16/09/20 21:30:32 INFO mapreduce.Job:  map 23% reduce 0%
16/09/20 21:30:33 INFO mapreduce.Job:  map 24% reduce 0%
16/09/20 21:30:34 INFO mapreduce.Job:  map 25% reduce 0%
16/09/20 21:30:36 INFO mapreduce.Job:  map 26% reduce 0%
16/09/20 21:30:40 INFO mapreduce.Job:  map 27% reduce 0%
16/09/20 21:30:43 INFO mapreduce.Job:  map 28% reduce 0%
16/09/20 21:30:46 INFO mapreduce.Job:  map 29% reduce 0%
16/09/20 21:30:47 INFO mapreduce.Job:  map 30% reduce 0%
16/09/20 21:30:48 INFO mapreduce.Job:  map 31% reduce 0%
16/09/20 21:30:51 INFO mapreduce.Job:  map 32% reduce 0%
16/09/20 21:30:56 INFO mapreduce.Job:  map 33% reduce 0%
16/09/20 21:30:58 INFO mapreduce.Job:  map 34% reduce 0%
16/09/20 21:30:59 INFO mapreduce.Job:  map 35% reduce 0%
16/09/20 21:31:01 INFO mapreduce.Job:  map 36% reduce 0%
16/09/20 21:31:03 INFO mapreduce.Job:  map 37% reduce 0%
16/09/20 21:31:08 INFO mapreduce.Job:  map 38% reduce 0%
16/09/20 21:31:09 INFO mapreduce.Job:  map 39% reduce 0%
16/09/20 21:31:14 INFO mapreduce.Job:  map 41% reduce 0%
16/09/20 21:31:18 INFO mapreduce.Job:  map 42% reduce 0%
16/09/20 21:31:19 INFO mapreduce.Job:  map 43% reduce 0%
16/09/20 21:31:23 INFO mapreduce.Job:  map 44% reduce 0%
16/09/20 21:31:26 INFO mapreduce.Job:  map 45% reduce 0%
16/09/20 21:31:28 INFO mapreduce.Job:  map 47% reduce 0%
16/09/20 21:31:31 INFO mapreduce.Job:  map 48% reduce 0%
16/09/20 21:31:35 INFO mapreduce.Job:  map 49% reduce 0%
16/09/20 21:31:38 INFO mapreduce.Job:  map 50% reduce 0%
16/09/20 21:31:40 INFO mapreduce.Job:  map 51% reduce 0%
16/09/20 21:31:41 INFO mapreduce.Job:  map 52% reduce 0%
16/09/20 21:31:46 INFO mapreduce.Job:  map 53% reduce 0%
16/09/20 21:31:48 INFO mapreduce.Job:  map 54% reduce 0%
16/09/20 21:31:49 INFO mapreduce.Job:  map 55% reduce 0%
16/09/20 21:31:53 INFO mapreduce.Job:  map 56% reduce 0%
16/09/20 21:31:55 INFO mapreduce.Job:  map 57% reduce 0%
16/09/20 21:31:58 INFO mapreduce.Job:  map 58% reduce 0%
16/09/20 21:31:59 INFO mapreduce.Job:  map 59% reduce 0%
16/09/20 21:32:01 INFO mapreduce.Job:  map 60% reduce 0%
16/09/20 21:32:06 INFO mapreduce.Job:  map 61% reduce 0%
16/09/20 21:32:07 INFO mapreduce.Job:  map 62% reduce 0%
16/09/20 21:32:08 INFO mapreduce.Job:  map 63% reduce 0%
16/09/20 21:32:11 INFO mapreduce.Job:  map 64% reduce 0%
16/09/20 21:32:16 INFO mapreduce.Job:  map 65% reduce 0%
16/09/20 21:32:18 INFO mapreduce.Job:  map 66% reduce 0%
16/09/20 21:32:19 INFO mapreduce.Job:  map 67% reduce 0%
16/09/20 21:32:21 INFO mapreduce.Job:  map 68% reduce 0%
16/09/20 21:32:25 INFO mapreduce.Job:  map 69% reduce 0%
16/09/20 21:32:27 INFO mapreduce.Job:  map 70% reduce 0%
16/09/20 21:32:29 INFO mapreduce.Job:  map 71% reduce 0%
16/09/20 21:32:32 INFO mapreduce.Job:  map 72% reduce 0%
16/09/20 21:32:35 INFO mapreduce.Job:  map 73% reduce 0%
16/09/20 21:32:37 INFO mapreduce.Job:  map 74% reduce 0%
16/09/20 21:32:38 INFO mapreduce.Job:  map 75% reduce 0%
16/09/20 21:32:41 INFO mapreduce.Job:  map 76% reduce 0%
16/09/20 21:32:45 INFO mapreduce.Job:  map 77% reduce 0%
16/09/20 21:32:46 INFO mapreduce.Job:  map 78% reduce 0%
16/09/20 21:32:48 INFO mapreduce.Job:  map 79% reduce 0%
16/09/20 21:32:49 INFO mapreduce.Job:  map 80% reduce 0%
16/09/20 21:32:55 INFO mapreduce.Job:  map 81% reduce 0%
16/09/20 21:32:57 INFO mapreduce.Job:  map 82% reduce 0%
16/09/20 21:32:58 INFO mapreduce.Job:  map 83% reduce 0%
16/09/20 21:33:00 INFO mapreduce.Job:  map 84% reduce 0%
16/09/20 21:33:02 INFO mapreduce.Job:  map 85% reduce 0%
16/09/20 21:33:08 INFO mapreduce.Job:  map 85% reduce 3%
16/09/20 21:33:09 INFO mapreduce.Job:  map 85% reduce 5%
16/09/20 21:33:10 INFO mapreduce.Job:  map 85% reduce 7%
16/09/20 21:33:11 INFO mapreduce.Job:  map 85% reduce 10%
16/09/20 21:33:12 INFO mapreduce.Job:  map 85% reduce 12%
16/09/20 21:33:14 INFO mapreduce.Job:  map 86% reduce 14%
16/09/20 21:33:15 INFO mapreduce.Job:  map 86% reduce 16%
16/09/20 21:33:16 INFO mapreduce.Job:  map 87% reduce 18%
16/09/20 21:33:17 INFO mapreduce.Job:  map 87% reduce 20%
16/09/20 21:33:18 INFO mapreduce.Job:  map 87% reduce 21%
16/09/20 21:33:19 INFO mapreduce.Job:  map 87% reduce 22%
16/09/20 21:33:21 INFO mapreduce.Job:  map 87% reduce 24%
16/09/20 21:33:22 INFO mapreduce.Job:  map 87% reduce 25%
16/09/20 21:33:26 INFO mapreduce.Job:  map 88% reduce 25%
16/09/20 21:33:28 INFO mapreduce.Job:  map 88% reduce 26%
16/09/20 21:33:29 INFO mapreduce.Job:  map 89% reduce 26%
16/09/20 21:33:35 INFO mapreduce.Job:  map 90% reduce 26%
16/09/20 21:33:40 INFO mapreduce.Job:  map 91% reduce 26%
16/09/20 21:33:43 INFO mapreduce.Job:  map 92% reduce 26%
16/09/20 21:33:44 INFO mapreduce.Job:  map 92% reduce 27%
16/09/20 21:33:52 INFO mapreduce.Job:  map 93% reduce 27%
16/09/20 21:33:54 INFO mapreduce.Job:  map 94% reduce 27%
16/09/20 21:33:59 INFO mapreduce.Job:  map 94% reduce 28%
16/09/20 21:34:00 INFO mapreduce.Job:  map 95% reduce 28%
16/09/20 21:34:06 INFO mapreduce.Job:  map 96% reduce 28%
16/09/20 21:34:07 INFO mapreduce.Job:  map 97% reduce 28%
16/09/20 21:34:13 INFO mapreduce.Job:  map 98% reduce 28%
16/09/20 21:34:19 INFO mapreduce.Job:  map 99% reduce 29%
16/09/20 21:34:21 INFO mapreduce.Job:  map 100% reduce 29%
16/09/20 21:34:26 INFO mapreduce.Job:  map 100% reduce 34%
16/09/20 21:34:27 INFO mapreduce.Job:  map 100% reduce 42%
16/09/20 21:34:28 INFO mapreduce.Job:  map 100% reduce 50%
16/09/20 21:34:29 INFO mapreduce.Job:  map 100% reduce 61%
16/09/20 21:34:30 INFO mapreduce.Job:  map 100% reduce 62%
16/09/20 21:34:31 INFO mapreduce.Job:  map 100% reduce 63%
16/09/20 21:34:32 INFO mapreduce.Job:  map 100% reduce 65%
16/09/20 21:34:33 INFO mapreduce.Job:  map 100% reduce 66%
16/09/20 21:34:34 INFO mapreduce.Job:  map 100% reduce 68%
16/09/20 21:34:35 INFO mapreduce.Job:  map 100% reduce 71%
16/09/20 21:34:36 INFO mapreduce.Job:  map 100% reduce 72%
16/09/20 21:34:37 INFO mapreduce.Job:  map 100% reduce 73%
16/09/20 21:34:38 INFO mapreduce.Job:  map 100% reduce 77%
16/09/20 21:34:39 INFO mapreduce.Job:  map 100% reduce 79%
16/09/20 21:34:40 INFO mapreduce.Job:  map 100% reduce 80%
16/09/20 21:34:41 INFO mapreduce.Job:  map 100% reduce 82%
16/09/20 21:34:42 INFO mapreduce.Job:  map 100% reduce 83%
16/09/20 21:34:43 INFO mapreduce.Job:  map 100% reduce 84%
16/09/20 21:34:44 INFO mapreduce.Job:  map 100% reduce 87%
16/09/20 21:34:45 INFO mapreduce.Job:  map 100% reduce 88%
16/09/20 21:34:46 INFO mapreduce.Job:  map 100% reduce 89%
16/09/20 21:34:47 INFO mapreduce.Job:  map 100% reduce 93%
16/09/20 21:34:48 INFO mapreduce.Job:  map 100% reduce 94%
16/09/20 21:34:49 INFO mapreduce.Job:  map 100% reduce 95%
16/09/20 21:34:50 INFO mapreduce.Job:  map 100% reduce 97%
16/09/20 21:34:53 INFO mapreduce.Job:  map 100% reduce 99%
16/09/20 21:34:56 INFO mapreduce.Job:  map 100% reduce 100%
16/09/20 21:34:57 INFO mapreduce.Job: Job job_1474407042043_0004 completed successfully
16/09/20 21:34:57 INFO mapreduce.Job: Counters: 50
        File System Counters
                FILE: Number of bytes read=4471113965
                FILE: Number of bytes written=8884001731
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=10000035462
                HDFS: Number of bytes written=10000000000
                HDFS: Number of read operations=918
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=16
        Job Counters
                Launched map tasks=298
                Launched reduce tasks=8
                Data-local map tasks=297
                Rack-local map tasks=1
                Total time spent by all maps in occupied slots (ms)=2926529
                Total time spent by all reduces in occupied slots (ms)=824611
                Total time spent by all map tasks (ms)=2926529
                Total time spent by all reduce tasks (ms)=824611
                Total vcore-seconds taken by all map tasks=2926529
                Total vcore-seconds taken by all reduce tasks=824611
                Total megabyte-seconds taken by all map tasks=2996765696
                Total megabyte-seconds taken by all reduce tasks=844401664
        Map-Reduce Framework
                Map input records=100000000
                Map output records=100000000
                Map output bytes=10200000000
                Map output materialized bytes=4375004118
                Input split bytes=35462
                Combine input records=0
                Combine output records=0
                Reduce input groups=100000000
                Reduce shuffle bytes=4375004118
                Reduce input records=100000000
                Reduce output records=100000000
                Spilled Records=200000000
                Shuffled Maps =2384
                Failed Shuffles=0
                Merged Map outputs=2384
                GC time elapsed (ms)=38800
                CPU time spent (ms)=1546160
                Physical memory (bytes) snapshot=147228581888
                Virtual memory (bytes) snapshot=479180533760
                Total committed heap usage (bytes)=173533560832
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
16/09/20 21:34:57 INFO terasort.TeraSort: done

real    5m45.321s
user    0m9.746s
sys     0m0.960s

///