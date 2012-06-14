# Thu Jun 14 09:04:38 CDT 2012

## Recall
\[ (1 + x)^n = \sum\limits_{k = 0}^{n} { n \choose k} x^k \]

\[ P( A \cup B) = P(A) + P(B) - P(A \cap B) = P(A) + P(B) - P(AB) \]


\[ P(A \cup B \cup C) = P(A) + P(B \cup C) - P( A ( B \cup C)) \\
  = P(A) + P(B) + P(C) - P(BC) - P(AB \cup AC)\\
  = P(A) + P(B) + P(C) - P(BC) - P(AB) - P(AC) + P(ABC) \]

## Theorem: Inclusion - Exclusion Principle

\[ P \left( \bigcup\limits_{i = 1}^{n} A_i \right) = \sum\limits_{i = 1}^{n}{ P( A_i) - \sum\limits_{i \notequal j}{ P( A_i A_g)} 
  + \sum\limits_{i, j,k distinct}{ P( A_i A_j A_k) 
  - \sum{ P(A_i A_g A_k A_l)}
  + \cdots + (-1)^{n-1} \sum{ P( A_1 A_2 \cdots A_n)}


* pf. Say each \[ A_i\] has only a finite # of elements. 
  Say an element \[ B\] in \[ m\] eof the events \[A_1, A_2, \dots, A_n \].
  How often is it counted?

\[ H = m - {m \choose 2} + {m \choose 3} - {m \choose 4} + \cdots + (-1)^{m+1}{m \choose m}\]

\[ 1 - H = 1 - m + {m \choose 2} - {m \choose 3}+ \cdots + (-1)^m{m \choose m}\]

\[ = \sum\limits_{k = 0}{ m}{m \choose k}(-1)^k = (1 + (-1))^m = 0^m = 0\]

## Something important

\[ \sum\limits_{ k= 0}^n{ {n \choose k} k^2} = 2^{k-2} n(n + 1)\]

* can be proven with calculus or with combintorial logic.

## Something Else

* Equation 1)
  * \[ {n + m \choose r} = {n \choose 0}{m \choose r} + {n \choose 1}{m \choose r - 1} + {n \choose 2}{m \choose r - 2} + \cdots + {n \choose r}{m \choose 0}\]
  * \[ {n + m \choose r}\]
* Equation 2)
  * \[ (1+ x)^{n + m} = \sum\limits_{k = 0}^{n + m}{ {n + m \choose k} x^k}\]
  * \[ (1+ x)^{n + m} = (1 + x)^n(1 + x)^m = \sum{ {n \choose s} x^s \cdot \sum{ {m \choose t} x^t} = \sum\limits_{s = 0}^{n}{ \sum\limits_{t = 0}^{m}{ {n \choose s}{m \choose t}x^{s + t}}}\]
  * get
  * \[ \sum\limits_{ s + t = r}{ {n \choose s}{m \choose t}} = {n \choose 0}{m \choose r} + {n \choose 1}{m \choose r - 1} + \cdots + {n \choose r}{m \choose 0}\]