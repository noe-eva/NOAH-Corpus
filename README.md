# Swiss German PoS Tagging

Swiss German is a dialect continuum of the Alemannic dialect group. It comprises numerous varieties used in the German-speaking part of Switzerland. Although mainly oral varieties (_Mundarten_), they are frequently used in written communication. On the basis of their high acceptance in the Swiss culture and with the introduction of digital communication, Swiss German has undergone a spread over all kinds of communication forms and social media. Considering the lack of standard spelling rules, this leads to a huge linguistic variability because people write the way they speak. 

Such a situation is a challenging task for NLP and we would like to provide data and resources to serve as a stepping stone to automatically process texts written in these dialects. We compiled NOAH's Corpus of Swiss German Dialects consisting of various text genres, manually annotated with Part-of-Speech tags. Furthermore, we applied this corpus as training set to a statistical Part-of-Speech tagger and a dialect identification model.



# Publications

Noëmi Aepli, Nora Hollenstein, Simon Clematide. _NOAH 3.0:  Recent Improvements in a Part-of-Speech Tagged Corpus for Swiss German Dialects._ [SwissText](https://www.swisstext.org/) 2018: 116.  ([PDF](/docs/swisstext_2018_abstracts.pdf)) ([poster](/docs/swisstext_2018_noah.pdf))

Nora Hollenstein & Noëmi Aepli. _A Resource for Natural Language Processing of Swiss German Dialects._ [GSCL](https://www.gscl.org/) 2015: 108.
([PDF](https://pdfs.semanticscholar.org/e250/0609bd7dc44f43f22560c8af69fccc3b7afd.pdf)) ([poster](/docs/gscl2015_poster.pdf))

Nora Hollenstein & Noëmi Aepli. _Compilation of a Swiss German Dialect Corpus and its Application to PoS Tagging._ [VarDial@COLING 2014](http://corporavm.uni-koeln.de/vardial/): 85.
([PDF](http://www.aclweb.org/anthology/W14-5310)) ([poster](/docs/vardial2014_poster.pdf))


# Talks

_Swiss German NLP_, [IBM Developer UnConference Meetup Zürich](https://www.meetup.com/de-DE/Big-Data-Developers-Switzerland/events/242917086/?isFromReg=true&fromJoin=242917086), 18.1.2018 ([slides](/docs/IBM_UnConference_2018_gsw.pdf))

_Swiss German NLP_, [NLP Meetup Zürich #3](https://www.meetup.com/NLP-Zurich/events/243080359/), 28.9.2017 ([slides](/docs/NLP_Meetup_2017_gsw.pdf))

# Demo

<form action="https://pub.cl.uzh.ch/demo/noah/wapiti.cgi" method="POST" accept-charset="UTF-8" name="FormName" target="resultat">
 

                <fieldset style="border-width:1px;border-color:#eefeee;border-radius:0.3rem">
                    <input style="color:#606c71; border-color:#c0c0c0" class="btn" type="submit" value="Analyze" name="submitButtonName">
                    <legend>Input </legend>
                    <textarea name="t" style="padding:0.6rem 0.9rem;width:100%;border-radius:0.3rem;border-color:#c0c0c0" rows="5" cols="180">Das isch es Bispiili mitem Wort Chuchichäschtli drin .</textarea>
                    Format: words separated by white-space
                </fieldset>

       
                <fieldset style="margin-top:1rem;border-width:1px;border-color:#eefeee;border-radius:0.3rem">
                    <legend>Output</legend>
                    <iframe style="padding:0.6rem 0.9rem;border-width:0px;width:100%  " name="resultat" id="resultat" src="" marginwidth="0" marginheight="0" align="left" scrolling="yes" >
                        <p>Your browser does not support  frames, sorry!</p>
                    </iframe>
                </fieldset>
</form>

