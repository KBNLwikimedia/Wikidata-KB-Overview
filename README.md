<p align="right">
<image src="images/Wikidata-logo-en.png" width="180" hspace="10"/>
<image src="images/KB_Nationale-Bibliotheek_Logo_RGB-Zwart-EN.jpg" width="400" align="top"/>
</p>

# Wikidata & KB national library of the Netherlands, an overview

*An overview of how Wikidata is used by/in/for both the linked open datasets (thesauri) and public domain heritage collections of the KB, national library of the Netherlands.* 

Latest update: 21 November 2023

<image src="images/VerdiepingWikidataEnKB_14Nov2023 - openingslide.png" width="250" align="right"/>

This page is a textual summary of the course *Verdieping: Wikidata & de KB* for employeees of [KB, national library of the Netherlands](https://www.kb.nl) on 14 November 2023, 15:00-16:15. 
* The (rather long) full slidedeck (in Dutch) for this course is available on [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek,_14_november_2023.pdf) and [Zenodo](https://zenodo.org/records/10160817) as PDFs.
* The two videos (in Dutch) of the course are on YouTube: [Part 1]() (covering blocks 1 & 2) and [Part 2]() (covering blocks 3 & 4) --> **To add**
* A [full text transcript](/transcripts/xxx) of the course in Dutch is also available. --> **To add**

**See also**
- [An overview of current, upcoming and possible future Wikidata (and Wikibase) activities, projects, ideas, experiments and opportunities for the KB](https://www.wikidata.org/wiki/Wikidata:GLAM/Koninklijke_Bibliotheek_Nederland)
    - [Wikidata projects of the KB](https://www.wikidata.org/wiki/Wikidata:GLAM/Koninklijke_Bibliotheek_Nederland/CurrentProjects)
- [Our Structured Data on Commons efforts](https://commons.wikimedia.org/wiki/Commons:Koninklijke_Bibliotheek/SDoC)
<hr>

### Contents
* [Intro](#intro)
  + [Required basic knowledge about Wikidata](#required-basic-knowledge-about-wikidata)
  + [Course objectives](#course-objectives)
  + [Course layout](#course-layout)
* [BLOCK 1 - What does Wikidata add for the KB?](#block-1---what-does-wikidata-add-for-the-kb-)
  + [Open doors](#open-doors)
  + [Wikidata characteristics](#wikidata-characteristics)
  + [Added value of Wikidata for KB](#added-value-of-wikidata-for-kb)
* [BLOCK 2 - Wikidata & KB thesauri (NTA + DBNLa)](#block-2---wikidata---kb-thesauri--nta---dbnla-)
  + [Criteria for suitability of KB thesauri for Wikidata](#criteria-for-suitability-of-kb-thesauri-for-wikidata)
  + [a) From the NTA to Wikidata](#a--from-the-nta-to-wikidata)
  + [b) From the DBNLa to Wikidata](#b--from-the-dbnla-to-wikidata)
    - [Federated query to retrieve extra data from Wikidata](#federated-query-to-retrieve-extra-data-from-wikidata)
  + [c) From Wikidata to the NTA - P1006](#c--from-wikidata-to-the-nta---p1006)
    - [Insights in the usage of P1006](#insights-in-the-usage-of-p1006)
    - [P1006 and data quality](#p1006-and-data-quality)
    - [Usage of NTA ids in Wikipedia articles](#usage-of-nta-ids-in-wikipedia-articles)
    - [Summary for NTA/P1006](#summary-for-nta-p1006)
  + [d) From Wikidata to the DBNLa - P723](#d--from-wikidata-to-the-dbnla---p723)
    - [Insights into the usage of P723](#insights-into-the-usage-of-p723)
    - [P723 and data quality](#p723-and-data-quality)
  + [Historical metrics of Wikidata and NTA & DBNLa](#historical-metrics-of-Wikidata-and-NTA--DBNLa)
* [BLOCK 3 - Intermezzo: Linking Wikimedia Commons with Wikidata](#block-3---intermezzo--linking-wikimedia-commons-with-wikidata)
  + [Regular metadata for KB images](#regular-metadata-for-kb-images)
  + [Structured Data on Commons](#structured-data-on-commons)
    - [Added value of SDoC](#added-value-of-sdoc)
  + [SPARQL queries for KB images](#sparql-queries-for-kb-images)
  + [What is depicted on KB images?](#what-is-depicted-on-kb-images-)
  + [Summary of image search options in Wikimedia Commons](#summary-of-image-search-options-in-wikimedia-commons)
  + [Tooltip: Hay's Structured Search](#tooltip--hay-s-structured-search)
  + [Adding Depicts tags to KB images yourself](#adding-depicts-tags-to-kb-images-yourself)
* [BLOCK 4 - Wikidata & KB heritage collections](#block-4---wikidata---kb-heritage-collections)
  + [Criteria for suitability of KB heritage collections for Wikidata](#criteria-for-suitability-of-kb-heritage-collections-for-wikidata)
  + [WikiProject KB Collection highlight (2020-present)](#wikiproject-kb-collection-highlight--2020-present-)
    - [Presentation of collection highlights on kb.nl](#presentation-of-collection-highlights-on-kbnl)
    - [A new paradigm for collection highlights](#a-new-paradigm-for-collection-highlights)
    - [Wikification of KB collection highlights](#wikification-of-kb-collection-highlights)
    - [50 cool new things you can do now with KB's collection highlights](#50-cool-new-things-you-can-do-now-with-kb-s-collection-highlights)
      - [Examples](#examples)
* [Contact](#contact)
* [Reuse and licensing](#reuse-and-licensing)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

<hr>

## Intro

### Required basic knowledge about Wikidata
[<image src="images/Wegwijzer_in_Wikidata,_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek,_6_juni_2023.jpg" width="250" align="right" >](https://commons.wikimedia.org/w/index.php?title=File:Wegwijzer_in_Wikidata,_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek,_6_juni_2023.pdf)

See the course *Wegwijzer in Wikidata* (Introduction to Wikidata), June 6, 2023 (in Dutch)
* Slides on [Zenodo](https://zenodo.org/record/8006441) and [Wikimedia Commons](https://commons.wikimedia.org/w/index.php?title=File:Wegwijzer_in_Wikidata,_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek,_6_juni_2023.pdf)  (PDF)
* [Textual summary in Dutch](https://commons.wikimedia.org/w/index.php?title=File:Wegwijzer_in_Wikidata,_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek,_6_juni_2023.pdf&page=141) (PDF) 
* Textual summary in English: **To add to dedicated Github repo**

### Course objectives
To provide more understanding about
1. Why we use Wikidata  at KB
2. How we use Wikidata for KB thesauri & heritage collections
3. What value this adds for KB

### Course layout
* BLOCK 1) [What does Wikidata add for the KB?](https://github.com/KBNLwikimedia/Wikidata-KB-Overview/blob/main/README.md#block-1---what-does-wikidata-add-for-the-kb)
* BLOCK 2) [Wikidata & KB thesauri (NTA + DBNLa)](https://github.com/KBNLwikimedia/Wikidata-KB-Overview/blob/main/README.md#block-2---wikidata--kb-thesauri-nta--dbnla)
* BLOCK 3) [Intermezzo: Linking Wikimedia Commons with Wikidata](https://github.com/KBNLwikimedia/Wikidata-KB-Overview/blob/main/README.md#block-3---intermezzo-linking-wikimedia-commons-with-wikidata)
* BLOCK 4) [Wikidata & KB heritage collections](https://github.com/KBNLwikimedia/Wikidata-KB-Overview/blob/main/README.md#block-4---wikidata--kb-heritage-collections)

<hr/>
<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf/page5-640px-Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf.jpg" width="200" align="right"/>

## BLOCK 1 - What does Wikidata add for the KB?

### Open doors
(Captain Obvious mode) For KB & its services: Be findable in Google - Be present on Facebook - Be present on Instagram - Be present on YouTube - Be present on Twitter. --> Summary (open door): Be present on the large (web-scale) platforms

So also open doors:
* Add your collection knowledge to Wikipedia
* Add your collection images to Wikimedia Commons
* Add your collection data to Wikidata

### Wikidata characteristics
Wikidata is one of the largest and most popular LOD platforms in the world.

Characteristics:
- Central part of the (web-scale) Wikimedia infrastructure (Wikipedia, Commons, [700+ Wikimedia platforms](https://meta.wikimedia.org/wiki/Complete_list_of_Wikimedia_projects))
- Free, public utility for data (no IT costs)
- Centralized, no data silos, 1 language (w.r.t. SPARQL and API calling)
- Global scope, (much) broader than KB/library/heritage/Netherlands domain
- Connection point for [8330+ external databases](https://hay.toolforge.org/propbrowse/) worldwide
- Multilingual, language independent, [300+ languages](https://www.wikidata.org/wiki/Help:Wikimedia_language_codes/lists/all)
- Collaborative --> International community, 25K+ content creators
- For humans (GUI) and machines (API, SPARQL, JSON, RDF, Python etc.)
- LOD, the least scary of all LOD platforms --> Understandable & warm, thanks to community!
- No copyright on data ([CC0](https://creativecommons.org/public-domain/cc0/))
- Strong growing, positive outlook & sustainable

Effective result: advantages of scale and community & network effects

### Added value of Wikidata for KB
What values does Wikidata add for the KB & its services?
1) Increased visibility, findability and reusability of our collections
    - Greater public reach of KB collections, worldwide
    - KB data in cross-domain, global, multilingual context --> Increasing interoperability KB with the outside world
    - Community: External expertise, skills, tools and enthusiasm to enrich & connect KB data
2) New functionalities for our data (and images) --> See [block 4](#block-4---wikidata---kb-heritage-collections)
    - Functionalities that we do not or cannot offer in our own KB services
    - Regarding Search, Data enrichment, data quality control, data visualization and data formats, Image metadata, Machine interactions
    - Both for our thesauri and heritage collections
    - For people and machines
    - 'KB collections as LEGO'
3) Toolkit & platform to create and publish new KB LOD
    - Internal KB LOD renewal process is not yet delivering public results   
4) Developing and sharing knowledge & skills related to LOD
    - Both internally and externally
    - Strengthening our cooperation with KB network partners via Wikidata/media

<hr/>
<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf/page17-640px-Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf.jpg" width="200" align="right"/>

## BLOCK 2 - Wikidata & KB thesauri (NTA + DBNLa)
KB datasets (thesauri): http://data.bibliotheken.nl/

### Criteria for suitability of KB thesauri for Wikidata
- Persons (authors) are more popular and in demand on Wikidata than (eg.) keywords or organizations
    - [Dutch Thesaurus of Author names (NTA)](http://data.bibliotheken.nl/id/dataset/persons) + [Thesaurus of DBNL authors (DBNLa)](http://data.bibliotheken.nl/id/dataset/dbnla) are more useful than [Brinkman](http://data.bibliotheken.nl/id/dataset/brinkman) or [GTT](http://data.bibliotheken.nl/id/dataset/gtt)
- NTA is internationally the only major authoritative dataset on 'Dutch authors'
    - NTA is very useful for Wikidata, in an international context
- Flat/simple data is more suitable than layered/complex data
    - People are easier to add to Wikidata than [titles](http://data.bibliotheken.nl/id/dataset/nbt) ([WEMI](https://rdabasics.com/2012/08/24/theoretical-foundations/) = complex)
- Small datasets are easier than large ones
    - [Alba amicorum](http://data.bibliotheken.nl/id/dataset/rise-alba) and [catchpenny prints](http://data.bibliotheken.nl/id/dataset/rise-centsprenten) are suitable for Wikidata

Ergo: Focus on [NTA](http://data.bibliotheken.nl/id/dataset/persons) and [DBNL authors](http://data.bibliotheken.nl/id/dataset/dbnla) with regard to the KB thesauri-Wikidata activities.

### a) From the NTA to Wikidata

Persons in the NTA with a Wikidata URI:
- Eg. *Darlene Dixon* : http://data.bibliotheken.nl/doc/thes/p208140131 --> schema:sameAs --> http://www.wikidata.org/entity/Q88505402
- All persons via [this SPARQL query](http://data.bibliotheken.nl/sparql?default-graph-uri=&qtxt=%23+Which+NTA+items+have+a+link+to+Wikidata%3F%0D%0A%0D%0ASELECT++*+WHERE+{%0D%0A+%3Fnta+schema%3AmainEntityOfPage%2Fschema%3AisPartOf+<http%3A%2F%2Fdata.bibliotheken.nl%2Fid%2Fdataset%2Fpersons>+.%0D%0A+%3Fnta+rdfs%3Alabel+%3FntaLabel.++%0D%0A+%3Fnta+schema%3AsameAs+%3Fwikidata+.%0D%0AFILTER(regex(%3Fwikidata%2C+'wikidata'%2C+'i'))%0D%0A}+LIMIT+1000&format=text%2Fhtml&timeout=0&debug=on&run=+Run+Query+)
```sparql
# Which NTA items have a link to Wikidata?
SELECT  * WHERE {
 ?nta schema:mainEntityOfPage/schema:isPartOf <http://data.bibliotheken.nl/id/dataset/persons> .
 ?nta rdfs:label ?ntaLabel.  
 ?nta schema:sameAs ?wikidata .
FILTER(regex(?wikidata, 'wikidata', 'i'))
} LIMIT 1000
```
- 499K of 2.75M NTA items have a Wikidata link ([source](https://nl.wikipedia.org/wiki/Wikipedia:GLAM/Koninklijke_Bibliotheek_en_Nationaal_Archief/Resultaten/KPIs/KPI10#Historische_ontwikkeling_van_KPI_10))

### b) From the DBNLa to Wikidata
  
Persons in DBNLa with a Wikidata URI (via the NTA)
- Eg. *Hans Aarsman (1951-)* : http://data.bibliotheken.nl/id/dbnla/aars001 --> owl:sameAs --> http://data.bibliotheken.nl/id/thes/p068680937 --> schema:sameAs --> http://www.wikidata.org/entity/Q325922
- All persons via [this SPARQL query](http://data.bibliotheken.nl/sparql?default-graph-uri=&qtxt=%23+Welke+DBNLa-items+bevatten+een+link+naar+Wikidata%3F%0D%0ASELECT+*++%0D%0AWHERE+{%0D%0A+%3Fdbnl+schema%3AmainEntityOfPage%2Fschema%3AisPartOf+<http%3A%2F%2Fdata.bibliotheken.nl%2Fid%2Fdataset%2Fdbnla>+.%0D%0A+%3Fdbnl+rdfs%3Alabel++%3FdbnlLabel.++%0D%0A+%3Fdbnl+owl%3AsameAs+%3Fnta+.%0D%0A+%3Fnta+schema%3AmainEntityOfPage%2Fschema%3AisPartOf+<http%3A%2F%2Fdata.bibliotheken.nl%2Fid%2Fdataset%2Fpersons>+.%0D%0A+%3Fnta+rdfs%3Alabel+%3FntaLabel.+++%0D%0A+%3Fnta+schema%3AsameAs+%3Fwikidata+.%0D%0A+FILTER(regex(%3Fwikidata%2C+'wikidata'%2C+'i'))%0D%0A}+LIMIT+1000&format=text%2Fhtml&timeout=0&debug=on&run=+Run+Query+)
```sparql
# Which DBNLa authors have a link to Wikidata?
SELECT *  
WHERE {
 ?dbnl schema:mainEntityOfPage/schema:isPartOf <http://data.bibliotheken.nl/id/dataset/dbnla> .
 ?dbnl rdfs:label  ?dbnlLabel.  
 ?dbnl owl:sameAs ?nta .
 ?nta schema:mainEntityOfPage/schema:isPartOf <http://data.bibliotheken.nl/id/dataset/persons> .
 ?nta rdfs:label ?ntaLabel.   
 ?nta schema:sameAs ?wikidata .
 FILTER(regex(?wikidata, 'wikidata', 'i'))
} LIMIT 1000
```
- 14.5K of 109K DBNLa items have a Wikidata link ([source](https://nl.wikipedia.org/wiki/Wikipedia:GLAM/Koninklijke_Bibliotheek_en_Nationaal_Archief/Resultaten/KPIs/KPI10#Historische_ontwikkeling_van_KPI_10))

#### Federated query to retrieve extra data from Wikidata
- *Achille Van Acker* ['acke001' in the DBNLa](http://data.bibliotheken.nl/doc/dbnla/acke001) and [in Wikidata](http://www.wikidata.org/entity/Q14997)
- Get additional data about 'acke001' from Wikidata. We want to retrieve the following data from the Wikidata item:
    - Image ([P18](https://www.wikidata.org/wiki/Property:P18)) -- Educated at ([P69](https://www.wikidata.org/wiki/Property:P69)) -- Member of political party ([P102](https://www.wikidata.org/wiki/Property:P102))
- We use this [SPARQL query](http://data.bibliotheken.nl/sparql?default-graph-uri=&qtxt=%23+Get+supplementary+data+about+DBNL+author+'acke001'+from+Wikidata%0D%0APREFIX+wdt%3A++<http%3A%2F%2Fwww.wikidata.org%2Fprop%2Fdirect%2F>%0D%0ASELECT+*+%0D%0AWHERE+{%0D%0A+%3Fdbnl+schema%3AmainEntityOfPage%2Fowl%3AsameAs++<http%3A%2F%2Fdata.bibliotheken.nl%2Fdoc%2Fdbnla%2Facke001>+.%0D%0A+%3Fdbnl+rdfs%3Alabel+%3FdbnlLabel.++%0D%0A+%3Fdbnl+owl%3AsameAs+%3Fnta+.%0D%0A+%3Fnta++schema%3AmainEntityOfPage%2Fschema%3AisPartOf+<http%3A%2F%2Fdata.bibliotheken.nl%2Fid%2Fdataset%2Fpersons>+.%0D%0A+%3Fnta+rdfs%3Alabel+%3FntaLabel.+++%0D%0A+%3Fnta+schema%3AsameAs+%3Fwikidata+.%0D%0A+FILTER(regex(%3Fwikidata%2C+'wikidata'%2C+'i'))%0D%0A%0D%0A+SERVICE+<https%3A%2F%2Fquery.wikidata.org%2Fsparql>+{%0D%0A+++%3Fwikidata+wdt%3AP18+%3FimageURL.+%23P18+%3D+image%0D%0A+++%3Fwikidata+wdt%3AP69+%3FedcucatedAt.+%23P69+%3D+educated++at%0D%0A+++%3Fwikidata+wdt%3AP102+%3FMemberOfPoliticalParty.+%23P102+%3D+member+of+political+party%0D%0A%0D%0A+}%0D%0A}+&format=text%2Fhtml&timeout=0&debug=on&run=+Run+Query+)
```sparql
# Get supplementary data about DBNL author 'acke001' from Wikidata
PREFIX wdt:  <http://www.wikidata.org/prop/direct/>
SELECT * 
WHERE {
 ?dbnl schema:mainEntityOfPage/owl:sameAs  <http://data.bibliotheken.nl/doc/dbnla/acke001> .
 ?dbnl rdfs:label ?dbnlLabel.  
 ?dbnl owl:sameAs ?nta .
 ?nta  schema:mainEntityOfPage/schema:isPartOf <http://data.bibliotheken.nl/id/dataset/persons> .
 ?nta rdfs:label ?ntaLabel.   
 ?nta schema:sameAs ?wikidata .
 FILTER(regex(?wikidata, 'wikidata', 'i'))

 SERVICE <https://query.wikidata.org/sparql> {
   ?wikidata wdt:P18 ?imageURL. #P18 = image
   ?wikidata wdt:P69 ?edcucatedAt. #P69 = educated  at
   ?wikidata wdt:P102 ?MemberOfPoliticalParty. #P102 = member of political party

 }
} 
```
Checks are OK:
- P18 (image): [Achiel Van Acker1.jpg](http://commons.wikimedia.org/wiki/Special:FilePath/Achiel%20Van%20Acker1.jpg)
- P69 (educated at): [Lille University of Science and Technology](http://www.wikidata.org/entity/Q500740)
- P102 (member of political party): [Belgian Socialist Party](http://www.wikidata.org/entity/Q2532509)

### c) From Wikidata to the NTA - P1006
Persons in Wikidata with an NTA id
- [P1006](https://www.wikidata.org/wiki/Property:P1006) = Nationale Thesaurus voor Auteursnamen ID
- Eg. *Harry Mulisch* : https://www.wikidata.org/wiki/Q927#P1006 --> [P1006](https://www.wikidata.org/wiki/Property:P1006) -- > https://data.bibliotheken.nl/doc/thes/p06854796X
-  All persons via [this SPARQL query](https://w.wiki/85Cs)
```sparql
SELECT ?item ?itemLabel ?NTAurl
{
  ?item wdt:P1006 ?NTAid.
  BIND(IRI(CONCAT('http://data.bibliotheken.nl/doc/thes/p', ?NTAid)) AS  ?NTAurl)
  SERVICE wikibase:label { bd:serviceParam wikibase:language "nl,en"  }
}
LIMIT 1000
```
#### Insights in the usage of P1006 
https://www.wikidata.org/wiki/Property_talk:P1006
- Wikidata contains 550K links to the NTA: see 'Current uses' at bottom of this page, or via [this SPARQL query](https://tinyurl.com/5bep7h8a)
- Map of birthplaces of people with an NTA id: https://w.wiki/7rsT
- Famous people with an NTA id: https://w.wiki/85si (famous people have extensive Wikidata entries) with many statements

#### P1006 and data quality
Two pages provide insight into the data quality (and possible improvements) of both Wikidata and the NTA
- Missing data for people listed in the NTA: [Database_reports/Humans_with_missing_claims/P1006](https://www.wikidata.org/wiki/Wikidata:Database_reports/Humans_with_missing_claims/P1006)
- Deviations and possible errors in Wikidata as well as NTA: [Database_reports/Constraint_violations/P1006](https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/P1006)

For example:
- Missing birth date
    - https://www.wikidata.org/wiki/Wikidata:Database_reports/Humans_with_missing_claims/P1006#Missing_date_of_birth_(P569)
    - The missing dates of birth may be added to Wikidata from the NTA
- Missing Dutch labels
    - https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/P1006#%22Label_in_'nl'_language%22_violations
    - Via SPARQL: https://w.wiki/85xT
    - E.g.: *Anna Bhau Sathe*, https://www.wikidata.org/wiki/Q55759 --> NL label is missing
    - The missing NL label can be added from the NTA
- The same NTA id appears in multiple Q items
    - https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/P1006#Unique_value
    - Via SPARQL: https://w.wiki/85zm
    - E.g. *Andreas Kaiser*: https://data.bibliotheken.nl/doc/thes/p068685564 appears in both [Q498631](https://www.wikidata.org/wiki/Q498631) (error) and in [Q106361537](https://www.wikidata.org/wiki/Q106361537) (good)
    - [Q498631](https://www.wikidata.org/wiki/Q498631) should get a different value at P1006
- One Wikidata item with multiple NTA ids
    - https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/P1006#Single_value
    - Via SPARQL: https://w.wiki/85$o
    - E.g. *Douglas Adams* : [Q43](https://www.wikidata.org/wiki/Q42#P1006) contains both http://data.bibliotheken.nl/doc/thes/p339433876 and http://data.bibliotheken.nl/doc/thes /p068744307
    - These NTA items are almost identical, consider merging into the NTA

#### Usage of NTA ids in Wikipedia articles
Wikidata: [Category:Articles with NTA identifiers](https://www.wikidata.org/wiki/Q47763687)
- English Wikipedia: [234K articles](https://en.wikipedia.org/wiki/Category:Articles_with_NTA_identifiers) on WP:EN have NTA ids. E.g. https://en.wikipedia.org/wiki/50_Cent --> http://data.bibliotheken.nl/id/thes/p262032139
- Turkish Wikidia: [25K articles](https://tr.wikipedia.org/wiki/Kategori:NTA_tan%C4%B1mlay%C4%B1c%C4%B1s%C4%B1_olan_Vikipedi_maddeleri) on WP:TR have NTA ids
- Czech Wikipedia: [36K articles](https://cs.wikipedia.org/wiki/Category:Monitoring:%C4%8Cl%C3%A1nky_s_identifik%C3%A1torem_NTA) on WP:CS have NTA ids
- Japanese Wikipedia: [51K articles](https://ja.wikipedia.org/wiki/Category:NTA%E8%AD%98%E5%88%A5%E5%AD%90%E3%81%8C%E6%8C%87%E5%AE%9A%E3%81%95%E3%82%8C%E3%81%A6%E3%81%84%E3%82%8B%E8%A8%98%E4%BA%8B) on WP:JA have NTA ids

**In summary:** via Wikidata the NTA is used as an authority in 100,000 Wikipedia articles in many languages. (but not Dutch!)

#### Summary for NTA/P1006
- By integrating NTA data into Wikidata we get a lot of new functionalities regarding data quality, connections and visualization that we cannot offer via our own KB-LOD service data.bibliotheken.nl! Also Wikipedia is having advantage from the NTA! 
- Theo van Veen, *[Wikidata als gemeenschappelijke thesaurus?](https://informatieprofessional.nl/resources/uploads/2016/10/IP2016-07.pdf)*, IP|Vakblad voor de Informatie Professional, October 2016, no. 07 - See [archived version](https://web.archive.org/web/20221028121446/https://informatieprofessional.nl/resources/uploads/2016/10/IP2016-07.pdf) 
- Project to include NTA in Wikidata and v.v. : [WikiProject Dutch National Thesaurus for Author Names](https://www.wikidata.org/wiki/Wikidata:WikiProject_Dutch_National_Thesaurus_for_Author_Names)

### d) From Wikidata to the DBNLa - P723
Persons in Wikidata with an DBNLa id
- [P723](https://www.wikidata.org/wiki/Property:P723) = Digitale Bibliotheek voor de Nederlandse Letteren author ID
- Eg. *Harry Mulisch* : https://www.wikidata.org/wiki/Q927#P723 --> [P723](https://www.wikidata.org/wiki/Property:P723) -- > http://www.dbnl.org/auteurs/auteur.php?id=muli002
-  All persons via [this SPARQL query](https://w.wiki/869Y)
```sparql
SELECT ?item ?itemLabel ?DBNLaUrl
{
  ?item wdt:P723 ?DBNLaId.
  BIND(IRI(CONCAT('http://data.bibliotheken.nl/id/dbnla/', ?DBNLaId)) AS ?DBNLaUrl)
  SERVICE wikibase:label { bd:serviceParam wikibase:language "nl,en"  }
}
LIMIT 1000
```
#### Insights into the usage of P723
https://www.wikidata.org/wiki/Property_talk:P723
- Wikidata contains 31K links to the DBNLa: https://www.wikidata.org/wiki/Property_talk:P723 (bottom, 'Current uses')

#### P723 and data quality
Two pages provide insight into the data quality (and possible improvements) of both Wikidata and the DBNLa
- Missing data for people listed in the DBNLa: [Database_reports/Humans_with_missing_claims/P723](https://www.wikidata.org/wiki/Wikidata:Database_reports/Humans_with_missing_claims/P723)
- Deviations and possible errors in Wikidata as well as DBNLa: [Database_reports/Constraint_violations/P723](https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/P723)

### Historical metrics of Wikidata and NTA & DBNLa
Historical metrics of the usage of NTA and DBNLa identifiers in Wikidata, and v.v.: https://nl.wikipedia.org/wiki/Wikipedia:GLAM/Koninklijke_Bibliotheek_en_Nationaal_Archief/Resultaten/KPIs/KPI10#Historische_ontwikkeling_van_KPI_10

<hr/>
<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf/page62-640px-Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf.jpg" width="200" align="right"/>

## BLOCK 3 - Intermezzo: Linking Wikimedia Commons with Wikidata
Look at [File:Atlas_de_Wit_1698-pl017-Leiden-St_Pancraskerk.jpg](https://commons.wikimedia.org/wiki/File:Atlas_de_Wit_1698-pl017-Leiden-St_Pancraskerk.jpg) on Wikimedia Commons (=Saint Pancras Church in Leiden, now called *Hooglandse Kerk* )

### Regular metadata for KB images
- Manifest textual and visual KB source references
- 'Manual' multilingualism of the title in Latin, Dutch and French
- [Source code](https://commons.wikimedia.org/w/index.php?title=File:Atlas_de_Wit_1698-pl017-Leiden-St_Pancraskerk.jpg&action=edit) appears to be structured, but really is unstructured metadata (free text)
- Tab 'Structured Data' 

### Structured Data on Commons
[Structured Data on Commons](https://commons.wikimedia.org/wiki/Commons:Structured_data) (SDoC) is a project to add multilingual structured information from Wikidata to files on Wikimedia Commons that can be understood by humans, with enough consistency that it can also be uniformly processed by machines. 

#### Added value of SDoC 
- Images are linked to Wikidata
- Images are provided with real structured (and therefore machine-readable) data
- Linked open data for Commons files is created, files become part of the LOD cloud
- Not only for images, eg. see the structured data on [this PDF file](https://commons.wikimedia.org/wiki/File:OpenRefine-Wikidata_introduction_workshop_-_Koninklijke_Bibliotheek,_4_juli_2023.pdf)
- Files are made searchable via SPARQL
- For KB: Structured 5* LOD metadata for [31,348 KB files](https://w.wiki/8BXk)

### SPARQL queries for KB images
- [All files from the KB collection](https://w.wiki/7zh5) --> Collection ([P195](https://www.wikidata.org/wiki/Property:P195)) = Koninklijke Bibliotheek ([Q1526131](https://www.wikidata.org/wiki/Q1526131))
     - The [result](https://w.wiki/8BXq) include [30,617 KB collection images](https://commons.wikimedia.org/wiki/Category:Media_contributed_by_Koninklijke_Bibliotheek), as well as non-collection images of the KB, such as images of [the KB buildings](https://commons.wikimedia.org/wiki/Buildings_of_Koninklijke_Bibliotheek), [events](https://commons.wikimedia.org/wiki/Events_at_Koninklijke_Bibliotheek) or [directors](https://commons.wikimedia.org/wiki/Directors_of_the_Koninklijke_Bibliotheek) 
- [PDF files from the KB](https://w.wiki/7zhm) --> MIME type ([P1163](https://www.wikidata.org/wiki/Property:P1163)) = “application/pdf”
- [Images from *Album amicorum by Jacobus Heyblocq*](https://w.wiki/7zjb)

### What is depicted on KB images?
<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf/page79-640px-Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf.jpg" width="200" align="right"/>

- What can be seen in / is depicted on images, tagged using Wikidata entries
- [Commons:Depicts](https://commons.wikimedia.org/wiki/Commons:Depicts) - documentation
- Things depicted on the image [Hooglandse kerk](https://commons.wikimedia.org/wiki/File:Atlas_de_Wit_1698-pl017-Leiden-St_Pancraskerk.jpg) in [Atlas De Wit 1698](https://commons.wikimedia.org/wiki/Category:Atlas_de_Wit_1698) : Hooglandse Kerk ([Q1537970](https://www.wikidata.org/wiki/Q1537970)) - horse ([Q726](https://www.wikidata.org/wiki/Q726) ) - dog ([Q144](https://www.wikidata.org/wiki/Q144)) - clock ([Q376](https://www.wikidata.org/wiki/Q376)) - people ([Q2472587](https://www.wikidata.org/wiki/Q2472587)) - cloud ([Q8074](https://www.wikidata.org/wiki/Q8074)) - carriage ([Q235356](https://www.wikidata.org/wiki/Q235356)) - stepped gable ([Q1939660](https://www.wikidata.org/wiki/Q1939660)) - tree ([Q10884](https://www.wikidata.org/wiki/Q10884)) - walking stick ([Q1347864](https://www.wikidata.org/wiki/Q1347864)) - The Castle ([Q18813071](https://www.wikidata.org/wiki/Q18813071)) - woman ( [Q467](https://www.wikidata.org/wiki/Q467)) - child ([Q7569](https://www.wikidata.org/wiki/Q7569)) - door ([Q36794](https://www.wikidata.org/wiki/Q36794)) - hat ([Q80151](https://www.wikidata.org/wiki/Q80151)) - weathercock ([Q2157687](https://www.wikidata.org/wiki/Q2157687)) - stained glass window ([Q488094](https://www.wikidata.org/wiki/Q488094))
- Depicted things in this plate via SPARQL: https://w.wiki/7zps
- Depicted things in [all plates of Atlas de Wit]((https://commons.wikimedia.org/wiki/Category:Atlas_de_Wit_1698)) via SPARQL: https://w.wiki/7zqj

### Summary of image search options in Wikimedia Commons
Let's summarize: KB images on Commons are searchable in 3 ways
1) Via regular metadata (= free text search)
2) Via structured metadata
3) By content (What is [depicted](https://commons.wikimedia.org/wiki/Commons:Depicts) in KB images?)

### Tooltip: Hay's Structured Search
The (super handy!) tool [Hay's Structured Search](https://hay.toolforge.org/sdsearch/) offers all three options. It is a visual, multilingual search engine to find images with (and without) structured data in Wikimedia Commons. 
- [All KB images, with and without structured data](https://hay.toolforge.org/sdsearch/#q=incategory:%22Media%20contributed%20by%20Koninklijke%20Bibliotheek%22) --> 30,617 images in [Category:Media_contributed_by_Koninklijke_Bibliotheek](https://commons.wikimedia.org/wiki/Category:Media_contributed_by_Koninklijke_Bibliotheek) (search in English interface)
- [KB images in which *something* is depicted](https://hay.toolforge.org/sdsearch/#q=incategory:%22Media%20contributed%20by%20Koninklijke%20Bibliotheek%22%20haswbstatement:P180) --> 19,764 out of 30,167 images (66%) (search in Dutch interface)
- [KB images, depicting dogs](https://hay.toolforge.org/sdsearch/#q=incategory:%22Media%20contributed%20by%20Koninklijke%20Bibliotheek%22%20haswbstatement:P180=Q144) - [dog = Q144](https://www.wikidata.org/wiki/Q144) (search in Dutch interface)
- [Town on the Zuiderzee](https://hay.toolforge.org/sdsearch/#q=incategory:%22Media%20contributed%20by%20Koninklijke%20Bibliotheek%22%20haswbstatement:P180=Q228655%20-incategory:%22Visboeck%20Coenen%22%20-incategory:%22Visboeck%20Coenen%20(opening)%22%20-incategory:%22Catchpenny%20prints%20from%20Royal%20Library%22) - [Zuiderzee = Q228655](https://www.wikidata.org/wiki/Q228655)
- [Miniatures from *Der Naturen Bloeme* showing fish](https://hay.toolforge.org/sdsearch/#q=incategory:%22Miniatures%20from%20Der%20naturen%20bloeme%20-%20KB%20KA%2016%22%20haswbstatement:P180=Q152) - [fish = Q152](https://www.wikidata.org/wiki/Q152) + [Category:Miniatures_from_Der_naturen_bloeme_-_KB_KA_16](https://commons.wikimedia.org/wiki/Category:Miniatures_from_Der_naturen_bloeme_-_KB_KA_16)
- [Images from *Atlas de Wit*, showing a bridge](https://hay.toolforge.org/sdsearch/#q=incategory:%22Atlas%20de%20Wit%201698%22%20haswbstatement:P180=Q12280) - [bridge = Q12280](https://www.wikidata.org/wiki/Q12280)
- [Images from *Atlas de Wit* depicting an 'igreja'](https://hay.toolforge.org/sdsearch/#offset=0&q=incategory:%22Atlas%20de%20Wit%201698%22%20haswbstatement:P180=Q16970) - [igreja = Q16970](https://www.wikidata.org/wiki/Q16970) = church building in Portuguese (search in Portuguese interface)
- [Images from *Atlas de Wit* showing both 'église' and 'chien'](https://hay.toolforge.org/sdsearch/#q=incategory:%22Atlas%20de%20Wit%201698%22%20haswbstatement:P180=Q16970%20haswbstatement:P180=Q144) - [église = Q16970](https://www.wikidata.org/wiki/Q16970) = church building in French, [chien = Q144](https://www.wikidata.org/wiki/Q144) = dog in French (search in  French interface)
  
**In summary:** The search functionalities shown (SPARQL, structured search, multilingual search, search by content) are much more advanced than the propriatary KB (image) services such as [Het Geheugen](https://geheugen.delpher.nl/nl)!

### Adding Depicts tags to KB images yourself
[This manual](https://commons.wikimedia.org/wiki/File:Instruction_KB-images_op_Commons_taggen_met_Wikidata_-_26032020.pdf) from 2020 explains step by step how to make images from the KB collection more discoverable, visible and reusable by indicating (tagging) which things (entities) can be seen on those images. This is done by connecting Wikidata items to those things. Available on [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Instruction_KB-images_op_Commons_taggen_met_Wikidata_-_26032020.pdf) and [Zenodo](https://zenodo.org/record/7777755)

Results per 1 november 2023
- [30,617 KB collection images](https://commons.wikimedia.org/wiki/Category:Media_contributed_by_Koninklijke_Bibliotheek) on Commons
- [19,764 images on which something is tagged](https://hay.toolforge.org/sdsearch/#q=incategory:%22Media%20contributed%20by%20Koninklijke%20Bibliotheek%22%20haswbstatement:P180)
- KB tagging champion is Madeleine van den Berg with [34K+ things added](https://commons.wikimedia.org/w/index.php?title=Special%3AContributions&target=Madeleine+van+den+Berg&namespace=all&tagfilter=&start=&end=&limit=1000)

<hr/>
<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf/page100-640px-Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf.jpg" width="200" align="right"/>

## BLOCK 4 - Wikidata & KB heritage collections

Examples of KB heritage collections: [Medieval manuscripts](https://commons.wikimedia.org/wiki/Koninklijke_Bibliotheek/Manuscripts/Medieval) - [Maps and atlases](https://commons.wikimedia.org/wiki/Koninklijke_Bibliotheek/Maps_and_atlases) - [Armorials](https://commons.wikimedia.org/wiki/Koninklijke_Bibliotheek/Manuscripts/Armorials) - [Alba amicorum](https://commons.wikimedia.org/wiki/Alba_amicorum_from_Koninklijke_Bibliotheek) - [Catchpenny prints](https://commons.wikimedia.org/wiki/Catchpenny_prints_from_Koninklijke_Bibliotheek) - [Children's picture books](https://commons.wikimedia.org/wiki/Koninklijke_Bibliotheek/Books/Picture_books) - [Flora and fauna books](https://commons.wikimedia.org/wiki/Koninklijke_Bibliotheek/Books/Flora_and_fauna)

### Criteria for suitability of KB heritage collections for Wikidata
1) Collection highlights, canonical objects: The most important objects of the KB must be present on Wikidata (and Commons)
2) Copyright free objects: Public domain = no hassle with copyright
3) Limited collection size: 10-100s of images are easier to process than 10-100Ks
4) Visually rich collections: What is depicted on the images, see Block 3
5) Connectable to other things: Making semantic links between the KB collections and persons, places, events etc. described in Wikidata
6) Collections consisting of similar, unique objects with narrow, flat, well-defined data models/classes: Similar values for [instance of](https://www.wikidata.org/wiki/Property:P31) and/or [subclass of](https://www.wikidata.org/wiki/Property:P279). Not OK: hetereogenous ephemera.

### WikiProject KB Collection highlights (2020-present)
KB collection highlights are part of our national heritage, just like e.g.
- [Act of Abjuration](https://en.wikipedia.org/wiki/Act_of_Abjuration) (collection highlight [National Archives](https://en.wikipedia.org/wiki/Nationaal_Archief))
- [Victory Boogie Woogie](https://en.wikipedia.org/wiki/Victory_Boogie_Woogie) (collection highlight [Kunstmuseum The Hague](https://en.wikipedia.org/wiki/Kunstmuseum_Den_Haag))
- [The Night Watch](https://en.wikipedia.org/wiki/The_Night_Watch) (collection highlight [Rijksmuseum Amsterdam](https://en.wikipedia.org/wiki/Rijksmuseum))

#### Presentation of collection highlights on kb.nl
[Collection highlights on (previous) KB website](https://web.archive.org/web/20200213191235/https://www.kb.nl/galerij/digitale-topstukken) from Febr 2020

Typical presentation of collection highlights on kb.nl, for instance for *Atlas Ortelius 1571*
1) [Catalog record](https://opc-kb.oclc.org/DB=1/XMLPRS=Y/PPN?PPN=369376781) --> Metadata
2) [Hi-res flip book](https://galerij.kb.nl/kb.html#/nl/ortelius/page/9/zoom/2/lat/-57.42129439209404/lng/-67.8515625) --> Images
3) [Contextual article](https://web.archive.org/web/20200213191235/https://www.kb.nl/themas/atlassen/atlas-ortelius) --> Stories, context

This presentation on kb.nl has limited functionalities and reuse options. This presentation represents an old way of thinking: Collection highlights (on kb.nl) are only for reading and viewing, inviting for passive consumption. More explanation in [this article](https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%201%2C%20Introduction.html).

#### A new paradigm for collection highlights

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf/page124-640px-Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf.jpg" width="200" align="right"/>

A new way of thinking: 
- KB collection highlights are building blocks and invite for active reuse and creation.
- Building blocks for tech community: Developers, app builders, tech companies, AIs, digital humanities, data scientists, hackathons, Wikimedia communities, LOD world, NDE, Europeana etc.
- KB collection highlights as a toolbox of Technical LEGO
    - Contents of this toolbox: Eg. 5-star Linked Open Data - Automatic image recognition (AI) - Semantic tagging - Data dumps & bulk downloads - SPARQL - Images searchable by content - Data visualizations - Python - Machine-readable data - Flexible REST APIs - Manifest legal terms - IIIF - Data as JSON, XML, CSV - Automatic multilingualism - External LOD Identifiers
- All these building blocks are available in the **Wikimedia infrastructure**: the combination of Wikidata (for metadata), Wikimedia Commons (for images) and Wikipedia (for contextual stories) - and their associated international communities - providing a coherent technical and social infrastructure to make KB's collection highlights much more visible, findable and reusable.

#### Wikification of KB collection highlights
[Wikifying KB’s collection highlights](https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%201%2C%20Introduction.html#wikifying-kbs-collection-highlights)

E.g. Atlas Ortelius:
1) [Catalog record KB](https://opc-kb.oclc.org/DB=1/XMLPRS=Y/PPN?PPN=369376781) --> Metadata to [Q67465742](https://www.wikidata.org/wiki/Q67465742#P195) on Wikidata, with [collection](https://www.wikidata.org/wiki/Property:P195) = [Koninklijke Bibliotheek](https://www.wikidata.org/wiki/Q1526131), and qualifier [subject has role](https://www.wikidata.org/wiki/Property:P2868) = [collection highlight](https://www.wikidata.org/wiki/Q29188408)
2) [Hi-res flip book KB](https://gallery.kb.nl/kb.html#/nl/ortelius/page/59/zoom/2/lat/-72.28906720017673/lng/-30.585937499999996) --> Images to [Atlas Ortelius 1571](https://commons.wikimedia.org/wiki/Atlas_Ortelius_1571) on Wikimedia Commons 
3) [Contextual article KB](https://www.kb.nl/ortelius) --> Context to [Theatrum Orbis Terrarum](https://nl.wikipedia.org/wiki/Theatrum_Orbis_Terrarum) on Dutch Wikipedia

The [WikiProject KB Collection highlights](https://www.wikidata.org/wiki/Wikidata:WikiProject_Collection_highlights_National_Library_of_the_Netherlands) (2020-present) aims to improve the findabilty, visibilty and reusability of KB's collection highlights for both humans and machines by
- creating and improving the [Wikidata descriptions](https://w.wiki/QpD) for all digitised KB collection highlights,
- uploading their [public domain images](https://commons.wikimedia.org/wiki/Category:Collection_highlights_of_Koninklijke_Bibliotheek) to Wikimedia Commons, reusing data from Wikidata as much as possible to create image metadata
- creating and improving the Wikipedia articles about them on Dutch and English Wikipedia

**Result of the project**: All  cool and value adding functionalities, tools and community capacities of the Wikimedia infrastructure are now available for our KB collection highlights. The party can start!

#### 50 cool new things you can do now with KB's collection highlights
<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf/page138-640px-Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek%2C_14_november_2023.pdf.jpg" width="200" align="right"/>

The party can start, let's build cool new things! --> See the article [50 cool new things you can do now with KB's collection highlights](https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights)<br/>
<sub>*In this series of 5 articles we show the added value of putting images and metadata of digitised collection highlights of the KB, national library of the Netherlands, into the Wikimedia infrastructure. By putting our collection highlights into Wikidata, Wikimedia Commons and Wikipedia, dozens of new functionalities have been added. As a result of Wikifying this collection in 2020, you can now do things with these highlights that were not possible before.*</sub>

This article has 5 parts:
- [Part 1, Introduction](https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%201%2C%20Introduction.html) - things you could already do with KB’s collection highlights before we started Wikifying them in 2020.
- [Part 2, Overviews of all highlights](https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%202%2C%20Overviews%20of%20all%20highlights.html) - new, handy & useful overviews for all highlights together
- [Part 3, Overviews per highlight](https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%203%2C%20Overviews%20per%20highlight.html) - new functionalities for individual highlights
- [Part 4, Images](https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%204%2C%20Images.html) - new things you can do with our individual highlight images
- [Part 5, Reuse](https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%205%2C%20Reuse.html) - some examples of programmatically reusing KB's collection highlights

##### Examples
1. All functionalities for KB images regarding SPARQL, structured search, multilingual search, search by content, as explained in Block 3
2. [Gallery of KB collection highlights](https://nl.wikipedia.org/wiki/Wikipedia:GLAM/Koninklijke_Bibliotheek_en_Nationaal_Archief/Topstuks/Galerij) on Dutch Wikipedia (never mind the new WP layout!)
3. [Persons/roles involved in each collection highlight](https://www.wikidata.org/wiki/Wikidata:WikiProject_Collection_highlights_National_Library_of_the_Netherlands/Admin/Overview/People)
4. [Contributors to the *Album Jacob Heyblocq*](https://commons.wikimedia.org/wiki/Category:Contributors_to_the_album_amicorum_Jacobus_Heyblocq)
   * [Facebook of contributors](https://w.wiki/phx)
   * [M/F distribution](https://w.wiki/F5J)
   * [Occupation cloud](https://w.wiki/F5N)
   * [Lifespan table](https://w.wiki/qzx)
5. [Works by these contributors in DBNL](https://w.wiki/3MLQ)
6. Works by these contributors elsewhere, via Europeana, as Excel: See for example [Govert Flinck on Europeana](https://www.europeana.eu/en/collections/person/63198-govert-flinck) + [this explanation](https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%205%2C%20Reuse.html), see Point 48
 

## Contact

Questions or remarks can be sent to Olaf Janssen, Wikimedia coordinator of the KB - olaf.janssen@kb.nl - @ookgezellig

## Reuse and licensing

This overview can be reused freely and openly, it is available under the [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license, so attribution is required. Use something like 

*Wikidata & KB national library of the Netherlands, an overview, Olaf Janssen & KB national library of the Netherlands, https://github.com/KBNLwikimedia/Wikidata-KB-Overview* 

<kbd><img src="images/cc-by.png" width="100"/></kbd>
