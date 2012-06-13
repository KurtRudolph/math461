# Wed Jun 13 09:02:27 CDT 2012

## Homework
Friday, Read axiomatics and assorted examples in chapter 2 and do p.50 # 3, 8, 15c, 16abc, 25, 36, and ?

## Recall
* \[ (x + y)^n = \sum\limit_{k=0}^n { \frac{ n!}{ k!(n - k)!} x^k y^{n-k} \]
  * \[ = \sum\limits_{ a + b - n , a \ge 0, b \ge 0}{ \frac{ n!}{ a! b!} x^a y^b \]
  * therefore \[ (x_1 + x_2)^n = \sum\limits_{ n_1 + n_2 = n,n_1 \ge 0, n_2 \ge 0}{ \frac{ n!}{ n_1! n_2!} x_1^{n_1} x_2^{n_2} \]
* Trinomial Theorem
  * \[ (x_1 + x_2 + x_3)^n = \sum\limits_{ n_1 + n_2 + n_3 = n,  n_i \ge 0}{ \frac{ n!}{ n_1! n_2! n_3!} x_1^{n_1} x_2^{n_2} x_3^{n_3} } \]
* Multinomial Theorem
  * \[ \left( \sum\limits_{ i = 1}^I{ x_i} \right)^n = \sum\limits_{ n_1 + \cdots n_I = n, n_i \ge 0}{ \frac{ n!}{ n_1! n_2! \cdots n_I!} x_1^{n_1} \cdots x_I^{n_I} \]


## Axromatic Probability 
* \[ { A \cup B}: \forall x \in S s.t. x \in A or x \in B \]

## Facts from set Theory 
* \[ A \cap \left( B \cup C \right) = \left( A \cap B \right) \cup \left( A \cap B \right)\]
* \[ A \left( B \cup C \right) = AB \cup AC\]
* \[ A \cup \left( B \cap C \right) = \left( A \cup B \right) \cap \left( A \cup C \right)\]
* \[ \left( \bigcup\limits_{ i\in I}{ A_i} \right) = \left( \bigcap\limits_{ i \in I}{ A_i^c \right) \]
* \[ \left( A \cup B \right)^c = A^c \cap B^c \]

## A probability theory is a triple
* \[ \left( S, \{ E_i \}, P \right) \]
* satisfying 3 axioms:
  * A.1 \[ 0 \le P(E) \le 1 \]
  * A.2 \[ P(S) = 1 \]
  * A.3 \[ P\left( \bigcup\limits_{ i = 1}^{ \infty}{ E_i} \right) = \sum\limits_{ i = 1}{ \infty}{ P\left( E_i \right) }\] whenever \[ E_i \cap E_2 = \emtyset \forall i \notequal j\]

## Thereom
* \[ P\left( A \cup B \right) = P( A) + P( B) - P( A \cap B) \]
  * PF: \[ P( A \cup B) = P( A \cup BA^c) = P( A) + P( B A^c)  \]
      * \[ P( A) + P( B A^c) = P( A) + P( B) - P( AB) \]
  * \[ P( B) = P( BA \cup BA^c) = P(AB) + P( BA^c) \]

## Somethign else
* \[ P( A \cup (B \cup C)) 
  \\ = P( A) + P( B \cup C) - P( AB \cup AC) 
  \\ = P( A) + P( B) + P( C) - P( BC) - P( AB \cup AC)
  \\ = P( A) + P( B) + P( C) - P( BC) - \left( P( AB) + P(AC) - P( ABC)\right) \]

## prop.
* \[ P( \emptyset) = 0 \]
  * PF: \[ P( S) = P( S \cup \emptyset) \\ = P( S) + P( \emptyset)\]
        * \therefore P( \emptyset) = 0