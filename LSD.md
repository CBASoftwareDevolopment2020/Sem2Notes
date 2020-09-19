# [Large System Development](https://datsoftlyngby.github.io/soft2020fall/LSD/)

## Plan

|        Week         | Topic                    | Subject                                                                                                         |
| :-----------------: | ------------------------ | --------------------------------------------------------------------------------------------------------------- |
| [36](LSD/Week36.md) | Tools and Structure      | [01 Introduction](https://datsoftlyngby.github.io/soft2020fall/LSD/week-36/)                                    |
| [37](LSD/Week37.md) | Tools and Structure      | [02 Bash Scripts, UML, and Logical Data Models](https://datsoftlyngby.github.io/soft2020fall/LSD/week-37/)      |
|         38          | Tools and Structure      | [03 Containers and Use Case Models](https://datsoftlyngby.github.io/soft2020fall/LSD/week-38/)                  |
|         39          | Tools and Structure      | [04 Version control and System Operation Contracts](https://datsoftlyngby.github.io/soft2020fall/LSD/week-39/)  |
|         40          | Tools and Structure      | [05 Time planning and scheduling](https://datsoftlyngby.github.io/soft2020fall/LSD/week-40/)                    |
|         41          | Tools and Structure      | [06 Continuous integration and project Kick-off](https://datsoftlyngby.github.io/soft2020fall/LSD/week-41/)     |
|         43          | Developmental Activities | [07 Code Reviews, Pair Programming, and Refactoring](https://datsoftlyngby.github.io/soft2020fall/LSD/week-43/) |
|         44          | Developmental Activities | [08 Coding Standards, Linting, and Static Analysis](https://datsoftlyngby.github.io/soft2020fall/LSD/week-44/)  |
|         45          | Developmental Activities | [09 Logging and Log Analysis](https://datsoftlyngby.github.io/soft2020fall/LSD/week-45/)                        |
|         46          | Developmental Activities | [10 Service Level Agreements and Monitoring](https://datsoftlyngby.github.io/soft2020fall/LSD/week-46/)         |
|         47          | Operational Activities   | [11 Scalability, Load Balancing, and SLA revisited](https://datsoftlyngby.github.io/soft2020fall/LSD/week-47/)  |
|         48          | Operational Activities   | [12 Deployment strategies and Version Strategies](https://datsoftlyngby.github.io/soft2020fall/LSD/week-48/)    |
|         49          | Operational Activities   | [13 Technical depth and Maintainability](https://datsoftlyngby.github.io/soft2020fall/LSD/week-49/)             |
|         50          | Operational Activities   | [14 Disciplined methods in perspective (UP)](https://datsoftlyngby.github.io/soft2020fall/LSD/week-50/)         |
|         51          | Operational Activities   | [15 Q&A, recap, text exam](https://datsoftlyngby.github.io/soft2020fall/LSD/week-51/)                           |

## Slides

- [01-Toolbox](https://datsoftlyngby.github.io/soft2020fall/resources/103c95af-01-toolbox-handouts.pdf)
- [05-Time-Planning](https://datsoftlyngby.github.io/soft2020fall/resources/eecf8efa-05-time-planning-handouts.pdf)

## Assignments

- [Assignment 1 - Logical Data Model](https://datsoftlyngby.github.io/soft2020fall/resources/535325c7-01-logical-data-model.pdf)
- [Assignment 2 - Use Case Model](https://datsoftlyngby.github.io/soft2020fall/resources/a9edbcd7-02-use-case-model.pdf)
- [Assignment 3 - System Operations Contract](https://datsoftlyngby.github.io/soft2020fall/resources/a3cead66-03-system-operations-contract.pdf)

## Curriculum

### _is able to start an virtual machine with Vagrant_ (1)

x

### _is able to launch a Docker container_ (1)

x

### _is able to launch and run a Java program in IntelliJ_ (1)

x

### is able to Apply techniques for dividing a system into subsystems (1)

- **Component** Reusable encapsulated well defined software. Cannot stand alone.
- **Subsystem** Encapsulated well defined stand-alone software. Might or might not be an application by itself.
- **Application** An end-usable piece of software.

Strategies for dividing systems

- Layered/functional sub-systems (High Cohesion)
  - Fit to competences between developers
  - Fit to distributions on machines
- Use-case based sub-systemer (Low coupling – primary on data level)
  - Fits requirements owner (users)
- Mixed or balanced division
  - Front ends – use-cases - presentation logic
  - Back end - technology - business logic

### is able to Design and specify requirements for subsystems (2,3,4,14)

thoughts:
- Problem = "big system/application"
- divide problem using UML
- for each problem make a fully dressed use case
- Wheen use cases are fully dressed, you may begin to think about them in terms of software, create high cohesion low coupling solutions, make sure you use interfaces to ensure testable code and the previously mentioned low coupling hehe 

### is able to Use architecture patterns dedicated to the development of large distributed systems (2,3,4,14)

- Revisit later, but it seems to be just archi patterns such as: [ref](https://towardsdatascience.com/10-common-software-architectural-patterns-in-a-nutshell-a0b47a1e9013)

### have the skills to Cooperate in large systems development organizations (2,3,4,8,10)

Netto thinks i am great

### knows Quality criteria for the design of interfaces to subsystems (4,5,7,8,10,13)

### is able to Use version control systems dedicated to the development of large distributed systems in a distributed development team (4,12)

### knows Issues related to the development of distributed and large-scale IT systems, and how disciplined and agile development methods prescribe how these issues should be handled (6)

### knows The advantages, disadvantages and costs of using a system for the continuous integration and delivery of IT systems (6)

### is able to Use a system for continuous integration and delivery (6)

### have the skills to Participate in globally distributed development (8)

### knows Configuration and error reporting systems dedicated to the development of large distributed systems (9)

### have the skills to Adapt development methods and processes to the development of large distributed systems (11)
