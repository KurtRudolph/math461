# Chapter 2

## 2.3 Axioms of Probability
* Let
  * \[S\] be the sample spcae.
  * \[E\] an event of the sampele space, \[E \in S\].
  * \[n( E)\] number of time the event \[E\] has occured in the sample space \[S\].
* Then
  * \[P( E) = \lim\limits_{x \to \infty } \]
      * The probability of the event \[E\]
      * The protion of the occurances of common type \[E\]
* Let
  * \[S\] be the sample spcae.
  * \[E\] an event of the sampele space, \[E \in S\].
* Assume a number \[P( E)\] is defined and satisifes the
following three axioms:
  * Axiom 1
      * \[0 \le P( E) \le 1\]
      * Outcome of the expriment is an outcome in \[E\] is some number between \[0\] and \[1\].
  * Axiom 2
      * \[ P( S) = 1\]
      * The probability of the outcome of the event in the sample space \[S\] is one.
  * Axiom 3
      * For any sequence of mutually exclusive events \[E_1, E_2, \dots where \[E_i E_j 
        = \emptyset\] when \[i \notequal j\], then
          * \[P\left( \bigcup\limits_{ i = 1}^{ \infty}{ E_i}\right) 
            = \sum\limits_{i = 1}^{\infty}{ P( E_i)}\]
      * For any suequence of mutally exclusive events, the probability of at least 
        one of these events occuing is just the sum of their respective probabilites.
* \[P( S) = \sum\limits_{i = 1}^{ \infty}{ P( E_i) 
  = P( S) + \sum\limits_{i = 2}^{ \infty}{ P( \emptyset )\]
    * From Axiom 3
    * Consider a sequence of events \[E_1, E_2, \dots,\] where \[E_1 = S\], 
      and \[E_i = \emptyset\] for \[i> 1\].  Then, because the events are mutually 
      exclusive and \[S = \bigcap\limits_{i = 1}^{\infty}{ E_i}\].
    * This implies that \[P( \emptyset) = 0\], that is the null event has probability 0 of occuring.
* \[P\left( \bigcup\limits_{i = 1}^{n}{ E_i}\right) = \sum\limits_{i = 1}^{n}{ P( E_i)}\]
  * For any sequence of mutually exclusive events \[E_1, E_2, \dots, E_n\]
  * This equation follows axiom 3 by defining \[E_i\] as the null event for all 
    values of \[i\] greater than \[n\].
  * Equivalent to Axiom 4 when the sample space is finite.

## 2.4 Some Simple propositions
* \[P( E^c) = 1 - P( E)\]
  * Poposition 4.1
  * The probability an event does not occur.
* Given \[E \subset F\] then \[P( E) \le P( F)\]