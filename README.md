# Learning Resources for Javaa Spring

## Contents

1. [Popular Reference Sites](#popular-reference-sites)
   - [WebSites](#websites)
   - [Youtube Channels](#youtube-channels)
   - [Courses](#courses)
1. [Core Java Concepts](#core-java-concepts)
2. [Logging](#logging-in-java)
   - [Log Levels](#log-levels)
3. [MultiThreading](#multithreading)
4. [Maven](#maven)
6. [Spring Basics](#spring-basics)
6. [kafka](#kafka)
7. [Sample Projects](#sample-projects)
8. [My Spring Boot Project](#my-spring-boot-project)

## Popular Reference Sites

#### WebSites
   - [Javatpoint (Java concepts)](https://www.javatpoint.com/)
   - [Baeldung (for Spring concepts)](https://www.baeldung.com/)

#### Youtube Channels
   - [Java Brains](https://www.youtube.com/user/koushks)
   - [Telusko](https://www.youtube.com/user/javaboynavin)
   - []()

#### Courses
   - [Udemy - Beginner to Guru Course](https://www.udemy.com/course/spring-framework-5-beginner-to-guru/ )

## Core Java Concepts

- OOP Concepts - Object Oriented Programming (Enough resources are there)
- Abstract and Nested Classes
- Interfaces
- [Exception Handling]()
- [Generics]()
- [Lembda Expressions in Java]()
- SOLID Principles
   - S: Single Responsibility   
   Each should have only reponsibility
   - O: Open/ Close Principle  
   Every class should be open for extension but close for modification
   - L: Liskov Substitution Principle  
   Objects of class should be replacable with instances of their subtypes WITHOUT altering the correctness of program
   - I: Interface Segregation Principle
   Make fine grained interfaces that are client specific, many client specific principles are better than one general purpose interface
   - D: Dependency Inversion Princple (not same as Dependency Injection)

## Logging in Java

- [Java Logger](https://www.javatpoint.com/java-logger)
- [Log4j](https://www.javatpoint.com/introduction-to-log4j)

#### Log Levels  
![Log Levels](pictures/log-levels.png)

## MultiThreading

- MultiThreading Concepts(Jenkov)
   - [Concurrency in Java]( http://tutorials.jenkov.com/java-concurrency/index.html)
   - [Concurrency Models](http://tutorials.jenkov.com/java-concurrency/concurrency-models.html)
   - [Concurrency vs Parallelism](http://tutorials.jenkov.com/java-concurrency/concurrency-vs-parallelism.html)
   - [Create and Start Java Threads](https://www.youtube.com/watch?v=eQk5AWcTS8w)
   - [Race Consition and Critical Sections](https://www.youtube.com/watch?v=RMR75VzYoos&list=PLL8woMHwr36EDxjUoCzboZjedsnhLP1j4&index=9)
   - [Thread Safety and Shared Resources](http://tutorials.jenkov.com/java-concurrency/thread-safety.html)
   - [Java Memory Model WRT MultiThreading](https://www.youtube.com/watch?v=LCSqZyjBwWA&list=PLL8woMHwr36EDxjUoCzboZjedsnhLP1j4&index=6)
   - [Synchronize blocks](https://www.youtube.com/watch?v=eKWjfZ-TUdo&list=PLL8woMHwr36EDxjUoCzboZjedsnhLP1j4&index=7)
   - [Volatile keyword](https://www.youtube.com/watch?v=nhYIEqt-jvY&list=PLL8woMHwr36EDxjUoCzboZjedsnhLP1j4&index=6)
   - [Threadpool](https://www.youtube.com/watch?v=ZcKt5FYd3bU&list=PLL8woMHwr36EDxjUoCzboZjedsnhLP1j4&index=12)

- [Java Executor Services Youtube Playlist(basic)](https://www.youtube.com/playlist?list=PLPn4T86dJstfydxMrepAcakR3MSZEHaa5)

## Maven

- What is Maven
   - [Video 1](https://www.youtube.com/watch?v=dqJanLvjDqc)
   - [Video 2](https://www.youtube.com/watch?v=bSaBmXFym30)
- [Maven installation](https://mkyong.com/maven/how-to-install-maven-in-windows/)
- Create first Maven project
   - [Article](https://www.baeldung.com/maven)
   - [Video](https://www.youtube.com/watch?v=uEYjXpMDJiU )
- [Java Brains Maven Playlist](https://www.youtube.com/playlist?list=PL92E89440B7BFD0F6)

## Spring Basics

- Java Design Patterns
   - [Singleton DP](https://www.javatpoint.com/singleton-design-pattern-in-java)
   - [Factory DP](https://www.tutorialspoint.com/design_pattern/factory_pattern.htm)

- [Spring Framework Basics Course](https://www.tutorialspoint.com/spring/index.htm)
   - [More on Dependency Injection](https://www.baeldung.com/spring-dependency-injection)
   - [Video on Spring MVC](https://www.youtube.com/watch?v=y8zyPlIdTyE)

- [Project Lombok](https://projectlombok.org/features/all)
- What is JPA
   - [English Video](https://www.youtube.com/c/JavaBrainsChannel/playlists?view=50&sort=dd&shelf_id=3)
   - [Hindi Video](https://www.youtube.com/watch?v=agTUJ4aVJSQ)
   - [JPA Annotations - Basic Mapping](https://stackabuse.com/guide-to-jpa-with-hibernate-basic-mapping)
   - [JPA Annotations - Relationship Mapping](https://stackabuse.com/a-guide-to-jpa-with-hibernate-relationship-mapping)
   - [Annotaions CheatSheet](pictures/AssociationMappingsWithJPAandHibernate.pdf)
- [What is CRUD Repository](https://www.youtube.com/c/JavaBrainsChannel/playlists?view=50&sort=dd&shelf_id=3)
- Spring Data MongoDB
   - [Baeldung Tutorial](https://www.baeldung.com/spring-data-mongodb-guide)
   - [Spring Boot REST APIs using MongoDB](https://www.bezkoder.com/spring-boot-mongodb-crud/)
   - [Reference Documentation](https://docs.spring.io/spring-data/mongodb/docs/current/reference/html/#preface)

- Spring Data Elasticsearch
   - [Baeldung Tutorial](https://www.baeldung.com/spring-data-elasticsearch-tutorial)
   - [Code Example](https://reflectoring.io/spring-boot-elasticsearch/)
   - [Reference Documentation](https://docs.spring.io/spring-data/elasticsearch/docs/current/reference/html/#reference)
   - [ElasticsearchRstTemplate Example](https://reflectoring.io/spring-boot-elasticsearch/)
- [Swagger2](https://dzone.com/articles/spring-boot-restful-api-documentation-with-swagger)

## Kafka

- [Kafka Fundamentals](https://www.youtube.com/watch?v=B5j3uNBH8X4&list=PLa7VYi0yPIH2PelhRHoFR5iQgflg-y6JA&index=3) 

## Sample Projects

- [Simple Spring Boot REST APIs using Spring JPA, Hibernate, MySql](https://dzone.com/articles/how-to-create-rest-api-with-spring-boot)   
- [Spring Boot REST APIs using MongoDB](https://www.bezkoder.com/spring-boot-mongodb-crud/)
- [Spring Boot Web App using Spring Data Elasticsearch Code Example](https://reflectoring.io/spring-boot-elasticsearch/)

## My Spring Boot Project

This is the project I am building while learning Spring Boot in order to implement what I have learnt
<!-- #### [My Spring Boot Movie Catelog REST APIs using H2 Database and MySQL](https://github.com/AVNV2201/spring-boot-movie-catelog.git) -->
#### [My Spring Boot Movie Catelog REST APIs using MongoDB and Elasticsearch](https://github.com/AVNV2201/movie-catelog-spring-boot-mongodb-elasticsearch)
