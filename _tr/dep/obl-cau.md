---
layout: relation
title: 'obl:cau'
shortdef: 'oblique nominal modifier indicating the causee of a causative predicate'
udver: '2'
---

This subtype of [obl]() is used for marking the performer of the real action, "causee", in a causative predicate.
The subject of the causative predicate is the actor who _causes_ the action to be taken.
Occasionally the performer of the action is also included in the phrase/sentence, and it is useful to mark it.
The causee is predictable for intransitive verbs,
since it is the object of the causative predicate.
For transitive verbs, it is often marked with dative [Case](tr-feat/Case),
but it is ambiguous as a dative nominal modifier also has the function of marking the "beneficiary" (and possibly others).


~~~ sdparse
Annesi bebeği uyuttu . \n Her mother caused the baby to sleep (=put the baby to sleep)
obl:cau(uyuttu, bebeği)
nsubj(uyuttu, Annesi)
~~~

~~~ sdparse
Öğretmen kitabı Ali'ye okuttu . \n The teacher caused (made) Ali to read the book
obl:cau(okuttu, Ali'ye)
nsubj(okuttu, Öğretmen)
~~~
Note that the above is ambiguous.
It may also mean "The teacher made someone to read the book to/for Ali".
In that case plain [obl]() should be used.

<!-- Interlanguage links updated So kvě 14 19:03:46 CEST 2022 -->
