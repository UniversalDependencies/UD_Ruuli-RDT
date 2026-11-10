# Summary

UD_Ruuli-RDT is a Universal Dependencies (UD) treebank for the Ruruuli-Lunyala (Ruuli) language. The annotation was converted from interlinear glossed text and manually annotated for syntactic relations. The treebank includes texts from various sources: conversations, oral folktales, biographic monologue, grammar examples, movie subtitles, and fiction and non-fiction prose. The treebank contains approximately 8,000 tokens.

# Introduction

The UD_Ruuli-RDT treebank consists of texts recorded in Ruuli or translated into it by native speakers, and subsequently glossed and annotated. The included texts are:

* spokenConv_Nakasongola1b (1223 words): Conversation between two speakers, a male and a female, about taking care of their elderly parents  
* spokenConv_Nakasongola2 (1544 words): Conversation between two females about socio-economic issues  
* spokenTale_Gweero (595 words): A traditional oral folktale about the cow who got in trouble with the lion and the hare who helped the cow  
* spokenTale_Sokoso (373 words): A traditional oral folktale about a woman who mistreated her mother-in-law  
* spokenBio_Nakasongola1 (795 words): Biographic monologue on childhood years, schooling, work, and other life experiences 
* grammar_Syntax (936 words): Language examples from *A dictionary and grammatical sketch of Ruruuli-Lunyala* (Namyalo et al. 2021)  
* film_Inception (469 words): An excerpt from the translated subtitles for the film *Inception* (2010)  
* fiction_Ekitwoni (313 words): Several written fictional tales on various dangerous experiences, narrated from the first person
* fiction_OMpologoma (188 words): A written version of a traditional folktale about the hare that wanted to become wise 
* nonfiction_Aniinire (1735 words): An excerpt from factual prose on the history and traditions of the language speakers


All sentences were converted from interlinear glossed text into CoNLL-U format using a custom conversion script. The syntactic relations were subsequently manually annotated following the UD framework.

Sentences from written texts and conversations were shuffled to anonymize the data.

# Genre Classification

* Spoken (incl. conversations, oral folktales, and biographic monologue): sentence IDs start with `spoken`
* Examples from the grammatical sketch: sentence IDs start with `grammar`
* Fiction movie subtitles: sentence IDs start with `film`
* Fiction prose: sentence IDs start with `fiction`
* Factual prose: sentence IDs start with `nonfiction`


# Acknowledgments

* This work was supported by the project "Event Packaging in Language" (University of Zurich Global Strategy and Partnerships Funding Scheme, 2023–2026).

* Preparation of this dataset greatly benefited from the results of the project "A comprehensive bilingual talking Ruruuli/Lunyala-English dictionary" (funded by the Volkswagen Foundation, 2017–2020; PI Saudah Namyalo). 

* We acknowledge the contribution of Anatole Kiriggwajjo, Amos Atuhairwe, Zarina Molochieva, Ruth Gimbo Mukama, and Margaret Zellers.

* Kira Tulchynska gratefully acknowledges the financial support of the Jack, Joseph and Morton Mandel School MA Honors Program at the Hebrew University of Jerusalem.
   
## References

* Molochieva, Zarina, Saudah Namyalo & Alena Witzlack-Makarevich. 2021. Phasal Polarity in Ruuli (Bantu, JE.103). In The Expression of Phasal Polarity
in African Languages. Raija Kramer (ed.). Berlin, Boston: De Gruyter Mouton. 73–92. (doi.org/doi:10.1515/9783110646290-005)
* Namyalo, Saudah & Witzlack-Makarevich, Alena & Kiriggwajjo, Anatole & Atuhairwe, Amos & Molochieva, Zarina & Mukama, Ruth Gimbo & Zellers, Margaret. 2021. A dictionary and grammatical sketch of Ruruuli-Lunyala. Language Science Press. Language Science Press. (doi:10.5281/zenodo.5548947) (https://langsci-press.org/catalog/view/326/3386/2402-1) (Accessed December 12, 2024.)
* Ruppert, Eloisa & Namyalo, Saudah & Witzlack-Makarevich, Alena. Forthcoming. Negation in Ruuli (JE.103). In Miestamo, Ljuba, Matti Veselinova (ed.), Negation in the world’s languages I: Africa. Berlin: Language Science Press.
* Sørensen, Marie-Louise Lind & Witzlack-Makarevich, Alena. 2020. Clausal complementation in Ruuli (Bantu, JE103). Studies in African Linguistics 49(1). 85–110.
(doi.org/10.32473/sal.v49i1.122264)


# Changelog

* 2026-05-15 v2.18
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.18
License: CC BY-NC-SA 4.0
Includes text: yes
Parallel: no
Genre: fiction grammar-examples nonfiction spoken
Lemmas: converted from manual
UPOS: converted from manual
XPOS: converted from manual
Features: converted from manual
Relations: manual native
Contributors: Tulchynska, Kira; Veselovsky, Anna; Witzlack-Makarevich, Alena
Contributing: here
Contact: kira.tulchynska@mail.huji.ac.il
===============================================================================
</pre>
