---
layout: feature
title: 'Clitic'
shortdef: 'clitic'
udver: '2'
---

(Please note: this part of the documentation is not yet completed.)

Language-specific feature identifying clitics attached to the word.

Finnish has a number of particle clitics used to express questions,
politeness, or focus. UD Finnish captures the presence of these
clitics using the `Clitic` feature, which takes one or more of the
following values, with multiple values expressing combinations, for
example `Clitic=Ko,S` for _-kos_ (_-ko_ + _-s_) as in _voi<b>kos</b>_.

### <a name="Kin">`Kin`</a>: -kin

Expresses focus. Can often be translated into English as *also*.
Forms contrasting pair with *-kaan*.

#### Examples

* [fi] _minä<b>kin</b> menen_ "<b>also</b> I am going"

### <a name="Kaan">`Kaan`</a>: -kaan

Expresses focus in negative contexts. Realized as *-kaan* or *-kään*.
Forms contrasting pair with *-kin*.

#### Examples

* [fi] _minä<b>kään</b> en mene_ "I am not going <b>either</b>"

### <a name="Ko">`Ko`</a>: -ko

Expresses a question. Realized as *-ko* or *-kö*.

#### Examples

* [fi] _menen<b>kö</b> minä_ "<b>do</b> I go<b>?</b>"

### <a name="Han">`Han`</a>: -han

Realized as *-han* or *-hän*.

#### Examples

* [fi] _ei<b>hän</b>_ ""

### <a name="Pa">`Pa`</a>: -pa

Realized as *-pa* or *-pä*.

#### Examples

* [fi] _vaikka<b>pa</b>_ ""

### <a name="S">`S`</a>: -s

TODO

#### Examples

* [fi] _mitä<b>s</b>_ ""

### <a name="Ka">`Ka`</a>: -ka

Realized as *-ka* or *-kä*. Attached to the negative verb *ei*, serves
also as a conjunction.

#### Examples

* [fi] _ei päätä ei<b>kä</b> häntää_ "neither head <b>nor</b> tail"

#### References

* Karttunen and Karttunen (1976) *The Clitic -kin/-kaan in Finnish* (TODO link)
* <http://www.cse.chalmers.se/~aarne/articles/discourse-clitics.pdf>
* <http://cowgill.ling.yale.edu/sra/clitics_iel.htm>
* <http://scripta.kotus.fi/visk/sisallys.php?p=126> (in Finnish)
* <http://scripta.kotus.fi/visk/sisallys.php?p=1635> (in Finnish)
<!-- Interlanguage links updated So kvě 14 19:02:06 CEST 2022 -->
