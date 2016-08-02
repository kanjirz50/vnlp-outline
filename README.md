# Vietnamese Natural Language Processing(Xử lý ngôn ngữ tiếng Việt)

## Outline
This page describes Vietnamese NLP tools, resources and some computation techniques related on Vietnamese.
If there is something missing or wrong information, please send an issue.

(Sorry, I don't speak Vietnamese.)


## Tools
### Diacritics restoration
#### Vietnamese diacritics restoration tool
[Github](https://github.com/kanjirz50/restore-tonemark), [demonstration](http://160.16.58.116/vietnamese/tone)

This tool is based on a point-wise diacritics restoration.

### Word segmentation
#### DongDu
[Github](https://github.com/rockkhuya/DongDu), [website](http://viet.jnlp.org/dongdu)

DongDu is a fastest and high accuracy word segmentation tool based on SVMs.

#### vnTokenizer
[website](http://vlsp.hpda.vn:8080/demo/?page=resources)

vnTokenizer provides Java interface.
I found some unofficial github repositories.

### Part-of-Speech tagging
#### vnTagger
[website](http://vlsp.hpda.vn:8080/demo/?page=resources)

This tool provides Java interface.

### Joint word segmentation and Part-of-Speech tagging
#### Vietnamese joint word segmentation and Part-of-Speech tagging based on SVM
[Github](https://github.com/kanjirz50/viet-morphological-analysis-svm), [demonstration](http://160.16.58.116/vietnamese/morph)

This tool provides Python interface.

#### Vietnamese joint word segmentation and Part-of-Speech tagging based on CRF
[Github](https://github.com/kanjirz50/viet-morphological-analysis-crf), [demonstration](http://160.16.58.116/vietnamese/morph_crf)

This tool provides Python interface.


### Other Tools
#### Vitk -- a Vietnamese text processing toolkit
[Github](https://github.com/phuonglh/vn.vitk)

This toolkit is for large data processing, includes word segmentation, part-of-sppech tagging, dependency parsing.


## Resources
### Treebank
Vietnamese treebank

[website](http://vlsp.hpda.vn:8080/demo/?page=resources)

### Corpus
#### VNESEcopus.txt
[website](http://vlsp.hpda.vn:8080/demo/?page=resources)

650 thousand sentences.

#### VNTQcorpus(small).txt
[website](http://viet.jnlp.org/download-du-lieu-tu-vung-corpus)

300 thousand sentences.

#### VNTQcorpus(big).txt
[website](http://viet.jnlp.org/download-du-lieu-tu-vung-corpus)

1.75 million sentences.

### Bilingual Corpus
#### English-Vietnamese bilingual corpus
[website](http://vlsp.hpda.vn:8080/demo/?page=resources)


## Technique
### Unicode normalization
NFC is a one of the unicode normalization form.
It is suitable for Vietnamese text preprocessing.

### Syllable normalization

## Articles
- Tuan Anh Luu and Kazuhide Yamamoto. A Point-wise Approach for Vietnamese Diacritics Restoration. Proceedings of the International Conference on Asian Language Processing (IALP 2012), pp.189-192 (2012.11)
