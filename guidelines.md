# Annotation Guidelines


Grundlegendes Tagset: 
_Stuttgart-Tübingen Tagset_ (STTS)
http://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/TagSets/stts-table.html

Grundlegendes Annotationsschema: _TIGER_
https://www.linguistics.ruhr-uni-bochum.de/~dipper/pub/tiger_annot.pdf

## Gemäss S. 123 vom TIGER Annotationsschema: "Vorgenommene Änderungen am STTS":
- PIDAT vs PIAT: Unterscheidung wird nicht getroffen, PIAT wird für alle attribuierenden Indefinitpronomen mit und ohne Determiner verwendet
- PAV vs. PROAV: Statt des STTS-Tags PAV wird - bei gleicher Bedeutung - PROAV verwendet.
- **(? - TODO!)** ADV: Präpositionen werden als ADV getaggt, wenn sie Numeralien modifizieren. (S. 12: Zur besseren Unterscheidung von PPs wird in Ausdrücken wie "unter 1000 Mark" der NM-Modifikator als ADV getagged)

## Prinzip

Grundlegendes Prinzip: Bei Entscheidungsschwierigkeiten entscheiden wir uns für diejenige Variante, welche syntaktisch am plausibelsten ist.

### Syntaktische Entscheidungen
- Abgetrennte Verbzusätze, welche nicht abgetrennt sein sollten, werden als ADV getagged (_eweg/ADV_ _gnoo/VVPP_)

### Abweichungen vom TIGER-Annotationsschema
- Partizip Perfekt von Modalverben werden als solche (VMPP) getagged, auch wenn sie morphologisch wie Infinitive aussehen: ("ich ha/VAFIN das _müesse/VMPP_ läse/VVINF.")
- Webseiten als XY



## NEUE TAGS

### PTKINF
- _go_, _cho_, _gogä_, _lo_ als Infinitiv Partikel

### TAG+
- TAG+ nur verwenden wenn man das Wort im Schwiizerdütsch getrennt schreiben "kann"
- _hemersi_, _machemer_
- _nüme_ (TAG+ immer wenn das Wort auf Hochdeutsch auseinander geschrieben wird)

## SPEZIALFÄLLE SCHWEIZERDEUTSCH

### ADV
- _dihei_ (von "zuhause")
- "Ich freu mich _uuuh_ (ADV) fescht."
- Abgetrennte Verbzusätze, welche nicht abgetrennt sein sollten, werden als ADV getagged (_eweg/ADV_ _gnoo/VVPP_)

### APPR
- _anhand_ (_anhand vo_ APPR APPR)

### ITJ
- für "gopfridstutz”, grüezi
- mmmh, okay, hoi, haha, gäll

### PIS
- man
- "als eini (PIS) vo de Partnerinnä"
- "und uf psundere wunsch git s namal äine (PIS)"
- "öppis/PIAT anders/PIS" (gemäss Tiger)
- "sovil"

### PPER
- "tuet eim (PPER) ide auge weh"
- "da cha eim (PPER) jede ine luege"

### PTKNEG


### PTKVZ
- "sie chunt hei (PTKVZ)" --> heicho

### VAFIN, VAINF, VAPP, VAIMP
- werden, sein, haben

### VMPP
- "hend chöne lärne" --> chöne = VMPP
Erklärung: Duden https://www.duden.de/rechtschreibung/koennen macht klar, dass können als Modalverb (und nicht als Vollverb) als Partizip die Form "können" hat.

### XY
- für :-), :(, etc.
- Abkürzungen, z.B. Kantonsbezeichnungen (NE für Neuchatel)
- URLs, Webseiten

## TOKENISIERUNG

### APOSTROPHE
Apostrophe werden abgetrennt, wenn sie klar zwei Wörter verbinden (zwei Wörter mit unterschiedlichen PoS-Tags):
Beispiel:
"s'Huus" --> s (ART) + ' ($() + Huus (NN)

Aber nicht, wenn ein Apostroph im Inneren eines einzelnen Wortes vorkommt:
Beispiele:
"D's Spiil" --> D's (ART) + Spiil (NN)
"g'sunge" --> g'sunge (VVPP)
"umz'stellä" --> umz'stellä (VVIZU)
"z'Nacht" --> z'Nacht (NN)
"z'Morge" --> z'Morge (NN)


## Difficult Cases


### PAV vs ADV
The following words are always tagged as PAV: _trotzdem_, _außerdem_ 


### CARD vs NN
In cases as _mehreri Hunderttusigi Stutz_ we tag _Hunderttusigi/CARD_ as in TIGER.
