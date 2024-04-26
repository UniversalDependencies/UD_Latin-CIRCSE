# Summary

UD_Latin-CIRCSE is a repository of treebanks featuring Latin texts natively annotated at the CIRCSE Research Centre in Milan (https://centridiricerca.unicatt.it/circse/en.html) following the Universal Dependencies (UD) (https://universaldependencies.org) annotation scheme.
The repository includes prose and poetry texts from different periods.


# Introduction

This treebank repository is a work in progress collective endeavour. Presently, it contains the following annotated texts: Seneca *Hercules Furens*, Seneca *Agamemnon*, Tacitus *Germania*.

#### Seneca *Hercules Furens*

*Hercules Furens* is a tragedy written by Seneca the younger in 1st century CE. The source text was received with tokenisation, and annotation with respect to lemmatisation, POS tagging, and morphological features from the Opera Latina corpus built by the [LASLA](http://web.philo.ulg.ac.be/lasla/) laboratory in Liège.
In few cases, the [received annotation](http://github.com/CIRCSE/LASLA) with regard to POS tag and morphological annotation was modified during the syntactic annotation; deviations from the received annotation are detailed in the file Sen_HF_LASLA_CIRCSE.
The syntactic annotation was performed manually at CIRCSE, and follows the UD scheme. 
The text was enhanced with the annotation of the speakers to whom each sentence is attributed. This annotation, performed manually at CIRCSE, is formatted as a comment in the conllu file following the comment line reporting the text of the sentence, as exemplified in what follows:

#sent_id = Latin_SenecaYounger_HercF_poetry-1

#text = soror Tonantis hoc enim solum mihi nomen relictum est semper alienum Iouem ac templa summi uidua deserui aetheris locumque caelo pulsa paelicibus dedi tellus colenda est paelices caelum tenent

#speaker = Iuno

In cases where more than one speaker utters words in the same sentence, the indication of speakers details the distribution of tokens between the speakers, as exemplified in what follows:

#sent_id = Latin_SenecaYounger_HercF_poetry-291

#text = hic onere uacuam litori puppem applicans repetebat umbras poscit Alcides uiam cedente turba dirus exclamat Charon quo pergis audax

#speaker = Theseus (token 1-16), Charon (token 17-19)

#### Seneca *Agamemnon*

*Agamemnon* is a tragedy written by Seneca the younger in 1st century CE. The source text was received with tokenisation, and annotation with respect to lemmatisation, POS tagging, and morphological features from the Opera Latina corpus built by the [LASLA] laboratory in Liège.
In few cases, the [received annotation](http://github.com/CIRCSE/LASLA) with regard to POS tag and morphological annotation was modified during the syntactic annotation; deviations from the received annotation are detailed in the file Sen_Ag_LASLA_CIRCSE.
The syntactic annotation was performed manually at CIRCSE, and follows the UD scheme.
The text was enhanced with the annotation of the speakers to whom each sentence is attributed. This annotation, performed manually at the CIRCSE, is formatted as a comment in the conllu file following the comment line reporting the text of the sentence, as exemplified in what follows:

#sent_id = Latin_SenecaYounger_Ag_poetry-1

#text = opaca linquens Ditis inferni loca adsum profundo Tartari emissus specu incertus utras oderim sedes magis fugio Thyestes inferos superos fugo

#speaker = Thyestis umbra

In cases where more than one speaker utters words in the same sentence, the indication of speakers details the distribution of tokens between the speakers, as exemplified in what follows:

#sent_id = Latin_SenecaYounger_Ag_poetry-199

#text = sistito infestum mare uehit ista Danaos classis et Troas uehit nec plura possunt occupat uocem mare

#speaker = Danai (token 1-10), Eurybates (token 11-16)

In cases of reported speech, the character who utters the reported speech is listed as first; the character reporting the speech is enclosed in round brackets, as exemplified in what follows, where the character named Eurybates reports words uttered by the people of Danai:

#sent_id = Latin_SenecaYounger_Ag_poetry-194

#text = nil nobile ausos pontus atque undae ferunt

#speaker = Danai (Eurybates)


#### Tacitus *Germania*

*Germania* is a treatise written by Cornelius Tacitus between 1st and 2nd century CE.
The text was received with tokenisation, and annotation with respect to lemmatisation, POS tagging, and morphological features from the Opera Latina corpus built by the [LASLA](http://web.philo.ulg.ac.be/lasla/) laboratory in Liège.
The syntactic annotation was performed manually at CIRCSE, and follows the UD scheme.

The sentence splitting differs from the [received one](http://github.com/CIRCSE/LASLA) in three cases, as follows:

LASLA: 

#sent_id = TacGerma-Q-01-21

#text = nec tamen affirmauerim nullam Germaniae uenam argentum aurumue gignere quis enim scrutatus est

CIRCSE:

#sent_id = Latin_Tacitus_Ger_prose-21

#text = nec tamen affirmauerim nullam Germaniae uenam argentum aurumue gignere

#sent_id = Latin_Tacitus_Ger_prose-22

#text = quis enim scrutatus est

LASLA:
#sent_id = TacGerma-Q-01-23

#text = est uidere apud illos argentea uasa legatis et principibus eorum muneri data non in alia uilitate quam quae humo finguntur quamquam proximi ob usum commerciorum aurum et argentum in pretio habent formasque quasdam nostrae pecuniae agnoscunt atque eligunt interiores simplicius et antiquius permutatione mercium utuntur

CIRCSE:

#sent_id = Latin_Tacitus_Ger_prose-24

#text = est uidere apud illos argentea uasa legatis et principibus eorum muneri data non in alia uilitate quam quae humo finguntur

#sent_id = Latin_Tacitus_Ger_prose-25

#text = quamquam proximi ob usum commerciorum aurum et argentum in pretio habent formasque quasdam nostrae pecuniae agnoscunt atque eligunt interiores simplicius et antiquius permutatione mercium utuntur  

LASLA:

#sent_id = TacGerma-Q-01-78

#text = tum in ipso concilio uel principum aliquis uel pater uel propinqui scuto frameaque iuuenem ornant haec apud illos toga hic primus iuuentae honos ante hoc domus pars uidentur mox rei publicae insignis nobilitas aut magna patrum merita principis dignationem etiam adulescentulis assignant ceteri robustioribus ac iam pridem probatis aggregantur nec rubor inter comites aspici

CIRCSE:

#sent_id = Latin_Tacitus_Ger_prose-80

#text = tum in ipso concilio uel principum aliquis uel pater uel propinqui scuto frameaque iuuenem ornant haec apud illos toga hic primus iuuentae honos ante hoc domus pars uidentur mox rei publicae

#sent_id = Latin_Tacitus_Ger_prose-81

#text = insignis nobilitas aut magna patrum merita principis dignationem etiam adulescentulis assignant ceteri robustioribus ac iam pridem probatis aggregantur nec rubor inter comites aspici


Each text in the treebank is split into three subsets, `dev`, `test` and `train`, with a respective approximate ratio of 10%/10%/80%.
The distribution of the Seneca Hercules Furens (tokens: 7930) with respect to the subsets is as follows:
* `train`: sentences 415 - tokens 6382
* `dev`: sentences 76 - tokens 799
* `test`: sentences 64 - tokens 749


The distribution of the Seneca Agamemnon (tokens: 5713) with respect to the subsets is as follows:
* `train`: sentences 309 - tokens 4579
* `dev`: sentences 35 - tokens 572
* `test`: sentences 65 - tokens 562


The distribution of the Tacitus Germania (tokens: 5840) with respect to the subsets is as follows:
* `train`: sentences 233 - tokens 4672
* `dev`: sentences 35 - tokens 587
* `test`: sentences 31 - tokens 581


Since the UD_Latin-CIRCSE treebank is a work in progress, its structure is subject to changes.


# Acknowledgments

The annotation of Seneca *Hercules Furens* and *Agamemnon* has been conducted in the framework of the _LiLa: Linking Latin_ project. LiLa has received funding from the European Research Council (ERC) under the European Union’s Horizon 2020 research and innovation programme – Grant Agreement No. 769994. Warmful thanks to Federica Gamba and Flavio Massimiliano Cecchini for their support and precious advices during the annotation process.

# References




# Changelog

* 2024-05-15 v2.14
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.14
License: CC BY-SA 4.0
Includes text: yes
Genre: fiction:"book", "poetry":"tragedy"
Lemmas: converted with corrections
UPOS: converted with corrections
XPOS: converted with corrections
Features: converted with corrections
Relations: manual native
Contributors: Iurescia, Federica; Passarotti, Marco; Mambrini, Francesco; Moretti, Giovanni; Ruffolo, Paolo; Gamba, Federica; Cecchini, Flavio Massimiliano
Contributing: here
Contact: federica.iurescia@unicatt.it
===============================================================================
</pre>
