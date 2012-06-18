# Mon Jun 18 14:10:51 CDT 2012

## Problem 3.13

Let \[E_i =\]  prob. that \[i\]th hand \[( 1 \le i \le 4)\] 
gets exactly one ace.

\[P( E_1) = \frac{ {4 \choose 1} {48 \choose 12}}{ {52 \choose 13}\]

\[P( E_2|E_1) = \frac{ {3 \choose 1} {36 \choose 12}}{ {52 \choose 13}}, \dots\]


## Conditiong

\[E = E F \cup E F^c\]

\[EF \cap EF^c = EFEF^c = \emptyset\]

\[P( E) = P( EF) + P(EF^c)\]

\[P( E) = P( E|F) P(F) + P( E|F^c)P(F^c) = P( E|F) P( F) + P( E|F^c)(1 - P( F))\]

## Ex
Multiple choice exam, each question has \[m\] answer choices.

\[p = \] prob student understans the material.

\[1 -p = \] prob the student does not understand the material. 

\[C:\] event "correct answer"

\[K:\] understans the answwer and the issue.

\[P( K|C) = \frac{ P( K C)}{ P( C)} = \frac{ P( K)}{ P( C)} = \frac{ P}{ P( C|K) P( K) + P( C|K^c) P( K^c)}\] 
\[= \frac{ P}{ 1 \cdot p + \frac{ 1}{ m} (1 - p)} = \frac{ m p}{ 1- p + m p} = \frac{ m p}{ 1 + (m - 1) p}\]


## Generalized Conditioning

* \[S = \bigcup{ F_i}, F_i \cap F_j \notequal \emptyset\]
* Then \[E = E \cap (\bigcup{ F_i}) = \bigcup{ E F_i} \]
* \[P( E) = \sum{ P( E F_i) = \sum\limits_{i}{ P( E|F_i)P( F_i)\]

Theorem \[P( F_j|E) = \frac{ P( E F_j)}{ P( E)}\]

\[P( F_j|E) = \frac{ P( E|E_j)P( F_j)}{ \sum\limits_{ i = 1}^{n}{ P( E|F_i) P( F_i)}}\]
  * Bayes' formula



## Other Notes

### Disjoint
[[/images/disjoint_sets.png]]


### Office hours 10:30 to 11:25
