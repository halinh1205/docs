---
layout: relation
title: 'det'
shortdef: 'determiner'
udver: '2'
---

The relation determiner (`det`) holds between a nominal head and its determiner. Most commonly, a word of POS DET will have the relation `det` and vice versa. 

~~~ sdparse
denne viktige posten \n this important post
det(posten,denne)
~~~

Other parts of speech than `DET` may in some cases be assigned a determiner relation to a nominal head. 
For Norwegian the `det` relation is also used for genitive nouns, like *årets* "this year's" and quantity nouns like *rekke* "number-of".

~~~ sdparse
årets fredspris \n this year's peace prize
det(fredspris,årets)
~~~

~~~ sdparse
en rekke saker \n a number-of cases
det(saker,rekke)
~~~

<!-- Interlanguage links updated So kvě 14 19:03:28 CEST 2022 -->
