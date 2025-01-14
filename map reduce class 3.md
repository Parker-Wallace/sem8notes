open source by google!![[Pasted image 20250114105812.png]]

- its an api or a set of libraries runnbale on commodity hardware
	- cheap 
	- able to do mass computation
- job - unit o fmapreduce work instnace
- map task -  runs on each worker node
- reduce task - runs on some worker nodes
- input data

MAP

executes the map() function on each node
outputs <key, value> pairs on each node


REDUCE
executes the reduce() function on some nodes
	this is key for optimization
aggregated sets of key, value  pairs on some nodes 
outputs a combines list 

> [!tip]- Some MapReduce Pseudocode
>
>```Java
>public class MapReduce {
>	Public static void Main(String[] args)
>	{
>		//create JobrunnerInstance
>		//call MapInstance on obInstance
>		//call ReduceInstance on JobInstance
>	}
>	public static void Map()
>	{
>		//write Mapper
>	}
>	public static void Reduce()
>	{
>		//write Reduceer
>	}
>} 
>```


HelloWorld equivelant example for mapreduce 
"word count" function
takes some text as input
produces a list of words and counts them
**key area** what is a word - consider for optimization and key when thinking about mapreduce 

word count example diagram 
```mermaid
---
title: A Simple Word Count MapReduce Job
---
flowchart LR
subgraph Input
A[Deer Bear River\nCar Car River\nDeer Car Bear]
end
subgraph Split
B[Deer Bear River]
C[Car Car River]
D[Deer Car Bear]
A --> B & C & D
end
subgraph Map
E[Deer, 1\nBear, 1\nRiver, 1]
F[Car, 1\nCar, 1\nRiver, 1]
G[Deer, 1\nCar, 1\nBear, 1]
B --> E
C --> F
D --> G
end
subgraph Shuffle
H[Bear, 1\nBear, 1]
I[Car, 1\nCar, 1\nCar, 1]
J[Deer, 1\nDeer, 1]
K[River, 1\nRiver, 1]
E --> H & J & K
F --> I & I & K
G --> J & I & H
end
subgraph Reduce
L[Bear, 2]
M[Car, 3]
N[Deer, 2]
O[River, 2]
H --> L
I --> M
J --> N
K --> O
end
subgraph Results
P[Bear, 2\nCar, 3\nDeer, 2\nRiver, 2]
L & M & N & O --> P
end
```
MAPREDUCE job output 
"success" to console
series of txt files
immutable if stored in hdfs
each run requires new file name
usually appends runtime to file name

DAEMONS and servoces for MapReduce
- JVMS or services - isolated processes which alllows for scalablility
	- job trakcer - one (controller and scheduler)
	- task tracker - one per cluser (mniter tasks)
- job configurations
	- speecify i/o locations for job instances
	- job clients submit jobs for execuction

MR job status and logs
- monitor job run ststus
- local websites
- logs
- troubleshooting failed job runs
- err logs (standard out and standard err logs)