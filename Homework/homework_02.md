# Homework 02
* Due: Friday, June 15th 9:00AM
* Read: axiomatics and assorted examples in chapter 2
* Problems: 
  * pg50 
      * 3
      * 8
      * 15c
      * 16abc
      * 25
      * 36
  * p.57
      * 13

* Let: 
  * \[A^c\] be the outcome of events not contained in the space \[A\]

## pg50_03

Two dice are thrown. Let \[E\] be the event that the sum of the 
dice is odd, let \[F\] be the event that at least one of the dice 
lands on \[1\], and let \[G\] be the event that the sum is \[5\]. Describe 
the events \[EF, E \cup F, FG, EF^c, EFG\].

* \[EF\]
  * The expression defines the space where the sum of the dice is \[odd\] and 
    one die lands on a \[1\].
  * The expression implies that secend device must be \[even\] as only \[1 + even = odd\].
* \[E \cup F\]
  * The expression defines the space where 
    * The sum of the dice is odd.
    * One of the dice lands on \[1\].
    * Both the proceeding bullets are true
* \[FG\]
  * The expression defins the space where one of the dice lands on a \[1\] and 
    the sum of the dice is \[5\],  
  * The expression implies the second dice lands on a \[4\].
* \[EF^c\]
  * The expression defines the space where the _sum_ of the dice is \[odd\] and
    at least one of dice does _not_ land on a \[1\].
* \[EFG\]
  * The expression defines the space where the _sum_ of the dice is \[odd\] 
    and at least one of dice land on a \[1\]
    and sum of the dice is \[5\]
  * The expression implies that one dice land on a \[1\] and the other on a \[4\],
    a space of two possible outcomes.

## pg50_08
Suppose that \[A\] and \[B\] are mutually exclusive events for which \[P(A) = .3\] 
and \[P(B) = .5\]. What is the probability that
* either \[A\] or \[B\] occurs?
  * \[P( A \cup B) = P(A) + P(B) = .8 \]
      * Keep in mind they are mutually exclusive.
* A occurs but B does not?
  * \[P( A\\B = P(A) + P(B) - P(B) = P(A) = .30\]
* Both A and B occur?
  * \[P( A \cap B = P(A) + P(B) - P(A \cup B) = 0 \]

## pg51_15c
If it is assumed that all \[52\] poker hands are \[52 \choose 5\]
equally likely, what is the probability of being dealt two pairs?
(This occurs when the cards have denominations \[a, a, b, c, d,\] 
where \[a, b, c, d\] are all distinct.)

* \[ \frac{ {13 \choose 1}{4 \choose 2}{12 \choose 1}{4 \choose 1}}{ {2 \choose 1}} {11 \choose 1}{4 \choose 1} \]