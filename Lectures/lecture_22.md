# Fri Jul  6 09:06:45 CDT 2012

## DNHI
Calculate

\[\int\limits_{-\infty}^{\infty} x^2 e^{-x^2} dx\]

## Ex

Say \[X\] is a random variable on \[S = [\alpha, \beta]\] 
with probability density function \[f(x) = C\].  Find \[C\],
\[E[ X]\] and \[Var( X)\].

* \[\int\limits_{\alpha}^{beta} C dx = 1\]
  * \[C (\beta - \alpha) = 1
* \[f(x) = \frac{ 1}{ \beta - \alpha}\]
* \[E[ X] = \int\limits_{\alpha}^{\beta} x \frac{ 1}{ \beta - \alpha} dx\]
* \[= \frac{ 1}{ \beta - \alpha\] \left( \frac{ \beta^2}{ 2} - \frac{ \alpha^2}{ 2}\right)\]
* \[= \frac{ \beta + \alpha}{ 2}\]

\[Var( X) = ?\]
* \[E( X^2) = \int\limits_{ \alpha}^{\beta} x^2 \frac{ 1}{ \beta - \alpha} dx\]
  * \[= \frac{ 1}{ \beta - \alpha} \frac{ \beta^3 - \alpha^3}{ 3} = \frac{ \beta^2 + \alpha \beta + \alpha^2}{ 3}\]
* \[Var( X) = \frac{ \beta^2 + \alpha \beta + \alpha^2}{ 3} = \frac{ \beta^2 + 2 \alpha \beta + \alpha^2}{ 4}\]
  * \[\frac{ \beta^2}{ 12} + \frac{ \alpha^2}{ 12} - \alpha \beta \frac{ 2}{ 12} = \frac{ 1}{ 12} (\beta - \alpha)^2\]
* \[\sqrt{ Var( X)} = \frac{ 1}{ \sqrt{ 12} (\beta - \alpha)\]