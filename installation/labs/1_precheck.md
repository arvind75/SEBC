#Pre-check settings



* vm.swappiness=60

* cat /etc/fstab
///
UUID=9996863e-b964-47d3-a33b-3920974fdbd9 /                       ext4    defaults        1 1
tmpfs                   /dev/shm                tmpfs   defaults        0 0
devpts                  /dev/pts                devpts  gid=5,mode=620  0 0
sysfs                   /sys                    sysfs   defaults        0 0
proc                    /proc                   proc    defaults        0 0
///




*ntp service installed.

*nscd service not installed.