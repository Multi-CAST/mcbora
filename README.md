# Multi-CAST Bora

## How to cite

If you use these data please cite
- the original source
  > Seifart, Frank & Hong, Tai. 2023. Multi-CAST Bora. In Haig, Geoffrey & Schnell, Stefan (eds.), Multi-CAST: Multilingual corpus of annotated spoken texts. Version 2311. Bamberg: University of Bamberg. (multicast.aspra.uni-bamberg.de/#bora) (date accessed)
- the derived dataset using the DOI of the [particular released version](../../releases/) you were using

![](cldf/media/image.jpg)

## Description


**Bora** ([bora1263](https://glottolog.org/resource/languoid/id/bora1263)) Bora is a Boran language spoken in various small communities in the Colombian and Peruvian Amazon region (e.g. 3.23°S 71.99°W, 1.75°S 72.50°W). The language has approximately 1 000 speakers, almost all of whom are bilingual in local Spanish. The number of children acquiring Bora is currently decreasing.

Bora has been extensively documented within a VolkswagenStiftung-funded [DOBES documentation project](https://hdl.handle.net/1839/42550453-b3db-4d83-b30f-3bce5304588e) (2005–2009). The Multi-CAST Bora corpus consists of two folkloristic narrative texts taken from the larger DOBES collection. They were recorded and annotated by Frank Seifart in collaboration with, especially, Clever Panduro (original transcription and translation) and Lena Sell (original morphological glossing). Annotations with GRAID and RefIND were added to the corpus in 2021–2022 by Tai Hong in collaboration with Frank Seifart.

The Multi-CAST Bora texts (version 2207) also constitute a part of the [Bora data set](https://doreco.huma-num.fr/languages/bora1263) in [DoReCo](https://doreco.huma-num.fr/), which has been time-aligned at the phone level.

This dataset is licensed under a CC-BY-4.0 license

Available online at https://multicast.aspra.uni-bamberg.de/#bora


```geojson
{
    "type": "FeatureCollection",
    "features": [
        {
            "type": "Feature",
            "geometry": {
                "type": "Point",
                "coordinates": [
                    -72.257066,
                    -2.000259
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
                            -77.257066,
                            2.999741
                        ],
                        [
                            -67.257066,
                            2.999741
                        ],
                        [
                            -67.257066,
                            -7.000259
                        ],
                        [
                            -77.257066,
                            -7.000259
                        ],
                        [
                            -77.257066,
                            2.999741
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
| **⟨0.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨0.2⟩** | 6 | 3 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 10 |
| **⟨0.h⟩** | 7 | 2 | 0 | 35 | 0 | 0 | 0 | 0 | 0 | 0 | 44 |
| **⟨0.d⟩** | 2 | 2 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 6 |
| **⟨0⟩** | 4 | 2 | 0 | 37 | 0 | 0 | 1 | 0 | 1 | 0 | 45 |
| **⟨pro.1⟩** | 40 | 33 | 0 | 28 | 4 | 0 | 0 | 0 | 37 | 3 | 145 |
| **⟨pro.2⟩** | 80 | 40 | 0 | 15 | 1 | 0 | 0 | 0 | 13 | 1 | 150 |
| **⟨pro.h⟩** | 442 | 196 | 1 | 42 | 7 | 2 | 0 | 0 | 120 | 6 | 816 |
| **⟨pro.d⟩** | 44 | 31 | 0 | 6 | 2 | 0 | 0 | 0 | 4 | 1 | 88 |
| **⟨pro⟩** | 25 | 6 | 1 | 18 | 20 | 7 | 25 | 5 | 5 | 9 | 121 |
| **⟨np.1⟩** | 0 | 0 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 2 |
| **⟨np.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.h⟩** | 38 | 23 | 0 | 38 | 4 | 12 | 0 | 5 | 0 | 18 | 138 |
| **⟨np.d⟩** | 13 | 5 | 0 | 8 | 0 | 0 | 0 | 2 | 0 | 3 | 31 |
| **⟨np⟩** | 52 | 11 | 0 | 102 | 85 | 30 | 24 | 33 | 0 | 123 | 460 |
| **⟨other.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.h⟩** | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 1 |
| **⟨other.d⟩** | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 1 |
| **⟨other⟩** | 9 | 0 | 0 | 5 | 5 | 0 | 0 | 29 | 0 | 0 | 48 |
| | 762 | 354 | 2 | 339 | 130 | 51 | 50 | 74 | 180 | 164 | 2106 |


**Clause boundaries**

| GRAID | count |
|:-----------|--------:|
| **⟨##⟩** | 694 |
| **⟨#⟩** | 547 |
| **totals** | 1241 |



## Corpus metadata

- [Annotation notes](cldf/media/annotation-notes.pdf)
- [Translated texts](cldf/media/translated-texts.pdf)


## CLDF Datasets

The following CLDF datasets are available in [cldf](cldf):

- CLDF [TextCorpus](https://github.com/cldf/cldf/tree/master/modules/TextCorpus) at [cldf/TextCorpus-metadata.json](cldf/TextCorpus-metadata.json)