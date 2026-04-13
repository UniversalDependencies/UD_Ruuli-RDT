# Summary

UD_Ruuli-RDT is a Universal Dependencies (UD) treebank for the Ruruuli-Lunyala (Ruuli) language. The annotation was converted from interlinear glossed text and manually supplemented with syntactic relations. The treebank includes texts from various sources: nonfiction, fiction, grammar examples, and spoken conversation. The treebank contains approximately 6,000 tokens.

# Introduction

The UD_Ruuli-RDT treebank consists of texts recorded in Ruuli or translated into it by native speakers, and subsequently glossed and annotated. The included texts are:

* conversation_Gweero (595 words): TODO  
* conversation_Nakasongola1 (795 words): TODO  
* conversation_Nakasongola1b (1224 words): TODO  
* conversation_Nakasongola2 (1544 words): TODO  
* conversation_Sokoso (373 words): TODO  
* film_Inception (470 words): A section of subtitles from *Inception* (2010)  
* grammar_Syntax (937 words): Examples from the syntax section of Namyalo et al. (2021)  
* nonfiction_Aniinire (70 words): TODO  

All sentences were converted from interlinear glossed text into CoNLL-U format using a custom conversion script. The syntactic relations were subsequently manually annotated following the UD framework.

Sentences from written texts and conversations were shuffled.

# Genre Classification

* Fiction: sentence IDs start with `film`
* Grammar: sentence IDs start with `grammar`
* Nonfiction: sentence IDs start with `nonfiction`
* Spoken: sentence IDs start with `conversation`

# Acknowledgments

This work was supported by the project "Event Packaging in Language" (University of Zurich Global Strategy and Partnerships Funding Scheme, 2023–2026).

Preparation of this dataset greatly benefited from the results of the project "A comprehensive bilingual talking Ruruuli/Lunyala-English dictionary" (funded by the Volkswagen Foundation, 2017–2020; PI Saudah Namyalo). 
We acknowledge the contribution of Anatole Kiriggwajjo, Amos Atuhairwe, Zarina Molochieva, Ruth Gimbo Mukama, and Margaret Zellers.
   
## References

* Namyalo, Saudah & Witzlack-Makarevich, Alena & Kiriggwajjo, Anatole & Atuhairwe, Amos & Molochieva, Zarina & Mukama, Ruth Gimbo & Zellers, Margaret. 2021. A dictionary and grammatical sketch of Ruruuli-Lunyala. Language Science Press. Language Science Press. (doi:10.5281/zenodo.5548947) (https://langsci-press.org/catalog/view/326/3386/2402-1) (Accessed December 12, 2024.)


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
Contributors: Tulchynska, Kira; Witzlack, Alena; Veselovsky, Anna
Contributing: here
Contact: kira.tulchynska@mail.huji.ac.il
===============================================================================
</pre>
