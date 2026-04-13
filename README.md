# Summary

UD_Ruuli-RDT is a Universal Dependencies (UD) treebank for the Ruruuli-Lunyala (Ruuli) language. The annotation was converted from interlinear glossed text and manually annotated for syntactic relations. The treebank includes texts from various sources: conversations, oral folktales, biographic monologue, movie subtitles, grammar examples, and factual prose. The treebank contains approximately 6,000 tokens.

# Introduction

The UD_Ruuli-RDT treebank consists of texts recorded in Ruuli or translated into it by native speakers, and subsequently glossed and annotated. The included texts are:

* conversation_Gweero (595 words): A traditional oral folktale about the cow who got in trouble with the lion and the hare who helped the cow  
* conversation_Nakasongola1 (795 words): Biographic monologue on childhood years, schooling, work, and other life experiences 
* conversation_Nakasongola1b (1224 words): Conversation between two speakers, a male and a female, about taking care of their elderly parents  
* conversation_Nakasongola2 (1544 words): Conversation between two females about socio-economic issues  
* conversation_Sokoso (373 words): A traditional oral folktale about a woman who mistreated her mother-in-law  
* film_Inception (470 words): An excerpt from the translated subtitles for the film *Inception* (2010)  
* grammar_Syntax (937 words): Language examples from *A dictionary and grammatical sketch of Ruruuli-Lunyala* (Namyalo et al. 2021)  
* nonfiction_Aniinire (70 words): An excerpt from factual prose on the history and traditions of the language speakers  

All sentences were converted from interlinear glossed text into CoNLL-U format using a custom conversion script. The syntactic relations were subsequently manually annotated following the UD framework.

Sentences from written texts and conversations were shuffled to anonymize the data.

# Genre Classification

* Spoken (incl. conversations, oral folktales, and biographic monologue): sentence IDs start with `conversation`
* Movie subtitles: sentence IDs start with `film`
* Examples from the grammatical sketch: sentence IDs start with `grammar`
* Factual Prose: sentence IDs start with `nonfiction`

# Acknowledgments

This work was supported by the project "Event Packaging in Language" (University of Zurich Global Strategy and Partnerships Funding Scheme, 2023–2026).

Preparation of this dataset greatly benefited from the results of the project "A comprehensive bilingual talking Ruruuli/Lunyala-English dictionary" (funded by the Volkswagen Foundation, 2017–2020; PI Saudah Namyalo). 
We acknowledge the contribution of Anatole Kiriggwajjo, Amos Atuhairwe, Zarina Molochieva, Ruth Gimbo Mukama, and Margaret Zellers.
   
## References

* Namyalo, Saudah & Witzlack-Makarevich, Alena & Kiriggwajjo, Anatole & Atuhairwe, Amos & Molochieva, Zarina & Mukama, Ruth Gimbo & Zellers, Margaret. 2021. A dictionary and grammatical sketch of Ruruuli-Lunyala. Language Science Press. Language Science Press. (doi:10.5281/zenodo.5548947) (https://langsci-press.org/catalog/view/326/3386/2402-1) (Accessed December 12, 2024.)
* Molochieva, Zarina, Saudah Namyalo & Alena Witzlack-Makarevich. 2021. Phasal Polarity in Ruuli (Bantu, JE.103). In The Expression of Phasal Polarity
in African Languages. Raija Kramer (ed.). Berlin, Boston: De Gruyter Mouton. 73–92. (doi.org/doi:10.1515/9783110646290-005)
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
