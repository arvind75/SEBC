```
Connecting to jdbc:hive2://ip-172-31-33-102.us-west-2.compute.internal:10000/default;principal=hive/ip-172-31-33-102.us-west-2.compute.internal@ARVIND75.NYC
Enter username for jdbc:hive2://ip-172-31-33-102.us-west-2.compute.internal:10000/default;principal=hive/ip-172-31-33-102.us-west-2.compute.internal@ARVIND75.NYC: weiner
Enter password for jdbc:hive2://ip-172-31-33-102.us-west-2.compute.internal:10000/default;principal=hive/ip-172-31-33-102.us-west-2.compute.internal@ARVIND75.NYC: ******
Connected to: Apache Hive (version 1.1.0-cdh5.7.3)
Driver: Hive JDBC (version 1.1.0-cdh5.7.3)
Transaction isolation: TRANSACTION_REPEATABLE_READ
2: jdbc:hive2://ip-172-31-33-102.us-west-2.co> SHOW TABLES;


+-----------+--+
| tab_name  |
+-----------+--+
+-----------+--+


Beeline version 1.1.0-cdh5.7.3 by Apache Hive
beeline> !connect "jdbc:hive2://ip-172-31-33-102.us-west-2.compute.internal:10000/default;principal=hive/ip-172-31-33-102.us-west-2.compute.internal@ARVIND75.NYC"
scan complete in 3ms
Connecting to jdbc:hive2://ip-172-31-33-102.us-west-2.compute.internal:10000/default;principal=hive/ip-172-31-33-102.us-west-2.compute.internal@ARVIND75.NYC
Enter username for jdbc:hive2://ip-172-31-33-102.us-west-2.compute.internal:10000/default;principal=hive/ip-172-31-33-102.us-west-2.compute.internal@ARVIND75.NYC: christie
Enter password for jdbc:hive2://ip-172-31-33-102.us-west-2.compute.internal:10000/default;principal=hive/ip-172-31-33-102.us-west-2.compute.internal@ARVIND75.NYC: ********
Connected to: Apache Hive (version 1.1.0-cdh5.7.3)
Driver: Hive JDBC (version 1.1.0-cdh5.7.3)
Transaction isolation: TRANSACTION_REPEATABLE_READ
0: jdbc:hive2://ip-172-31-33-102.us-west-2.co> show tables;
INFO  : Compiling command(queryId=hive_20160923121515_f854ad74-36e7-47c0-a603-ce98b69d7eba): show tables
INFO  : Semantic Analysis Completed
INFO  : Returning Hive schema: Schema(fieldSchemas:[FieldSchema(name:tab_name, type:string, comment:from deserializer)], properties:null)
INFO  : Completed compiling command(queryId=hive_20160923121515_f854ad74-36e7-47c0-a603-ce98b69d7eba); Time taken: 0.059 seconds
INFO  : Executing command(queryId=hive_20160923121515_f854ad74-36e7-47c0-a603-ce98b69d7eba): show tables
INFO  : Starting task [Stage-0:DDL] in serial mode
INFO  : Completed executing command(queryId=hive_20160923121515_f854ad74-36e7-47c0-a603-ce98b69d7eba); Time taken: 0.138 seconds
INFO  : OK
+-----------+--+
| tab_name  |
+-----------+--+
+-----------+--+
No rows selected (0.327 seconds)






```
