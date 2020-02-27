<!-- This is cut out from the original README.md file where it doesn't fit anymore. Will be cut up more and put where it belongs either here on the Wiki or in individual files on the repo proper. -->
#project draft

## Implementation
### Step 1: Examination of Materials

The project participants meet IRL at the National Library in Oslo for a one-day workshop (aka hackathon) in September 2018.

#### Schedule for the kick-off workshop

| Time | Topic |
|------|------|
| 10.00 – 10.45 | Introduction to NorKorr |
| 10.45 – 11.00  | Break |
| 11.00 – 13.00 | Create an overview of correspondence editions in our collections |
| 13.00 – 14.00 | Lunch |
| 14.00 – 15.45 | Write a report on what we have collected, assign tasks for further work and decide on further steps |
| 15.45 – 16.00 | Wrapping up + coffee |

### Examination of Materials

We will take a close look at our materials (digital editions of Norwegian correspondences), with regards to:

 - Technical aspects
	 - file format
	 - TEI P5
	 - TEI P4
	 - Other XML
	 - Non-XML
	 - Plain text
	 - Image (scan)
 -  metadata format and coverage
	 - authority data for person & place names, ISO standard for dates
	 - [http://viaf.org/](http://viaf.org/) (NB is member
	 - [https://en.wikipedia.org/wiki/Virtual_International_Authority_File](https://en.wikipedia.org/wiki/Virtual_International_Authority_File)
	 - [https://www.geonames.org/](https://www.geonames.org/)
	 - [https://www.iso.org/iso-8601-date-and-time-format.html](https://www.iso.org/iso-8601-date-and-time-format.html)
	 - licences (aka copyright, other limitations)
	 - …
 - Content
	 - persons (who)
	 - periods
	 - scope (part, whole, selection etc.)
 - Time and Budget

#### Materials to depart from
-   [NB-kilder](https://www.nb.no/forskning/nb-kilder/)
-   [Ibsen skrifter](http://ibsen.uio.no/brev.xhtml)
-   [Munch tekster](https://www.emunch.no/english.xhtml)
-   [Qvigstad brev](https://www.dokpro.uio.no/qvigstad/ombrev.html) (started as a project of EDD/UiO [http://www.dokpro.uio.no/qvigstad/](http://www.dokpro.uio.no/qvigstad/), now at UiT/NB)
-   [Bokselskap.no](http://www.bokselskap.no/)

Goal of the workshop is to come up with (1) an overview of digital editions of correspondences that are good candidates for CorrespSearch and (2) identify the work tasks needed to transform (select, format) the metadata to conform to the CorrespSearch CMIF standard (3) assign tasks to the participants and (4) agree on delivery dates for the work packages.

A brief but precise description of (1) will be done, including a list of authors (see Appendix 1), time periods and content of the correspondences to show the potential for future research on this corpus.

### CorrespSearch and CMIF

[CMIF Standard](https://github.com/TEI-Correspondence-SIG/CMIF)

[CorrespDesc](https://github.com/TEI-Correspondence-SIG/correspDesc)

### Step 2: NorKorr to CorrespSearch

The participants prepare a conference paper and a research article about the workflow (material, data formats, distributed hosting, transformations etc.) for NorKorr as an example of preparing large distributed heterogeneous metadata sets for ingestion into CorrespSearch. They explore the potential of such an endeavour and discuss advantages (and challenges) of using decentralized infrastructure and third-party solutions with regards to Norwegian cultural heritage institution’s scope and policies. The workflow is supposed to serve as a basis for further editions of Norwegian correspondences and should stand as an example of re-use of digital data (and especially metadata) provided by large institutions of cultural heritage and research, especially in the Nordic countries.

The paper could be presented at the TEI2019 International Conference in Graz/Austria in September 2019. Alternatively (or additionally), the paper could be given at one of the DH conferences (DHN2019 in early March, DHd2019 in late March, DH2019 in July) or at conferences for edition philology (NNE2019 in September or AG-Edition in February 2020) or Historical Network Research (HNR2019 tba).

The article should be an edited and polished version of the paper and published soon after delivering the paper (aim: 2020, open access journal, international).

### Step 3: NorKorr at NB - The Catalogue Data from the Private Archives and Automatic Correspondence Metadata Extraction from Bokhylla.no

This part of the project is tentative. It shall show the potential of the physical and digital collections of the National Library of Norway, especially in regards to exploiting digital humanities methods in metadata and text mining.

#### Correspondence Material in the Private Archives

<!-- Via nb.no/nbsok using the search phrase “brev -indulgens” yields 14.824 letters in the holdings of the Private Archives that have been digitized. These should be combed through to select all that are not correspondences or letters. Of the remaining, the letters have to be matched with DSEs in NB-kilder and Bokselskap.no as well as the digitized scholarly editions of letters in bokhylla.no. They can be used as facsimile or alternative presentations where copyright of scholarly editions prevents external access. The metadata of these letters could be extracted and matched with the CIMF standard. -->

#### Hvem-til-hvem

<!-- As of XXXX, metadata for correspondences in the holdings of the Private Archive are stored in HANSKE (Manuscript Catalogue, [https://www.nb.no/hanske/](https://www.nb.no/hanske/) ) which in the course of being phased out and replaced by ZZ.. Some of the correspondence metadata in the archive have previously been extracted for searching for correspondence partners and dates. There’s a website providing access to a tool (BETA version) where users can type in person names or years and get a list of results from which they can navigate onwards: [https://www.nb.no/hanske/brev/](https://www.nb.no/hanske/brev/) . The service has been developed by Torstein Tjelta (NB). -->

Tasks:

-   Take a look at the catalogue data and materials and sketch a workflow for making them compatible with the CMIF-Standard used by CorrespSearch
-   Take a look at database behind “Hvem skrev til hvem” and decide if and how to extract data and transform to CMIF-Standard
-   How is correspondence metadata stored today and in the future and how can it be easily fed into CorrespSearch, granted this is wanted by NB

#### Bokhylla.no

The digitisation efforts of the NB provide an enormous amount of textual data. Included in this are Norwegian scholarly editions of correspondences that formerly were printed and now have been digitized in full text (OCR). In order to complete the NorKorr metadata set, first a selection of scholarly editions of Norwegian correspondences has to be made. Then, from the text of the editions, correspondence metadata has to be (semi-)automatically extracted, stored, and transformed into a CMIF compliant format to be ingested into CorrespSearch.

This is an endeavour of considerable complexity and size and requires expert knowledge in information retrieval from plain text. At this stage, it should be seen as an experiment in retrieving specific textual data from a large collection of text without too much manual interference. The results of this experiment could be presented as a paper or article in the future and the workflow and code could be published for re-use on other full-text collections that contain flat encoded texts (aka plain text).

A list of URNs of digitized scholarly editions of correspondences and letters will be created (by AR) and the raw OCR files will be extracted from bokhylla.no by LJ. The corpus will then be divided into materials that are in the public domain and such that are still under copyright protection. For the letters still under copyright protection, no full-text can be shown outside of the NB, however, amount of words, word lists and topic models can be extracted that should allow for ‘distant reading’ of these letters.

#### Aims

The aims for the two subprojects in Step 3 are:

-   meaningful re-use of a tool/service developed by NB (HANSKE / Hvem skrev til hvem)
-   accessibility of correspondence metadata that hasn’t been edited yet (or won’t ever be)
-   targeted retrieval of specific data (correspondence metadata from digitized scholarly editions) from bokhylla.no showing the potential of the digital collection even though it is flat encoded
-   large scale show case for “distant reading the network of Norwegian correspondence”
- 
## Bibliography

### Links

[https://www.nb.no/hanske/brev/](https://www.nb.no/hanske/brev/)

[https://www.nb.no/hanske/](https://www.nb.no/hanske/)

[http://historicalnetworkresearch.org/](http://historicalnetworkresearch.org/)

[https://journal.tei-c.org/index.php/journal/index](https://journal.tei-c.org/index.php/journal/index)

[https://correspsearch.net/index.xql?l=en](https://correspsearch.net/index.xql?l=en)

[https://correspsearch.net/index.xql?id=participate](https://correspsearch.net/index.xql?id=participate)

[http://dh2016.adho.org/abstracts/121](http://dh2016.adho.org/abstracts/121)

[http://correspsearch-test.nodegoat.net/viewer.p/4/136/scenario/1/geo/fullscreen](http://correspsearch-test.nodegoat.net/viewer.p/4/136/scenario/1/geo/fullscreen)

[http://www.tei-c.org/activities/sig/correspondence/](http://www.tei-c.org/activities/sig/correspondence/)

[https://github.com/TEI-Correspondence-SIG](https://github.com/TEI-Correspondence-SIG)

[http://www.dokpro.uio.no/](http://www.dokpro.uio.no/)

[http://www.nnedit.org/index.html](http://www.nnedit.org/index.html)

[http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-correspDesc.html](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-correspDesc.html)

[http://www.tei-c.org/release/doc/tei-p5-doc/en/html/HD.html#HD44CD](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/HD.html#HD44CD)

### Articles

Dumont, Stefan. “CorrespSearch – Connecting Scholarly Editions of Letters.” Journal of the Text Encoding Initiative, no. 10 (December 7, 2016). [https://doi.org/10.4000/jtei.1742](https://doi.org/10.4000/jtei.1742).

Neuber, Frederike. “CorrespSearch.” Variants. The Journal of the European Society for Textual Scholarship, no. 12–13 (December 31, 2016): 284–85.

Dumont, S. (2016). correspSearch - A Web Service to Connect Diverse Scholarly Editions of Letters. In Digital Humanities 2016: Conference Abstracts. Jagiellonian University & Pedagogical University, Kraków, pp. 175-178.

## Appendix 1

### Digital Editions of Letters in NB-kilder
Status: 1/8-2018

| FRA | TIL | ÅR | PUBLISERT |
|---|---|---|---|
|Collett, Camilla| Bjørnson, Bjørnstjerne| 1867|NB kilder 2:2/2015|
|Collett, Camilla|Collett, Johan Christian|1849|NB kilder 2:4/2018|
|Collett, Camilla|Collett, Peter Jonas|1841-1851|NB kilder 2:4/2018|
|Collett, Camilla|Didriks, Emilie|1841-1842|NB kilder 2:4/2018|
|Collett, Camilla|Herre, Johanne Caroline|1830|NB kilder 2:4/2018|
|Collett, Camilla|Herre, Marie Emilie|1830|NB kilder 2:4/2018|
|Collett, Camilla|Ibsen, Henrik|1872-1889|NB kilder 2:1/2014|
|Collett, Camilla|Ibsen, Susanna|1872-1894|NB kilder 2:1/2014|
|Collett, Camilla|Lie, Jonas|1863-1884|NB kilder 2:3/2016|
|Collett, Camilla|Petersen, Emma|1839|NB kilder 2:4/2018|
|Collett, Camilla|Wergeland, Amalie Sofie|1839|NB kilder 2:4/2018|
|Collett, Camilla|Wergeland, Laura Augusta|1846|NB kilder 2:4/2018|
|Collett, Camilla|Wergeland, Nicolai|1841-1844|NB kilder 2:4/2018|
|Collett, Camilla|Wergeland, Oscar|1844|NB kilder 2:4/2018|

### Planned Digital Editions of Letters in NB-kilder

· Correspondence between Kitty Kielland and Arne Garborg, shall be published in 2018

· Letters from Sumatra (Jacob Iversen et al.), shall be published in 2018

· Letters by Just Qvigstad, shall be published in 2019

· Correspondence between Kitty Kielland and Eilif Peterssen, shall be published in 2019(?)

### Digital Editions of Letters in NSL/bokselskap.no
Status: 1/8-2018

| FRA | TIL | ÅR | PUBLISERT |
|---|---|---|---|
|Bjørnson, Bjørnstjerne|Div. danske mottakere (ca 400 brev)|1854-1874|NSL/bokselskap.no 2010|
|Brandes, Georg|Thoresen, Magdalene|1865-1899|NSL/bokselskap.no 2015|
|Ibsen, Henrik|Bjørnson, Bjørnstjerne|1864-1898|HIS/bokselskap.no 2014|
|Ibsen, Henrik|Collett, Camilla|1877-1893|HIS/bokselskap.no 2013|
|Ibsen, Henrik|Lie, Jonas|1879-1900|HIS/bokselskap.no 2012|
|Kielland, Alexander L.|Div. mottakere (ca 1800 brev)|1869-1906|NSL/bokselskap.no 2010|
|Obstfelder, Sigbjørn|Div. mottakere (ca 200 brev)|1884-1900|NSL/bokselskap.no 2016|
|Skram, Amalie|Skram, Erik|1882-1902|NSL/bokselskap.no 2016|
|Skram, Erik|Skram, Amalie|1882-1902|NSL/bokselskap.no 2016|
|Thoresen, Magdalene|Brandes, Georg|1865-1899|NSL/bokselskap.no 2015|
|Wergeland, Henrik|Bekkevold, Amalie|1838-1845|NSL/bokselskap.no 2011|

### Digital Letters in emunch.no
Status: 11/10-2018

tba

## Appendix 2

### Zotero Group Library

For scholarly editions of letters and correspondences in the hold of NB. Link to [Group Library](https://www.zotero.org/groups/2214573/norkorr).

### URNs

tba

### Selection Criteria

-   has to be letters as part of an actual correspondence (no fictional letters, no religious sermons in the form of letters, no ‘letters to the editor’, no Briefromane)
    
-   has to be a scholarly edition - although, in the broadest, most inclusive sense

Q: What to do with so called “utvandrerbrev”? There’s a couple of editions with letters from/to Norwegian emigrants (to the US and other places); could be of interest? Perhaps as a subcorpus; I assume that getting authority data for the senders/receivers is difficult in this case.

Q: Should the corpus be limited to “important” people? Pragmatically speaking, limiting the correspondences to “important” people like writers, politicians, cultural and academic elite, nobility could be the easiest way to create a corpus where authority data is available. Letters and correspondences of other people is interesting from a different perspective (local history, cultural history, genealogy etc.) but presumably harder to back with authority data and larger correspondences (aka ‘letters of a lifetime’).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MzIzMDIxNDEsNTc3MTk2MzA5LDEwOD
I3OTM3MDksLTgwNjczODcwOSwtMjA1OTg3MjcwOSwtMTQ1MjEz
Nzk1NSwtMTIxOTQ0NTYwNywtMjgyNjU4NDkzXX0=
-->
