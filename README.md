# Summary

UD_Latin-CIRCSE is a repository of treebanks featuring Latin texts natively annotated at the CIRCSE Research Centre in Milan (https://centridiricerca.unicatt.it/circse/en.html) following the Universal Dependencies (UD) (https://universaldependencies.org) annotation scheme.
The repository includes prose and poetry texts from different periods.


# Introduction

This treebank repository is a work in progress collective endeavour. Presently, it contains the following annotated texts: 
Seneca *Hercules Furens*
*Hercules Furens* is a tragedy written by Seneca the younger in 1st century CE. The source text (7711 tokens) was received with tokenisation, and annotation with respect to lemmatisation, POS tagging, and morphological features from the Opera Latina corpus built by the [LASLA] laboratory in Liège (http://github.com/CIRCSE/LASLA).
In few cases, the received annotation with regard to POS tag and morphological annotation was modified during the syntactic annotation; deviations from the received annotation are detailed in the file Sen_HF_LASLA_CIRCSE.
The syntactic annotation was performed manually at CIRCSE, and follows the UD scheme. 
The text was enhanced with the annotation of the speakers to whom each sentence is attributed. This annotation, performed manually at CIRCSE, is formatted as a comment in the conllu file following the comment line reporting the text of the sentence, as exemplified in what follows:

#sent_id = SenHerFu-P-15-1

#text = soror Tonantis hoc enim solum mihi nomen relictum est semper alienum Iouem ac templa summi uidua deserui aetheris locumque caelo pulsa paelicibus dedi tellus colenda est paelices caelum tenent

#speaker = Iuno

In cases where more than one speaker utters words in the same sentence, the indication of speakers details the distribution of tokens between the speakers, as exemplified in what follows:

#sent_id = SenHerFu-P-15-291

#text = hic onere uacuam litori puppem applicans repetebat umbras poscit Alcides uiam cedente turba dirus exclamat Charon quo pergis audax

#speaker = Theseus (token 1-16), Charon (token 17-19)

Seneca *Agamemnon*
*Agamemnon* is a tragedy written by Seneca the younger in 1st century CE. The source text (5576 tokens) was received with tokenisation, and annotation with respect to lemmatisation, POS tagging, and morphological features from the Opera Latina corpus built by the [LASLA] laboratory in Liège (http://github.com/CIRCSE/LASLA).
In few cases, the received annotation with regard to POS tag and morphological annotation was modified during the syntactic annotation; deviations from the received annotation are detailed in the file Sen_Ag_LASLA_CIRCSE.
The syntactic annotation was performed manually at CIRCSE, and follows the UD scheme.
The text was enhanced with the annotation of the speakers to whom each sentence is attributed. This annotation, performed manually at the CIRCSE, is formatted as a comment in the conllu file following the comment line reporting the text of the sentence, as exemplified in what follows:

#sent_id = SenAgamn-P-21-1

#text = opaca linquens Ditis inferni loca adsum profundo Tartari emissus specu incertus utras oderim sedes magis fugio Thyestes inferos superos fugo

#speaker = Thyestis umbra

In cases where more than one speaker utters words in the same sentence, the indication of speakers details the distribution of tokens between the speakers, as exemplified in what follows:
#sent_id = SenAgamn-P-21-199

#text = sistito infestum mare uehit ista Danaos classis et Troas uehit nec plura possunt occupat uocem mare

#speaker = Danai (token 1-10), Eurybates (token 11-16)

In cases of reported speech, the character who utters the reported speech is listed as first; the character reporting the speech is enclosed in round brackets, as exemplified in what follows, where the character named Eurybates reports words uttered by the people of Danai:
#sent_id = SenAgamn-P-21-194

#text = nil nobile ausos pontus atque undae ferunt

#speaker = Danai (Eurybates)


Tacitus *Germania*
*Germania* is a treatise written by Cornelius Tacitus between 1st and 2nd century CE.
The text (5669 tokens) was received with tokenisation, and annotation with respect to lemmatisation, POS tagging, and morphological features from the Opera Latina corpus built by the [LASLA] laboratory in Liège (http://github.com/CIRCSE/LASLA).
The syntactic annotation was performed manually at CIRCSE, and follows the UD scheme.


# Acknowledgments

The annotation of Seneca *Hercules Furens* and *Agamemnon* has been conducted in the framework of the _LiLa: Linking Latin_ project. LiLa has received funding from the European Research Council (ERC) under the European Union’s Horizon 2020 research and innovation programme – Grant Agreement No. 769994. Warmful thanks to Federica Gamba and Flavio Massimiliano Cecchini for their support and precious advices during the annotation process.

## References

* (citation)


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
