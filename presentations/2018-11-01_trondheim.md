# Connecting Norwegian Correspondences – From Manuscript Catalogues to Linked Open Data

Annika Rockenberger, Ph.D. – The National Library of Norway
annika.rockenberger@nb.no (Email)
@ARockenberger (Twitter)
@arockenberger (GitHub)
http://www.annikarockenberger.com (Website)

Introducing Research Practices and Tools for Digital Humanities
2day Seminar at NTNU Trondheim, Nov 1–2, 2018

**Presented version with added links and contact information**

Norwegian Correspondences is a collaborative project of a group (in alphabetical order):

* Hilde Bøe, Munch Museum
* Philipp Conzett, The Arctic University of Tromsø, University Library
* Marianne Paasche, University of Bergen, University Library
* Ola Søndena, University of Bergen, University Library
* Evelyn Thor, Norwegian University of Science and Technology, University Library
* Ellen Wiger, National Library of Norway
* Mette Witting, National Library of Norway
* Ove Wolden, Norwegian University of Science and Technology, University Library

This paper has, however, been conceptualised, written, and presented by Annika Rockenberger.

## Introduction

Imagine a linguist. He wants to write a biography of the ethnographer, philologist and expert on the Sami language and culture Just Knud Qvigstad. While parts of Qvigstad’s correspondence have earlier been transcribed and published online, many letters he wrote and received are still only accessible as digital images in libraries all over Scandinavia.

Now, imagine a literary scholar. They are working on a scholarly edition of Camilla Collett’s writings. They are collaborating with the library that holds the Nachlaß of Collett, which has amongst many drafts of her novels and published works also some 235 letters written as well as received by Collett. The edition, however, focusing on Collett’s writing, will only contain the letters she has penned herself.

Then, imagine a researcher in science studies. She is studying how the collections in museums of natural history in the Northern hemisphere were gathered, curated, and managed around the turn of the last century. For her praxeological approach, she wants to analyze the nearly 2.000 letters the botanist Mikael Heggelund Foslie received from all over the world in his function as curator of the botanical and zoological collection at the Royal Norwegian Society of Sciences and Letters Museum in Trondheim. But what about the letters he wrote?

Finally, imagine a team of special collections librarians. They are tasked with registering 16 running meters of handwritten material from disparate collections, including several thousand letters, postcards, telegrams and official correspondences. Creating metadata for this material and incorporating it into the library’s online catalogue together with a digital copy will have them occupied for the next couple of years and there is no way they can spend extra time on finding letter pairs and cross-referencing their collections with those of other libraries, archives and museums in Norway, the Nordic countries and beyond.

What do they all have in common? They all work with letters – or similar types of correspondence – but their collections are incomplete. They want to gather exhaustive correspondences of an individual or a group, but the individual letters are spread across collections, institutions, and countries. They want to be able to search cross-institutionally and internationally for writers and recipients of letters – and get access to the contents of the letters: be it in a scholarly edition, in a transcribed file or simply as a digital copy of the original put online.
Until recently, this has not been possible. Neither for scholars who are using letters and similar correspondence media as source material for their research, or for the specialists in the ALM sector who build, curate and disseminate collections of letters in their holdings nor for the interested lay person who wants to find out about their heritage and family history in a global society.

Now, things are changing. In Norway, thanks to the mass digitization efforts of the National Library and many of the University Libraries, but also archives and museums a vast amount of historical documents is available in digital copy, online. At the same time, catalogue metadata has been transferred to database solutions and almost all newly acquired material is registered digitally. These metadata are by default open data: They can be accessed, queried, retrieved and processed without interfering with copyright issues and other legal restrictions.

We face, however, still an almost insurmountable obstacle: You may call it the silo mentality. Without turning this observation into a general criticism of any institution or organisation – it is the way of thinking about solving problems of data storage, document description, metadata, data types, data formats, retrieval systems, storage systems, user interfaces etc. individually. A given institution will come up with an in-house solution, constrained by budgets, personnel, tradition, institutional best practices, disciplinary standards, available hardware, user groups, technical expertise. This results in a wild mix of metadata, data storage and retrieval systems, interfaces and accessibility modes that are almost impossible to harmonize. It is, on the other hand, simply not feasible to stop every institution from developing their own silo and superimpose a national, transdisciplinary and trans-institutional standard. So, what are we going to do? What is it those diverse researchers need and we – and I mean cultural heritage institutions in the broadest sense – could provide to facilitate cross-institutional, cross-disciplinary, and cross-national searchability of Norwegian correspondences?

## The Project

Norwegian Correspondences is a collaborative project in its early phase. I came up with the idea when I browsed the digital scholarly editions that are freely available on [bokselskap.no](http://www.bokselskap.no/), the Norwegian Society for Language and Literature’s ebook platform that is co-hosted by the National Library of Norway. There are quite a few editions of letters by Norwegian writers available there, but the platform itself doesn’t offer an advanced search of the correspondence material. As many other editions of letters and the like, it’s author-centred and tailored towards reading.

I remembered that there was a small group of researchers and developers based in Berlin who – a quite recently – came up with a idea of how to connect editions of letters. They had been working in medium-scale projects editing and publishing manuscripts of 19th century intellectuals and were very active in the special interest group for correspondence-editions in the TEI, the Text Encoding Initiative. They had come up with a way of connecting disparate editions of letters with each other via a metadata set derived from the CorrespDesc module in TEI. They built a query for these metadata and created a graphical user interface for finding letters across editions: [CorrespSearch](https://correspsearch.net/). In CorrespSearch, you can search for names, places and dates and the query engine will retrieve the metadata of the letters that match it, granted, the letters and correspondence editions are already part of the corpus CorrespSearch builds on. Shortly after its publication the Berlin-based team made a call for contributions and provided an interface on their website for adding editions of letters manually. The corpus grew and now includes 135 editions with a total of 45.453 individual letters, mostly from Germany, but also from France, Spain, Austria – and Norway!

The first Norwegian letters were added a little over a week ago. It’s letters written by Camilla Collett, a writer and often called Norway’s first feminist activist, from 1841–1851, in total some 50 letters. They had previously been published as a digital scholarly edition on [bokselskap.no](http://www.bokselskap.no/). It took less than 2 hours to incorporate Collett’s letters into CorrespSearch, where they can now be found – and put in context with – all the other letters in the corpus.

The project Norwegian Correspondences wants to facilitate that workflow: every time a scholarly edition of letters, be it single letters or a selection or an entire correspondence,  is published, the correspondence metadata can be delivered to CorrespSearch and will thus be included in an international collection of letters. It doesn’t matter who wrote the letters. Or how many letters there are. Or when and where they are from since CorrespSearch has no thematic or period limitations like comparable projects like The Republic of Letters that only incorporates letters from the Renaissance and Early Modern Era.

Imagine: all the scholarly editions of letters that have ever been published, searchable via a single point of entry! That alone would be an astonishing achievement.
Last time I checked, the National Library of Norway held 173 printed scholarly editions of letters that were part of the mass-digitization efforts that started in 2004. They are all retrievable via the nb.no website and available in machine-readable format (with some restrictions due to copyright). These will be added to CorrespSearch – we are currently investigating a semi-automatic workflow for retrieving letter metadata from the full texts. This will likely add another ca. 50.000 letters to the corpus. But that is by far not enough! Because the vast majority of letters – or telegrams, postcards, message cards etc. – will never be selected for a scholarly edition. In most cases, what enters the archives will at best be catalogued and perhaps digitized for safe keeping; but it will never be transcribed, corrected, translated, scholarly edited or published for readers or researchers. Some of it might become part of the source material in a research project, get a citation or mention in a list of sources in the appendix of a doctoral thesis or monograph. But it will never be easily retrievable and always be difficult to contextualize with other correspondences.
Our aim is to change this. And we have an incredible advantage here in Norway that many other nations do not have. We have in comparison rather few documents but an enormous digitization machinery, good infrastructure and staff.

We will extend the scope of CorrespSearch beyond printed and digital scholarly editions so that it can include all digitized correspondences, too.

## Institutions

Today, there are five institutions that are part of the NorKorr project. It’s the National Library where we have 16.680 digitized letters – of a total of ca. 200.000 letters in our manuscript collection. The Munch Museum is collaborating with their collection of letters written by and addressed to Edvard Munch, in total 8.802. At NTNU Gunnerus library, four letter collections were initially selected to be part of NorKorr, these amount to 8.825 letters, many of which are digitized already. The University Library of the Arctic University of Norway in Tromsø contributes with two ongoing digital scholarly editions. First, of the correspondence of Just Knut Qvigstad where most of the 257 letters written by Qvigstad are held in the University Library of Uppsala and the National Archives of Finland, while some are in Oslo. Second, the letters by Sophus Bugge will be included, too. Finally, the University Library at the University of Bergen contributes with 3.400 letters from three diverse collections. We are also in contact with KODE Bergen, where a digital edition and catalogue of works of Nikolai Astrup is prepared.

If you have been counting along, this all amounts already to 37.964 Norwegian letters additionally to the estimated 50.000 letters that have in the past been edited and published.

## LOD

But what has to be done to actually add all these letters to the CorrespSearch corpus and make them available for research beyond the individual authors: We have to map a minimum of metadata for each letter onto the Correspondence Metadata Interchange Format, short [CMIF](https://github.com/TEI-Correspondence-SIG/CMIF). CMIF is based on the CorrespDesc module from TEI, that is recommended to use when preparing editions of letters. It covers

* The full name of the letter writer (where this is known)
* The full name of the letter recipient (where this is known)
* The date of writing and/or the date of receiving the letter (where this is known)
* The place of writing and/or receiving the letter (where this is known)

CMIF also contains information of the source, that is, the bibliographic information of the edition – printed or digital – the letter is part of. In the case of digital editions, this is basically a URN (Uniform Resource Name) in the form of a permanent link to the edition or individual letter. As long as such a link exists, a letter can be referenced properly.

Ok, this is nice and all, you provide some names and dates but that’s not really that powerful; a name doesn’t tell you much and doesn’t allow for queries beyond that. – And that’s where the linked open data come into play. What CMIF requires additionally is that you provide the [VIAF](https://viaf.org/) identifier (Virtual International Authority File) to all person names and the geolocation as provided bei [geoNames](https://www.geonames.org/) for all places. And all dates? They have to be noted according to the [ISO 8601 standard](https://www.iso.org/iso-8601-date-and-time-format.html). With all that in place we don’t just have proper identification set up, we can also pull additional information about the persons and places in our letters. We can easily sort by country, even if we only know the names of cities, towns and villages; we can query for the gender of our writers – and their age at the time of writing or receiving a letter. We could ask, for example, what the relation is between the place of writing and the place of death for male letter writers during the last 10 years of their lives, sorted by country of birth. This will of course not work in all cases, with all letters. Not all writers are known, not all recipients can be identified. Not all letters are dated and place names are often missing when envelopes have been tossed and formal letter writing conventions have not been followed. And of course, even if we have a name, it doesn’t mean we know anything about the person behind without extensive research. But hopefully, with time passing and more information getting added to databases like [VIAF](https://viaf.org/) or [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) – and our own catalogues, we can enrich the letters with meaningful data.

## Conclusion

As a conclusion – or final note – let me invite you to contribute to the Norwegian Correspondences. We develop our project in plain view on [GitHub](). We will  – and already have – put all our code for mapping catalogue and [TEI](http://www.tei-c.org/) metadata onto [CMIF](https://github.com/TEI-Correspondence-SIG/CMIF) there, there is information on the different collections and institutions; the project in general, its collaborators and plans. It will also have a website (soon) which will be hosted via GitHub.
That’s all for now – thank you for your attention and pay us a visit!

## References
### Links

*Links to websites which were shown during the presentation*

* (https://github.com/arockenberger/NorKorr)
* (https://github.com/TEI-Correspondence-SIG/CMIF/blob/master/templates/cmif-digital-edition.xml)
* (http://www.bokselskap.no/boker/collettbrev1841_51/tittelside)
* (https://emunch.no)
* (https://ntnu.tind.io/record/134742#?c=0&m=0&s=0&cv=0)
* (http://correspsearch-test.nodegoat.net/viewer.p/4/136/scenario/1/geo/fullscreen)
