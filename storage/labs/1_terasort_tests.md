
#time /opt/cloudera/parcels/CDH/bin/hadoop jar /opt/cloudera/parcels/CDH/jars/hadoop-examples.jar terasort  /benchmark/teragen /benchmark/terasort

///

16/09/20 17:59:38 INFO mapreduce.Job: Job job_1474407042043_0001 completed successfully
16/09/20 17:59:38 INFO mapreduce.Job: Counters: 50
        File System Counters
                FILE: Number of bytes read=4484163881
                FILE: Number of bytes written=8898135925
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=10000008625
                HDFS: Number of bytes written=10000000000
                HDFS: Number of read operations=249
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=16
        Job Counters
                Launched map tasks=75
                Launched reduce tasks=8
                Data-local map tasks=73
                Rack-local map tasks=2
                Total time spent by all maps in occupied slots (ms)=1130220
                Total time spent by all reduces in occupied slots (ms)=408727
                Total time spent by all map tasks (ms)=1130220
                Total time spent by all reduce tasks (ms)=408727
                Total vcore-seconds taken by all map tasks=1130220
                Total vcore-seconds taken by all reduce tasks=408727
                Total megabyte-seconds taken by all map tasks=1157345280
                Total megabyte-seconds taken by all reduce tasks=418536448
        Map-Reduce Framework
                Map input records=100000000
                Map output records=100000000
                Map output bytes=10200000000
                Map output materialized bytes=4403697747
                Input split bytes=8625
                Combine input records=0
                Combine output records=0
                Reduce input groups=100000000
                Reduce shuffle bytes=4403697747
                Reduce input records=100000000
                Reduce output records=100000000
                Spilled Records=200000000
                Shuffled Maps =600
                Failed Shuffles=0
                Merged Map outputs=600
                GC time elapsed (ms)=23426
                CPU time spent (ms)=1007760
                Physical memory (bytes) snapshot=47584833536
                Virtual memory (bytes) snapshot=129926516736
                Total committed heap usage (bytes)=57372311552
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
16/09/20 17:59:38 INFO terasort.TeraSort: done

real    2m43.982s
user    0m8.189s
sys     0m0.876s

///