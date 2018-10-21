# Corpus

We provide PoS tag annotated Swiss German text as _xml_ files as well as a PoS tagger model trained on NOAH's Corpus.


## Content

NOAH's Corpus of Swiss German Dialects contains five XML files. Each file contains Swiss German texts in a different text genre:

- _blick.xml_: newspaper articles from ["Blick am Abig", Version Zurich, Nr. 97, 28. Mai 2013](http://epaper.blick.ch/webreader/baa/download/?doc=BAA280513ZH)
- _blogs.xml_: BlogSpot blogs, extracted January 31, 2014 [1](http://alessandrainitaly.blogspot.ch/), [2](http://alinesabroad.blogspot.ch/), [3](http://anitainmexico.blogspot.ch/) 
- _swatch.xml_: [SWATCH annual report 2012](http://www.forum-helveticum.ch/logicio/client/forumhelveticum/file/news/SwatchJahresbericht2012.pdf)
- _schobinger.xml_: [criminal novels by Viktor Schobinger](http://www.zuerituetsch.ch/) 
- _wiki.xml_: articles from the [alemannic Wikipedia](http://als.wikipedia.org), extracted April 10, 2012



## Tagset

As the basic tagset we use the [Stuttgart-Tübingen-TagSet (STTS)](http://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/TagSets/stts-table.html), which is the standard for German. Because of the differences between German and the Swiss German dialects we additionally introduced the tag **PTKINF** as well as the adding of a "**+**"-sign to any PoS tag of a merged word.

The newly introduced tag **PTKINF** represents an infinitive particle like e.g. in "_ich mues **go** poschte_". It is a commonly used and therefore widely analysed phenomenon for Swiss German dialects with no corresponding word or construction in Standard German. 

In order to handle *merged words*, we introduced the "**+**"-sign which can be added to any PoS tag. Since Swiss German does not have official spelling rules, words can be freely joined. Instead of splitting, we identify these merged words by using the corresponding STTS-tag for the main part and add a plus sign to show that a given word consists of more than one simple word. There are sequences of words that are commonly merged, but also less common combinations can appear as it depends on the preferences of the writer.