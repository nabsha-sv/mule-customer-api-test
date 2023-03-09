# Objective
This is a sample mule application that is written to evaluate candidates knowledge around, but not limited to, the following fields
* Mulesoft 
* API Design
* Database Integration


## Whats included 
The provided application is a very rudimentary implementation that 
* compiles fine without any extra setup/access
* runs happy scenario
* provides necessary instructions to setup the development envvironment

### Environment Setup
* JDK: 1.8
* Maven: apache-maven-3.8.6
* Mulesoft: 4.4.0
* Anypoint Studio: 7.14.0 
* PostGRES: docker latest
## DB Schema
This application has a PostGRES backend that has the following Schema. The database executable itself is not provided as part of this application. It is expected to be configured as a setup activity.
```
create table public.customers
(
    id          integer not null
        primary key,
    "firstName" varchar,
    "lastName"  varchar,
    phone       varchar,
    email       varchar
);
    
```


# Goals
* Identify and resolve issues in the application to the best of abilities
* Introduce the best practices in the application to the best of abilities
 
