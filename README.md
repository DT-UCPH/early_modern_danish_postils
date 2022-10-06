<<<<<<< HEAD
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7113232.svg)](https://doi.org/10.5281/zenodo.7113232)
=======
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7113233.svg)](https://doi.org/10.5281/zenodo.7113233)
>>>>>>> ce647aefdfab9b5bb5d8022140d538fef7d66f49
[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
# Early Modern Danish Postils
This repository contains raw data for a growing collection of postils from Early Modern Denmark. The data has been collected from digitizations of original sources, primarily through the Early European Books project, and prepared for text mining with [Transkribus](https://readcoop.eu/transkribus/?sc=Transkribus).

The compilation of this repository is an extension of the PhD project Piety and theology in 17th century Denmark: Studies in the theology of Jesper Rasmussen Brochmand. Suggestions for additional sources to include and corrections of errors in metadata can be directed at Jonas Kjøller-Rasmussen (jkr@teol.ku.dk)
## Sources
The sources in the corpus are listed by author in order of publication date with brief comments on the state of the text as exported from Transkribus. Unless otherwise noted the data only includes the body of the text and ignores header, footer, and marginalia. This also means that page numbers are not currently part of the dataset, but might be included in future versions with better metadata and annotations.
### Hans Tausen (1494-1561)
Text recognition is performed using a model adapted from Niels Hemmingsen's Postil (HTR+; CER 0.04/0.96). Inital letters have been corrected throughout the postil.
>Tausen, Hans. *Winterdelen aff Postillen berid aff M. Hanss Tausen / Predickere ÿ Kjøbenhaffn*. Magdeburg: Hanss Walther, 1539.

>Tausen, Hans. *Sommerdelen aff Postillen berid aff M. Hanss Tausen / Predickere ÿ Kjøbenhaffn*. Magdeburg: Hanss Walther, 1539.

### Martin Luther (1483-1564)
Text recognition is performed using a model adapted from Hemmingsen's Postil (HTR+; CER 0.03/0.09).
>Luther, Martin. 1564. *Husspostille Offuer alle Søndagers oc de besynderlige Høytiders Euangelier det gantske Aar igennem / met xiij. Predickener offuer Christi pinis Historie.* Translated by Peder Tidemand. København: Lorentz Benedict.

>Luther, Martin. 1564. *Husspostille Offuer alle Søndagers Euangelier fra Paaske indtil Aduente.* Translated by Peder Tidemand. København: Lorentz Benedict.

>Luther, Martin. 1564. *Husspostille Offuer alle Euangelier som læsis paa besynderlige Høytider.* Translated by Peder Tidemand. København: Lorentz Benedict.

### Niels Hemmingsen (1513-1600)
Text recognition is performed using a model adapted from Brochmand's Sabbati Sanctificatio Winter Part (HTR+; CER 0.03/1.27). Initial letters have been corrected throughout the postil.
>Hemmingsen, Niels. 1576. *Postilla Eller Forklaring offuer Euangelia / som almindelige om Søndage oc andre Hellige dage predickis i den christne Kircke / vdi Danmarck og Norge… Første Part*. Translated by Rasmus Hansen Reravius. København: Andrea Gutterwitz oc Hans Stöckelmands Arffuinge.

>Hemmingsen, Niels. 1576. *Postilla Eller Forklaring offuer Euangelia / som almindelige om Søndage oc andre Hellige dage predickis i den christne Kircke / vdi Danmarck og Norge… Anden Part*. Translated by Rasmus Hansen Reravius. København: Andrea Gutterwitz oc Hans Stöckelmands Arffuinge.

>Hemmingsen, Niels. 1576. *Postilla Eller Forklaring offuer Euangelia / som predickis oc læsis i Kirckerne paa Fester og Helligedage...* Translated by Rasmus Hansen Reravius. København: Andrea Gutterwitz oc Hans Stöckelmands Arffuinge.

### Christoph Fischer (1519-1598)
Text recognition is performed using a model adapted from Brochmand's Sabbati Sanctificatio Winter Part (HTR+; CER 0.04/1.80).
>Fischer, Christoph. 1616. *Haand Postilla, i huilcken alle Søndagers og Festers Evangelia med fire korte Spørsmaal bliffver forklaret paa danske*. Translated by Anna Krabbe. Lübeck: N.p.

### Poul Andersen Medelby (1557-1632)
Text recognition is performed using a model adapted from Niels Hemmingsen's Postil (HTR+; CER 0.04/0.43).
>Medelby, Poul Andersen. 1621. *Ungdommens Postil :  Kort oc god Forklaring / Effter den Augszburgeske Confeszion / Offuer alle Evangelia / som paa Søndagene / oc alle andre Hellige Fester fremsættes … Vinter Parten*. København: Salomon Sartor.

>Medelby, Poul Andersen. 1621. *Ungdommens Postil :  Kort oc god Forklaring / Effter den Augszburgeske Confeszion / Offuer alle Evangelia / som paa Søndagene / oc alle andre Hellige Fester fremsættes … Sommer Parten*. København: Salomon Sartor.

### Jesper Rasmussen Brochmand (1585-1652)
Text recognition is performed using a model trained on the first 120 pages of Brochmand's Sabbati Sanctificatio Winter Part (PyLaia HTR; CER 0.70/0.90).
>Brochmand, Jesper Rasmussen. 1635. *SABBATI SANCTIFICATIO. Det er: Gudelig Betenckning oc kort Forklaring offuer alle EVANGELIER oc EPISTLER, som paa Søndage oc alle hellige Dage / udi Guds Meenighed / det gandske Aar igiennem / pleye at fremsættis oc forhandlis: Guds Børn til Gudelig Øffuelse forfattet. Vinter-Parten*. København: Melchior Martzan.

>Brochmand, Jesper Rasmussen. 1638. *SABBATI SANCTIFICATIO. Det er: Gudelig Betenckning oc kort Forklaring offuer alle EVANGELIER oc EPISTLER, som paa Søndage oc alle hellige Dage / udi Guds Meenighed / det gandske Aar igiennem / pleye at fremsættis oc forhandlis: Guds Børn til Gudelig Øffuelse forfattet. Sommer-Parten*. København: Melchior Martzan.

## Stopwords
The collection is accompanied by a list of stopwords for 16th and 17th century Danish. The list is based on a collection of function words (particles, prepositions, conjunctions, articles, adverbs, auxiliary verbs) developed in the project Danish under Digital Study (DUDS) at University of Copenhagen and adapted for early modern orthography using the 300 most frequently occuring word forms in the corpus.