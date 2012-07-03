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
non-overlapping subgroups of sizes \[n_1, n_2, \dots, n_r\]

## Chapter 2: Axioms of Probability

### Union
* \[0 \le P( A) \le 1\]
* \[P( S) = 1\]
* For mutually exclusive events \[A_i, i \ge 1\]

\[P\left(\bigcup\limits_{i = 1}^{\infty}{ A_i}\right) = \sum\limits_{i = 1}^{\infty}{ P( A_i)}\]

### Union
\[P(A \cup B) = P( A) + P( B) - P( AB)\]

## Chapter 3: Conditional Probability and Independence
### Conditional Prob
\[E\] given \[F\] has occurred is denoted

\[P( E|F) = \frac{ P( EF)}{ P( F)}\]

### Multiplication rule
\[P( E_1 E_2 \cdots E_n) = P( E_1) P( E_2|E_1) \cdots P( E_n|E_1 \cdots E_{n - 1})\]

### Identity
\[P( E) = P( E|F)P(F) + P( E|F^c)P( F^c)\]

### Bayes Formula

\[P( F_j | E ) = \frac{ P( E|F_j)P( F_j)}{ \sum\limits_{i = 1}^{n}{ P( E|F_i) P( F_i)}\]


# Problems

## Chapter 1: Combinatorial Analysis

### Problem 3
\[20\] workers are to be assigned to \[20\] different jobs, 
one to each job. How many different assignments are possible?

* \[20!\]
  * \[20\] unique jobs and \[20\] unique workers 

### Problem 7
In how many ways can 3 boys and 3 girls sit in a row?
* \[6!\]
  * \[6\] unique individuals 

In how many ways can \[3\] boys and \[3\] girls sit in a row
if the boys and the girls are each to sit together?
* \[(2) 3! 3!\]
  * \[2\] groups of \[3\] unique individuals filling \[3\] seats per group
    with \[2\] possible arrangements of the groups

In how many ways if only the boys must sit together?  
* \[(4) 3! 3!\]
  * \[2\] groups of \[3\] unique individuals filling \[3\] seats per group
    with \[4\] possible arrangements of the groups as the groups, the group
    of boys having four positions between the girls.

In how many ways if no two people of the same sex are allowed to sit together?
* \[(2) 3! 3!\]
  * \[2\] groups of \[3\] unique individuals filling \[3\] seats per group
    with \[2\] possible arrangements of the groups

### Problem 8
How many different letter arrangements can be made from the letters

* Fluke
  * \[5!\]
      * All unique letters
* Propose
  * \[\frac{ 7!}{ 2! 2!} \]
      * \[7\] letters, \[5\] unique, \[2\] sets of \[2\] same latter

### Problem 14
How many 5-card poker hands are there?

* \[{52 \choose 5}\]

## Chapter 2: Axioms of Probability

### Problem 3
Two dice are thrown. 
Let \[E\] be the event that the sum of the dice is odd, 
Let \[F\] be the event that at least one of the dice lands on \[1\],
Let \[G\] be the event that the sum is \[5\]. 

Describe the events.

* \[E F\]

* \[E \cup F\]

* \[F G\]

* \[E F^c\]

* \[E F G\].

### Problem 8
Suppose that \[A\] and \[B\] are mutually exclusive events 
for which \[P( A) = .3\] and \[P( B) = .5\]. 

What is the probability that


* either \[A\] or \[B\] occurs?
  * \[P( A \cup B) = .8\]

* \[A\] occurs but \[B\] does not?
  * \[P( A \cap B^c) = P( A)\]

### Problem 16
Poker dice is played by simultaneously rolling 5
dice. 

* \[P\{\text{two pair}\}\]
  * \[\frac{ {6 \choose 2} {5 \choose 2} {3 \choose 2} {4 \choose 1}}{ 6^5}\]


### Problem 25

A pair of dice is rolled until a sum of either 5 or 7 appears. 
Find the probability that a 5 occurs first.

\[P( 5) = \{ (1,4), (2,3), (3,2), (4,1)\} = \frac{ 4}{ 36} = \frac{ 1}{ 9}\]
\[P( 7) = \{ (1,6), (2,5), (3,4), (4,3), (5,2), (6,1)\} = \frac{ 6}{ 36} = \frac{ 1}{ 6}\]
\[P( (7 \cup 5)^c) = \frac{ 13}{ 18}\]
Let \[E\] be the even that a 5 occurs before a 7.
\[P(E_n) = \left(\frac{ 13}{ 18}\right)^{n-1} \frac{ 1}{ 9} =  \]

