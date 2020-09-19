# [Discrete Mathematics](https://datsoftlyngby.github.io/soft2020fall/DM/)

## Plan

|        Week        | Topic                   | Subject                                                                               |
| :----------------: | ----------------------- | ------------------------------------------------------------------------------------- |
| [36](DM/Week36.md) | Basics                  | [01 Introduction and Logic](https://datsoftlyngby.github.io/soft2020fall/DM/week-36/) |
| [37](DM/Week37.md) | Basics                  | [02 Predicates](https://datsoftlyngby.github.io/soft2020fall/DM/week-37/)             |
|         38         | Basics                  | [03 Set Theory](https://datsoftlyngby.github.io/soft2020fall/DM/week-38/)             |
|         40         | Sequences and Languages | 04 Sequences                                                                          |
|         41         | Sequences and Languages | 05 Regular Languages and Finite State Automata                                        |
|         43         | Static Analysis         | 06 Relations                                                                          |
|         44         | Static Analysis         | 07 Static Analysis                                                                    |
|         45         | Static Analysis         | 08 Static Analysis Cont. and recap                                                    |

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
- 5 Analysing Log Data
- 6a Static Analysis Data Structure
- 6b Static Analysis Engine

## Curriculum

### knows logic and reasoning (1)

x

### _knows laws of logical equivalence including de Morgan’s law_ (1)

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

### is able to argue about the correctness of statements using Boolean algebra and truth tables (1)

|  a  |  b  |     |  c  | &not;(a &or; b) | &not;(b &rarr; a) | &not;a | &not;(a &rarr; b) | &not;b | &not;(a &harr; b) | &not;(a &and; b) | a &and; b | a &harr; b |  b  | a &rarr; b |  a  | b &rarr; a | a &or; b |  t  |
| :-: | :-: | --- | :-: | :-------------: | :---------------: | :----: | :---------------: | :----: | :---------------: | :--------------: | :-------: | :--------: | :-: | :--------: | :-: | :--------: | :------: | :-: |
|  0  |  0  |     |  0  |        1        |         0         |   1    |         0         |   1    |         0         |        1         |     0     |     1      |  0  |     1      |  0  |     1      |    0     |  1  |
|  0  |  1  |     |  0  |        0        |         1         |   1    |         0         |   0    |         1         |        1         |     0     |     0      |  1  |     1      |  0  |     0      |    1     |  1  |
|  1  |  0  |     |  0  |        0        |         0         |   0    |         1         |   1    |         1         |        1         |     0     |     0      |  0  |     0      |  1  |     1      |    1     |  1  |
|  1  |  1  |     |  0  |        0        |         0         |   0    |         0         |   0    |         0         |        0         |     1     |     1      |  1  |     1      |  1  |     1      |    1     |  1  |

### _is able to explain sentences: negation (not), conjunction (and), and disjunction (or), tautologies and contradictions_ (1)

|               |       |            |                                              |
| ------------- | ----- | :--------: | -------------------------------------------- |
| Negation      | not   | &not; or ~ | true if input is false, false otherwise      |
| Conjunction   | and   |   &and;    | true if all inputs are true, false otherwise |
| Disjunction   | or    |    &or;    | true if any input is true, false otherwise   |
| Tautology     | true  |   **t**    | always true                                  |
| Contradiction | false |   **c**    | always false                                 |

### _is able to explain truth tables_ (1)

A truth table is a boolean algebraic table used to determine if a compound statement is true or false. In a truth table, each statement is typically represented by a letter or variable, like p, q, or r, and each statement also has its own corresponding column in the truth table that lists all of the possible truth values.  
Can be used to determine if they are logicaly equivalent.

### _is able to explain conditional statements, their contrapositive, converse, and inverse, hypothesis and conclusion_ (1)

|                       |                                         |                                                                           |
| --------------------- | :-------------------------------------: | ------------------------------------------------------------------------- |
| Hypothesis            |                    a                    | A hypothesis is the "if" part (antecedent) of a conditional statement     |
| Conclusion            |                    b                    | The truth of the conclusion is conditioned to the truth of the hypothesis |
| Conditional statement |    a &rarr; b &equiv; &not;a &or; b     | False if hypothesis is true and conclusion is false, true otherwise       |
| Contrapositive        | a &rarr; b &equiv; &not;b &rarr; &not;a | If a implies b then not b implies not a                                   |
| Converse              |               b &rarr; a                | The conclusion implies the hypothesis                                     |
| Inverse               |          &not;a &rarr; &not;b           | The contrapositive of the converse                                        |
| Biconditional         |      a &harr; b &equiv; b &harr; a      | A conditional statement that goes both ways                               |

### _is able to explain arguments, modus ponens and modus tollens_ (1)

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

### have the skills to write programs based on predictive logic (1,2)

flueben

### knows Predicates and Quantifiers (2)

A predicate is a sentence that contains a finite number of variables and becomes a statement when specific values are substituted for all variables.

&forall; - universal quantifier: for all
&exist; - Existential quantifier: there exists

### _knows laws of multi-quantified statements including De Morgan’s law_ (2)

&not;(&forall;x &in; D, &exist;y &in; E, P(x,y)) &equiv; &exist;x &in; D, &forall;y &in; E, &not;P(x,y)

### _is able to define predicates and their truth sets_ (2)

If P(x) is a predicate, and the domain of x is D. Then the truth set of P(x) is the set of all elements x &in; D where P(x) is true. { x &in; D | P(x) }

### _is able to explain the universal and existential quantifiers_ (2)

&forall; - universal quantifier: for all
&exist; - Existential quantifier: there exists

### _is able to present some arguments with quantified statements_ (2)

&forall;x, P(x) &rarr; Q(x)
P(a)
&there4; Q(a)

### knows Set notations and Set Theory (3)

set notation: {1, 2, ..., 10}
set builder notation: { x &in; D | P(x) }

### is able to understand set properties and operations on sets (3)

Inclusion of intersection: A &cap; B &sube; A
Inclusion in union: A &sube; A &cup; B
Transitivity of subsets: A &sube; B &and; B &sube; C &rarr; A &sube; C

### knows Sequences and induction (4)

### have the skills to optimize code using rules of induction and recursion (4)

### knows Regular expressions and Finite-State Automata (5)

### have the skills to use and implement regular expressions as finite-state automata to evaluate input (5)

### knows Relations (6)

### is able to understand the properties of relations as the foundation of relational databases and static analysis (6)

### knows Static Analysis and Design by Contract (7)

### have the skills to implement static analysis on simple code (7)
