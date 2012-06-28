# Thu Jun 28 09:01:02 CDT 2012

## Yesterday
\[\int\limits_{-\infty}{\infty}{ e^{-t^2} d t } = \sqrt{\pi}\]

## Review Log

when \[|x| < 1\] then \[1 + x + x^2 + x^3 + \cdots = \frac{ 1}{ 1 - x}\]

Integrate: \[x + \frac{ 1}{ 2} x^2 + \frac{ 1}{ 3} x^3 + \frac{ 1}{ 4} x^4 \cdots = - \log{|1 - x|}\]

Replace \[x\] by \[-x\]: \[x - \frac{ 1}{ 2} x^2 + \frac{ 1}{ 3} x^3 - \frac{ 1}{ 4} x^4 \cdots = \log{ |1 + x|}\]

add both sides and divide by 2 \[x + \frac{ 1}{ 3} x^3 + \frac{ 1}{ 5} x^5 + \cdots = \frac{ 1}{ 2} log|\frac{ 1 + x}{ 1 - x}\]



## Stirling Formulas
To estimate \[n!\]

### Approximate 
\[n \log{ n } - n < \sum\limits_{ k = 1}^{n}{ \log{k}} < (n + 1)\log( n + 1) - n \]

guess \[\sum\limits_{ k = 1}^{n}{ \log{k}}\]

\[(n + 1) - n = 1\]

\[\log( n + 1) - n = 1\]

\[\lgo( n + 1) - \log n  = \log \frac{ n + 1}{ n} = \log\left( 1 + \frac{ 1}{ n}\right \rightarrow 0)\]

Average \[\approx \left( n + \frac{ 1}{ 2}\right) \log n - n\]

A guess

\[\sum\limits_{k = 1}^{n}{ \log k } \approx \left( n + \frac{ 1}{ 2}\right) \log n - n\]


Exponentiate

\[n! \approx e^{n \log n + \frac{ 1}{ 2} \log n - n} = \frac{ n^n \sqrt{ n}}{ e^n}\]

Let 

\[d_n = \log n! - \left(n + \frac{ 1}{ 2}\right) \log n + n \]

\[d_{n + 1} = \log( n + 1)! - \left( n + \frac{ 3}{ 2}\right) \log( n + 1) + n + 1\]

Consider

\[d_n = d_{n + 1} = \left(n + \frac{ 1}{ 2}\right) \log \frac{ n + 1}{ n} - 1\]


Recall

\[x + \frac{ x^3}{ 3} + \frac{ x^5}{ 5} + \cdots = \frac{ 1}{ 2} \log \frac{ 1 + x}{1 - x}\]

let

\[\frac{ n + 1}{ n} = \frac{ 1 + x}{ 1 - x}\]

\[n - n x + 1 - x = n + n x \Rightarrow x = \frac{ 1}{ 2 n + 1}\]

now 

\[\frac{ 1}{ 2} \log \frac{ n + 1}{ n} = \frac{ 1}{ 2}\log\frac{ 1 + x}{ 1 - x} = x + \frac{ x^3}{ 3} + \frac{ x^5}{ 5} + \frac{ x^5}{ 5} + \frac{ x^7}{6} + \cdots\]

\[ = \frac{ 1}{ 2 n + 1} + \frac{ 1}{ 3 (2 n + 1)^3} + \frac{ 1}{ 5 (2 n + 1)^5} + \cdots\]

so 

\[d_n - d_{n + 1} = 1 +  \frac{ 1}{ 3 (2 n + 1)^3} + \frac{ 1}{ 5 (2 n + 1)^5} + \cdots - 1 > 0\]

so \[ d_n - d_{n + 1} > 0 \Rightarrow d_n\] is decreasing


\[d_n - d_{n + 1} < ...\]



### Definition

We say \[f( n)\] is asymtotic to \[g( n)\], denoted by \[f( n)  ~ g( n)\]

if 

\[ \lim_{n \rightarrow \infty \frac{ f( n)}{ g( n)} = 1\]

Stirling formula

\[ n! ~ \frac{ n^n}{ e^n}\sqrt{ 2 \pi n}\]

##  Binomial Coefficient


## Probability