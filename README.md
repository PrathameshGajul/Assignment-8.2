Q.Explain the core changes made in Hadoop 2.x
Ans:
-Many changes were made in Hadoop 2.x as compared to Hadoop 1.x.
-The main changes that took place in hadoop 2.x are Single Point Of Failure and Decentralize JobTracker to data nodes.
-The major changes in Hadoop 2.x are:
1)Nodes limitation(4000 to unlimited)
2)Single point of failure
3)JobTracker Bottleneck
4)High availability
5)MapReduce slots are changed from static to dynamic
6)Supports interactive and graph iterative algorithms
7)It allows other applications to integrate with HDFS
8)High Scalability and supports Horizontal scalability
9)Improved cluster utilization
10)Supports multiple namespaces


Q.Explain the difference between MapReduce 1 and MapReduce 2 / Yarn
Ans:
-In Mapreduce1,Hadoop centralizes all tasks to the JobTracker.
-It also allocates the resources and scheduling the jobs across the cluster.
-It can support only a single namenode.
-So it does not provide system availability and scalability.
-In Mapreduce2/YARN, it decentralizes all tasks to ease the work pressure on the JobTracker.
-Resource Manager responsibility is to allocate resources to the particular nodes.
-Node Manager schedules the jobs on the ApplicationMaster.
-YARN allows parallel execution and ApplicationMaster managing and execute the job.
-This approach can ease most of the JobTracker problems and improves to scale up the ability and optimize the job performance.
-YARN can allow to create multiple applications to scale up on the distributed environment.
-As we can create redundant namenodes it provides high scalability and availability.
