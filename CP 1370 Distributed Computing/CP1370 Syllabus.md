**COURSE NUMBER:** CP1370 

**COURSE TITLE:** Distributed Computing  

**COURSE DESCRIPTION:** 

This course aims to equip students with a rounded comprehension of Distributed Computing and  
Apache Spark. It covers a spectrum of concepts and practical implementations, showing the core  
principles of distributed computing and their integration within modern data processing  
frameworks.  
Commencing with an analysis of distributed computing, students will know its relevance through  
practical scenarios illustrating its proficiency in managing extensive data processing operations.  
Exploring elements like the Hadoop Distributed File System (HDFS) and Spark, students will  
examine data processing functionalities incorporating transformations, actions, and fault  
tolerance mechanisms.  
Upon completion, participants will possess the proficiency and insights needed to navigate  
distributed computing landscapes adeptly while harnessing the capabilities offered by Apache  
Spark.

**PREREQUISITES:** 
CP2280 - Object-Oriented Programming in Java  
CP1895 – Advanced Python Programming  

**CO-REQUISTIES:** None  

**CARGANIE UNIT:** Three (3)  
**CREDIT VALUE:** Four (4) 

|Lecture Type  |credit hours   |
|---|---|
|COURSE HOURS PER WEEK:| Three (3)  |
|LAB HOURS PER WEEK: |Three (3)  |
|Total|Six (6)|

**REQUIRED TEXT:**  
***Hien, L. Beginning Apache Spark 3. (2021)***. 
Apress. 
Print ISBN: 9781484273821
eText ISBN: 9781484273838

**LEARNING RESOURCES**:  
***Perrin, J. Spark in Action, Second Edition (2020)***. 
Manning Publications. 
Print ISBN:  9781617295522
eText ISBN: 9781638351306
## MAJOR TOPICS:  
1. Concepts of Distributed Computing  
2. Spark Core  
3. Spark SQL  
4. Spark Streaming  
## LEARNING OBJECTIVES:  
1. Concepts of Distributed Computing  
	1. Define distributed computing  
		1. Explain the principles of distributed computing  
		2. Discuss parallelism, fault tolerance, and scalability  
		3. Provide examples of scenarios where distributed computing is advantageous  
	2. Describe the architecture and components of the Hadoop ecosystem  
		1. Examine the core components of [Hadoop](Hadoop), including:  
			1. [HDFS](Hadoop#HDFS)
			2. [MapReduce](Hadoop#MapReduce)  
			3. [YARN](Hadoop#YARN)  
		2. Describe the roles of Hadoop components in a cluster  
		3. Explain the advantages of using the Hadoop ecosystem for distributed computing  
	3. Work with Hadoop Distributed File System (HDFS)  
		1. Explore the structure of HDFS  
		2. Interact with HDFS through command-line tools  
		3. Discuss the importance of data replication in HDFS and its impact on fault tolerance  
		4. Set up a Virtual Hadoop environment  
			1. Configure Hadoop on a multi-node cluster  
			2. Perform cluster management and security considerations  
			3. Configure nodes for optimal performance and resource utilization  
			4. Test the cluster setup with development commands  
2. Spark Core  
	1. Discuss the role of Spark Core in the Apache Spark ecosystem  
	2. Differentiate between Spark Core and other Spark libraries such as Spark SQL and Spark Streaming  
	3. Discuss various data processing scenarios where Spark Core is commonly used  
		1. Discuss Spark DataFrames, transformations, and actions
		2. Discuss how Spark Core manages data across clusters  
		3. Discuss the lazy evaluation mechanism and lineage in Spark DataFrames  
		4. Describe various data sources compatible with Spark DataFrames such as HDF and local files  
		5. Create Spark DataFrames including parallelizing collections and loading external data  
	4. Differentiate between Spark transformations and actions  
	5. Utilize Spark Core’s transformations such as (but not limited to):  
		1. Map  
		2. Filter  
		3. reducyByKey  
	6. Complete actions such as (but not limited to):  
		1. Count  
		2. Collect  
		3. SaveAsTextFile  
	7. Discuss how Spark Core leverages parallel processing  
		1. Implement the execution plan and job scheduling within Spark applications  
		2. Analyze the relationship between Spark Cluster’s  
			1. Partitions  
			2. Tasks  
			3. Nodes  
	8. Discuss how Spark Core provides fault tolerance through lineage information  
		1. Utilize checkpoints and data lineage  
		2. Discuss how fault tolerance mechanisms contribute to data processing  
	9. Develop Spark Core applications to process and analyze datasets  
	10. Use transformations, actions, and Spark DataFrame operations  
3. Spark SQL  
	1. Utilize Spark SQL for Data Processing  
		1. Discuss the role of Spark SQL in performing SQL-like queries on structured data  
		2. Discuss the advantages of using Spark SQL for data processing tasks  
		3. Explain how Spark SQL can handle both structured and semi-structured data  
		4. Utilize Spark SQL for Data Processing
	2. Discuss the concept of DataFrames and Datasets as concepts in Spark SQL  
		1. Create DataFrames and Datasets  
			1. Manipulate DataFrames and Datasets 
			2. Transform DataFrames and Datasets  
		2. Differentiate between DataFrames and RDDs in terms of optimization and performance  
	3. Write SQL queries in Spark SQL using Python  
		1. Execute SQL queries in Spark SQL using Python  
		2. Discuss the integration of SQL queries with Spark Core  
		3. Analyze how to work with complex data types and functions within Spark SQ  
	4. Discuss the advantages of the Parquet and Avro data formats  
	5. Work with Parquet and Avro data in Spark SQL  
	6. Discuss the benefits of columnar storage and schema evolution  
	7. Apply Spark SQL to projects using Python  
		1. Develop Spark SQL applications that involve:  
			1. Reading  
			2. Processing  
			3. Analyzing structured data  
		2. Utilize Spark SQL's capabilities to solve specific business use cases  
4. Spark Streaming  
	1. Discuss Spark Streaming and its applications for real-time data processing  
		1. Explore the key differences between batch processing and streaming processing  
		2. Discuss the advantages of using Spark Streaming in various industries and use cases
		3. Implement Spark Streaming for real-time data processing  
	2. Explain Discretized Streams (DStreams) role in stream processing  
		1. Create DStreams for real-time data analysis and transformations  
		2. Manipulate DStreams for real-time data analysis and transformations  
		3. Compare DStreams to other stream processing technologies  
	3. Implement Spark Streaming applications using Python  
		1. Work with Python libraries and APIs to connect with Spark Streaming  
		2. Analyze the performance benefits and limitations of Python in Spark Streaming applications  
	4. Discuss window operations in Spark Streaming for time-based data analysis  
		1. Apply sliding and tumbling windows to segment and analyze streaming data  
	5. Integrate Spark Streaming with a data source  
		1. Implement a data ingestion system for real-time stream processing  
		2. Analyze the benefits of stream processing applications  
	6. Discuss the importance of fault tolerance in Spark Streaming applications  
		1. Explore mechanisms for handling failures and ensuring data reliability  
		2. Implement strategies to maintain uninterrupted stream processing  
	7. Utilize Python to develop Spark Streaming applications  
	8. Build end-to-end streaming applications for specific business use cases  
## EVALUATION: 

| Type        | Percentyle |
| ----------- | ---------- |
| Assignments | 30%        |
| Project     | 20%        |
| Tests       | 20%        |
| Final Exam  | 30%        |

This course is supplementary eligible.  
DATE DEVELOPED: November 2023 DATE REVIEWED:  
REVISION NUMBER: DATE REVISED:  
Effective PeopleSoft Date: September 2022  
Note to instructor: Check PIRS to ensure this outline is the most current version.
