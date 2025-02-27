---
layout: feature
title: 'VerbForm'
shortdef: 'form of verb or deverbative'
udver: '2'
---
<table class="typeindex" border="1">
<tr>
  <td style="background-color:cornflowerblue;color:white"><strong>Values:</strong> </td>
  <td><a href="#Conv">Conv</a></td>
  <td><a href="#Fin">Fin</a></td>
  <td><a href="#Inf">Inf</a></td>
  <td><a href="#NomAg">NomAg</a></td>
  <td><a href="#Part">Part</a></td>
  <td><a href="#Vnoun">Vnoun</a></td>
</tr>
</table>

Even though the name of the feature seems to suggest that it is used
exclusively with [verbs](myv-pos/VERB), this is not the case.
The `Part` value can also be used with [adjectives](myv-pos/ADJ), while
the `NomAg` and `Vnoun` value can also be used with [nouns](myv-pos/Noun).


### <a name="Conv">`Conv`</a>: converb, gerund

The converb, also called adverbial participle or traditionally gerund, is a non-finite
verb form that shares properties of verbs and adverbs.

#### Examples

- _эрить <b>киштезь-моразь</b>_ “they live <b>dancing and singing</b>”

### <a name="Fin">`Fin`</a>: finite

Finite verb occurs in the conditional, subjunctive (aka conjunctive), conditional-subjunctive desiderative indicative, imperative, optative or precative.

#### Examples

- _сими_ &nbsp;“he/she/it drinks”
- _кортыть_ &nbsp;“they talk”

### <a name="Inf">`Inf`</a>: infinitive

Infinitive is the citation form of verbs.
It is also appears as the argument of modal and other verbs.

#### Examples

- _симемс_ &nbsp;“to drink”
- _кортамс_ &nbsp;“to talk”

### <a name="NomAg">`NomAg`</a>: Nomen Agensis

The Nomen Agensis is derived from a verb with an agent or performer, and it represents the nominalization of the subject. `-Ыця`

#### Examples

* [myv] _— Оно косот кинь <b>невтицятне</b>._ "— See where the ones are showing the way."

### <a name="Part">`Part`</a>: participle

Words in participle forms are assigned the `VerbForm` value `Part`.
Participle forms are further differentiated using the feature
[PartForm]().

#### Examples

* [myv] _пилень <b>дёлиця</b> вайгеленть_ "The voice <b>that is soothing</b> to the ears"


### <a name="Vnoun">`Vnoun`</a>: verbal noun

The verbal noun in Erzya represents a mixture of verb and nominal features.

#### Examples

* [myv] _пек <b>сиземадо</b> мейле мик эске лангсо мадезь удомат сы._ "after you get really tired, you will even want to fall asleep when you're lying on spikes"

<!-- Interlanguage links updated So kvě 14 19:02:44 CEST 2022 -->
