[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
# Early Modern Danish Postils
This repository contains raw data for a growing collection of postils from Early Modern Denmark. The data has been collected from digitizations of original sources, primarily through the Early European Books project, and prepared for text mining with [Transkribus](https://readcoop.eu/transkribus/?sc=Transkribus).

The compilation of this repository is an extension of the PhD project Piety and theology in 17th century Denmark: Studies in the theology of Jesper Rasmussen Brochmand. Suggestions for additional sources to include and corrections of errors in metadata can be directed at Jonas Kjøller-Rasmussen (jkr@teol.ku.dk)
## Sources

### Hans Tausen (1494-1561)
Published in Danish in a winter and summer part in 1539.
The corpus includes only the text body. Text recognition is performed using a model adapted from Niels Hemmingsen's Postil (HTR+; CER 0.04/0.96). Inital letters have been corrected throughout the postil.

### Niels Hemmingsen (1513-1600)
Published in Latin in 1561 and in Danish translation in 1576 by Rasmus Hansen Reravius
The corpus includes only the text body. Text recognition is performed using a model adapted from Brochmand's Sabbati Sanctificatio Winter Part (HTR+; CER 0.03/1.27).

### Christoph Fischer (1519-1598)
Published in 1616 in Danish translated from German by Anna Krabbe.
The corpus includes only the text body. Text recognition is performed using a model adapted from Brochmand's Sabbati Sanctificatio Winter Part (HTR+; CER 0.04/1.80).

## Poul Andersen Medelby (1557-1632)
Published in Danish in 1621 in a winter and a summer part. Text recognition is performed using a model adapted from Niels Hemmingsen's Postil (HTR+; CER 0.04/0.43).

### Jesper Rasmussen Brochmand (1585-1652)
Published in a winter and summer part in 1635 and 1638.
The corpus includes text from header, footer, and marginalia in addition to text body. It is possible that it will be replaced with a new version that excludes header, footer, and marginalia to reduce noice, but until the process can be automatized, it will be impossible to make updates to the text, once it has been implemented. Text recognition is performed using a model trained on the first 120 pages of Brochmand's Sabbati Sanctificatio Winter Part (PyLaia HTR; CER 0.70/0.90).
