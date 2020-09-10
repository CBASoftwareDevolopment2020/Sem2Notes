# Week of Monday 31 of August (36)

## Topics

- Introduction
- Logic

## Objectives

- **knows logic and reasoning**
- knows laws of logical equivalence including de Morgan’s law
- **is able to argue about the correctness of statements using Boolean algebra and truth tables**
- is able to explain sentences: negation (not), conjunction (and), and disjunction (or), tautologies and contradictions
- is able to explain truth tables
- is able to explain conditional statements, their contrapositive, converse, and inverse, hypothesis and conclusion
- is able to explain arguments, modus ponens and modus tollens
- **have the skills to write programs based on predictive logic**

## Slides

- [Physics and logic](https://datsoftlyngby.github.io/soft2020fall/resources/9a804d37-physics-and-logic.pdf)
- [01 Logic](https://datsoftlyngby.github.io/soft2020fall/resources/67dd8298-01-logic-handouts.pdf)

## Exercises

- [Assignment 1 - Logic](https://datsoftlyngby.github.io/soft2020fall/resources/359a9edb-01-assignment.pdf)

## Logic table

|  a  |  b  |     |  c  | &not;(a &or; b) | &not;(b &rarr; a) | &not;a | &not;(a &rarr; b) | &not;b | &not;(a &harr; b) | &not;(a &and; b) | a &and; b | a &harr; b |  b  | a &rarr; b |  a  | b &rarr; a | a &or; b |  t  |
| :-: | :-: | --- | :-: | :-------------: | :---------------: | :----: | :---------------: | :----: | :---------------: | :--------------: | :-------: | :--------: | :-: | :--------: | :-: | :--------: | :------: | :-: |
|  0  |  0  |     |  0  |        1        |         0         |   1    |         0         |   1    |         0         |        1         |     0     |     1      |  0  |     1      |  0  |     1      |    0     |  1  |
|  0  |  1  |     |  0  |        0        |         1         |   1    |         0         |   0    |         1         |        1         |     0     |     0      |  1  |     1      |  0  |     0      |    1     |  1  |
|  1  |  0  |     |  0  |        0        |         0         |   0    |         1         |   1    |         1         |        1         |     0     |     0      |  0  |     0      |  1  |     1      |    1     |  1  |
|  1  |  1  |     |  0  |        0        |         0         |   0    |         0         |   0    |         0         |        0         |     1     |     1      |  1  |     1      |  1  |     1      |    1     |  1  |
