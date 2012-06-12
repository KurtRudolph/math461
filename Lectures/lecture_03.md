# Tue Jun 12 09:02:52 CDT 2012

## Homework 

* p. 18 #12 omit part c (or DNHI)

## random walk
* \[ d = rt\]
  * [wiki](http://en.wikipedia.org/wiki/Random_walk)

## something else
\[ (1 + x)^n = \sum\limits_{k=0}^n {n \choose k} x^k \]
\[ {n \choose k} = \frac{ n!}{ k!(n-k)!} \]

NOTE: \[k!\] is the number of permutation of \[k\] objects.

### ex

\[ (1+x)^4 = (1 + x)(1 + x)(1 + x)(1 + x) = 1 + 4x + 6x^2 + 4x^3 + x^3\]
* \[6x^2 = {4 \choose 2}\]

### binomial theorem
* alternate form
  * \[ \left(1 + \frac{ x}{ y} \right)^n = \sum\limits_{k=0}^n { {n \choose k} \left( \frac{ x}{ y} \right)^k}\]
* \[M.y^n\]
  * \[ (x + y)^n = \sum\limits_{k=0}^n{ {n \choose k} x^k y^{n-k}} \]

## calculus agam

\[ \mathop {\lim }\limits_{x \to \infty }{ \frac{ x^n}{ e^x} = 0 \]

\[ \mathop {\lim }\limits_{x \to \infty }{ \frac{ x^n}{ e^{\fraac{ x}{ 100}}} = 0 \]

## Integral of Euler

\[ E(n) = \int\limits_0^\infty{ x^n e^{\frac{-x}{2}} dx} = - \int{ x^n d(e^{-x}} \]

\[ = - \left( e^{-x} x^{-x} - \int { e^{-x n x{n-1} dx\]

NOTE: need to figureout latex bar
\[ = \bar\limits_0^{ \infty} {- e^{-x} x^n } + \int\limits_0^{\infty}{ e^{-x}n x^{n-1} dx}\]

\[ = n \int\limits_0^{ \infty}{ x^{ n-1} e^{ -x} dx} \]


\[ E(n) = n E( n-1) \\ = n (n-1) E( n -2) \\ = n(n - 1)(n - 2)E( n - 3) \]