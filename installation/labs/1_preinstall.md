# 1) Modified hosts file
# 2) cat /etc/fstab

///
UUID=9996863e-b964-47d3-a33b-3920974fdbd9 /                       ext4    defaults        1 1
tmpfs                   /dev/shm                tmpfs   defaults        0 0
devpts                  /dev/pts                devpts  gid=5,mode=620  0 0
sysfs                   /sys                    sysfs   defaults        0 0
proc                    /proc                   proc    defaults        0 0
/dev/xvdf               /data01                 ext4    defaults,noatime,acl    0
///

# 3) nslookup for DNS check
# 4) checked MTU
# 4) yum install nscd -y
# 5) 
*Services switchoff	chkconfig iptables off
*chkconfig ip6tables off
*chkconfig postfix off
*chkconfig ntpd on
*chkconfig nscd on

# 6) modified /etc/sysctl.conf and added following


vm.swappiness = 1
vm.overcommit_memory = 1
vm.overcommit_ratio = 50
net.ipv4.ip_local_port_range = 1024 65535
net.ipv4.tcp_tw_recycle = 1
net.ipv4.tcp_tw_reuse = 1
net.ipv4.tcp_syncookies = 1
net.ipv4.tcp_sack = 1
net.ipv4.tcp_timestamps = 1
net.ipv4.tcp_mtu_probing=1
net.ipv4.tcp_max_syn_backlog = 8096
net.core.netdev_max_backlog = 25000
net.core.somaxconn = 4096
net.core.rmem_max = 4194304
net.core.rmem_default = 87380
net.core.wmem_max = 4194304
net.core.wmem_default = 4194304
net.core.optmem_max=4194304
net.ipv4.tcp_rmem =  4096 87380 4194304
net.ipv4.tcp_wmem = 4096 87380 4194304
net.ipv4.tcp_mem = 67108864 67108864 67108864
net.ipv4.route.flush=1
net.ipv4.tcp_adv_win_scale=1

# 7) Added cloudera_limits.conf in /etc/security/
///
cloudera-scm    soft  nofile  32768
cloudera-scm    soft  nproc   65536
cloudera-scm    hard  nofile  1048576
cloudera-scm    hard  nproc   unlimited
cloudera-scm    hard  memlock unlimited

hbase    soft  nofile  32768
hbase    soft  nproc   65536
hbase    hard  nofile  1048576
hbase    hard  nproc   unlimited
hbase    hard  memlock unlimited

impala    soft  nofile  32768
impala    soft  nproc   65536
impala    hard  nofile  1048576
impala    hard  nproc   unlimited
impala    hard  memlock unlimited

solr    soft  nofile  32768
solr    soft  nproc   65536
solr    hard  nofile  1048576
solr    hard  nproc   unlimited
solr    hard  memlock unlimited

hive    soft  nofile  32768
hive    soft  nproc   65536
hive    hard  nofile  1048576
hive    hard  nproc   unlimited
hive    hard  memlock unlimited

yarn    soft  nofile  32768
yarn    soft  nproc   65536
yarn    hard  nofile  1048576
yarn    hard  nproc   unlimited
yarn    hard  memlock unlimited

hdfs    soft  nofile  32768
hdfs    soft  nproc   65536
hdfs    hard  nofile  1048576
hdfs    hard  nproc   unlimited

oozie    soft  nofile  32768
oozie    soft  nproc   65536
oozie    hard  nofile  1048576
oozie    hard  nproc   unlimited

sqoop2    soft  nofile  32768
sqoop2    soft  nproc   65536
sqoop2    hard  nofile  1048576
sqoop2    hard  nproc   unlimited

kafka    soft  nofile  32768
kafka    soft  nproc   65536
kafka    hard  nofile  1048576
kafka    hard  nproc   unlimited

sentry    soft  nofile  32768
sentry    soft  nproc   65536
sentry    hard  nofile  1048576
sentry    hard  nproc   unlimited

hue    soft  nofile  32768
hue    soft  nproc   65536
hue    hard  nofile  1048576
hue    hard  nproc   unlimited
zookeeper    soft  nofile  32768
zookeeper    soft  nproc   65536
zookeeper    hard  nofile  1048576
zookeeper    hard  nproc   unlimited
zookeeper    hard  memlock unlimited

///

# 8) Checked for Transparent Huge pages. Couldn't find the enabled file, but we can place the disable command in /etc/rc.local file

# 9) Modified /etc/bashrc for ease of administration and added following
export PS1="\u@\h:\$PWD >"
///
set -o vi
alias l='ls -lrt'
alias hls="hadoop fs -ls $@"
alias hfs="hadoop fs $@"

export ALL_NODES="172.31.3.236 172.31.1.79 172.31.1.78 172.31.1.77 172.31.1.76 172.31.13.184"
///
