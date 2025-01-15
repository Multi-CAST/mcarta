<a name="ds-textcorpusmetadatajson"> </a>

# TextCorpus Multi-CAST Arta

**CLDF Metadata**: [TextCorpus-metadata.json](./TextCorpus-metadata.json)

**Sources**: [sources.bib](./sources.bib)

**Arta** ([arta1239](https://glottolog.org/resource/languoid/id/arta1239)) is an endangered Austronesian language spoken by a group of hunter-gatherers living in Luzon, the Philippines. The number of fluent speakers is between nine and eleven, most of which are over the age of forty. Since all speakers have settled down in the communities of neighboring Negrito groups (Casiguran/Nagitupunan Agta people), the language is not in active use and no longer taught to children. All of the speakers are multilingual with Casiguran/Nagtipunan Agta and Ilokano.

The texts were collected by Yukinori Kimoto during fieldwork in the Quirino and Aurora provinces in Luzon between 2012 and 2018. See [Kimoto (2017)](Source#cldf:kimoto2017) for [a description of the language](MediaTable#cldf:Kimoto2017_a-grammar-of-Arta.pdf).

property | value
 --- | ---
[dc:bibliographicCitation](http://purl.org/dc/terms/bibliographicCitation) | Kimoto, Yukinori. 2023. Multi-CAST Arta. In Haig, Geoffrey & Schnell, Stefan (eds.), Multi-CAST: Multilingual corpus of annotated spoken texts. Version 2311. Bamberg: University of Bamberg. (multicast.aspra.uni-bamberg.de/#arta) (date accessed)
[dc:conformsTo](http://purl.org/dc/terms/conformsTo) | [CLDF TextCorpus](http://cldf.clld.org/v1.0/terms.rdf#TextCorpus)
[dc:identifier](http://purl.org/dc/terms/identifier) | https://multicast.aspra.uni-bamberg.de/#arta
[dc:license](http://purl.org/dc/terms/license) | https://creativecommons.org/licenses/by/4.0/
[dcat:accessURL](http://www.w3.org/ns/dcat#accessURL) | https://github.com/Multi-CAST/mcarta
[prov:wasDerivedFrom](http://www.w3.org/ns/prov#wasDerivedFrom) | <ol><li><a href="https://github.com/Multi-CAST/mcarta/tree/v2207">Multi-CAST/mcarta v2207</a></li><li><a href="https://github.com/glottolog/glottolog/tree/v5.1">Glottolog v5.1</a></li></ol>
[prov:wasGeneratedBy](http://www.w3.org/ns/prov#wasGeneratedBy) | <ol><li><strong>python</strong>: 3.12.3</li><li><strong>python-packages</strong>: <a href="./requirements.txt">requirements.txt</a></li></ol>
[rdf:ID](http://www.w3.org/1999/02/22-rdf-syntax-ns#ID) | mcarta
[rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | http://www.w3.org/ns/dcat#Distribution


## <a name="table-utterancescsv"></a>Table [utterances.csv](./utterances.csv)

Annotated clauses of the texts in the collection.

property | value
 --- | ---
[dc:conformsTo](http://purl.org/dc/terms/conformsTo) | [CLDF ExampleTable](http://cldf.clld.org/v1.0/terms.rdf#ExampleTable)
[dc:extent](http://purl.org/dc/terms/extent) | 815


### Columns

Name/Property | Datatype | Description
 --- | --- | --- 
[ID](http://cldf.clld.org/v1.0/terms.rdf#id) | `string`<br>Regex: `[a-zA-Z0-9_\-]+` | Primary key
[Language_ID](http://cldf.clld.org/v1.0/terms.rdf#languageReference) | `string` | References [languages.csv::ID](#table-languagescsv)
[Primary_Text](http://cldf.clld.org/v1.0/terms.rdf#primaryText) | `string` | The example text in the source language.
[Analyzed_Word](http://cldf.clld.org/v1.0/terms.rdf#analyzedWord) | list of `string` (separated by `	`) | A grammatical word in the object language (or #, marking clause boundaries or ZERO marking zero anaphora). “Word” here should be understood in terms of a GRAID annotation unit.
[Gloss](http://cldf.clld.org/v1.0/terms.rdf#gloss) | list of `string` (separated by `	`) | The morphological glossing for the grammatical word, as per the Leipzig Glossing Rules. (or #, marking clause boundaries or ZERO marking zero anaphora).
[Translated_Text](http://cldf.clld.org/v1.0/terms.rdf#translatedText) | `string` | The translation of the example text in a meta language
[Meta_Language_ID](http://cldf.clld.org/v1.0/terms.rdf#metaLanguageReference) | `string` | References the language of the translated text<br>References [languages.csv::ID](#table-languagescsv)
[LGR_Conformance](http://cldf.clld.org/v1.0/terms.rdf#lgrConformance) | `string`<br>Valid choices:<br> `WORD_ALIGNED` `MORPHEME_ALIGNED` | The level of conformance of the example with the Leipzig Glossing Rules
[Comment](http://cldf.clld.org/v1.0/terms.rdf#comment) | `string` | 
[Media_IDs](http://cldf.clld.org/v1.0/terms.rdf#mediaReference) | list of `string` (separated by ` `) | References [media.csv::ID](#table-mediacsv)
[Position](http://cldf.clld.org/v1.0/terms.rdf#position) | `integer` | 
`Audio_Start` | `integer` | 
`Audio_End` | `integer` | 
`graid` | list of `string` (separated by `	`) | A morphosyntactic annotation unit with the GRAID scheme (Grammatical relations and animacy in discourse, Haig & Schnell 2014) or ## as clause boundary marker.
`add_orthography` | `string` | The object language text in another orthographical system; in Mandarin or Japanese, for instance, this tier contains the text in its original orthography (hanzi, or kanji and kana) while the utterance tier is a transliteration of the text (pinyin, or romaji).
[Text_ID](http://cldf.clld.org/v1.0/terms.rdf#contributionReference) | `string` | References [texts.csv::ID](#table-textscsv)

## <a name="table-textscsv"></a>Table [texts.csv](./texts.csv)

A collection of texts from one language, with shared provenance.

property | value
 --- | ---
[dc:conformsTo](http://purl.org/dc/terms/conformsTo) | [CLDF ContributionTable](http://cldf.clld.org/v1.0/terms.rdf#ContributionTable)
[dc:extent](http://purl.org/dc/terms/extent) | 11


### Columns

Name/Property | Datatype | Description
 --- | --- | --- 
[ID](http://cldf.clld.org/v1.0/terms.rdf#id) | `string`<br>Regex: `[a-zA-Z0-9_\-]+` | Primary key
[Name](http://cldf.clld.org/v1.0/terms.rdf#name) | `string` | 
[Description](http://cldf.clld.org/v1.0/terms.rdf#description) | `string` | 
[Contributor](http://cldf.clld.org/v1.0/terms.rdf#contributor) | list of `string` (separated by ` and `) | 
[Citation](http://cldf.clld.org/v1.0/terms.rdf#citation) | `string` | 
`Text_Number` | `integer` | Numeric text identifier, used as prefix of referent indices.
[Media_IDs](http://cldf.clld.org/v1.0/terms.rdf#mediaReference) | list of `string` (separated by ` `) | References [media.csv::ID](#table-mediacsv)
`Clause_Count` | `integer` | 
`Speaker` | `string` | 
`Speaker_Gender` | `string`<br>Valid choices:<br> `male` `female` | 
`Speaker_Age` | `integer` | The age of the speaker at the time of recording.
`Speaker_Age_Approximated` | `boolean`<br>Valid choices:<br> `yes` `no` | Whether the age of the speaker was approximated.
`Speaker_Year_Born` | `integer` | The speaker’s year of birth
`Speaker_Year_Born_Approximated` | `boolean`<br>Valid choices:<br> `yes` `no` | Whether the year of birth of the speaker was approximated.
`Type` | `string`<br>Valid choices:<br> `TN` `SN` `AN` | TN = traditional narratives, AN = autobiographical narratives, SN = stimulus-based narratives.
`Year_Recorded` | `integer` | 
`Recording_Length` | `float` | 
[Source](http://cldf.clld.org/v1.0/terms.rdf#source) | list of `string` (separated by `;`) | References [sources.bib::BibTeX-key](./sources.bib)

## <a name="table-languagescsv"></a>Table [languages.csv](./languages.csv)

property | value
 --- | ---
[dc:conformsTo](http://purl.org/dc/terms/conformsTo) | [CLDF LanguageTable](http://cldf.clld.org/v1.0/terms.rdf#LanguageTable)
[dc:extent](http://purl.org/dc/terms/extent) | 2


### Columns

Name/Property | Datatype | Description
 --- | --- | --- 
[ID](http://cldf.clld.org/v1.0/terms.rdf#id) | `string`<br>Regex: `[a-zA-Z0-9_\-]+` | Primary key
[Name](http://cldf.clld.org/v1.0/terms.rdf#name) | `string` | 
[Macroarea](http://cldf.clld.org/v1.0/terms.rdf#macroarea) | `string` | 
[Latitude](http://cldf.clld.org/v1.0/terms.rdf#latitude) | `decimal`<br>&ge; -90<br>&le; 90 | 
[Longitude](http://cldf.clld.org/v1.0/terms.rdf#longitude) | `decimal`<br>&ge; -180<br>&le; 180 | 
[Glottocode](http://cldf.clld.org/v1.0/terms.rdf#glottocode) | `string`<br>Regex: `[a-z0-9]{4}[1-9][0-9]{3}` | 
[ISO639P3code](http://cldf.clld.org/v1.0/terms.rdf#iso639P3code) | `string`<br>Regex: `[a-z]{3}` | 
`Affiliation` | `string` | Genealogical affiliation of the language.
`Areas` | `string` | Areas where the language is spoken.
`Varieties` | `string` | Varieties of the language recorded in this dataset.

## <a name="table-mediacsv"></a>Table [media.csv](./media.csv)

property | value
 --- | ---
[dc:conformsTo](http://purl.org/dc/terms/conformsTo) | [CLDF MediaTable](http://cldf.clld.org/v1.0/terms.rdf#MediaTable)
[dc:extent](http://purl.org/dc/terms/extent) | 59


### Columns

Name/Property | Datatype | Description
 --- | --- | --- 
[ID](http://cldf.clld.org/v1.0/terms.rdf#id) | `string`<br>Regex: `[a-zA-Z0-9_\-]+` | Primary key
[Name](http://cldf.clld.org/v1.0/terms.rdf#name) | `string` | 
[Description](http://cldf.clld.org/v1.0/terms.rdf#description) | `string` | 
[Media_Type](http://cldf.clld.org/v1.0/terms.rdf#mediaType) | `string`<br>Regex: `[^/]+/.+` | 
[Download_URL](http://cldf.clld.org/v1.0/terms.rdf#downloadUrl) | `anyURI` | 
[Path_In_Zip](http://cldf.clld.org/v1.0/terms.rdf#pathInZip) | `string` | 
`version` | `string` | 
`Size` | `integer` | File size in bytes
`Length` | `float` | Recording length in seconds for audio files.
[Contribution_ID](http://cldf.clld.org/v1.0/terms.rdf#contributionReference) | `string` | References [texts.csv::ID](#table-textscsv)
`Date_Updated` | `date` | 

