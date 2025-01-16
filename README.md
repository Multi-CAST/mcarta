# Multi-CAST Arta

## How to cite

If you use these data please cite
- the original source
  > Kimoto, Yukinori. 2022. Multi-CAST Arta. In Haig, Geoffrey & Schnell, Stefan (eds.), Multi-CAST: Multilingual corpus of annotated spoken texts. Version 2207. Bamberg: University of Bamberg. (multicast.aspra.uni-bamberg.de/#arta) (date accessed)
- the derived dataset using the DOI of the [particular released version](../../releases/) you were using

![](cldf/media/image.jpg)

## Description


**Arta** ([arta1239](https://glottolog.org/resource/languoid/id/arta1239)) is an endangered Austronesian language spoken by a group of hunter-gatherers living in Luzon, the Philippines. The number of fluent speakers is between nine and eleven, most of which are over the age of forty. Since all speakers have settled down in the communities of neighboring Negrito groups (Casiguran/Nagitupunan Agta people), the language is not in active use and no longer taught to children. All of the speakers are multilingual with Casiguran/Nagtipunan Agta and Ilokano.

The texts were collected by Yukinori Kimoto during fieldwork in the Quirino and Aurora provinces in Luzon between 2012 and 2018. See [Kimoto (2017)](Source#cldf:kimoto2017) for [a description of the language](MediaTable#cldf:Kimoto2017_a-grammar-of-Arta.pdf).

This dataset is licensed under a CC-BY-4.0 license

Available online at https://multicast.aspra.uni-bamberg.de/#arta


```geojson
{
    "type": "FeatureCollection",
    "features": [
        {
            "type": "Feature",
            "geometry": {
                "type": "Point",
                "coordinates": [
                    121.656,
                    16.4185
                ]
            }
        },
        {
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            116.656,
                            21.4185
                        ],
                        [
                            126.656,
                            21.4185
                        ],
                        [
                            126.656,
                            11.418500000000002
                        ],
                        [
                            116.656,
                            11.418500000000002
                        ],
                        [
                            116.656,
                            21.4185
                        ]
                    ]
                ]
            }
        }
    ]
}
```



## Corpus counts

Only a small number of basic GRAID symbols are counted:

*Function symbols*
- ⟨0⟩ zero
- ⟨pro⟩ definite pronoun
- ⟨np⟩ full noun phrase
- ⟨other⟩ form not further specified

*Person/Animacy symbols*
- ⟨.1⟩ first person
- ⟨.2⟩ second person
- ⟨.h⟩ third person, human
- ⟨.d⟩ third person, anthropomorphic
- ø third person, non-human

*Function symbols*
- ⟨:s⟩ subject of an intransitive clause
- ⟨:a⟩ subject of a transitive clause
- ⟨:ncs⟩ non-canonical subject
- ⟨:p⟩ direct object
- ⟨:obl⟩ oblique argument
- ⟨:g⟩ goal argument
- ⟨:l⟩ locational argument
- ⟨:pred⟩ predicate
- ⟨:poss⟩ possessive
- ⟨:other⟩ function not further specified

Only basic categories are listed; categories represented by complex symbols with additional
specifiers (e.g. ⟨dem_pro⟩ ‘demonstrative pronoun’) have been subsumed under the more basic
category (e.g. ⟨pro⟩ ‘definite pronoun’). Please refer to the annotation notes for this corpus for
information on all annotated categories, including those not listed here.

| GRAID | ⟨:s⟩ | ⟨:a⟩ | ⟨:ncs⟩ | ⟨:p⟩ | ⟨:obl⟩ | ⟨:g⟩ | ⟨:l⟩ | ⟨:pred⟩ | ⟨:poss⟩ | ⟨:other⟩ | totals |
|:--------------|-------:|-------:|---------:|-------:|---------:|-------:|-------:|----------:|----------:|-----------:|---------:|
| **⟨0.1⟩** | 3 | 12 | 0 | 3 | 0 | 1 | 0 | 0 | 0 | 0 | 19 |
| **⟨0.2⟩** | 1 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 8 |
| **⟨0.h⟩** | 52 | 33 | 0 | 32 | 1 | 2 | 0 | 0 | 0 | 0 | 120 |
| **⟨0.d⟩** | 2 | 2 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 5 |
| **⟨0⟩** | 24 | 7 | 0 | 73 | 0 | 1 | 0 | 0 | 0 | 0 | 105 |
| **⟨pro.1⟩** | 63 | 123 | 0 | 16 | 0 | 2 | 0 | 2 | 132 | 2 | 340 |
| **⟨pro.2⟩** | 20 | 40 | 1 | 5 | 1 | 0 | 0 | 3 | 21 | 0 | 91 |
| **⟨pro.h⟩** | 58 | 162 | 2 | 21 | 1 | 0 | 0 | 2 | 92 | 1 | 339 |
| **⟨pro.d⟩** | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 |
| **⟨pro⟩** | 29 | 6 | 0 | 43 | 3 | 11 | 8 | 7 | 9 | 7 | 123 |
| **⟨np.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.h⟩** | 77 | 41 | 14 | 62 | 4 | 11 | 0 | 6 | 30 | 7 | 252 |
| **⟨np.d⟩** | 0 | 0 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 2 |
| **⟨np⟩** | 82 | 6 | 44 | 152 | 19 | 9 | 20 | 67 | 14 | 68 | 481 |
| **⟨other.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.h⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.d⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other⟩** | 2 | 0 | 0 | 4 | 0 | 0 | 1 | 125 | 0 | 0 | 132 |
| | 413 | 440 | 61 | 414 | 29 | 37 | 29 | 212 | 298 | 85 | 2018 |


**Clause boundaries**

| GRAID | count |
|:-----------|--------:|
| **⟨##⟩** | 690 |
| **⟨#⟩** | 340 |
| **totals** | 1030 |



## Corpus metadata

- [Annotation notes](cldf/media/annotation-notes.pdf)
- [Translated texts](cldf/media/translated-texts.pdf)
- [Kimoto2017_a grammar of arta](cldf/media/Kimoto2017_a-grammar-of-Arta.pdf)


## CLDF Datasets

The following CLDF datasets are available in [cldf](cldf):

- CLDF [TextCorpus](https://github.com/cldf/cldf/tree/master/modules/TextCorpus) at [cldf/TextCorpus-metadata.json](cldf/TextCorpus-metadata.json)