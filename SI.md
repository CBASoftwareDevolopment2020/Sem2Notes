# [System Integration](https://datsoftlyngby.github.io/soft2020fall/SI/)

## Plan

|        Week        | Topic                              | Subject                                                                                             |
| :----------------: | ---------------------------------- | --------------------------------------------------------------------------------------------------- |
| [36](SI/Week36.md) | Application Connectivity           | [01 Introduction to System Integration](https://datsoftlyngby.github.io/soft2020fall/SI/week-36/)   |
| [37](SI/Week37.md) | Application Connectivity           | [02 Distributed computing](https://datsoftlyngby.github.io/soft2020fall/SI/week-37/)                |
|         38         | Application Connectivity           | [03 Web Services](https://datsoftlyngby.github.io/soft2020fall/SI/week-38/)                         |
|         39         | Application Connectivity           | [04 Application programming interfaces](https://datsoftlyngby.github.io/soft2020fall/SI/week-/39)   |
|         40         | Enterprise Application Integration | [05 Enterprise Application Integration](https://datsoftlyngby.github.io/soft2020fall/SI/week-/40)   |
|         41         | Enterprise Application Integration | [06 Business Process Modelling](https://datsoftlyngby.github.io/soft2020fall/SI/week-/41)           |
|         43         | Enterprise Application Integration | [07 Enterprise Integration Patterns, MOM](https://datsoftlyngby.github.io/soft2020fall/SI/week-/43) |
|         44         | Enterprise Application Integration | [08 Data-driven Integration](https://datsoftlyngby.github.io/soft2020fall/SI/week-/44)              |
|         45         | Enterprise Application Integration | [09 Event-driven integration](https://datsoftlyngby.github.io/soft2020fall/SI/week-/45)             |
|         46         | Microservices Architecture         | [10 Microservices Architecture](https://datsoftlyngby.github.io/soft2020fall/SI/week-/46)           |
|         47         | Microservices Architecture         | [11 Microservices Integration](https://datsoftlyngby.github.io/soft2020fall/SI/week-/47)            |
|         48         | Microservices Architecture         | [12 Agile development and integration](https://datsoftlyngby.github.io/soft2020fall/SI/week-/48)    |
|         49         | Microservices Architecture         | [13 Exam Project](https://datsoftlyngby.github.io/soft2020fall/SI/week-/49)                         |
|         50         | Microservices Architecture         | [14 Exam Project](https://datsoftlyngby.github.io/soft2020fall/SI/week-/50)                         |
|         51         | Microservices Architecture         | [15 Exam Project](https://datsoftlyngby.github.io/soft2020fall/SI/week-/51)                         |

## Slides

- [Introduction](https://datsoftlyngby.github.io/soft2020fall/resources/dbbcb324-Session1Intro.pdf)
- [Point-to-Point Connection](https://datsoftlyngby.github.io/soft2020fall/resources/b129c63e-Session1P2P.pdf)
- [Distributed Computing, RPC, RMI](https://datsoftlyngby.github.io/soft2020fall/resources/3c5a921b-Session2RPC.pdf)
- [Week37 exercises](https://datsoftlyngby.github.io/soft2020fall/resources/27ed6290-Session2Practice.pdf)
- [Web Services](https://datsoftlyngby.github.io/soft2020fall/resources/f4cb7736-Session3WS.pdf)
- [SOAP Web Services](https://datsoftlyngby.github.io/soft2020fall/resources/822d3220-Session3SOAP.pdf)
- [Web Services in Java](https://datsoftlyngby.github.io/soft2020fall/resources/034634be-Session3JWS.pdf)

## Assignments

- [Assignment 1: P2P Tasks](https://datsoftlyngby.github.io/soft2020fall/resources/2581556e-A1-TCP-UDP.html)
- [Assignment 2: RPC Task](https://datsoftlyngby.github.io/soft2020fall/resources/53040c09-A2-RPC.pdf)
- [Assignment 3: Reading task](https://datsoftlyngby.github.io/soft2020fall/resources/fbbdae82-A3-REST-Read.pdf)
- [Mini Project: Web Services](https://datsoftlyngby.github.io/soft2020fall/resources/473f0f56-MP1-WS.pdf)
- Assignment 4: Group Project 1. RESTfull API
- Assignment 5: SOA Reading Task
- Assignment 6: Group Project 2. BPM
- Assignment 7: EIP Reading Task
- Assignment 8: Group Project 3. MOM
- Assignment 9: Microservices Reading Task
- Assignment 10: Group Project 4. Microservices
- Assignment 11: CI_CD Reading Task\_
- Assignment 12: Multiple-choice final test
- Exam Project

## Curriculum

### knows Business considerations in relation to system integration (1,5,6)

System Integration Challenges

- Business Challenges
  - Various processes and operations
  - Different levels of automation
  - Wide geographical locations of resources
  - Accumulation of software in time
  - Various channels for data acquisition
  - Various types of data
- Software Challenges
  - Complex systems with various components
    - built in different architecture styles monolith, client-server, MVC
    - various development platforms
    - different programming languages
    - conflicting data formats and semantic definitions among the participating systems
- Developers Challenges
  - Work in teams
  - Work with legacy systems
  - Solve same problems of customers again and again

### knows Standards and standards organisations (1,2,3,5,6)

Standards  
ASCII, UTF, HTTP  
[ref](https://brocku.ca/policies/wp-content/uploads/sites/94/System-Integration-Standards.pdf)

Organisations  
IEEE, ISO, ANSI, OSI, W3C

### have the skills to Acquire knowledge of developments in standards for integration (1,7,8,9,12)

we can google

### knows Tools for integration (2,7,9,11)

RPC, SOAP, REST, HTTP, registry, contracts

### is able to Use an object-oriented system in a service-oriented architecture (2,4,10)

RPC, Soap

### is able to Use patterns that support system integration (2,7,8,9)

RPC

### knows The concept of services and their ties to service-oriented architectures (3,4,5)

- Service - discrete unit of functionality that can be accessed remotely and acted upon and updated independently
- A service has the following properties
  - logically represents a business activity with a specified outcome
  - self-contained
  - a black box for its consumers
  - may consist of other underlying services
- Software service – important digital concept nowadays
  - software, which serves, creates value for businesses or society
  - architectural component
- Web services – software services hosted and accessed online
  - have evolved from the existing technologies, such as RPC/RMI
  - intended to solve the problems of those technologies
- Software system
  - identified by an URI
  - having public interfaces and bindings
- Can be discovered by other software systems
  - interacting after the prescription
  - exchanging (XML) messages conveyed by Internet protocols
- Web Applications can
  - consume published web services
  - expose their own services for consumption of other web applications

### knows Technologies, which can be used to implement a service-oriented architecture (3,4,6,10,11)

SOAP, REST

### is able to Integrate generic and other systems (3,10)

Any sort of integration that is generic that doesn't bind to a given language or technology

### is able to Design a system that is easy to integrate with other systems, and uses existing services (4,6,11)

### is able to Transform or expand a system so that it can function in a service-oriented architecture (5,8,9,10,12)

### have the skills to Choose from various integration techniques (5)

### is able to Translate elements in a business strategy into specific requirements for system integration (6,10)

### knows Storage, transformation and integration of data sources (7,8)

### have the skills to Adapt IT architecture to take into account future system integration (11)

### is able to Choose from various integration methods (12)
