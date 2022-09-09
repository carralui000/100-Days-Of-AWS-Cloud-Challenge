# Topic:

Amazon Elastic MapReduce:

 - Introduction
 - Benefits of EMR
 - How to build cluster?
 - The Amazon EMR File System (EMRFS)

Amazon Kinesis:

 - Introduction
 - Uses
 - How does AWS Kinesis work?
 - Benefits of Kinesis.

# Amazon Elastic MapReduce:

 - Amazon Elastic MapReduce (EMR) is an Amazon Web Service (AWS) tool for big data 
   processing and analysis.
 - MapReduce is a software framework that allows developers to write programs that process
   massive amounts of unstructed data in parallel across a distributed cluster of processors
   as stand alone computer.
   
# Features of EMR uses and benefits:

 - Easy to use
 - Low cost
 - Elastic
 - Reliable
 - Secure
 - Flexible

# What Do I Need to Build a Cluster?

1) Choose instances
2) Choose your software
3) Choose your access method

# The Amazon EMR File System (EMRFS)

 - allow you to levearge Amazon S3 as a file system
 - Streams data directly from Amazon S3
 - Uses HOFS for intermediates
 - Better read/write performances and error handling than open source components.
 - Consistent view - consistency for read after write.
 - Support for encryption
 - Fast listing of objects

# Amazon Kinesis:

 - Amazon kinesis enables you to ingest, buffer, and process streaming data in real time, 
   so you can derive insights in seconds or minutes instead of hour or days.

# Uses:

 - Kenesis data streams can be used to collect log and events data from sources such as
   servers, desktops, and mobile devices.
 - You can build kinesis applications to continously process the data, generate metrics,
   power live dashboards, and emit aggegated data into stores such as Amazon S3.
   
# How does AWS kinesis work?

 - Kinesis data streams segregates the data records belonging to a stream into multiple
   shards. It uses the partition key that is associated with each data record to determine
   which shard a given data record belongs to. When a application put data into a stream, it    must specify a partition key.
   
# Benefits of kinesis:

 - Durability
 - Elasticily
 - Fast / less time consuming
 - Security
 - scalebility
   
