---
layout: relation
title: 'det'
shortdef: 'determiner'
udver: '2'
---

The relation [det]() holds between a nominal head and its determiner. Most commonly, a word of POS [DET]() will have the relation [det]() and vice versa. 

In Bulgarian all words that are categorsed as [DET]() also bear [det]() relation.


~~~ sdparse
Представени са също така някои икономически оценки .
det(оценки-7, някои-5)
~~~

~~~ sdparse
Presented are also some economical evaluations .
det(evaluations-6, some-4)
~~~

However, the short possessive and reflexive-possessive pronouns are treated as [PRON]() but also bear the [det]() relation.

~~~ sdparse
Изглежда , любопитството й беше по-силно от всичко .
det(любопитството-3, й-4)
~~~

~~~ sdparse
It seems that curiosity her.SHORT was stronger than anything else .
det(curiosity-4, her.SHORT-5)
~~~


<!-- Interlanguage links updated So kvě 14 19:03:27 CEST 2022 -->
