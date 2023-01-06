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

### Annotations

All texts have been tokenized and manually annotated with Part-of-Speech tags. The UPOS tags were created by a mapping from STTS to UPOS.
The original tagset is described in "Compilation of a Swiss German Dialect Corpus and its Application to PoS Tagging".

### Metadata

Each article in the XML files contains a title and, where known, the dialect it is written in.

## Model (updated: Jan 2023)

The most recent model (Jan 2023) is available on the Huggingface Model Hub: [swiss_german_pos_model](https://huggingface.co/noeminaepli/swiss_german_pos_model)

## Test Set used in the ACL 2022 paper
### ACL Publication: [Improving Zero-Shot Cross-lingual Transfer Between Closely Related Languages by Injecting Character-Level Noise](https://noe-eva.github.io/publication/acl22/)

- test_GSW_STTS.txt (annotated with [STTS](https://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/germantagsets/) tags)
- test_GSW_UPOS.txt (annotated with [Universal POS](https://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/germantagsets/) tags)



## Publications

```
@inproceedings{hollenstein2014compilation,
  title={Compilation of a Swiss German dialect corpus and its application to PoS tagging},
  author={Hollenstein, Nora and Aepli, No{\"e}mi},
  booktitle={Proceedings of the first workshop on applying NLP tools to similar languages, varieties and dialects},
  pages={85--94},
  year={2014}
}

@inproceedings{DBLP:conf/gldv/HollensteinA15,
  author={Nora Hollenstein and Noëmi Aepli},
  title={A Resource for Natural Language Processing of Swiss German Dialects},
  year={2015},
  cdate={1420070400000},
  pages={108-109},
  url={http://gscl2015.inf.uni-due.de/wp-content/uploads/2016/02/GSCL-201515.pdf},
  booktitle={GSCL},
  crossref={conf/gldv/2015}
}

@inproceedings{zora159152,
       booktitle = {SwissText 2018},
           month = {June},
           title = {Parsing Approaches for Swiss German},
          author = {No{\"e}mi Aepli and Simon Clematide},
       publisher = {s.n.},
            year = {2018},
        language = {english},
             url = {https://doi.org/10.5167/uzh-159152}
}


@inproceedings{aepli-sennrich-2022-improving,
    title = "Improving Zero-Shot Cross-lingual Transfer Between Closely Related Languages by Injecting Character-Level Noise",
    author = {Aepli, No{\"e}mi  and
      Sennrich, Rico},
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2022",
    month = may,
    year = "2022",
    address = "Dublin, Ireland",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.findings-acl.321",
    doi = "10.18653/v1/2022.findings-acl.321",
    pages = "4074--4083",
}

```


## License

This resource is freely available for research, education and evaluation. 



## [Official Website](https://noe-eva.github.io/NOAH-Corpus/)
