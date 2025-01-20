1.6 differenciete  between web services, api's and microservices
what is a web api
- using http with a shared language to do CRUD operations
- stands for application programming interface
types of web api
- composite
	- merge service and data apis
	> we will be predominatley using RESTful apis in this course utilizing Json
	
- Partner
- open 
- internal

> this section appends to the soap vs REST table present in 1.6

a microservice is best described as an autonomous application designed for a single, specific service as part of a larger application architecture. in contract, a web service acts as a strategy to facilitate service availabilit accross appliactions by using a web interface

![[Pasted image 20250120115952.png]]

1.8 Db integration with java
JDBC is the javasoft specification of a standard API that allows java apps to acces DB management systems.

ORMS
stands for object relational mapping
- technique for converting data betweem relational dbs and oop langs such as java C#
advantages
largley consists of the following entities
api for CRUS on objects of persistent classes
configurable facilityfor specifying mapping metadata
technique to interact with transactional objects to perform dirty checking, lazy associating fetching and other optimization