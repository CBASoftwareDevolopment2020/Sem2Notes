# [Discrete Mathematics](https://datsoftlyngby.github.io/soft2020fall/DM/)

## Plan

|        Week        | Topic                   | Subject                                                                               |
| :----------------: | ----------------------- | ------------------------------------------------------------------------------------- |
| [36](DM/Week36.md) | Basics                  | [01 Introduction and Logic](https://datsoftlyngby.github.io/soft2020fall/DM/week-36/) |
|       [37]()       | Basics                  | [02 Predicates](https://datsoftlyngby.github.io/soft2020fall/DM/week-37/)             |
|       [38]()       | Basics                  | [03 Set Theory](https://datsoftlyngby.github.io/soft2020fall/DM/week-38/)             |
|       [40]()       | Sequences and Languages | [04 Sequences]()                                                                      |
|       [41]()       | Sequences and Languages | [05 Regular Languages and Finite State Automata]()                                    |
|       [43]()       | Static Analysis         | [06 Relations]()                                                                      |
|       [44]()       | Static Analysis         | [07 Static Analysis]()                                                                |
|       [45]()       | Static Analysis         | [08 Static Analysis Cont. and recap]()                                                |

## Slides

- [01 Logic](https://datsoftlyngby.github.io/soft2020fall/resources/67dd8298-01-logic-handouts.pdf)
- [02 Predicates](https://datsoftlyngby.github.io/soft2020fall/resources/01a8c5fa-02-predicates-handouts.pdf)
- [03 Set Theory](https://datsoftlyngby.github.io/soft2020fall/resources/e02255b2-03-set-theory-handouts.pdf)
- [04 Sequences](https://datsoftlyngby.github.io/soft2020fall/resources/0513dad7-04-sequences-handouts.pdf)

## Assignments

- [1 Logic](https://datsoftlyngby.github.io/soft2020fall/resources/359a9edb-01-assignment.pdf)
- [2 Programming with Predicates](https://datsoftlyngby.github.io/soft2020fall/resources/43ec6fda-02-assignment.pdf)
- [3 Programming with sets](https://datsoftlyngby.github.io/soft2020fall/resources/2f52520c-03-assignment.pdf)
- [4 Sequences and Recursion](https://datsoftlyngby.github.io/soft2020fall/resources/4ff38378-04-assignment.pdf)
- [5 Analysing Log Data]()
- [6a Static Analysis Data Structure]()
- [6b Static Analysis Engine]()

## Curriculum

### **knows logic and reasoning**

### knows laws of logical equivalence including de Morgan’s law

| Law              |                                                                      Equivalence                                                                       |
| ---------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------: |
| Commutative      |                                               a &and; b &equiv; b &and; a <br> a &or; b &equiv; b &or; a                                               |
| Associative      |                            (a &and; b) &and; c &equiv; a &and; (b &and; c) <br> (a &or; b) &or; c &equiv; a &or; (b &or; c)                            |
| Distributive     |                  a &and; (b &or; c) &equiv; (a &and; b) &or; (a &and; c) <br> a &or; (b &and; c) &equiv; (a &or; b) &and; (a &or; c)                   |
| identity         |                                                  a &and; **t** &equiv; a <br> a &or; **c** &equiv; a                                                   |
| Negation         | a &or; &not;a &equiv; **t** <br> a &and; &not;a &equiv; **c** <br> &not;(&not;a) &equiv; a <br> &not;**t** &equiv; **c** <br> &not;**c** &equiv; **t** |
| Idempotent       |                                                      a &and; a &equiv; a <br> a &or; a &equiv; a                                                       |
| Universal bounds |                                                      a &or; t &equiv; t <br> a &and; c &equiv; c                                                       |
| De Morgan's      |                              &not;(a &and; b) &equiv; &not;a &or; &not;b <br> &not;(a &or; b) &equiv; &not;a &and; &not;b                              |
| Absorbtion       |                                             a &or; (a &and; b) &equiv; a <br> a &and; (a &or; b) &equiv; a                                             |

### **knows Predicates and Qualifiers**

### knows laws of multi-qualified statements including De Morgan’s law

### **knows Set notations and Set Theory**

### **knows Sequences and induction**

### **knows Regular expressions and Finite-State Automata**

### **knows Relations**

### **knows Static Analysis and Design by Contract**

### **is able to argue about the correctness of statements using Boolean algebra and truth tables**

### is able to explain sentences: negation (not), conjunction (and), and disjunction (or), tautologies and contradictions

|               |       |            |                                              |
| ------------- | ----- | :--------: | -------------------------------------------- |
| Negation      | not   | &not; or ~ | true if input is false, false otherwise      |
| Conjunction   | and   |   &and;    | true if all inputs are true, false otherwise |
| Disjunction   | or    |    &or;    | true if any input is true, false otherwise   |
| Tautology     | true  |   **t**    | always true                                  |
| Contradiction | false |   **c**    | always false                                 |

### is able to explain truth tables

A truth table is a mathematical table used to determine if a compound statement is true or false. In a truth table, each statement is typically represented by a letter or variable, like p, q, or r, and each statement also has its own corresponding column in the truth table that lists all of the possible truth values

### is able to explain conditional statements, their contrapositive, converse, and inverse, hypothesis and conclusion

|                       |                                         |
| --------------------- | :-------------------------------------: |
| Hypothesis            |                    a                    |
| Conclusion            |                    b                    |
| Conditional statement |    a &rarr; b &equiv; &not;a &or; b     |
| Contrapositive        | a &rarr; b &equiv; &not;b &rarr; &not;a |
| Converse              |               b &rarr; a                |
| Inverse               |          &not;a &rarr; &not;b           |
| Biconditional         |      a &harr; b &equiv; b &harr; a      |

### is able to explain arguments, modus ponens and modus tollens

An argument is a sequence of statements  
An argument form is a series of statement forms
All statements (forms) in an argument (form), except the final ine, are called premises (or assumptions or hypotheses)  
The final statement (form) is called the conclusion  
The symbol &there4; read "therefore" is placed before the conclusion

|                     |                                                                        |
| ------------------- | ---------------------------------------------------------------------- |
| Modus ponens        | a &rarr; b<br>a<br>&there4;b                                           |
| Modus tollens       | a &rarr; b<br>&not;b<br>&there4;&not;a                                 |
| Generalization      | a<br>&there4;a &or; b<br><br>b<br>&there4;a &or; b                     |
| Specialization      | a &and; b<br>&there4;a<br><br>a &and; b<br>&there4;b                   |
| Conjunction         | a<br>b<br>&there4;a &and; b                                            |
| Elimination         | a &or; b<br>&not;b<br>&there4;a<br><br>a &or; b<br>&not;a<br>&there4;b |
| Transivity          | a &rarr; b<br>b &rarr; c<br>&there4;a &rarr; c                         |
| Division into cases | a &or; b<br>a &rarr; c<br>b &rarr; c<br>&there4;c                      |
| Contradiction       | &not;a &rarr; **c**<br>&there4;a                                       |

### is able to define predicates and their truth sets

### is able to explain the universal and existential quantifiers

### is able to present some arguments with qualified statements

### **is able to understand set properties and operations on sets**

### **is able to understand the properties of relations as the foundation of relational databases and static analysis**

### **have the skills to write programs based on predictive logic**

### **have the skills to optimize code using rules of induction and recursion**

### **have the skills to use and implement regular expressions as finite-state automata to evaluate input**

### **have the skills to implement static analysis on simple code**
