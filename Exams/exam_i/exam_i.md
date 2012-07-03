# Exam I Review

# Topics

* Combinatorics including 
  * Dice
  * Card Hands
* 
  * _Binomial Expansion_
  * Geometric Series
  * Exponential Series
  * Logrithmic Series
* 
  * Binomial coefficients
  * Multinomial coefficients
* 
  * Axioms of probability
  * Conditional probability
* Baye's formula
* Independence
* Inclusion-exclusion
* 
  * Expectation
  * Variance
* 
  * Binomial random variable \[(n,p)\]
  * Poisson random variable \[(\lambda)\]
  * Geometric random variable \[(p)\]
* 
  * Stirling's Formula 
  * Integrals of probability theory


# Formulas

## Chapter 1: Combinatorial Analysis

### Binomial Coefficient
\[{n \choose i} = \frac{ n!}{ (n - i)! i!}\]

where \[0 \le i \le n\]

### Binomial Theorem
\[(x + y)^n = \sum\limits_{i = 0}^{n}{ {n \choose i} x^i y^{n-i}}\]

### Multinomial Coefficient
For nonnegative integers \[n_1, \dots, n_r\] summing to \[n\]

\[{n \choose n_1, n_2, \dots, n_r} = \frac{ n!}{ n_1! n_2! \cdots n_r!}\]

is the number of division of \[n\] items into \[r\] distinct 
nonoverlapping subgroups of sizes \[n_1, n_2, \dots, n_r\]

# Problems

## Chapter 1: Combinitorial Analysis

### Problem 3
\[20\] workers are to be assigned to \[20\] different jobs, 
one to each job. How many different assignments are possible?

* \[20\] unique jobs and \[20\] unique workers \[\Rightarrow 20!\]

### Problem 7
In how many ways can 3 boys and 3 girls sit in a row?
* \[6!\]
  * \[6\] unique individuals 

In how many ways can \[3\] boys and \[3\] girls sit in a row
if the boys and the girls are each to sit together?
* \[(2) 3! 3!\]
  * \[2\] groups of \[3\] unique individuals filling \[3\] seats per group
    with \[2\] posible arrangments of the groups

In how many ways if only the boys must sit together?  
* \[3! {6 \choose 3}\]
  * \[2\] groups of \[3\] unique individuals filling \[3\] seats per group
    with \[4\] posible arrangments of the groups as the groups, the group
    of boys having four positions between the girls.

In how many ways if no two people of the same sex are allowed to sit together?
* \[(2) 3! 3!\]
  * \[2\] groups of \[3\] unique individuals filling \[3\] seats per group
    with \[2\] posible arrangments of the groups

