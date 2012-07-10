# Tue Jul 10 09:02:51 CDT 2012

## Notes for homework due Wednesday
p.228 # 11 converging problem.
Assume \[g(x)\] is _not_ a huge function, say \[|g( x)| < e^{M x}\]
for som fixed \[M > 0\]

## Types of Random Variables
* Bernoulli \[\subseteq\] Binomial \[(n,p)\]
  * \[p( i) = {n \choose i} p^i (1 - p)^{n - i}\]
  * \[E[ X] = n p\]
  * \[Var( X) = n p (1 - p)\]
* Poisson
  * \[p( i) =\frac{ e^{-\lambda} \lambda^i}{ i!}\]
  * \[E[ X] = Var( X) = \lambda\]
* Geometric
  * \[p( i) = p (1 - p)^{i - 1}\]
  * \[E[ X] = \frac{ 1}{ p}\]
  * \[Var( X) = \frac{ 1 - p}{ p^2}\]
* Uniform \[\subseteq\] Beta
* Normal
* Exponential \[\subseteq\] Gamma
* Cauchy
  * \[f(x) = \frac{ 1}{ \pi (1 + x^2)}\]

Also note:
* Stirling's Formula
  * \[k! \sim k^{k + \frac{ 1}{ 2}} e^{-k} \sqrt{ 2 \pi}\]