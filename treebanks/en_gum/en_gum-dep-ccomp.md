---
layout: base
title:  'Statistics of ccomp in UD_English-GUM'
udver: '2'
---

## Treebank Statistics: UD_English-GUM: Relations: `ccomp`

This relation is universal.

1158 nodes (1%) are attached to their parents as `ccomp`.

1034 instances of `ccomp` (89%) are left-to-right (parent precedes child).
Average distance between parent and child is 6.17443868739206.

The following 17 pairs of parts of speech are connected with `ccomp`: <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-VERB.html">VERB</a></tt> (727; 63% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt> (144; 12% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt> (123; 11% instances), <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-VERB.html">VERB</a></tt> (62; 5% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-PRON.html">PRON</a></tt> (24; 2% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-INTJ.html">INTJ</a></tt> (20; 2% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-PROPN.html">PROPN</a></tt> (13; 1% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-ADV.html">ADV</a></tt> (11; 1% instances), <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt> (8; 1% instances), <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt> (8; 1% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-SCONJ.html">SCONJ</a></tt> (6; 1% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-NUM.html">NUM</a></tt> (4; 0% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (3; 0% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-ADP.html">ADP</a></tt> (2; 0% instances), <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="en_gum-pos-ADP.html">ADP</a></tt>-<tt><a href="en_gum-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-X.html">X</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 7 ccomp	color:blue
1	You	you	PRON	PRP	Case=Nom|Number=Sing|Person=2|PronType=Prs	4	nsubj	4:nsubj	Discourse=evaluation-comment:11->13:1|Entity=(12-person-new-cf3-1-ana)|SpaceAfter=No
2	're	be	AUX	VBP	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin	4	cop	4:cop	_
3	so	so	ADV	RB	_	4	advmod	4:advmod	_
4	stupid	stupid	ADJ	JJ	Degree=Pos	0	root	0:root	_
5	thinking	think	VERB	VBG	VerbForm=Ger	4	advcl	4:advcl	Discourse=attribution-positive:12->13:0
6	I	I	PRON	PRP	Case=Nom|Number=Sing|Person=1|PronType=Prs	7	nsubj	7:nsubj	Discourse=adversative-antithesis:13->14:1|Entity=(4-person-giv:act-cf1*-1-ana)
7	spent	spend	VERB	VBD	Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin	5	ccomp	5:ccomp	_
8	the	the	DET	DT	Definite=Def|PronType=Art	9	det	9:det	Entity=(7-time-giv:inact-cf2-2-coref
9	night	night	NOUN	NN	Number=Sing	7	obj	7:obj	Entity=7)|SpaceAfter=No
10	.	.	PUNCT	.	_	4	punct	4:punct	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 10 ccomp	color:blue
1	And	and	CCONJ	CC	_	4	cc	4:cc	Discourse=attribution-positive:126->127:0
2	I	I	PRON	PRP	Case=Nom|Number=Sing|Person=1|PronType=Prs	4	nsubj	4:nsubj	Entity=(1-person-giv:act-cf1*-1-ana)
3	was	be	AUX	VBD	Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin	4	aux	4:aux	_
4	thinking	think	VERB	VBG	Tense=Pres|VerbForm=Part	0	root	0:root	SpaceAfter=No
5	,	,	PUNCT	,	_	6	punct	6:punct	_
6	hm	hm	INTJ	UH	_	10	discourse	10:discourse	Discourse=evaluation-comment:127->129:1|SpaceAfter=No
7	,	,	PUNCT	,	_	6	punct	6:punct	_
8	this	this	PRON	DT	Number=Sing|PronType=Dem	10	nsubj	10:nsubj	Entity=(73-abstract-giv:act-cf2-1-ana)
9	is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	10	cop	10:cop	_
10	interesting	interesting	ADJ	JJ	Degree=Pos	4	ccomp	4:ccomp	SpaceAfter=No
11	.	.	PUNCT	.	_	4	punct	4:punct	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 10 ccomp	color:blue
1	So	so	ADV	RB	_	4	discourse	4:discourse	Discourse=attribution-positive:19->20:0
2	you	you	PRON	PRP	Case=Nom|Number=Sing|Person=2|PronType=Prs	4	nsubj	4:nsubj	Entity=(24-person-giv:act-cf1*-1-ana)
3	might	might	AUX	MD	VerbForm=Fin	4	aux	4:aux	_
4	be	be	VERB	VB	VerbForm=Inf	0	root	0:root	_
5	like	like	ADP	RP	_	4	compound:prt	4:compound:prt	_
6	this	this	PRON	DT	Number=Sing|PronType=Dem	10	nsubj	10:nsubj	Discourse=evaluation-comment:20->16:2|Entity=(25-abstract-new-cf2-1-cata)
7	is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	10	cop	10:cop	_
8	a	a	DET	DT	Definite=Ind|PronType=Art	10	det	10:det	Entity=(25-abstract-acc:com-cf2-3-coref
9	terrible	terrible	ADJ	JJ	Degree=Pos	10	amod	10:amod	_
10	list	list	NOUN	NN	Number=Sing	4	ccomp	4:ccomp	Entity=25)|SpaceAfter=No
11	.	.	PUNCT	.	_	4	punct	4:punct	_

~~~


