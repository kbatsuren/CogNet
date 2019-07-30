# CogNet: a Large-Scale Cognate Database For 338 languages

![alt text](http://ukc.disi.unitn.it/wp-content/uploads/2019/05/Cognate_fish.jpg)

CogNet is a large-scale database of cognate pairs: it contains 5.9 million cognates in 338 languages, 38 writing systems, and 91285 concepts. It was automatically constructed from wordnets and dictionaries contained within the UKC resource, as described in our paper.

UKC resource is at http://ukc.disi.unitn.it, and more details of CogNet is at http://cognet.ukc.disi.unitn.it/

## Why cognates are important?
In Computational Linguistics: improve the cross-lingual NLP tasks, e.g., word translation, cross-lingual knowledge transfer.
![alt text](http://ukc.disi.unitn.it/wp-content/uploads/2019/07/cognate_morphology.jpg)

## CogNet Format
Each line represents one instance of a pair of cognate words. Columns are separated by TAB.

| Column | Description |
| --- | --- |
| concept | A code used by Princeton WordNet 3.0 to represent a meaning (called a synset)|
| language 1 |	the 3-letter iso code for the first language |
| word 1 |	a word in the language 1 |
| language 2 |	the 3-letter iso code for the second language |
| word 2 |	a word in the language 2 |
| evidence |	direct etymological or indirect algorithmic |
| transliteration 1 |	a romanized word for the first word |
| tranlisteration 2 |	a romanized word for the second word |

## License
This tool is available under the Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) License. Read more about this license from https://creativecommons.org/licenses/by-nc-sa/4.0/.

## Reference
Please cite the following article if you use this resource:
https://aclweb.org/anthology/papers/P/P19/P19-1302/

Khuyagbaatar Batsuren, Gabor Bella, and Fausto Giunchiglia – CogNet: A large-scale cognate database, Proceedings of The 57th Annual Meeting of the Association for Computational Linguistics (ACL), 2019.

## Acknowledgements
Thanks to Global Wordnet Association (GWA) and all the wordnet developers.
http://globalwordnet.org/resources/wordnets-in-the-world/
