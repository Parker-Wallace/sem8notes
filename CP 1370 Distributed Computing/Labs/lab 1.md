***Due Date***: Janurary 22nd
Lab #1 Big Data and Hadoop File System ( total 64 marks)  
Parts 1 and 2 are to be done using a Google Cloud DataProc cluster  
# Part 1: HDFS file system commands  
## Choose 5 HDFS file system commands. (20 marks)

For each command provide a description of the command and run the command on the DataProc  
master node. Capture a screenshot of the output from running the command **( 4 marks each )**
>[!note] these must be file system HDFS commands, so something like “hadoop version” does not count


For reference, there are two links posted on d2l related to Hadoop file system commands.  
## Part 2: Map Reduce Exercise (20 marks) 
> (You may use AI to help you with your Map Reduce code. Be Sure you understand and can explain any code which you use though)
1. The file “movieRatings.txt” contains movie ratings data.  
Each row contains 4 pieces of data.  
From left to right, we have USERID MOVIENAME RATING TIMESTAMP  
For example, for the line “182 Terminator2 5 860279251”,  
182 is the USERID, Terminator2 is the MOVIENAME, 5 is the RATING and 860279251 is the TIMESTAMP  
Write a complete Map Reduce program which contains a Mapper class, a Reducer class and a Job class.  
The Map Reduce Program should output the number of occurrences of each rating. Please note that  
ratings range from 1 to 5. Submit the source code for the map reduce program, the compiled .jar file  
and the text output. ( 20 marks)  
For reference, there are a two links posted on d2l related to MapReduce programs. Specifically Eric  
demonstrated building a .jar file and running it from this link: https://medium.com/@mufasadev/word-  
count-with-mapreduce-in-hadoop-and-java-210c38afba11  
Bonus (5 marks)  
Modify the program in part #1 to only include ratings from Tom Cruise movies.  
Part 3: Questions (24 marks) ( please note that you must complete the exercises before tackling the  
questions. If the exercises are not done, I will not be marking the questions) ( You are not to use AI to  
answer these questions)  
Answer Questions #1 - #6 pg 690 Chapter14Database.pdf (4 marks each)

[link](https://medium.com/@mufasadev/word-count-with-mapreduce-in-hadoop-and-java-210c38afba11 "https://medium.com/@mufasadev/word-count-with-mapreduce-in-hadoop-and-java-210c38afba11")

| Evaluation | Value |
| ---------- | ----- |
