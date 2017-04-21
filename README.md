# seeker

Taken from LinuxInsight (http://linuxinsight.com/how_fast_is_your_disk.html).  A c program to measure random I/O of a disk.  Some clones are included in the *clone/* directory, and my modifications will be added once I find them!

All credits to the original authors.

Example;

```
chad@myhost:~$ sudo ./seeker /dev/sda
Seeker v2.0, 2007-01-15, http://www.linuxinsight.com/how_fast_is_your_disk.html
Benchmarking /dev/sda [122104MB], wait 30 seconds..............................
Results: 14847 seeks/second, 0.07 ms random access time
```
