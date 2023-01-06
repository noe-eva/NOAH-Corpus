# NOAH's Corpus: Part-of-Speech Tagging for Swiss German

Swiss German is a dialect continuum of the Alemannic dialect group. It comprises numerous varieties used in the German-speaking part of Switzerland. Although mainly oral varieties (_Mundarten_), they are frequently used in written communication. On the basis of their high acceptance in the Swiss culture and with the introduction of digital communication, Swiss German has undergone a spread over all kinds of communication forms and social media. Considering the lack of standard spelling rules, this leads to a huge linguistic variability because people write the way they speak. 

Such a situation is a challenging task for NLP and we would like to provide data and resources to serve as a stepping stone to automatically process texts written in these dialects. We compiled NOAH's Corpus of Swiss German Dialects consisting of various text genres, manually annotated with Part-of-Speech tags. Furthermore, we applied this corpus as training set to a statistical Part-of-Speech tagger and a dialect identification model.

## Original Corpus

NOAH's Corpus of Swiss German Dialects contains five XML files.
Each file contains Swiss German texts in a different text genre:
- blick.xml: newspaper articles from "Blick am Abig", Version Zurich, Nr. 97, 28. Mai 2013 [1]
- blog.xml: BlogSpot blogs, extracted 31 January, 2014 [2]
- swatch.xml: SWATCH annual report from 2012 [3]
- schobinger.xml: criminal novels by Viktor Schobinger [4]
- wiki.xml: articles from the alemannic Wikipedia [5]

[1] http://epaper.blick.ch/webreader/baa/download/?doc=BAA280513ZH
[2] http://alessandrainitaly.blogspot.ch/, http://alinesabroad.blogspot.ch/, http://anitainmexico.blogspot.ch/
[3] http://www.forum-helveticum.ch/logicio/client/forumhelveticum/file/news/SwatchJahresbericht2012.pdf
[4] http://www.zuerituetsch.ch/
[5] als.wikipedia.org, downloaded: 10 April, 2012

## Model

The most recent model (Jan 2023) is available on the Huggingface Model Hub: [swiss_german_pos_model](https://huggingface.co/noeminaepli/swiss_german_pos_model)

## Test Set used in the ACL 2022 paper [Improving Zero-Shot Cross-lingual Transfer Between Closely Related Languages by Injecting Character-Level Noise](https://noe-eva.github.io/publication/acl22/)

- test_GSW_STTS.txt (annotated with [STTS](https://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/germantagsets/) tags)
- test_GSW_UPOS.txt (annotated with [Universal POS](https://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/germantagsets/) tags)


## Annotations

All texts have been tokenized and manually annotated with Part-of-Speech tags.
The tagset is described in "Compilation of a Swiss German Dialect Corpus and its Application to PoS Tagging" 
(Nora Hollenstein and Noëmi Aepli, VarDial Workshop, 2014).
The UPOS tags were created by a mapping from STTS to UPOS.

## Metadata

Each article in the XML files contains a title and, where known, the dialect it is written in.

## License

This resource is freely available for research, education and evaluation. 



## [Official Website](https://noe-eva.github.io/NOAH-Corpus/)
