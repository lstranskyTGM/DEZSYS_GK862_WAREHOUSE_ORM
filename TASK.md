# DEZSYS_GK862_WAREHOUSE_ORM

This lesson introduces the data accessing model in Spring and the basics of Object Relational Mapping (ORM).

## Introduction

This exercise is intended to demonstrate the interaction between a programming language (Java) and a persistance layer (MySQL, PostgreSQL).

First you should follow the Spring tutorial ["Accessing data with MySQL"](https://spring.io/guides/gs/accessing-data-mysql) and document all important steps in your protocol. Don't forget to make notes about all problems occured during the setup. Afterwards you should extend the data model of the example and adapt it for the Data Warehouse application (used in the former projects). One relation between the entities Datawarehouse and Products is required in this example. Please read the documentation how you implementation entity relations using the ORM model.

Document all individual implementation steps and any problems that arise in a log (Markdown).
Create a GITHUB repository for this project and add the link to it in the comments.

## Assessment

- Group size: 1 Person.
- Result by protocol and delivery meeting (in English).
- Requirements **überwiegend erfüllt**.
    - Answer the questions below about the ORM framework.
    - Use the tutorial ["Accessing data with MySQL"](https://spring.io/guides/gs/accessing-data-mysql)
    - Implement the MySQL example with the User database
    - Document each single development step in your protocol and describe the most important code snippets in few sentences. Furthermore, the output of the application and any problems that occur should be documented in submission document.
- Requirements zur **Gänze erfüllt**
    - Customize the data model for the Data Warehouse application (min. 2 entities with 1 relation).
    -  *. Insert following records: 2 Data Warehouse records, 10 Product records.
    - Document which parts of the program need to be adapted
- Extended Requirements **überwiegend erfüllt**
    - Find out which methods are available for the CrudRepository to collect data
      https://docs.spring.io/spring-data/commons/docs/current/api/org/springframework/data/repository/CrudRepository.html.
    - Extend the Data Warehouse repository with following functionalities:
        - Collect all data of one data warehouse specified by datawarehouseID.
        - Collect a single product of a data warehouse specified by datawarehouseID and productID.
        - Update a data warehouse using datawarehouseID.
    - Document the parts of your project which have to be extend
- Extended Requirements zur **Gänze erfüllt**.
    - Replace the MySQL database management system with a PostgreSQL database management system.
    - Document which configuration files need to be adapted

## Questions

- What is ORM and how is JPA used?
- What is the application.properties used for and where must it be stored?
- Which annotations are frequently used for entity types? Which key points must be observed?
- What methods do you need for CRUD operations?

## Links & Further Resources

- https://docs.spring.io/spring-framework/reference/data-access/orm.html

- https://spring.io/guides/gs/accessing-data-mysql

- https://dzone.com/articles/what-is-the-difference-between-hibernate-and-sprin-1
