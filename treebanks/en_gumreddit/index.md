---
layout: base
title:  'UD_English-GUMReddit'
udver: '2'
---

<!-- This page is automatically generated from the README file and from
     the data files in the latest release.

     Please do not edit this page directly. -->

# UD English GUMReddit

Language: [English](/en/index.html) (code: `en`)<br/>
Family: Indo-European, Germanic

This treebank has been part of Universal Dependencies since the UD v2.6 release.

The following people have contributed to making this treebank part of UD: Siyao Peng, Amir Zeldes.

Repository: [UD_English-GUMReddit](https://github.com/UniversalDependencies/UD_English-GUMReddit)<br />
Search this treebank on-line: [PML-TQ](https://lindat.mff.cuni.cz/services/pmltq/#!/treebank/uden_gumreddit210)<br />
Download all treebanks: [UD 2.10](/#download)

License: CC BY 4.0. The underlying text is not included; the user must obtain it separately and then merge with the UD annotation using a script distributed with UD

Genre: blog, social

Questions, comments?
General annotation questions (either English-specific or cross-linguistic) can be raised in the [main UD issue tracker](https://github.com/UniversalDependencies/docs/issues).
You can report bugs in this treebank in the [treebank-specific issue tracker on Github](https://github.com/UniversalDependencies/UD_English-GUMReddit/issues).
If you want to collaborate, please contact [amir&nbsp;•&nbsp;zeldes&nbsp;(æt)&nbsp;georgetown&nbsp;•&nbsp;edu].
Development of the treebank happens outside the UD repository.
If there are bugs, either the original data source or the conversion procedure must be fixed.
Do not submit pull requests against the UD repository.

| Annotation | Source |
|------------|--------|
| Lemmas | annotated manually |
| UPOS | annotated manually in non-UD style, automatically converted to UD |
| XPOS | annotated manually |
| Features | annotated manually in non-UD style, automatically converted to UD |
| Relations | annotated manually, natively in UD style |

## Description

Universal Dependencies syntax annotations from the Reddit portion of the GUM corpus (https://gucorpling.org/gum/)



**This repository only contains annotations, without the underlying textual data from Reddit**

In order to obtain the underlying text, you will need to use the script `get_text.py`. For more information on the underlying Reddit text see [this page](https://github.com/amir-zeldes/gum/blob/master/README_reddit.md). For Universal Dependencies annotations of other genres from GUM, see https://github.com/UniversalDependencies/UD_English-GUM

GUM, the Georgetown University Multilayer corpus, is an open source collection of richly annotated texts from multiple text types. The corpus is collected and expanded by students as part of the curriculum in the course LING-367 "Computational Corpus Linguistics" at Georgetown University. The selection of text types is meant to represent different communicative purposes, while coming from sources that are readily and openly available (usually Creative Commons licenses), so that new texts can be annotated and published with ease.

The dependencies in the corpus up to GUM version 5 were originally annotated using Stanford Typed Depenencies (de Marneffe & Manning 2013) and converted automatically to UD using DepEdit (https://gucorpling.org/depedit/). The rule-based conversion took into account gold entity annotations found in other annotation layers of the GUM corpus (e.g. entity annotations), and has since been corrected manually in native UD. The original conversion script used can found in the GUM build bot code from version 5, available from the (non-UD) GUM repository. Documents from version 6 of GUM onwards were annotated directly in UD, and subsequent manual error correction to all GUM data has also been done directly using the UD guidelines. Enhanced dependencies were added semi-automatically from version 7.1 of the corpus. For more details see the [corpus website](https://gucorpling.org/gum/).

## Acknowledgments

GUM annotation team (so far - thanks for participating!)

Adrienne Isaac, Akitaka Yamada, Alex Giorgioni, Alexandra Berends, Alexandra Slome, Amani Aloufi, Amber Hall, Amelia Becker, Andrea Price, Andrew O'Brien, Anna Runova, Anne Butler, Arianna Janoff, Aryaman Arora, Ayan Mandal, Aysenur Sagdic, Bertille Baron, Bradford Salen, Brandon Tullock, Brent Laing, Candice Penelton, Charlie Dees, Chenyue Guo, Colleen Diamond, Connor O'Dwyer, Cristina Lopez, Dan Simonson, Derek Reagan, Didem Ikizoglu, Edwin Ko, Emile Zahr, Emily Pace, Emma Manning, Ethan Beaman, Felipe De Jesus, Han Bu, Hana Altalhi, Hang Jiang, Hannah Wingett, Hanwool Choe, Hassan Munshi, Helen Dominic, Ho Fai Cheng, Hortensia Gutierrez, Jakob Prange, James Maguire, Janine Karo, Jehan al-Mahmoud, Jemm Excelle Dela Cruz, Jessica Cusi, Jessica Kotfila, Joaquin Gris Roca, John Chi, Jongbong Lee, Juliet May, Jungyoon Koh, Katarina Starcevic, Katelyn MacDougald, Katherine Vadella, Khalid Alharbi, Lara Bryfonski, Lauren Levine, Leah Northington, Lindley Winchester, Linxi Zhang, Siyao Peng, Lucia Donatelli, Luke Gessler, Mackenzie Gong, Margaret Anne Rowe, Margaret Borowczyk, Maria Stoianova, Mariko Uno, Mary Henderson, Maya Barzilai, Md. Jahurul Islam, Michael Kranzlein, Michaela Harrington, Minnie Annan, Mitchell Abrams, Mohammad Ali Yektaie, Naomee-Minh Nguyen, Negar Siyari, Nicholas Mararac, Nicholas Workman, Nicole Steinberg, Nitin Venkateswaran, Phoebe Fisher, Rachel Thorson, Rebecca Childress, Rebecca Farkas, Riley Breslin Amalfitano, Rima Elabdali, Robert Maloney, Ruizhong Li, Ryan Mannion, Ryan Murphy, Sakol Suethanapornkul, Sarah Bellavance, Sasha Slone, Sean Macavaney, Sean Simpson, Seyma Toker, Shane Quinn, Shannon Mooney, Shelby Lake, Shira Wein, Sichang Tu, Siddharth Singh, Siyu Liang, Stephanie Kramer, Sylvia Sierra, Talal Alharbi, Tatsuya Aoyama, Timothy Ingrassia, Trevor Adriaanse, Ulie Xu, Wai Ching Leung, Wenxi Yang, Xiaopei Wu, Yang Liu, Yi-Ju Lin, Yifu Mu, Yilun Zhu, Yingzhu Chen, Yiran Xu, Young-A Son, Yu-Tzu Chang, Yuhang Hu, Yunjung Ku, Yushi Zhao, Zhuosi Luo, Zhuxin Wang, Amir Zeldes

... and other annotators who wish to remain anonymous!

## References

To cite the Reddit subset of GUM in particular, please use this citation:

* Behzad, Shabnam and Zeldes, Amir (2020) "A Cross-Genre Ensemble Approach to Robust Reddit Part of Speech Tagging". In: Proceedings of the 12th Web as Corpus Workshop (WAC-XII).

```
@InProceedings{BehzadZeldes2020,
author = {Shabnam Behzad and Amir Zeldes},
title = {A Cross-Genre Ensemble Approach to Robust {R}eddit Part of Speech Tagging},
booktitle = {Proceedings of the 12th Web as Corpus Workshop (WAC-XII)},
pages = {50--56},
year = {2020},
}
```

As a scholarly citation for the GUM corpus as a whole, please use this article (note that this paper predates the inclusion of Reddit data in GUM):

* Zeldes, Amir (2017) "The GUM Corpus: Creating Multilayer Resources in the Classroom". Language Resources and Evaluation 51(3), 581–612.

```
@Article{Zeldes2017,
author = {Amir Zeldes},
title = {The {GUM} Corpus: Creating Multilayer Resources in the Classroom},
journal = {Language Resources and Evaluation},
year = {2017},
volume = {51},
number = {3},
pages = {581--612},
doi = {http://dx.doi.org/10.1007/s10579-016-9343-x}
}
```


# Statistics of UD English GUMReddit

## POS Tags

[ADJ](en_gumreddit-pos-ADJ.html) – [ADP](en_gumreddit-pos-ADP.html) – [ADV](en_gumreddit-pos-ADV.html) – [AUX](en_gumreddit-pos-AUX.html) – [CCONJ](en_gumreddit-pos-CCONJ.html) – [DET](en_gumreddit-pos-DET.html) – [INTJ](en_gumreddit-pos-INTJ.html) – [NOUN](en_gumreddit-pos-NOUN.html) – [NUM](en_gumreddit-pos-NUM.html) – [PART](en_gumreddit-pos-PART.html) – [PRON](en_gumreddit-pos-PRON.html) – [PROPN](en_gumreddit-pos-PROPN.html) – [PUNCT](en_gumreddit-pos-PUNCT.html) – [SCONJ](en_gumreddit-pos-SCONJ.html) – [SYM](en_gumreddit-pos-SYM.html) – [VERB](en_gumreddit-pos-VERB.html) – [X](en_gumreddit-pos-X.html)

## Features

[Abbr](en_gumreddit-feat-Abbr.html) – [Case](en_gumreddit-feat-Case.html) – [Definite](en_gumreddit-feat-Definite.html) – [Degree](en_gumreddit-feat-Degree.html) – [Gender](en_gumreddit-feat-Gender.html) – [Mood](en_gumreddit-feat-Mood.html) – [Number](en_gumreddit-feat-Number.html) – [NumForm](en_gumreddit-feat-NumForm.html) – [NumType](en_gumreddit-feat-NumType.html) – [Person](en_gumreddit-feat-Person.html) – [Polarity](en_gumreddit-feat-Polarity.html) – [Poss](en_gumreddit-feat-Poss.html) – [PronType](en_gumreddit-feat-PronType.html) – [Reflex](en_gumreddit-feat-Reflex.html) – [Tense](en_gumreddit-feat-Tense.html) – [Typo](en_gumreddit-feat-Typo.html) – [VerbForm](en_gumreddit-feat-VerbForm.html) – [Voice](en_gumreddit-feat-Voice.html)

## Relations

[acl](en_gumreddit-dep-acl.html) – [acl:relcl](en_gumreddit-dep-acl-relcl.html) – [advcl](en_gumreddit-dep-advcl.html) – [advmod](en_gumreddit-dep-advmod.html) – [amod](en_gumreddit-dep-amod.html) – [appos](en_gumreddit-dep-appos.html) – [aux](en_gumreddit-dep-aux.html) – [aux:pass](en_gumreddit-dep-aux-pass.html) – [case](en_gumreddit-dep-case.html) – [cc](en_gumreddit-dep-cc.html) – [cc:preconj](en_gumreddit-dep-cc-preconj.html) – [ccomp](en_gumreddit-dep-ccomp.html) – [compound](en_gumreddit-dep-compound.html) – [compound:prt](en_gumreddit-dep-compound-prt.html) – [conj](en_gumreddit-dep-conj.html) – [cop](en_gumreddit-dep-cop.html) – [csubj](en_gumreddit-dep-csubj.html) – [csubj:pass](en_gumreddit-dep-csubj-pass.html) – [dep](en_gumreddit-dep-dep.html) – [det](en_gumreddit-dep-det.html) – [det:predet](en_gumreddit-dep-det-predet.html) – [discourse](en_gumreddit-dep-discourse.html) – [dislocated](en_gumreddit-dep-dislocated.html) – [expl](en_gumreddit-dep-expl.html) – [fixed](en_gumreddit-dep-fixed.html) – [flat](en_gumreddit-dep-flat.html) – [goeswith](en_gumreddit-dep-goeswith.html) – [iobj](en_gumreddit-dep-iobj.html) – [mark](en_gumreddit-dep-mark.html) – [nmod](en_gumreddit-dep-nmod.html) – [nmod:poss](en_gumreddit-dep-nmod-poss.html) – [nmod:tmod](en_gumreddit-dep-nmod-tmod.html) – [nsubj](en_gumreddit-dep-nsubj.html) – [nsubj:pass](en_gumreddit-dep-nsubj-pass.html) – [nummod](en_gumreddit-dep-nummod.html) – [obj](en_gumreddit-dep-obj.html) – [obl](en_gumreddit-dep-obl.html) – [obl:agent](en_gumreddit-dep-obl-agent.html) – [obl:npmod](en_gumreddit-dep-obl-npmod.html) – [obl:tmod](en_gumreddit-dep-obl-tmod.html) – [parataxis](en_gumreddit-dep-parataxis.html) – [punct](en_gumreddit-dep-punct.html) – [reparandum](en_gumreddit-dep-reparandum.html) – [root](en_gumreddit-dep-root.html) – [vocative](en_gumreddit-dep-vocative.html) – [xcomp](en_gumreddit-dep-xcomp.html)

<h2>Tokenization and Word Segmentation</h2>


<ul>
<li>This corpus contains 895 sentences, 15995 tokens and 16364 syntactic words.</li>
</ul>

<ul>
<li>This corpus contains 1957 tokens (12%) that are not followed by a space.</li>
</ul>

<ul>
<li>This corpus does not contain words with spaces.</li>
</ul>

<ul>
<li>This corpus does not contain words that contain both letters and punctuation.</li>
</ul>

<ul>
<li>This corpus contains 369 multi-word tokens. On average, one multi-word token consists of 2.00 syntactic words.</li>
<li>There are 1 types of multi-word tokens. Examples: __.</li>
</ul>

<h2>Morphology</h2>

<h3>Tags</h3>

<ul>
<li>This corpus uses 17 UPOS tags out of 17 possible: <a>ADJ</a>, <a>ADP</a>, <a>ADV</a>, <a>AUX</a>, <a>CCONJ</a>, <a>DET</a>, <a>INTJ</a>, <a>NOUN</a>, <a>NUM</a>, <a>PART</a>, <a>PRON</a>, <a>PROPN</a>, <a>PUNCT</a>, <a>SCONJ</a>, <a>SYM</a>, <a>VERB</a>, <a>X</a></li>
</ul>

<ul>
<li>This corpus contains 1 word types tagged as particles (PART): _</li>
</ul>

<ul>
<li>This corpus contains 1 lemmas tagged as pronouns (PRON): _</li>
</ul>

<ul>
<li>This corpus contains 1 lemmas tagged as determiners (DET): _</li>
</ul>

<ul>
<li>Out of the above, 1 lemmas occurred sometimes as PRON and sometimes as DET: _</li>
</ul>

<ul>
<li>This corpus contains 1 lemmas tagged as auxiliaries (AUX): _</li>
</ul>

<ul>
<li>Out of the above, 1 lemmas occurred sometimes as AUX and sometimes as VERB: _</li>
</ul>

<ul>
<li>There are 4 <a href="../feat/VerbForm.html">(de)verbal forms:</a></li>
</ul>

<ul>
  <li>Fin
  <ul>
    <li>AUX: _</li>
    <li>VERB: _</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Ger
  <ul>
    <li>AUX: _</li>
    <li>VERB: _</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Inf
  <ul>
    <li>AUX: _</li>
    <li>VERB: _</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Part
  <ul>
    <li>AUX: _</li>
    <li>VERB: _</li>
  </ul>
  </li>
</ul>

<h3>Nominal Features</h3>


<ul>
  <li><a>Gender</a></li>
</ul>

<ul>
  <li>Fem
    <ul>
      <li>PRON: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Masc
    <ul>
      <li>PRON: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Neut
    <ul>
      <li>PRON: _</li>
    </ul>
  </li>
</ul>


<ul>
  <li><a>Number</a></li>
</ul>

<ul>
  <li>Plur
    <ul>
      <li>AUX-Fin: _</li>
      <li>DET: _</li>
      <li>NOUN: _</li>
      <li>PRON: _</li>
      <li>PROPN: _</li>
      <li>VERB-Fin: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sing
    <ul>
      <li>ADJ: _</li>
      <li>AUX-Fin: _</li>
      <li>DET: _</li>
      <li>NOUN: _</li>
      <li>PRON: _</li>
      <li>PROPN: _</li>
      <li>SYM: _</li>
      <li>VERB-Fin: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Case</a></li>
</ul>

<ul>
  <li>Acc
    <ul>
      <li>PRON: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Nom
    <ul>
      <li>PRON: _</li>
    </ul>
  </li>
</ul>


<ul>
  <li><a>Definite</a></li>
</ul>

<ul>
  <li>Def
    <ul>
      <li>DET: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>DET: _</li>
    </ul>
  </li>
</ul>

<h3>Degree and Polarity</h3>


<ul>
  <li><a>Degree</a></li>
</ul>

<ul>
  <li>Cmp
    <ul>
      <li>ADJ: _</li>
      <li>ADV: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pos
    <ul>
      <li>ADJ: _</li>
      <li>ADV: _</li>
      <li>SCONJ: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sup
    <ul>
      <li>ADJ: _</li>
      <li>ADV: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Polarity</a></li>
</ul>

<ul>
  <li>Neg
    <ul>
      <li>ADJ: _</li>
      <li>ADV: _</li>
      <li>DET: _</li>
      <li>INTJ: _</li>
      <li>NOUN: _</li>
      <li>PART: _</li>
    </ul>
  </li>
</ul>


<h3>Verbal Features</h3>



<ul>
  <li><a>Mood</a></li>
</ul>

<ul>
  <li>Imp
    <ul>
      <li>VERB-Fin: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>AUX-Fin: _</li>
      <li>VERB-Fin: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Tense</a></li>
</ul>

<ul>
  <li>Past
    <ul>
      <li>AUX-Fin: _</li>
      <li>AUX-Part: _</li>
      <li>VERB-Fin: _</li>
      <li>VERB-Part: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pres
    <ul>
      <li>AUX-Fin: _</li>
      <li>VERB-Fin: _</li>
      <li>VERB-Part: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Voice</a></li>
</ul>

<ul>
  <li>Pass
    <ul>
      <li>VERB-Part: _</li>
    </ul>
  </li>
</ul>


<h3>Pronouns, Determiners, Quantifiers</h3>


<ul>
  <li><a>PronType</a></li>
</ul>

<ul>
  <li>Art
    <ul>
      <li>DET: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Dem
    <ul>
      <li>ADV: _</li>
      <li>DET: _</li>
      <li>PRON: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>DET: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Int
    <ul>
      <li>ADV: _</li>
      <li>DET: _</li>
      <li>PRON: _</li>
      <li>SCONJ: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Prs
    <ul>
      <li>PRON: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Rel
    <ul>
      <li>ADV: _</li>
      <li>PRON: _</li>
      <li>SCONJ: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Tot
    <ul>
      <li>DET: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>NumType</a></li>
</ul>

<ul>
  <li>Card
    <ul>
      <li>NUM: _</li>
      <li>PROPN: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Frac
    <ul>
      <li>NOUN: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Mult
    <ul>
      <li>ADV: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ord
    <ul>
      <li>ADJ: _</li>
      <li>ADV: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Poss</a></li>
</ul>

<ul>
  <li>Yes
    <ul>
      <li>PRON: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Reflex</a></li>
</ul>

<ul>
  <li>Yes
    <ul>
      <li>PRON: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Person</a></li>
</ul>

<ul>
  <li>1
    <ul>
      <li>AUX-Fin: _</li>
      <li>PRON: _</li>
      <li>VERB-Fin: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>2
    <ul>
      <li>AUX-Fin: _</li>
      <li>PRON: _</li>
      <li>VERB-Fin: _</li>
      <li>VERB-Inf: _</li>
    </ul>
  </li>
</ul>

<ul>
  <li>3
    <ul>
      <li>AUX-Fin: _</li>
      <li>PRON: _</li>
      <li>VERB-Fin: _</li>
    </ul>
  </li>
</ul>




<h3>Other Features</h3>


<ul>
  <li><a>Abbr</a>
    <ul>
      <li>Yes
        <ul>
          <li>ADJ: _</li>
          <li>ADV: _</li>
          <li>NOUN: _</li>
          <li>PROPN: _</li>
          <li>X: _</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>NumForm</a>
    <ul>
      <li>Digit
        <ul>
          <li>NUM: _</li>
        </ul>
      </li>
      <li>Word
        <ul>
          <li>NUM: _</li>
          <li>PROPN: _</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Typo</a>
    <ul>
      <li>Yes
        <ul>
          <li>ADJ: _</li>
          <li>ADP: _</li>
          <li>ADV: _</li>
          <li>AUX-Fin: _</li>
          <li>AUX-Inf: _</li>
          <li>CCONJ: _</li>
          <li>DET: _</li>
          <li>NOUN: _</li>
          <li>PART: _</li>
          <li>PRON: _</li>
          <li>PROPN: _</li>
          <li>PUNCT: _</li>
          <li>SCONJ: _</li>
          <li>VERB-Fin: _</li>
          <li>VERB-Ger: _</li>
          <li>VERB-Inf: _</li>
          <li>VERB-Part: _</li>
          <li>X: _</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<h2>Syntax</h2>

<h3>Auxiliary Verbs and Copula</h3>

<ul>
<li>This corpus uses 1 lemmas as copulas (<a>cop</a>). Examples: _.</li>
</ul>

<ul>
<li>This corpus uses 1 lemmas as auxiliaries (<a>aux</a>). Examples: _.</li>
<li>This corpus uses 1 lemmas as passive auxiliaries (<a>aux:pass</a>). Examples: _.</li>
</ul>

<h3>Core Arguments, Oblique Arguments and Adjuncts</h3>

Here we consider only relations between verbs (parent) and nouns or pronouns (child).
<ul>
  <li><a>nsubj</a>
    <ul>
      <li>VERB-Fin--NOUN (223)</li>
      <li>VERB-Fin--PRON (77)</li>
      <li>VERB-Fin--PRON-Nom (378)</li>
      <li>VERB-Ger--NOUN (6)</li>
      <li>VERB-Ger--PRON (2)</li>
      <li>VERB-Ger--PRON-Nom (1)</li>
      <li>VERB-Inf--NOUN (69)</li>
      <li>VERB-Inf--PRON (26)</li>
      <li>VERB-Inf--PRON-Nom (190)</li>
      <li>VERB-Part--NOUN (33)</li>
      <li>VERB-Part--PRON (9)</li>
      <li>VERB-Part--PRON-Nom (121)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>obj</a>
    <ul>
      <li>VERB-Fin--NOUN (248)</li>
      <li>VERB-Fin--PRON (28)</li>
      <li>VERB-Fin--PRON-Acc (48)</li>
      <li>VERB-Ger--NOUN (57)</li>
      <li>VERB-Ger--PRON (5)</li>
      <li>VERB-Ger--PRON-Acc (12)</li>
      <li>VERB-Inf--NOUN (221)</li>
      <li>VERB-Inf--PRON (30)</li>
      <li>VERB-Inf--PRON-Acc (57)</li>
      <li>VERB-Part--NOUN (58)</li>
      <li>VERB-Part--PRON (5)</li>
      <li>VERB-Part--PRON-Acc (11)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>iobj</a>
    <ul>
      <li>VERB-Fin--NOUN (5)</li>
      <li>VERB-Fin--PRON (1)</li>
      <li>VERB-Fin--PRON-Acc (20)</li>
      <li>VERB-Ger--NOUN (2)</li>
      <li>VERB-Ger--PRON-Acc (4)</li>
      <li>VERB-Inf--NOUN (3)</li>
      <li>VERB-Inf--PRON-Acc (8)</li>
      <li>VERB-Part--NOUN (4)</li>
      <li>VERB-Part--PRON-Acc (1)</li>
    </ul>
  </li>
</ul>



<h3>Verbs with Reflexive Core Objects</h3>

<ul>
  <li>This corpus contains 1 lemmas that occur at least once with a reflexive core object (<a>obj</a> or <a>iobj</a>). Examples: _ _</li>
</ul>

<h3>Relations Overview</h3>

<ul>
<li>This corpus uses 12 relation subtypes: <a>acl:relcl</a>, <a>aux:pass</a>, <a>cc:preconj</a>, <a>compound:prt</a>, <a>csubj:pass</a>, <a>det:predet</a>, <a>nmod:poss</a>, <a>nmod:tmod</a>, <a>nsubj:pass</a>, <a>obl:agent</a>, <a>obl:npmod</a>, <a>obl:tmod</a></li>
<li>The following 3 relation types are not used in this corpus at all: <a>clf</a>, <a>list</a>, <a>orphan</a></li>
</ul>
