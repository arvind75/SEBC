///
 hdfs@ip-172-31-13-184:/var/lib/hadoop-hdfs >time /opt/cloudera/parcels/CDH/bin/hadoop jar /opt/cloudera/parcels/CDH/jars/hadoop-examples.jar teragen    -Ddfs.block.size=32M 100000000 /benchmark/teragen_32m
16/09/20 21:24:47 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-13-184.us-west-2.compute.internal/172.31.13.184:8032
16/09/20 21:24:48 INFO terasort.TeraSort: Generating 100000000 using 2
16/09/20 21:24:48 INFO mapreduce.JobSubmitter: number of splits:2
16/09/20 21:24:48 INFO Configuration.deprecation: dfs.block.size is deprecated. Instead, use dfs.blocksize
16/09/20 21:24:48 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1474407042043_0003
16/09/20 21:24:48 INFO impl.YarnClientImpl: Submitted application application_1474407042043_0003
16/09/20 21:24:48 INFO mapreduce.Job: The url to track the job: http://ip-172-31-13-184.us-west-2.compute.internal:8088/proxy/application_1474407042043_0003/
16/09/20 21:24:48 INFO mapreduce.Job: Running job: job_1474407042043_0003
16/09/20 21:24:54 INFO mapreduce.Job: Job job_1474407042043_0003 running in uber mode : false
16/09/20 21:24:54 INFO mapreduce.Job:  map 0% reduce 0%
16/09/20 21:25:06 INFO mapreduce.Job:  map 8% reduce 0%
16/09/20 21:25:09 INFO mapreduce.Job:  map 13% reduce 0%
16/09/20 21:25:12 INFO mapreduce.Job:  map 18% reduce 0%
16/09/20 21:25:15 INFO mapreduce.Job:  map 20% reduce 0%
16/09/20 21:25:18 INFO mapreduce.Job:  map 23% reduce 0%
16/09/20 21:25:22 INFO mapreduce.Job:  map 25% reduce 0%
16/09/20 21:25:25 INFO mapreduce.Job:  map 27% reduce 0%
16/09/20 21:25:28 INFO mapreduce.Job:  map 29% reduce 0%
16/09/20 21:25:31 INFO mapreduce.Job:  map 32% reduce 0%
16/09/20 21:25:34 INFO mapreduce.Job:  map 35% reduce 0%
16/09/20 21:25:37 INFO mapreduce.Job:  map 37% reduce 0%
16/09/20 21:25:40 INFO mapreduce.Job:  map 39% reduce 0%
16/09/20 21:25:43 INFO mapreduce.Job:  map 41% reduce 0%
16/09/20 21:25:46 INFO mapreduce.Job:  map 44% reduce 0%
16/09/20 21:25:49 INFO mapreduce.Job:  map 46% reduce 0%
16/09/20 21:25:52 INFO mapreduce.Job:  map 49% reduce 0%
16/09/20 21:25:55 INFO mapreduce.Job:  map 52% reduce 0%
16/09/20 21:25:58 INFO mapreduce.Job:  map 55% reduce 0%
16/09/20 21:26:01 INFO mapreduce.Job:  map 57% reduce 0%
16/09/20 21:26:04 INFO mapreduce.Job:  map 60% reduce 0%
16/09/20 21:26:07 INFO mapreduce.Job:  map 61% reduce 0%
16/09/20 21:26:10 INFO mapreduce.Job:  map 64% reduce 0%
16/09/20 21:26:13 INFO mapreduce.Job:  map 67% reduce 0%
16/09/20 21:26:16 INFO mapreduce.Job:  map 69% reduce 0%
16/09/20 21:26:19 INFO mapreduce.Job:  map 72% reduce 0%
16/09/20 21:26:22 INFO mapreduce.Job:  map 74% reduce 0%
16/09/20 21:26:25 INFO mapreduce.Job:  map 76% reduce 0%
16/09/20 21:26:28 INFO mapreduce.Job:  map 78% reduce 0%
16/09/20 21:26:31 INFO mapreduce.Job:  map 79% reduce 0%
16/09/20 21:26:34 INFO mapreduce.Job:  map 82% reduce 0%
16/09/20 21:26:37 INFO mapreduce.Job:  map 84% reduce 0%
16/09/20 21:26:40 INFO mapreduce.Job:  map 86% reduce 0%
16/09/20 21:26:43 INFO mapreduce.Job:  map 90% reduce 0%
16/09/20 21:26:46 INFO mapreduce.Job:  map 92% reduce 0%
16/09/20 21:26:49 INFO mapreduce.Job:  map 95% reduce 0%
16/09/20 21:26:52 INFO mapreduce.Job:  map 97% reduce 0%
16/09/20 21:26:54 INFO mapreduce.Job:  map 98% reduce 0%
16/09/20 21:26:55 INFO mapreduce.Job:  map 99% reduce 0%
16/09/20 21:26:57 INFO mapreduce.Job:  map 100% reduce 0%
16/09/20 21:26:57 INFO mapreduce.Job: Job job_1474407042043_0003 completed successfully
16/09/20 21:26:58 INFO mapreduce.Job: Counters: 31
        File System Counters
                FILE: Number of bytes read=0
                FILE: Number of bytes written=244654
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=170
                HDFS: Number of bytes written=10000000000
                HDFS: Number of read operations=8
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=4
        Job Counters
                Launched map tasks=2
                Other local map tasks=2
                Total time spent by all maps in occupied slots (ms)=238290
                Total time spent by all reduces in occupied slots (ms)=0
                Total time spent by all map tasks (ms)=238290
                Total vcore-seconds taken by all map tasks=238290
                Total megabyte-seconds taken by all map tasks=244008960
        Map-Reduce Framework
                Map input records=100000000
                Map output records=100000000
                Input split bytes=170
                Spilled Records=0
                Failed Shuffles=0
                Merged Map outputs=0
                GC time elapsed (ms)=1760
                CPU time spent (ms)=144260
                Physical memory (bytes) snapshot=425320448
                Virtual memory (bytes) snapshot=3124629504
                Total committed heap usage (bytes)=448790528
        org.apache.hadoop.examples.terasort.TeraGen$Counters
                CHECKSUM=214760662691937609
        File Input Format Counters
                Bytes Read=0
        File Output Format Counters
                Bytes Written=10000000000

real    2m13.475s
user    0m5.720s
sys     0m0.777s


///