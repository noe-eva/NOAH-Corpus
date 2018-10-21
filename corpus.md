# Corpus


## Content

NOAH's Corpus of Swiss German Dialects contains five XML files. Each file contains Swiss German texts in a different text genre:

- BlickAmAbend.xml: newspaper articles from "Blick am Abig", Version Zurich, Nr. 97, 28. Mai 2013 [1]
- Blogs.xml: BlogSpot blogs, extracted January 31, 2014 [2,3,4]
- SwatchAnnualReport.xml: SWATCH annual report from 2012 [5]
- ViktorSchobinger.xml: criminal novels by Viktor Schobinger [6]
- Wikipedia.xml: articles from the alemannic Wikipedia, extracted April 10, 2012 [7]



## Tagset

As the basic tagset we use the [Stuttgart-Tübingen-TagSet (STTS)](http://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/TagSets/stts-table.html), which is the standard for German. Because of the differences between German and the Swiss German dialects we additionally introduced the tag PTKINF as well as the adding of a "+"-sign to any PoS tag of a merged word.

The newly introduced tag PTKINF represents an infinitive particle. It is a commonly used and therefore widely analysed phenomenon for Swiss German dialects with no corresponding word or construction in German. In NOAH's Corpus we found 37 occurrences of this tag.

Furthermore, we introduce special tags for merged words. Since Swiss German does not have official spelling rules, words can be freely joined. Instead of splitting, we identify these merged words by using the corresponding STTS-tag for the first part and add a plus sign to show that a given word consists of more than one simple word. There are sequences of words that are commonly joined, but also less common combinations can appear as it depends on the preferences of the writer. We found 1008 occurrences of merged words, which represent 1.37% of all tokens in the corpus. 