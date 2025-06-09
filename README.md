# Sa’idi Egyptian Arabic Literary Corpus

##  About  
We present the **first Sa’idi Egyptian Arabic literary corpus**, consisting of **4 million words** drawn from novels and poetry.  
This **open-source** dataset includes: Sa’idi Egyptian Arabic (SEA), Modern Standard Arabic (MSA), Cairene Egyptian Arabic (CEA)


For more details, please see our paper:  
[**Beyond Cairo: Sa’idi Egyptian Arabic Corpus Construction and Analysis**](https://aclanthology.org/2025.nlp4dh-1.26/)


## Preprocessing  
-Corpus is separated author by author, novel by novel.  
-For poetry, separated by poems and listed by author.  
-Corpus separated by new line, dialogue extracted after the punctuation marks that indicate the beginning of the dialogue. 
-This is different by author and novel, therefore, please consult the appendix of the paper for more information.  
-If the author does not consistently mark their dialogue, we only present their novel without extracting the dialogue.

## Directory Structure  
For each novel there are two files: the full novel (`full_authornumber_novelnumber.tsv`) and the dialogue (`Dialogue_authornumber_novelnumber.tsv`) of the novel extracted in a separate file. This would look like the following:

- Catalog.tsv
  - Contains metadata (title, author, year, genre)
- CollectionSEANovels/
  - 1/
    - 1/
      - full_1.1.tsv
      - Dialogue_1.1.tsv
    - 2/
      - full_1.2.tsv
      - Dialogue_1.2.tsv


## Citation  
Please use the following citation when referencing or using this resource:

**APA:**

> Mai Mohamed Eida and Nizar Habash. 2025. *Beyond Cairo: Sa’idi Egyptian Arabic Corpus Construction and Analysis*. In *Proceedings of the 5th International Conference on Natural Language Processing for Digital Humanities*, pages 292–304, Albuquerque, USA. Association for Computational Linguistics.  
> [https://aclanthology.org/2025.nlp4dh-1.26/](https://aclanthology.org/2025.nlp4dh-1.26/)

**BibTeX:**

```bibtex
@inproceedings{mohamed-eida-habash-2025-beyond,
    title     = "Beyond {C}airo: {S}a{'}idi {E}gyptian {A}rabic Literary Corpus Construction and Analysis",
    author    = "Mohamed Eida, Mai  and Habash, Nizar",
    booktitle = "Proceedings of the 5th International Conference on Natural Language Processing for Digital Humanities",
    year      = "2025",
    address   = "Albuquerque, USA",
    pages     = "292--304",
    ISBN      = "979-8-89176-234-3"
}
