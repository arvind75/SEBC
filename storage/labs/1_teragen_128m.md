///
time /opt/cloudera/parcels/CDH/bin/hadoop jar /opt/cloudera/parcels/CDH/jars/hadoop-examples.jar teragen    -Ddfs.block.size=128M 100000000 /benchmark/teragen_128m
16/09/20 21:35:51 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-13-184.us-west-2.compute.internal/172.31.13.184:8032
16/09/20 21:35:52 INFO terasort.TeraSort: Generating 100000000 using 2
16/09/20 21:35:52 INFO mapreduce.JobSubmitter: number of splits:2
16/09/20 21:35:52 INFO Configuration.deprecation: dfs.block.size is deprecated. Instead, use dfs.blocksize
16/09/20 21:35:52 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1474407042043_0005
16/09/20 21:35:52 INFO impl.YarnClientImpl: Submitted application application_1474407042043_0005
16/09/20 21:35:52 INFO mapreduce.Job: The url to track the job: http://ip-172-31-13-184.us-west-2.compute.internal:8088/proxy/application_1474407042043_0005/
16/09/20 21:35:52 INFO mapreduce.Job: Running job: job_1474407042043_0005
16/09/20 21:35:58 INFO mapreduce.Job: Job job_1474407042043_0005 running in uber mode : false
16/09/20 21:35:58 INFO mapreduce.Job:  map 0% reduce 0%
16/09/20 21:36:10 INFO mapreduce.Job:  map 8% reduce 0%
16/09/20 21:36:14 INFO mapreduce.Job:  map 13% reduce 0%
16/09/20 21:36:17 INFO mapreduce.Job:  map 15% reduce 0%
16/09/20 21:36:20 INFO mapreduce.Job:  map 17% reduce 0%
16/09/20 21:36:23 INFO mapreduce.Job:  map 19% reduce 0%
16/09/20 21:36:26 INFO mapreduce.Job:  map 22% reduce 0%
16/09/20 21:36:29 INFO mapreduce.Job:  map 24% reduce 0%
16/09/20 21:36:32 INFO mapreduce.Job:  map 25% reduce 0%
16/09/20 21:36:35 INFO mapreduce.Job:  map 27% reduce 0%
16/09/20 21:36:38 INFO mapreduce.Job:  map 29% reduce 0%
16/09/20 21:36:41 INFO mapreduce.Job:  map 31% reduce 0%
16/09/20 21:36:44 INFO mapreduce.Job:  map 34% reduce 0%
16/09/20 21:36:47 INFO mapreduce.Job:  map 36% reduce 0%
16/09/20 21:36:50 INFO mapreduce.Job:  map 38% reduce 0%
16/09/20 21:36:53 INFO mapreduce.Job:  map 40% reduce 0%
16/09/20 21:36:56 INFO mapreduce.Job:  map 44% reduce 0%
16/09/20 21:36:59 INFO mapreduce.Job:  map 46% reduce 0%
16/09/20 21:37:02 INFO mapreduce.Job:  map 48% reduce 0%
16/09/20 21:37:05 INFO mapreduce.Job:  map 49% reduce 0%
16/09/20 21:37:08 INFO mapreduce.Job:  map 53% reduce 0%
16/09/20 21:37:11 INFO mapreduce.Job:  map 55% reduce 0%
16/09/20 21:37:15 INFO mapreduce.Job:  map 57% reduce 0%
16/09/20 21:37:18 INFO mapreduce.Job:  map 61% reduce 0%
16/09/20 21:37:21 INFO mapreduce.Job:  map 63% reduce 0%
16/09/20 21:37:24 INFO mapreduce.Job:  map 66% reduce 0%
16/09/20 21:37:27 INFO mapreduce.Job:  map 68% reduce 0%
16/09/20 21:37:30 INFO mapreduce.Job:  map 70% reduce 0%
16/09/20 21:37:33 INFO mapreduce.Job:  map 72% reduce 0%
16/09/20 21:37:36 INFO mapreduce.Job:  map 74% reduce 0%
16/09/20 21:37:39 INFO mapreduce.Job:  map 77% reduce 0%
16/09/20 21:37:42 INFO mapreduce.Job:  map 80% reduce 0%
16/09/20 21:37:45 INFO mapreduce.Job:  map 82% reduce 0%
16/09/20 21:37:48 INFO mapreduce.Job:  map 83% reduce 0%
16/09/20 21:37:51 INFO mapreduce.Job:  map 85% reduce 0%
16/09/20 21:37:54 INFO mapreduce.Job:  map 87% reduce 0%
16/09/20 21:37:57 INFO mapreduce.Job:  map 89% reduce 0%
16/09/20 21:38:01 INFO mapreduce.Job:  map 91% reduce 0%
16/09/20 21:38:05 INFO mapreduce.Job:  map 95% reduce 0%
16/09/20 21:38:07 INFO mapreduce.Job:  map 97% reduce 0%
16/09/20 21:38:11 INFO mapreduce.Job:  map 98% reduce 0%
16/09/20 21:38:14 INFO mapreduce.Job:  map 100% reduce 0%
16/09/20 21:38:15 INFO mapreduce.Job: Job job_1474407042043_0005 completed successfully
16/09/20 21:38:15 INFO mapreduce.Job: Counters: 31
        File System Counters
                FILE: Number of bytes read=0
                FILE: Number of bytes written=244658
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
                Total time spent by all maps in occupied slots (ms)=262433
                Total time spent by all reduces in occupied slots (ms)=0
                Total time spent by all map tasks (ms)=262433
                Total vcore-seconds taken by all map tasks=262433
                Total megabyte-seconds taken by all map tasks=268731392
        Map-Reduce Framework
                Map input records=100000000
                Map output records=100000000
                Input split bytes=170
                Spilled Records=0
                Failed Shuffles=0
                Merged Map outputs=0
                GC time elapsed (ms)=1664
                CPU time spent (ms)=143000
                Physical memory (bytes) snapshot=459395072
                Virtual memory (bytes) snapshot=3129298944
                Total committed heap usage (bytes)=457703424
        org.apache.hadoop.examples.terasort.TeraGen$Counters
                CHECKSUM=214760662691937609
        File Input Format Counters
                Bytes Read=0
        File Output Format Counters
                Bytes Written=10000000000

real    2m26.652s
user    0m6.340s
sys     0m0.738s


///