
# KU Leuven Libraries on GitHub

Read [here](https://github.com/KU-Leuven-Libraries/Welcome-to-KU-Libraries-OpenGLAM/blob/master/README.md) a brief introduction of KU Leuven Libraries on GitHub.  

# The Portraits Collection
The portrait collection at [KU Libraries Special Collections](https://bib.kuleuven.be/bijzondere-collecties/english/home) contains approximately 10.000 prints created between the sixteenth and the twentieth century. They were executed in various techniques: etching, lithograph, mezzotint, steel engraving, wood engraving, heli engraving, etc. The portraits depict professors and academics from Leuven as well as kings, emperors and other aristocratic figures. In some cases they present other scholars and artists. Most portraits are loose leaf materials; others are preserved as part of portrait albums. The portraits were digitised and described as part of the [Europeana project](https://www.europeana.eu/portal/en). The digitisation project was completed in the spring of 2012. 

# The Portraits Dataset

## Repository type
The Portraits dataset is a repository of descriptive metadata representing all the single-file documents with graphic art from the Special Collections of the KU Leuven Libraries that depict people. The digitized Portraits Collection can also be explored through the [Libraries’ Curated Collections](https://limo.libis.be/primo-explore/collectionDiscovery?vid=KULeuven&collectionId=81386064490001488&lang=en_US) discovery interface, within the thematic collection ["Graphic works"](https://limo.libis.be/primo-explore/collectionDiscovery?vid=KULeuven&collectionId=81411248760001488&lang=en_US&query=any,contains,portraits). 



## Who can use it
The repository is designated as a free resource for digital humanities research, for scholars, students and teachers. It also is intended for creative reuses, data visualisations and algorithmic processing.

## Provenance
The dataset is fully based on the library catalogue metadata. It holds the descriptive metadata as well as URL links to the digital representation in thumbnail format. The dataset is published in two formats: an XML file that contains the unprocessed dataset as downloaded from the Alma digital preservation environment of KU Leuven Libraries and a CSV file that contains computationally more amenable curated data. The data was cleaned, transformed and refined with the OpenRefine application software, resulting into 760 individual data processing tasks. The ensuing file of the OpenRefine can also be found in the repository. 

## Technical Aspects
The CSV file contains 10.511 records in rows and 23 columns with the following metadata:


| Column | Content type | Description| Instance
|--|--|--|--|
| A | Record ID |  unique key = record id in original cataloging system | 9985111730101488
| B | Type of date | encoded indication of type of date, [https://www.loc.gov/marc/bibliographic/bd008a.html] | q
| C | Single/first date | the date the print was created | 16uu
| D | Second date | a second indicative date the print was created | \\\\
| E | Language | encoded indication of primary language of publication, [https://www.loc.gov/marc/languages/](https://www.loc.gov/marc/languages/) | lat
| F | Main title | Main title of the publication, [https://www.loc.gov/marc/bibliographic/bd245.html](https://www.loc.gov/marc/bibliographic/bd245.html) | 00$aHenricus van Baelen
| G | Imprint 1-Date of publication | [https://www.loc.gov/marc/bibliographic/bd260.html](https://www.loc.gov/marc/bibliographic/bd260.html) | \$cs.d
| H | Imprint 2-Place of manufacture | [https://www.loc.gov/marc/bibliographic/bd264.html](https://www.loc.gov/marc/bibliographic/bd264.html) | Gravenhage
| I | Imprint 3-Date of manufacture | [https://www.loc.gov/marc/bibliographic/bd264.html](https://www.loc.gov/marc/bibliographic/bd264.html) | date mentioned on print
| J | Imprint 4-Manufacturer | [https://www.loc.gov/marc/bibliographic/bd260.html](https://www.loc.gov/marc/bibliographic/bd260.html) | F.L. Dony & Comp.
| K | Physical Description 1-print length | Description of physical object, varying parameters depending on the nature of the objects, [https://www.loc.gov/marc/bibliographic/bd300.html](https://www.loc.gov/marc/bibliographic/bd300.html) | 242
| L | Physical Description 2-print width | same as above | 152
| M | Physical Description 3-portrait | same as above | 218 x 152 mm
| N | Physical Description 4-page size | same as above | 
| O | Description of graphic material | Describes material and colors of graphic material, [https://www.loc.gov/marc/bibliographic/bd340.html](https://www.loc.gov/marc/bibliographic/bd340.html) | \\$oBlack-and-white
| P | General notes | [https://www.loc.gov/marc/bibliographic/bd500.html](https://www.loc.gov/marc/bibliographic/bd500.html) | \\$atitel gecreeÌ erd door catalograaf
| Q | Authors | [https://www.loc.gov/marc/bibliographic/bd700.html](https://www.loc.gov/marc/bibliographic/bd700.html) | -
| R | Typographical terms 1 | Terms taken from a list of terms to retrieve certain (typo)graphical techniques, phenomena etc.(local use), | etching
| S | Typographical terms 2 | Terms taken from a list of terms to retrieve certain (typo)graphical techniques, phenomena etc.(local use), | engraving
| T | Inscriptions | Transcriptions of the texts found on the portraits, local use | \\$aHENRICVS VAN BAELEN
| U | Link to digital object 1 | direct url to record in Limo, the search interface of the library | http://resolver.libis.be/FL4856542/thumbnail
| V | Query URL | url l | [https://limo.libis.be/primo-explore/search?](https://limo.libis.be/primo-explore/search?query=any,contains,9985111730101488&tab=all_content_tab&search_scope=ALL_CONTENT&vid=KULeuven)
| W | Physical original | direct code to physical location of the print | KU Leuven Libraries BIBC BRES RC97/094




## Cite this dataset
When referring to or using the data repository in research publications and documentation, consider citing the dataset with its digital object identifier (DOI) that is minted in Zenodo [![DOI](https://zenodo.org/badge/203035328.svg)](https://zenodo.org/badge/latestdoi/203035328)
. Citing the data repository of the Portraits collection creates a mapping of attribution supporting efforts to release other datasets in the future. It also reduces the amount of "orphaned data," helping to retain source links. 
Cite the repository as: KU Leuven Libraries, Digitisation Department. (2019). The Portraits Collection Dataset of KU Leuven Libraries, Special Collections (Version 01-beta2) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.3370729.

## License    
The Portraits Collection repository is licensed under a [Public Domain Mark](https://creativecommons.org/share-your-work/public-domain/pdm/) (PDM). PDM operates as a label indicating that the dataset is no longer restricted by copyright and can be freely used by everyone. 
KU Leuven Libraries follows an open images policy that allows its public domain digitised heritage collections to be freely copied, modified, distributed and reused, only by mentioning “KU Leuven. [Name of the collection]” without asking for further permission. For a detailed view of the library’s legal compliances see:
https://bib.kuleuven.be/BD/digitalisering-en-document-delivery/digitalisering/gebruiksvoorwaarden 

## Code of Conduct
The GitHub repository of KU Leuven Libraries follows the [CNCF Code of Conduct](https://github.com/cncf/foundation/blob/master/code-of-conduct.md), as a way to be overt in our openness, welcoming all people to contribute, and pledging in return to value them. In order to make our open communities welcoming, diverse and inclusive, we are encouraging the adaptation of the Contributor Covenant as a means to express and codify those values. Any unacceptable behavior as trolling, insulting/derogatory comments, personal or political attacks will not be tolerated. The Contributor Covenant is released under the Creative Commons Attribution 4.0 International Public License.

## Project Attribution
[KU Leuven Libraries](https://bib.kuleuven.be/english)
* Dr. Nele Gabriels: Digitisation Department (project supervisor) 
* Bruno Vandermeulen: Digitisation Department (project advisor)
* Diederik Lanoye: Metadata Services and Acquisitions
* An Smets: Special Collections 
<br/>

[Advanced Master of Digital Humanities (MSc), KU Leuven](https://set.kuleuven.be/onderwijs/mdh)
* Mariana Ziku: Trainee

## Contributors
This project follows the [all-contributors](https://allcontributors.org) specification. KU Leuven Libraries recognises contributions and engagement for its open data repository through [emoji key](https://allcontributors.org/docs/en/emoji-key)✨, in a way to reward every contribution, not only code. Contributions of any kind like questions, ideas, link to videos, translations and many more will be automatically acknowledged through the all-contributors bot 🤖.
</br>
</br>
KU Leuven Libraries would like to thank the following contributors (emoji key):
