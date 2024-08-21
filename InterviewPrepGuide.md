# Interview Prep

Target 
1. Prepare proper Resume - Flask, USUP Project, Pyspark, Kafka, Sleuth, RabbitMq
2. Blind 75 solve them
3. Microservices learn
4. DSA Roadmap - geekforgeeks -  here 
5. Apply for proper companies - FAANG, Optum, Oracle, Qualcomm
6. DSA Scaler - here
    1. Two Pointer Approach 

## Intro - 

### Newer

Hello, I am Ponnuri Yeswanth. I have 3+ years of experience as a full-stack developer, which totally lies with my current company IBM. I've honed my skills in both frontend and backend development, where I've worked extensively with Angular, Spring Boot, Java, Micro-services, PostgreSQL and other related technologies. I also have experience in designing efficient database structures, writing optimized queries, and maintaining CI/CD pipelines in IBM Cloud.

In addition to this, I've contributed to building and deploying AI/ML models as part of my projects. In my current role, I handle a variety of tasks including working on Jira stories, conducting code reviews, managing frontend, backend, and database-related tasks, maintaining the application, and ensuring continuous support through code fixes. I also analyze requirements and architecture while regularly interacting with clients to ensure successful project delivery.

My commitment to continuous learning and improvement drives me to stay updated with the latest technologies and best practices, which I apply to deliver high-quality software solutions.

### Older —

Hello, This is Yeswanth and starting the intro with my work experience, I have 3 years of experience as a full stack developer and my experience lies totally with my current company IBM. 

I have experience in building and maintaining end-to-end web applications covering both frontend and backend mainly working on Angular, Spring Boot, Java, Micro-services & PostgreSQL. Along with this I am experienced in designing efficient database structures and write optimised queries, also maintaining Pipelines in IBM Cloud, CICD. Additionally, I have also experience in Building and deploying AI/ML Models as part of my projects. 

In my current role, my day to day responsibilities include working on Jira stories, conducting code reviews, handling frontend, backend, and database related tasks, maintaining the application to provide continuous support and implement code fixes, analyzing requirements and architecture, and interacting with clients.

During my time at IBM, I have contributed my work with various projects and teams, utilizing Jira, ServiceNow, GitHub and other related tools while adhering to agile methodologies. 

Additionally, I have actively participated in and won several hackathons hosted by IBM.

Finally Coming to the key skills that I am proficient are Python, Java, Angular, Spring Boot, Microservices, PostgreSQL, IBM DB2, React, Nodejs. 

——


## Why you want to switch now - 

I'm looking for a position that offers me greater opportunities for professional development and growth in my career and skills. While I've enjoyed my time at my current company, but due to the constrained growth prospects within my current role I feel I've reached a point where my growth potential is limited.

## Topics to prepare before interview - 

1. Java 
    1. Basics from w3schools
    2. OOPS
    3. JDK, JRE, JVM - [here](https://www.javatpoint.com/difference-between-jdk-jre-and-jvm) 
    4. Collections
        1. Hierarchy - [here](https://data-flair.training/blogs/collection-framework-in-java/) 
    5. Streams
    6. Exceptions - Checked vs Unchecked Exceptions - [here](https://medium.com/javarevisited/checked-and-unchecked-exceptions-in-java-19166e68b66f)  
    7. Design Patterns  - Singleton, Prototype patterns
2. Python - To write code - Recall
3. Angular
    1. Interview Questions - [here](https://www.simplilearn.com/tutorials/angular-tutorial/angular-interview-questions)  
4. Spring Boot
    1. Interview questions - [here](https://www.simplilearn.com/spring-boot-interview-questions-article)
    2. Interview questions on Rest API - CRUD, JSON
    3. Exceptions - User Defined 
5. Microservices - [here](https://www.geeksforgeeks.org/microservices-interview-questions/)
    1. API gateway - Spring Cloud API gateway - Adding Uris in properties
    2. Service Registry & Discovery - Eureka server, client, load balancing
    3. Config server 
        1. Spring cloud config(Git or any), Changes can be reflected using actuator refresh
        2. Spring Cloud Bus - Microservices subscribe to any broker (RabbitMq or Kafka) - busrefresh can be done to reflect in all micro services
    4. Distributed Tracing - Spring Cloud Sleuth, Zipkin - Tracing using Span Id, Trace Id
    5. Resilence4j - using Circuit Breaker (Closed, Open, Half_Open states) , Retry mechanism 
        1. Failover threshold - 10
        2. Rate Limiting
        3. Wait Time
        4. Max Retries
    6. Communication btw Microservices 
        1. Sync - RestTemplate, Web Client, OpenFeign Client
        2. Async - Rabbit MQ
            1. Rabbit MQ - Acts as broker btw Producer & Consumer 
            2. Producer -> Exchange -> RabbitMQ -> Consumer
            3. Binding of queues will be based on Routing Key 
            4. Internally Spring Boot - Connection factory, Rabbit Template, Rabbit Admin
    7. Swagger RestAPI Docs - Spring cloud OpenAPI Package, Customize using OpenApiDefinition, Info, Contact, Tag(Controllers), ApiResponse, Schema(DTOs)
    8. Design Patterns 
6. Kafka - Producer, Consumer, Cluster , ZooKeeper 
    1. Cluster - Contains Brokers(Minimum 3) - - Fault Tolerance (If one broker fails, other can handle)
    2. Broker - Contains Topics - Topics divided into Partitions - Offset is given to messages in Partitions
    3. Zookeeper - Maintains the state of brokers in clusters 
    4. Producer 
        1. Contains Kafka Template
        2. Send message based on the topic created 
        3. Serializes date before producing data
    5. Consumer 
        1. Each consumer has unique group id
        2. Subscribe to Kafka Listener - Consume message based on topic by providing group id of current consumer
        3. Deserialise after consuming data
7. SQL - PostgreSQL
    1. Interview Questions - [here](https://www.interviewbit.com/sql-interview-questions/) 
    2. DDL, DML, DQL
    3. ACID Properties - [here](https://www.geeksforgeeks.org/acid-properties-in-dbms/)
    4. Row Number, Rank, Dense Rank
    5. Offset, Limit, Second highest salary
8. Docker & Kubernetes
9. Data Structures - Roadmap - [here](https://www.geeksforgeeks.org/complete-roadmap-to-learn-dsa-from-scratch/)
    1. Linked List - Singly, Doubly - Head, Tail, Prev, Next, Value
    2. Stack - LIFO, DFS, Bracket Sequence - Push, Pop, Peek
    3. Queue  - FIFO, BFS (get all neighbours) - Enqueue, Dequeue, Peek 
    4. Priority Queue - Heap - Max Heap, Min Heap - Add, Poll 
        1. Insert, Delete 
    5. Binary Tree - Only 2 children - Child, Parent, Leaf
    6. BST - Left Low, Right High - O(log n) 
        1. Add, Remove
        2. Traversals - PreOrder (NLR), InOrder (LNR), PostOrder(LRN) - Stack
    7. Graphs 
10. Key Topics 
    1. Valid Paranthesis 
    2. Longest consecutive or increasing subsequence

### DSA - 
1. DSA Scaler - [here](https://www.scaler.com/topics/course/dsa-interviews-java/?utm_medium=email&utm_source=midfunnel&utm_campaign=scaler_academy_pq0mps_mar-2024-w4_india_active_x&utm_content=topics)
2. DSA Roadmap - geekforgeeks  
3. Leetcode Blind 75.


## Resume -  

### Summary 

3+ years of Full Stack Developer experience in analysis, design, development, documentation, implementing and testing of robust web applications in Java, Spring Boot, Microservices architecture, and Angular 16. 
Extensive experience in developing Microservices using SpringBoot, JPA, Zuul, Eureka, Zipkin, Spring Cloud & Config server. Proficient in database management using PostgreSQL, MySQL & DB2, alongside adept handling of RESTful APIs to uphold application security standards.
Build core web application design patterns, such as MVVM and Skilled in enhancing database query efficiency, optimizing application performance, and elevating code quality to deliver seamless user experiences. 
Additionally I have also experienced in developing and deploying Machine Learning Classification & Regression models to streamline Predictive Models. 

### Skills

* Java
* Spring Boot, JPA, Hibernate, Security, JWT
* Micro Services, RESTful Services, Kafka, RabbitMq, Maven
* Angular 16, RxJs
* Javascript, Typescript
* Python, Flask, Pyspark
* PostgreSQL, MySQL, DB2
* Machine Learning - Classification & Regression Models
* Data Structures
* Git, Jira
* Docker & CI/CD
* HTML, CSS
* ReactJs
* Node.Js & ExpressJs
* Web scraping & Selenium 
* IBM Cloud, Watson


### Work Experience 

* Developed and maintained web applications using Spring Boot, Angular and PostgreSQL.
* Built a scalable and maintainable systems using Microservices architecture with RESTful APIs. Leveraged Spring Config Server for centralized configuration and Splunk for comprehensive logging.
* Enhanced system reliability with Zipkin for distributed tracing and implemented fault tolerance strategies for a highly available distributed system.
* Working in an agile framework as an individual contributor Responsibilities include - Interaction with Business team in story grooming, reviewing story/acceptance criteria. 
* Streamlined CI/CD pipelines using Jenkins, Docker and custom scripts to manage and deploy applications, resulting in a 50% deployment time reduction. 
* Improved application performance through caching techniques, optimized SQL queries, and strategic use of indexes.
* Implemented authentication and authorisation using JWT, improving security and protecting sensitive data using AES encryption techniques.
* Optimized data processing using Spring Batch with chunk based approach, achieving sub-2-minute execution for 1M+ records, resulting in a significant improvement of 90% in processing speed.
* Developed Python scripts using Flask and PySpark to automate manual tasks, resulting in a 99% improvement in efficiency and accuracy.
* Optimised service layers, request queues and PostgreSQL data model to handle peak loads of 74,000-96,000 requests per second.
* Implemented unit testing and continuous integration, resulting in a much improvement in code quality and maintainability.
* Worked on developing AI & ML models with a 95% accuracy rate increasing customer engagement - To automate license prediction of installed softwares using Web Scraping & Selenium 
* Worked with wide array of Structured and Unstructured data sources, as well as text and images - To identify log anomalies & PO-NonPO classification models.
* Collaborated with Project Managers on pre-release software project development to create detailed project timelines and deliverables.
* Modernized legacy codebases by migrating from Struts & JSP to Angular & Spring Boot , improving functionality, maintainability, and ensuring the application adheres to modern development standards. 
* Designed and worked on multiple applications that helps for Managers, Employees and HR Partners to automate & simplify their day to day tasks resulting in a 90% increase in their productivity.

Environment - Angular 16, Typescript, Spring Boot 3.0, Java, PostgreSQL, JPA, Hibernate, JDBC, Python 3, Flask, Tomcat and Open Liberty, Maven, IBM Cloud

### Achievements 

* Stood one among the top performer in IBM GitHub Apps Hackathon, streamlining many manual tasks by developers on GitHub.
* Top performer in a nationwide hackathon hosted by IBM, devising an innovative solution for acquiring access to IBM buildings.
* Certified in Python, Angular, Spring Boot, and Python for Data Science by IBM.

### Education 
