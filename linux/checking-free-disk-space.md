# Linux / Unix: Checking Free Disk Space

Scared your server might be running on low disk space?

Run this command to find out:

```bash
$ df -h
```

**Output**

```bash
Filesystem      Size  Used Avail Use% Mounted on
/dev/vda1        79G  7.5G   68G  10% /
none            4.0K     0  4.0K   0% /sys/fs/cgroup
udev            4.0G  4.0K  4.0G   1% /dev
tmpfs           812M  2.9M  809M   1% /run
none            5.0M     0  5.0M   0% /run/lock
none            4.0G  4.0K  4.0G   1% /run/shm
none            100M     0  100M   0% /run/user
```
