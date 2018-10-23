# Corpus

We provide PoS-tag annotated Swiss German text as _xml_ files as well as a PoS-tagger model trained on NOAH's Corpus.


## Content

NOAH's Corpus of Swiss German Dialects contains five _xml_ files. Each file contains Swiss German texts of a different genre:

- **blick**: newspaper articles from ["Blick am Abig", Version Zurich, Nr. 97, 28. Mai 2013](/docs/blick_am_abend_chde_2013.pdf)
- **blogs**: "BlogSpot" blogs, extracted 31.1.2014 [blog1](http://alessandrainitaly.blogspot.ch/), [blog2](http://alinesabroad.blogspot.ch/), [blog3](http://anitainmexico.blogspot.ch/) 
- **swatch**: [SWATCH annual report 2012](/docs/2012_annual_report_complete_ch.pdf)
- **schobinger**: extracts of criminal novels by [Viktor Schobinger](http://www.zuerituetsch.ch/) 
- **wiki**: articles from the [Alemannic Wikipedia](http://als.wikipedia.org), extracted 10.4.2012



## Tagset

As the basic tagset we use the [Stuttgart-Tübingen-TagSet (STTS)](http://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/TagSets/stts-table.html), which is the standard for German. Because of the differences between German and the Swiss German dialects we additionally introduced the tag **PTKINF** as well as the adding of a "**+**"-sign to any PoS tag of a merged word.

The newly introduced tag **PTKINF** represents an infinitive particle like e.g. in "_ich mues **go** poschte_". It is a commonly used and therefore widely analysed phenomenon for Swiss German dialects with no corresponding word or construction in Standard German. 

In order to handle *merged words*, we introduced the "**+**"-sign which can be added to any PoS tag. Since Swiss German does not have official spelling rules, words can be freely joined. Instead of splitting, we identify these merged words by using the corresponding STTS-tag for the main part and add a plus sign to show that a given word consists of more than one simple word. There are sequences of words that are commonly merged, but also less common combinations can appear as it depends on the preferences of the writer.
