# Simple_SpringBoot_REST
1. This is a very basic program to understand REST API Implementation with Spring Boot.
2. No Dao or Database has been used here.
3. Just simply understand how REST works. (GET, POST, PUT, DELETE) with basic java list.
4. How this protocols works ? you will find it when you open this project in your eclopse and run it.
5. How to run it ?? Please check comment out section of --> SpringrestApplication.java
6. How do I understand the flow ?? Please check comment out section of --> SpringrestApplication.java
7. You need a client to test the API. Just import {Postmanfile.json} in your postman.

8. After understanding the basic flow as a beginner we will move to Database connection with the project. We will use Oracle DB. That project will be im another repository. 



If someone needs to start from scratch instead of opening this project ==> 

First create a basic structure for spring boot project => 
Whatever configuration I used for this project is mentioned bellow: 

Google --> Spring boot initializr

SELECT => 
	i) Maven Project
	ii) Java
	iii) Select a spring boot version
	
Project Metadata
	i) Group -> com.springrest
	ii) Artifact -> springrest
	iii) Name -> springrest
	iv) Description -> Demo project for spring boot
	v) Package name -> com.springrest.springrest 
	
	vi) Packaging -> jar
	java -> 8

Add dependencies => 
		i) Spring web
		ii) Oracle sql driver
		iii) Spring data jpa
		
===> Generate Project <===
They'll provide a jar. Extract it and open it in your IDE as a Maven Project
