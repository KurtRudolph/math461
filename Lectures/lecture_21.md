# Thu Jul  5 09:01:02 CDT 2012

## Homework

p.224 
* 1
* 2
* 7
* 8
* 11
* 18

p.227
* 5.7
* 5.8

## Practice Problem

Use integration by parts to reduce 
\[\int\limits_{-\infty}^{\infty}{ x^2 e^{-x^2} dx}\] 
to an integral we already know.

* \[x^2 e^{-x^2} = \in\]


## Exam

### 1a)

\[P( A \cup B \cup C) = P( A) + P( B) + P(C) - P( AB) - P( AC) - P( BC)\]

### 1b) 

### 1c)
\[\sum\limits_{n = 1}^{\infty} n \left(\frac{ 3}{ 5}\right) \left(\frac{ 2}{ 5}\right)^{n-1}\]

\[\sum_{n = 0}^{\infty}{ x^n = \frac{ 1}{ 1 -x}\]
\[\sum_{n = x_1}^{\infty} n x^{n - 1} = \frac{ 1}{ (1 - x)^2}\]

\[\sum_{n = 1}^{\infty}{ n \left(\frac{ 3}{ 5}\right)^{n - 1} = \frac{ 1}{ \left(1 - \frac{ 2}{ 5}\right)^2 = \frac{ 25}{ 9}\]

\[\frac{ 25}{ 9} \frac{ 3}{ 5}\]


Also could have noticed it is an expectation of a gemetric random variable.

### 3)

\[\bigcup\limits_{i = 1}^{3} B_i = S\] is a disjoint union

\[P( B_1|A) = \frac{ P( B_1 A)}{ P( A)} = \frac{ P( A|B_1) P( B_1)}{ P( A)}\]

\[P( A) = P( A| B_1)P( B_1) + P( A|B_2)P( B_2) + P( A|B_3) P( B_3)\]

so 

\[P( B_1|A) = \frac{ P( A| B_1) \frac{ 1}{ 2}}{ P( A|B_1) \frac{ 1}{ 2} + P( A|B_2)\frac{ 1}{ 3} + P( A|B_3) \frac{ 1}{6}} = \dots\]


### 4)

\[\lambda = np = 100 \frac{ 20}{ 100} = 20\]

for poisson Distribution Approximation

\[E( X) = \lambda = 20\]

For Binomial r.v. \[(100, \frac{ 1}{ 5}\]

\[Var( X) = n p(1 - p) = 100 \frac{ 1}{ 5} \frac{ 4}{ 5} = 16\]

\[I = \int\limits_{0}^{\infty} e^{-x^2} dx\]
\[I^2 = \int\limits_{0}^{\infty} e^{-x^2} dx \int\limits_{0}^{\infty} e^{-y^2} dy\]
\[I^2 = \int\limits_{0}^{\infty}  \int\limits_{0}^{\infty} e^{-(x^ +y^2)} dx dy\]
\[ = \int\limits_{0}^{\frac{ \pi}{ 2}}  \int\limits_{0}^{\infty} e^{-(r^2)} r dr d \theta = \frac{ \pi}{ 2} \int\limits_{0}^{\infty} r e^{-r^2} dr\]

\[I = \sqrt{ = \frac{ \pi}{ 2} \int\limits_{0}^{\infty} r e^{-r^2} dr}\]



### 7)

\[n! \sim \frac{ n^n}{ e^n} \frac{ 1}{ 2 \pi n}\]
\[\frac{ 1}{ 3^{3n}} \frac{ (3n)!}{ (n!)^3 \sim \frac{ 1}{ 3^{ 3n}}}  \frac{ (3n)^{3n}}{ e^{3n}} \sqrt{ 2 \pi 3 n}\]
\[ \rightarrow \left(\frac{ e^n}{ n^n} \frac{ 1}{ (2 \pi n)^{\frac{ 3}{ 2}} \sim \frac{ \sqrt{ 2 \pi n} \sqrt{ 3}}{ ( 2 \pi n)^{\frac{ 3}{ 2}} = \frac{ \sqrt{ 3}{ 2 \pi n}\]