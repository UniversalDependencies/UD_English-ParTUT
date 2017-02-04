# Corpus Description

UD_English-ParTUT data is derived from the already-existing parallel treebank Par(allel)TUT.

ParTUT is a morpho-syntactically annotated collection of Italian/French/English parallel sentences, 
which includes texts from different sources and representing different genres and domains, released in several formats.

ParTUT data can be downloaded [here](http://www.di.unito.it/~tutreeb/treebanks.html) and [here](https://github.com/msang/partut-repo) (CoNLL format only).

ParTUT comprises approximately 167,000 tokens, with an average amount
of 2,100 sentences per language. The texts of the collection currently available were
gathered from a large number of sources and domains:
* the [Creative Commons](http://creativecommons.org/licenses/by-nc-sa/2.0) open license;
* the [DGT-Translation Memory](https://ec.europa.eu/jrc/en/language-technologies/dgt-translation-memory)
* the [Europarl](http://www.statmt.org/europarl/) parallel corpus (section ep_00_01_17);
* publicly available pages from [Facebook website](https://www.facebook.com/help/345121355559712/);
* the [JRC-Acquis multilingual parallel corpus](http://optima.jrc.it/Acquis/index_2.2.html) (section jrc52006DC243);
* several articles from [Project Syndicate©](https://www.project-syndicate.org/) [ABSENT IN UD_French-ParTUT];
* the [Universal Declaration of Human Rights](http://www.ohchr.org/EN/UDHR/Pages/SearchByLang.aspx);
* Wikipedia articles retrieved in the English section and then translated into Italian only by graduate students in Translation  Studies [ABSENT IN UD_French-ParTUT];
* the [Web Inventory of Translated Talks](https://wit3.fbk.eu/mt.php?release=2012-02) .


## Corpus splitting

The corpus was randomly splitted as follows:

* en_partut-ud-train.conllu: 25872 words (1090 sentences)
* en_partut-ud-dev.conllu: 12243 words (500 sentences)
* en_partut-ud-test.conllu: 11534 words (500 sentences)

In order to preserve the 1:1 correspondence among the three language sections, all of them were partitioned in the same way; therefore the same sentences, in the same order,
are found in the training, development and test set of UD_French-ParTUT and UD_Italian-ParTUT as well.


## Basic statistics

* Tree count:  2090			
* Word count:  49649			
* Token count: 49616			
* Dep. relations: 47 of which 12 language specific			
* POS tags: 17			
* Category=value feature pairs: 32			
		

## References
 
* Manuela Sanguinetti, Cristina Bosco. 2014. PartTUT: The Turin University Parallel Treebank. 
  In Basili, Bosco, Delmonte, Moschitti, Simi (editors) Harmonization and development of resources and tools for Italian Natural Language Processing within the PARLI project, LNCS, Springer Verlag
  
* Manuela Sanguinetti, Cristina Bosco. 2014. Converting the parallel treebank ParTUT in Universal Stanford Dependencies. 
  In Proceedings of the 1rst Conference for Italian Computational Linguistics (CLiC-it 2014), Pisa (Italy)
  
* Cristina Bosco, Manuela Sanguinetti. 2014. Towards a Universal Stanford Dependencies parallel treebank. 
  In Proceedings of the 13th Workshop on Treebanks and Linguistic Theories (TLT-13), Tubingen (Germany)
  

## Acknowledments

We are deeply grateful to Project Syndicate© for letting us download and exploit their articles as text material, under the terms of educational use. 


=== Machine-readable metadata =================================================
Documentation status: partial
Data source: semi-automatic
Data available since: UD v2.0
License: CC BY-NC-SA 4.0
Genre: legal news wiki 
Contributors: Bosco, Cristina; Sanguinetti, Manuela
Contact: msanguin@di.unito.it 
===============================================================================

