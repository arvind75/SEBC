```
ip-172-31-40-208@root:/root >ls -l /etc/yum.repos.d
total 24
-rw-r--r--. 1 root root  272 Sep 23 09:38 cloudera-manager.repo
-rw-r--r--. 1 root root  606 Sep 23 08:33 redhat-rhui-client-config.repo
-rw-r--r--. 1 root root 6300 Sep 23 08:33 redhat-rhui.repo
-rw-r--r--. 1 root root  529 Oct 30  2013 rhel-source.repo
-rw-r--r--. 1 root root   80 Sep 23 08:33 rhui-load-balancers.conf


mysql> grant all on scm.* to 'scm'@'ip-172-31-40-208.us-west-2.compute.internal' IDENTIFIED BY 'scm_password';
Query OK, 0 rows affected (0.00 sec)

mysql> grant all on scm.* to 'scm'@'172.31.40.208' IDENTIFIED BY 'scm_password';
Query OK, 0 rows affected (0.00 sec)


2016-09-23 09:47:41,837 INFO main:com.cloudera.server.cmf.Main: Starting SCM Server. JVM Args: [-Dlog4j.configuration=file:/etc/cloudera-scm-server/log4j.properties, -Dfile.encoding=UTF-8, -Dcmf.root.logger=INFO,LOGFILE, -Dcmf.log.dir=/var/log/cloudera-scm-server, -Dcmf.log.file=cloudera-scm-server.log, -Dcmf.jetty.threshhold=WARN, -Dcmf.schema.dir=/usr/share/cmf/schema, -Djava.awt.headless=true, -Djava.net.preferIPv4Stack=true, -Dpython.home=/usr/share/cmf/python, -XX:+UseConcMarkSweepGC, -XX:+UseParNewGC, -XX:+HeapDumpOnOutOfMemoryError, -Xmx2G, -XX:MaxPermSize=256m, -XX:+HeapDumpOnOutOfMemoryError, -XX:HeapDumpPath=/tmp, -XX:OnOutOfMemoryError=kill -9 %p], Args: [], Version: 5.8.2 (#17 built by jenkins on 20160916-1426 git: d23c620f3a3bbd85d8511d6ebba49beaaab14b75)



grep "Started Jetty server" /var/log/cloudera-scm-server/cloudera-scm-server.log
2016-09-23 09:49:08,506 INFO WebServerImpl:com.cloudera.server.cmf.WebServerImpl: Started Jetty server.


```
