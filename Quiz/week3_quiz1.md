1.HDFS is strictly POSIX compliant.

- False

2.Following issues may be caused by lot of small files in HDFS

- NameNode memory usage increases significantly
- Network load decreases
- Number of map tasks need to process the same amount of data will be larger.
- I/O rate will be faster



3.10gb / 128megabyte ~ 80

4.20GB

5.What is the first step in a write process from a HDFS client?

- Start locally catching the data that needs to be wirtten and then contact NameNode


6.HDFS NameNode is not rack aware when it places the replica blocks.

- False
