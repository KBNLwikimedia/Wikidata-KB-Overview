Logo Wikidata + Logo KB

# Wikidata & KB, national library of the Netherlands, an overview

*An overview of how Wikidata is used by/in/for the KB, national library of the Netherlands* 

This page is a textual summary of the lecture *title* for employeees of KB, national library of the Netherlands on 14 November 2023, 15:00-16:15. The (rather long) slidedeck (in Dutch) for this lecture is available on [Wikimedia Commons] and [Zenodo] as PDFs. The [full text transcript] is avialabe at [page in this repo]

**Reuse and licensing**

This overview can be reused freely and openly, it is available under the [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license, so attribution is required. Use something like 

*Wikibase resources, Olaf Janssen & KB national library of the Netherlands, https://github.com/KBNLwikimedia/Wikidata-KB-Overview* 

<kbd><img src="cc-by.png" width="100"/></kbd>

**Latest updates**

Latest update: 15 November 2023
<hr>

### Contents - to adapt
- [Recap Wikidata](#recap-wikidata)
  * [Institutional use cases incompatible with Wikidata](#institutional-use-cases-incompatible-with-Wikidata)
- [What is Wikibase?](#what-is-wikibase-)
- [Wikibase courses and tutorials](#wikibase-courses-and-tutorials)
- [Examples of institutions/projects using Wikibase](#examples-of-institutions-projects-using-wikibase)
  * [Wikibase projects in libraries](#wikibase-projects-in-libraries)
- [Wikibase components & architecture](#wikibase-components---architecture)
- [Wikibase data model](#wikibase-data-model)
  * [Using alternative vocabularies in Wikibase](#using-alternative-vocabularies-in-wikibase)
- [Wikibase hosting](#wikibase-hosting)
- [Requesting data from a Wikibase](#requesting-data-from-a-wikibase)
  * [Cool Wikibase SPARQL queries](#cool-wikibase-sparql-queries)
- [Adding data to a Wikibase](#adding-data-to-a-wikibase)
- [Wikibase community](#wikibase-community)
- [Staying updated](#staying-updated)
- [Finding help](#finding-help)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

<hr>

## Intro

========================================
Internal communication about this session
* https://plein.kb.nl/calendar_events/8707
* https://plein.kb.nl/thoughts/25719

Required basic knowledge about Wikidata: Introduction course Guide to Wikidata, June 6, 2023
* https://zenodo.org/record/8006441
* https://commons.wikimedia.org/wiki/File:Wegwijzer_in_Wikidata,_Introductioncurus_Wikidata_-_Koninklijke_Bibliotheek,_6_juni_2023.pdf

=======================================
Objective of the course: To provide more understanding about
1. Why we at KB use Wikidata
2. How we use Wikidata for our thesauri & heritage
3. What added value this brings us

What do we do?
BLOCK 1) What does Wikidata add for the KB?
BLOCK 2) Wikidata & KB thesauri (NTA + DBNLa)
BLOCK 3) Intermezzo: Linking Wikimedia Commons with Wikidata
BLOCK 4) Wikidata & KB heritage collections


## BLOCK 1) What does Wikidata add for the KB?

(Captain Obvious)
- Be findable in Google
- Be present on Facebook
- Be present on Instagram
- Be present on YouTube
- Be present on Twitter
Summary open door: Be present on the large (web-scale) platforms

So also open door:
- Add your collection knowledge to Wikipedia
- Add your collection images to Wikimedia Commons
- Add your collection data to Wikidata

Wikidata is one of the largest and most popular LOD platforms in the world
Characteristics:
- Central part of the (web-scale) Wikimedia infrastructure (Wikipedia, Commons, 700+ Wikimedia platforms)
- Free, public utility for data (no IT costs)
- Centralized, no data silos, 1 language
- Global scope, (much) broader than KB/library/heritage/Netherlands domain
- Connection point for 8000+ databases worldwide
- Multilingual, language independent, 300+ languages
- Collaborative --> International community, 25K+ content creators
- For humans (GUI) and machines (API, SPARQL, JSON, RDF, Python etc.)
- LOD, but understandable & warm (thanks to community!)
- No copyright (CC0)
- Strong growing & sustainable
Result: economies of scale, community and network effects

Added value: What does Wikidata add for the KB?
1) Increase visibility, findability and reusability of our collections
- Greater public reach of KB collections, worldwide
- KB data in cross-domain, global, multilingual context --> Increasing interoperability KB with the outside world
- Community: External expertise, skills, tools and enthusiasm to enrich & connect KB data
2) New functionalities for our data (and images)
- Functionalities that we cannot (or cannot) offer in our KB services
- Due to Search, Data enrichment, quality control, visualization and formats, Image metadata, Machine interactions
- Both for our thesauri and heritage collections
- For people and machines
- KB collections as LEGO
3) Toolkit & platform to create and publish new KB LOD
- Internal KB LOD renewal is delayed
4) Developing and sharing knowledge & skills based on LOD
- Both internally and externally
- Strengthening cooperation with KB network partners via Wikidata/media


## BLOK 2) Wikidata & KB-thesauri (NTA + DBNLa)
KB-datasets (thesauri): http://data.bibliotheken.nl/ 

Critaria geschiktheid KB-thesauri voor Wikidata
- Personen (auteurs) zijn op Wikidata gewilder dan bv. trefwoorden of organisaties --> NTA + DBNLa zijn nuttiger dan Brinkman of GTT
- NTA is internationaal de enige grote gezaghebbende dataset over ‘Nederlandse auteurs’ --> NTA nuttig voor Wikidata (in internationale context)
- Platte/eenvoudige data is geschikter dan gelaagde/complexe data --> Personen zijn makkelijker aan Wikidata toe te voegen dan titels (WEMI = lastig)
- Kleine datasets zijn makkelijker dan grote --> Alba amicorum en Centsprenten zijn geschikt voor Wikidata

Ergo: Focus op NTA en DBNLauteurs v.w.b. de KB thesauri-Wikidata-activiteiten

Wikidata in de NTA

Personen in de NTA met een Wikidata-URI: 
- Bv. Darlene Dixon : http://data.bibliotheken.nl/doc/thes/p208140131  --> schema:sameAs --> http://www.wikidata.org/entity/Q88505402
- Alle personen: http://data.bibliotheken.nl/sparql?default-graph-uri=&qtxt=%23+Welke+NTA-items+bevatten+een+Wikidata-link%3F%0D%0A%0D%0ASELECT+*+WHERE+{%0D%0A+%3Fnta+schema%3AmainEntityOfPage%2Fschema%3AisPartOf+%3Chttp%3A%2F%2Fdata.bibliotheken.nl%2Fid%2Fdataset%2Fpersons%3E+.%0D%0A+%3Fnta+rdfs%3Alabel+%3FntaLabel.++%0D%0A+%3Fnta+schema%3AsameAs+%3Fwikidata+.%0D%0AFILTER(regex(%3Fwikidata%2C+%27wikidata%27%2C+%27i%27))%0D%0A}+LIMIT+1000&format=text%2Fhtml&timeout=0&debug=on&run=+Run+Query+
- 499K v/d 2.75M NTA-items hebben een Wikidata-link (bron= https://nl.wikipedia.org/wiki/Wikipedia:GLAM/Koninklijke_Bibliotheek_en_Nationaal_Archief/Resultaten/KPIs/KPI10#Historische_ontwikkeling_van_KPI_10)

Personen in DBNLa met Wikidata-URI (via de NTA)
- Bv  HansAarsman (1951-): http://data.bibliotheken.nl/id/dbnla/aars001 -->  owl:sameAs --> http://data.bibliotheken.nl/id/thes/p068680937 --> schema:sameAs --> http://www.wikidata.org/entity/Q325922 
- Alle personen: http://data.bibliotheken.nl/sparql?default-graph-uri=&qtxt=%23+Welke+DBNLa-items+bevatten+een+link+naar+Wikidata%3F%0D%0ASELECT+*+%0D%0AWHERE+{%0D%0A+%3Fdbnl+schema%3AmainEntityOfPage%2Fschema%3AisPartOf+%3Chttp%3A%2F%2Fdata.bibliotheken.nl%2Fid%2Fdataset%2Fdbnla%3E+.%0D%0A+%3Fdbnl+rdfs%3Alabel+%3FdbnlLabel.++%0D%0A+%3Fdbnl+owl%3AsameAs+%3Fnta+.%0D%0A+%3Fnta+schema%3AmainEntityOfPage%2Fschema%3AisPartOf+%3Chttp%3A%2F%2Fdata.bibliotheken.nl%2Fid%2Fdataset%2Fpersons%3E+.%0D%0A+%3Fnta+rdfs%3Alabel+%3FntaLabel.+++%0D%0A+%3Fnta+schema%3AsameAs+%3Fwikidata+.%0D%0A+FILTER(regex(%3Fwikidata%2C+%27wikidata%27%2C+%27i%27))%0D%0A}+LIMIT+1000&format=text%2Fhtml&timeout=0&debug=on&run=+Run+Query+
- 14.5K v/d 109K DBNLa-items hebben een Wikidata-link (bron= https://nl.wikipedia.org/wiki/Wikipedia:GLAM/Koninklijke_Bibliotheek_en_Nationaal_Archief/Resultaten/KPIs/KPI10#Historische_ontwikkeling_van_KPI_10)

Achille Van Acker 
- In de DBNL: http://data.bibliotheken.nl/doc/dbnla/acke001 
- In Wikidata: http://www.wikidata.org/entity/Q14997 
Aanvullende data over 'acke001' uit Wikidata ophalen. We willen de volgende gegevens ophalen: 
- Image: https://www.wikidata.org/wiki/Property:P18 
- Educated at: https://www.wikidata.org/wiki/Property:P69
- Member of political party: https://www.wikidata.org/wiki/Property:P102
SPARQL: 
http://data.bibliotheken.nl/sparql?default-graph-uri=&qtxt=%23+Aanvullende+gegevens+over+DBNL-auteur+%27acke001%27+uit+Wikidata+ophalen%0D%0APREFIX+wdt%3A+%3Chttp%3A%2F%2Fwww.wikidata.org%2Fprop%2Fdirect%2F%3E%0D%0ASELECT+*+%0D%0AWHERE+{%0D%0A+%3Fdbnl+schema%3AmainEntityOfPage%2Fowl%3AsameAs++%3Chttp%3A%2F%2Fdata.bibliotheken.nl%2Fdoc%2Fdbnla%2Facke001%3E+.%0D%0A+%3Fdbnl+rdfs%3Alabel+%3FdbnlLabel.++%0D%0A+%3Fdbnl+owl%3AsameAs+%3Fnta+.%0D%0A+%3Fnta+schema%3AmainEntityOfPage%2Fschema%3AisPartOf+%3Chttp%3A%2F%2Fdata.bibliotheken.nl%2Fid%2Fdataset%2Fpersons%3E+.%0D%0A+%3Fnta+rdfs%3Alabel+%3FntaLabel.+++%0D%0A+%3Fnta+schema%3AsameAs+%3Fwikidata+.%0D%0A+FILTER(regex(%3Fwikidata%2C+%27wikidata%27%2C+%27i%27))%0D%0A%0D%0A+SERVICE+%3Chttps%3A%2F%2Fquery.wikidata.org%2Fsparql%3E+{%0D%0A+++%3Fwikidata+wdt%3AP18+%3FimageURL.+%23P18+%3D+image%0D%0A+++%3Fwikidata+wdt%3AP69+%3FedcucatedAt.+%23P69+%3D+educated+at%0D%0A+++%3Fwikidata+wdt%3AP102+%3FMemberOfPoliticalParty.+%23P102+%3D+member+of+political+party%0D%0A%0D%0A+}%0D%0A}+&format=text%2Fhtml&timeout=0&debug=on&run=+Run+Query+
Checks: 
- P18 (image): http://commons.wikimedia.org/wiki/Special:FilePath/Achiel%20Van%20Acker1.jpg 
- P69 (educated at): http://www.wikidata.org/entity/Q500740 
- P102 (member of political party): http://www.wikidata.org/entity/Q2532509 

En nu de andere kant op: De NTA (en DBNLa) in Wikidata

Harry Mulisch in Wikidata: https://www.wikidata.org/wiki/Q927 
NTA in Wikidata: https://www.wikidata.org/wiki/Property:P1006 
Harry Mulisch in de NTA: https://data.bibliotheken.nl/doc/thes/p06854796X 

Personen in Wikidata met een NTA-id: https://w.wiki/85Cs 
Inzichten in het gebruik van P1006: https://www.wikidata.org/wiki/Property_talk:P1006 
- Wikidata bevat 550K links naar de NTA: https://tinyurl.com/5bep7h8a
- Kaart van geboorteplaatsen van mensen met een NTA-id: https://w.wiki/7rsT
- Beroemde personen met een NTA-id: https://w.wiki/85si (beroemde personen hebben uitgebreide Wikidata-items)

P1006 en datakwaliteit
Twee pagina’s geven inzicht in de datakwaliteit (en mogelijke verbeteringen) van zowel Wikidata als de NTA

1) Ontbrekende data in Wikidata: https://www.wikidata.org/wiki/Wikidata:Database_reports/Humans_with_missing_claims/P1006
- Mensen die voorkomen in de NTA van wie geboorteplaats/datum in Wikidata ontbreekt: https://www.wikidata.org/wiki/Wikidata:Database_reports/Humans_with_missing_claims/P1006#Missing_date_of_birth_(P569)
- Vanuit de NTA kunnen de ontbrekende geboortedata mogelijk aan Wikidata worden toegevoegd

2) Afwijkende data in Wikidata: https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/P1006 
Deze pagina rapporteert afwijkingen en mogelijke fouten in Wikidata en de NTA 

a- Ontbrekende Nederlandstalige labels
-- https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/P1006#%22Label_in_'nl'_language%22_violations
-- Via SPARQL: https://w.wiki/85xT
-- Bv: Anna Bhau Sathe, https://www.wikidata.org/wiki/Q55759 --> NL label ontbreekt
-- Vanuit de NTA kan het ontbrekende NL label worden toegevoegd

b- Zelfde NTA-id komt voor in meerdere Q-items: 
-- https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/P1006#Unique_value 
-- Via SPARQL: https://w.wiki/85zm 
-- Bv: Andreas Kaiser, https://data.bibliotheken.nl/doc/thes/p068685564 --> https://www.wikidata.org/wiki/Q498631 (fout) + https://www.wikidata.org/wiki/Q106361537 (goed)
-- https://www.wikidata.org/wiki/Q498631 moet een andere waarde bij P1006 krijgen

c- Eén Wikidata-item met meerdere NTA-ids: 
-- https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/P1006#Single_value 
-- Via SPARQL: https://w.wiki/85$o 
-- Bv. Douglas Adams, https://www.wikidata.org/wiki/Q42#P1006 --> http://data.bibliotheken.nl/doc/thes/p339433876 + http://data.bibliotheken.nl/doc/thes/p068744307 
-- Deze zijn vrijwel identiek, overweeg samenvoeging in de NTA

Samenvattend: door het integreren van NTA-data in Wikidata krijgen we een hoop nieuwe functionaliteiten m.b.t. datakwaliteit, -verbindingen en -visualisatie die we niet via onze eigen KB-LOD dienst data.bibliotheken.nl (kunnen) aanbieden! 

Theo van Veen, Wikidata als gemeenschappelijke thesaurus?, IP, Vakblad voor informatieprofessionals, oktober 2016, nr. 07
- https://informatieprofessional.nl/resources/uploads/2016/10/IP2016-07.pdf
- https://web.archive.org/web/20221028121446/https://informatieprofessional.nl/resources/uploads/2016/10/IP2016-07.pdf 

WikiProject Dutch National Thesaurus for Author Names: https://www.wikidata.org/wiki/Wikidata:WikiProject_Dutch_National_Thesaurus_for_Author_Names 

Gebruik NTA-ids in Wikipedia-artikelen
- Wikidata: Category:Articles with NTA identifiers - https://www.wikidata.org/wiki/Q47763687 
- Engelstalige Wikipedia: 
-- 234K artikelen op WP:EN zijn voorzien van een NTA-id
-- https://en.wikipedia.org/wiki/Category:Articles_with_NTA_identifiers 
-- Bv. https://en.wikipedia.org/wiki/50_Cent --> http://data.bibliotheken.nl/id/thes/p262032139  
- Turkse Wikidia
-- 25K artikelen op WP:TR zijn voorzien van een NTA-id
-- https://tr.wikipedia.org/wiki/Kategori:NTA_tan%C4%B1mlay%C4%B1c%C4%B1s%C4%B1_olan_Vikipedi_maddeleri 
- Tjechische Wikipedia
-- 36K artikelen op WP:CS zijn voorzien van een NTA-id
-- https://cs.wikipedia.org/wiki/Kategorie:Monitoring:%C4%8Cl%C3%A1nky_s_identifik%C3%A1torem_NTA 
- Japanse Wikipedia
-- 51K artikelen op WP:JA zijn voorzien van een NTA-id
-- https://ja.wikipedia.org/wiki/Category:NTA%E8%AD%98%E5%88%A5%E5%AD%90%E3%81%8C%E6%8C%87%E5%AE%9A%E3%81%95%E3%82%8C%E3%81%A6%E3%81%84%E3%82%8B%E8%A8%98%E4%BA%8B 
Samenvattend: via Wikidata wordt onze NTA als autoriteit in 100.000den Wikipedia-artikelen in vele talen gebruikt. (maar niet het Nederlands!)

DBNLa in Wikidata
- Alles wat hierboven genoemd wordt voor de NTA geldt analoog voor de DBNLa
- DBNLa in Wikidata: https://www.wikidata.org/wiki/Property:P723 
- Personen in Wikidata met een DBNLa-id : https://w.wiki/869Y 
- Inzichten in het gebruik van P723: https://www.wikidata.org/wiki/Property_talk:P723 
- Wikidata bevat 31K links naar de DBNLa: https://www.wikidata.org/wiki/Property_talk:P723 (onderaan, 'Current uses')
- Inzicht in de datakwaliteit (en mogelijke verbeteringen) van zowel Wikidata als de DBNLa
-- https://www.wikidata.org/wiki/Wikidata:Database_reports/Humans_with_missing_claims/P723
-- https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/P723

Gebruik van KB-identifiers in Wikidata, en v.v., zowel voor de NTa als de DBNLa: https://nl.wikipedia.org/wiki/Wikipedia:GLAM/Koninklijke_Bibliotheek_en_Nationaal_Archief/Resultaten/KPIs/KPI10 

==================================================================
BLOK 3) Intermezzo: Koppeling van Wikimedia Commons met Wikidata
=================================================================
De Sint Pancraskerk in Leiden heet nu de Hooglandse Kerk: https://commons.wikimedia.org/wiki/File:Atlas_de_Wit_1698-pl017-Leiden-St_Pancraskerk.jpg

Reguliere metadata
- Manifeste tekstuele en visuele KB-bronvermeldingen
- ‘Handmatige’ meertaligheid
- Broncode = ongestructureerde metadata (vrije tekst) --> https://commons.wikimedia.org/w/index.php?title=File:Atlas_de_Wit_1698-pl017-Leiden-St_Pancraskerk.jpg&action=edit

Structured Data on Commons 
- is a project to add multilingual structured information from Wikidata to files on Wikimedia Commons that can be understood by humans, with enough consistency that it can also be uniformly processed by machines. 
- https://commons.wikimedia.org/wiki/Commons:Structured_data

Gestructureerde metadata bij afbeeldingen op Commons
- Afbeelding wordt gekoppeld met Wikidata 
- Voorzien van echte gestructureerde (en dus machineleesbare) data
- Linked open data voor Commons-bestanden

Niet alleen voor afbeeldingen, maar ook bv PDFs: https://commons.wikimedia.org/wiki/File:OpenRefine-Wikidata_introduction_workshop_-_Koninklijke_Bibliotheek,_4_juli_2023.pdf

Meerwaarde voor KB
- Gestructureerde 5* LOD metadata bij meer dan 30.000 KB-mediabestanden in https://commons.wikimedia.org/wiki/Category:Media_contributed_by_Koninklijke_Bibliotheek 
- KB-bestanden worden onderdeel van de LOD-cloud, en worden via SPARQL doorzoekbaar.
	
SPARQL queries met KB-bestanden
- Alle bestanden uit de KB-collectie: https://w.wiki/7zh5. - Collectie (P195) = Koninklijke Bibliotheek (Q1526131)
- PDF-bestanden van de KB: https://w.wiki/7zhm - MIME-type (P1163) = “application/pdf”
- Afbeeldingen van Album amicorum van Jacobus Heyblocq: https://w.wiki/7zjb

Wat is er op KB-afbeeldingen te zien??
- https://commons.wikimedia.org/wiki/Commons:Depicts
- Wat is er op deze afbeelding te zien, getagd m.b.v. Wikidata-items
- Dingen afgebeeld op de plaat "Hooglandse kerk" in Atlas De Wit 1698 (https://commons.wikimedia.org/wiki/File:Atlas_de_Wit_1698-pl017-Leiden-St_Pancraskerk.jpg): Hooglandse Kerk (Q1537970) - paard (Q726) - hond (Q144) - klok (Q376) - volk (Q2472587) - wolk (Q8074) - rijtuig (Q235356) - trapgevel (Q1939660) - boom (Q10884) - wandelstok (Q1347864) - De Burcht (Q18813071) - vrouw (Q467) - kind (Q7569) - deur (Q36794) - hoed (Q80151) - windhaan (Q2157687) - glas-in-loodraam (Q488094)
- Afgebeelde dingen op de plaat "Hooglandse kerk" in Atlas De Wit 1698 (M32246848) via SPARQL opvragen: https://w.wiki/7zps 
- Afgebeelde dingen in heel Atlas de Wit (https://commons.wikimedia.org/wiki/Category:Atlas_de_Wit_1698) via SPARQL opvragen: https://w.wiki/7zqj 

Even samenvatten: KB-beelden op Commons zijn dus op 3 manieren doorzoekbaar 
1) Reguliere metadata (vrije tekst)
2) Gestructureerde metadata
3) Op inhoud (Wat is er op KB-afbeelding te zien?)

De (superhandige!) tool Hay’s Structured Search biedt alle drie de opties: 
- Visuele, meertalige zoekmachine om afbeeldingen met (en zonder) gestructureerde data in Wikimedia Commons te vinden
- https://hay.toolforge.org/sdsearch/ 

- Alle KB-beelden, met én zonder gestructureerde data (30.617 beelden in https://commons.wikimedia.org/wiki/Category:Media_contributed_by_Koninklijke_Bibliotheek)
-- Zoeken in het Engels
-- https://hay.toolforge.org/sdsearch/#q=incategory:%22Media%20contributed%20by%20Koninklijke%20Bibliotheek%22

- KB-beelden, waarop iets afgebeeld is
-- Zoeken in het Nederlands
-- https://hay.toolforge.org/sdsearch/#q=incategory:%22Media%20contributed%20by%20Koninklijke%20Bibliotheek%22%20haswbstatement:P180
-- 19.764 v/d 30.167 beelden (66%)

- KB-beelden, waarop honden zijn afgebeeld
-- Zoeken in het Nederlands
-- https://hay.toolforge.org/sdsearch/#q=incategory:%22Media%20contributed%20by%20Koninklijke%20Bibliotheek%22%20haswbstatement:P180=Q144
 
- Steden aan de Zuiderzee
-- https://hay.toolforge.org/sdsearch/#q=incategory:%22Media%20contributed%20by%20Koninklijke%20Bibliotheek%22%20haswbstatement:P180=Q228655%20-incategory:%22Visboeck%20Coenen%22%20-incategory:%22Visboeck%20Coenen%20(openings)%22%20-incategory:%22Catchpenny%20prints%20from%20Koninklijke%20Bibliotheek%22 

- Miniaturen uit Der Naturen Bloeme waarop vissen staan
-- https://hay.toolforge.org/sdsearch/#q=incategory:%22Miniatures%20from%20Der%20naturen%20bloeme%20-%20KB%20KA%2016%22%20haswbstatement:P180=Q152 
-- https://commons.wikimedia.org/wiki/Category:Miniatures_from_Der_naturen_bloeme_-_KB_KA_16 

- Beelden uit Atlas de Wit, waarop een brug staat
-- https://hay.toolforge.org/sdsearch/#q=incategory:%22Atlas%20de%20Wit%201698%22%20haswbstatement:P180=Q12280
-- https://commons.wikimedia.org/wiki/Category:Atlas_de_Wit_1698  

- Beelden uit Atlas de Wit waarop een 'igreja' (kerkgebouw) staat
-- Zoeken in het Portugees
-- igreja = kerkgebouw in het Portugees
-- https://hay.toolforge.org/sdsearch/#offset=0&q=incategory:%22Atlas%20de%20Wit%201698%22%20haswbstatement:P180=Q16970
-- https://commons.wikimedia.org/wiki/Category:Atlas_de_Wit_1698  

- Beelden waarop zowel 'église' (kerkgebouw) als 'chien' (hond) staan
-- Zoeken in het Frans
-- https://hay.toolforge.org/sdsearch/#q=incategory:%22Atlas%20de%20Wit%201698%22%20haswbstatement:P180=Q16970%20haswbstatement:P180=Q144
-- https://commons.wikimedia.org/wiki/Category:Atlas_de_Wit_1698 
-- Beeldt af : Kerkgebouw + Beeldt af : Hond
-- Taalonafhankelijk zoeken naar afgebeelde dingen in Atlas De Wit

Samenvattend: Getoonde zoekfunctionaliteiten (SPARQL, gestructureerd, meertalig zoeken, op inhoud) zijn veel geavanceerder dan in onze eigen KB-(beeld)diensten!

Wil je zelf Depicts-tags aan KB-beelden toevoegen?
- https://commons.wikimedia.org/wiki/File:Instructie_KB-beelden_op_Commons_taggen_met_Wikidata_-_26032020.pdf
- https://zenodo.org/record/7777755 
- Deze handleiding (2020) legt stap voor stap uit hoe je afbeeldingen uit de KB-collectie beter vindbaar, zichtbaar en herbruikbaar maakt door aan te geven (taggen) welke dingen (entiteiten) er te zien zijn op die afbeeldingen. 
- Resultaten dd 1-11-2023
-- 30.617 KB-collectiebeelden op Commons - https://commons.wikimedia.org/wiki/Category:Media_contributed_by_Koninklijke_Bibliotheek
-- 19.764 beelden waarop iets getagd is (te zien is) - https://hay.toolforge.org/sdsearch/#q=incategory:%22Media%20contributed%20by%20Koninklijke%20Bibliotheek%22%20haswbstatement:P180
-- KB-tagkampioene: Madeleine van den Berg ? 34K+ dingen toegevoegd - https://commons.wikimedia.org/w/index.php?title=Special%3AContributions&target=Madeleine+van+den+Berg&namespace=all&tagfilter=&start=&end=&limit=500  

==================================================================
BLOK 4) Wikidata & KB-erfgoedcollecties
=================================================================
Voorbelden KB-erfgoedcollecties:Manuscripten - Atlassen - Wapenboeken - Vriendenboeken - Centsprenten - Kinderprentenboeken - Flora- en faunaboeken

Criteria geschiktheid KB-erfgoed voor Wikidata
- 1) Topstukken, canonieke objecten
- 2) Rechtenvrije objecten (publiek domein)
- 3) Beperkte collectieomvang
- 4) Visueel rijke collecties
- 5) Verbindbaar met andere dingen (personen, plaatsen, gebeurtenissen...)
- 6) Collecties van gelijksoortige, unieke objecten (smalle, platte, goedgedefinieerd datamodel/klasse)

WikiProject KB Topstukken (2020-heden)
KB-Topstukken zijn onderdeel van ons nationale erfgoed, netzo als bv.
- Plakkaat van Verlatinghe (Topstuk Nationaal Archief)
- Victory Boogie Woogie (Topstuk Kunstmuseum Den Haag)
- De Nachtwacht (Topstuk Rijksmuseum Amsterdam)

Projectpagina WikiProject KB Topstukken: https://www.wikidata.org/wiki/Wikidata:WikiProject_Collection_highlights_National_Library_of_the_Netherlands

Topstukken op (vorige) KB-website: https://www.kb.nl/galerij/digitale-topstukken

Typische presentatie topstukken op kb.nl 
- 1) Catalogusrecord --> Metadata
- 2) Hi-res bladerboek --> Beelden
- 3) Context-artikel --> Verhalen

Deze presentatie op kb.nl heeft beperkte functionaliteiten en hergebruiksmogelijkheden 
Oude manier van denken: Topstukken (op kb.nl) zijn alleen om te lezen en bekijken --> Passief consumeren
Meer uitleg in dit artikel: https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%201%2C%20Introduction.html

Nieuwe manier van denken: KB-Topstukken zijn bouwstenen en nodigen uit tot actief creëren
Bouwstenen voor tech community: Ontwikkelaars, app-bouwers, techbedrijven, AIs, digital humanities, data scientists, hackathons, LOD-wereld, NDE, Europeana etc.

KB Topstukken als doos Technisch LEGO
Inhoud van de doos (The unboxing): 5* Linked Open Data - Automatische beeldherkenning (AI) - Semantic tagging - Datadumps & bulkdownloads - SPARQL - Afbeelding doorzoekbaar op inhoud - Datavisualisaties - Python - Machineleesbare data - Flexibele REST APIs - Manifeste juridische voorwaarden - IIIF - JSON, XML, CSV - Automatische meertaligheid - Externe LOD-identifiers

Al deze bouwstenen zijn beschikbaar in de Wikimedia infrastructuur: Wikidata (metadata), Wikimedia Commons (beelden) en Wikipedia (verhalen) - en de bijbehorende internationale communities - bieden een samenhangende technische en sociale infrastructuur om onze Topstukken veel beter herbruikbaar te maken.

Wikificatie van onze Topstukken: https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%201%2C%20Introduction.html

Bv a.d.h.v. Atlas Ortelius: 
- 1) Catalogusrecord KB (https://opc-kb.oclc.org/DB=1/XMLPRS=Y/PPN?PPN=369376781) --> Metadata naar Wikidata (https://www.wikidata.org/wiki/Q67465742#P195 --> subject has role collection highlight)
- 2) Hi-res bladerboek KB (https://galerij.kb.nl/kb.html#/nl/ortelius/page/59/zoom/2/lat/-72.28906720017673/lng/-30.585937499999996) --> Beelden naar Wikimedia Commons (https://commons.wikimedia.org/wiki/Atlas_Ortelius_1571)
- 3) Context-artikel KB (https://www.kb.nl/ortelius) --> Verhaal op Wikipedia (https://nl.wikipedia.org/wiki/Theatrum_Orbis_Terrarum)

Resultaat Topstukkenproject: Alle functionaliteiten & meerwaarden van de Wikimedia- infrastructuur zijn nu beschikbaar voor onze KB-Topstukken

Het feest kan beginnen! Coole dingen bouwen!
50 cool new things you can now do with KB’s collection highlights: https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/

By putting our collection highlights into Wikidata, Wikimedia Commons and Wikipedia, dozens of new functionalities have been added (LEGO box). As a result of Wikifying this collection in 2020, you can now do things with these highlights that were not possible before.

50 cool new things: 
- Part 2, Overviews of all highlights - new, handy & useful overviews for all highlights together: https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%202%2C%20Overviews%20of%20all%20highlights.html
- Part 3, Overviews per highlight - new functionalities for individual highlights: https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%203%2C%20Overviews%20per%20highlight.html
- Part 4, Images - new things you can do with our individual highlight images: https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%204%2C%20Images.html
- Part 5, Reuse - some examples of programmatically reusing KB’s collection highlights: https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%205%2C%20Reuse.html

Een paar voorbeelden: 
- 1) Nieuwe functionaliteiten uit Blok 3, zie boven
- 2) Galerij van KB-topstukken: https://nl.wikipedia.org/wiki/Wikipedia:GLAM/Koninklijke_Bibliotheek_en_Nationaal_Archief/Topstukken/Galerij
- 3) Bij elk topstuk betrokken personen/rollen: https://www.wikidata.org/wiki/Wikidata:WikiProject_Collection_highlights_National_Library_of_the_Netherlands/Admin/Overview/People
- 4) Bijdragers aan het Album Jacob Heyblocq
-- Smoelenboek: https://w.wiki/phx 
-- M/V-verdeling: https://w.wiki/F5J
-- Beroepenwolk: https://w.wiki/F5N
-- Levenduur tabel: https://w.wiki/qzx
- 5) Werken van deze bijdragers in DBNL: https://w.wiki/3MLQ 
- 6) Werken van deze bijdragers elders, via Europeana, als Excel: https://www.europeana.eu/en/collections/person/63198-govert-flinck + uitleg op https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/Part%205%2C%20Reuse.html, Punt 48

================================================
De slotconclusie van dit verhaal? Wikidata voegt heel veel waarde toe aan onze KB-thesauri & -erfgoedcollecties!

================================================
Vragen?	Olaf Janssen - olaf.janssen@kb.nl - @ookgezellig

============================================
Licentie: de inhoud van deze pagina is beschikbaar onder de CC-BY-SA 4.0 licentie: https://creativecommons.org/licenses/by-sa/4.0/deed.nl


