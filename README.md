# 🌍 Geomelon API — Global Cities, Countries & Regions

**Geomelon API** is a read-only geospatial and metadata API that provides rich, multilingual information about **cities, countries, and regions worldwide**.  
It is designed for developers building location-aware applications, mapping tools, analytics platforms, travel products, and data-driven services that require **accurate geographic data with localization support**.

---

## ✨ Key Features

### 🏙 Cities
- City names in **multiple languages**, with automatic language preference fallback
- Country and region names localized to the preferred language
- Geographic coordinates (latitude / longitude)
- Population, area, elevation, postal codes, dialing codes and time zones
- Distance calculations and proximity-based queries
- Search, filtering, sorting, and pagination
- Settlement types and full translation listings

### Example city
```
  {
    "id": "e6f2131f-dd05-4bff-8d8c-ab1be5e12287",
    "wikidataId": "Q62",
    "name": "San Francisco",
    "localizedName": "San Francisco",
    "countryId": "877ac2ad-2c52-413b-9754-a11f94c98384",
    "countryName": "United States",
    "countryCode": "US",
    "countryEmoji": "🇺🇸",
    "regionCode": "US-CA",
    "regionName": "California",
    "regionId": "dbb075ea-1514-4357-a69c-eb8113f2f884",
    "population": 808988,
    "latitude": 37.775,
    "longitude": -122.419444444,
    "elevation": 30,
    "area": 600.59028,
    "postalCode": "94133",
    "officialWebsite": null,
    "timeZone": "UTC−08:00",
    "flagImage": "http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20San%20Francisco%2C%20California.svg",
    "dialingCode": "628",
    "normalizedName": "san francisco",
    "translations": [
      {
        "language": "en",
        "name": "San Francisco"
      },
      {
        "language": "hi",
        "name": "सैन फ्रांसिस्को"
      },
      {
        "language": "ja",
        "name": "サンフランシスコ"
      },
      {
        "language": "sr",
        "name": "Сан Франциско"
      },
      {
        "language": "zh",
        "name": "舊金山"
      }
    ]
  },
```

### 🌐 Countries
- ISO country codes
- Flag emoji / flag image
- Localized country names
- Population, area, and geographic coordinates
- Government and administrative metadata
- Region listings per country

### 🗺 Regions
- ISO region codes
- Localized region names
- Population data
- Filtering by country

### 🗣 Languages
- List and inspect supported languages
- Useful for building dynamic localization pipelines

---

## 🔎 Geospatial & Search Capabilities

- **Find closest cities** to a given latitude/longitude
- **Find most populous cities** near a coordinate
- **Calculate distance** between two cities (in kilometers)
- City name search with optional population, country, and region filters
- Sort results by population or relevance
- Offset-based pagination for large datasets

---

## 🌍 Localization & Internationalization

- Accepts `preferredLanguages` query parameter (e.g. `en,fr,ja,hi`)
- Automatic fallback to the best available translation
- Consistent localization across cities, countries, and regions

---

## 📦 API Style & Format

- RESTful, **read-only** API
- JSON responses
- OpenAPI 3.0 / Swagger-documented
- Stable, predictable schemas
- UUID-based entity identifiers
- Designed for high-performance querying and caching

---

## 🧑‍💻 Ideal Use Cases

- Location-based search and discovery
- Mapping and GIS applications
- Travel, tourism, and logistics platforms
- Data enrichment for analytics and ML pipelines
- Autocomplete and geocoding features
- Internationalized apps needing reliable geo metadata

---

## 📘 Documentation

- Fully documented with Swagger / OpenAPI
- Clear request and response schemas
- Self-describing endpoints for rapid integration

---

## 🚀 Summary

**Geomelon API** offers a comprehensive, multilingual, and developer-friendly way to work with global geographic data.  
If you need **accurate cities, countries, regions, distances, and translations**—all in one clean API—Geomelon is built for you.

## Languages
 |                          name                          | iso code | cities count 
 |--------------------------------------------------------|----------|--------------
 | English                                                | en       |       972660
 | Chinese                                                | zh       |       708095
 | Dutch                                                  | nl       |       641067
 | Spanish                                                | es       |       386729
 | French                                                 | fr       |       386725
 | German                                                 | de       |       274317
 | Polish                                                 | pl       |       271927
 | Chechen                                                | ce       |       263639
 | Turkish                                                | tr       |       252088
 | Swedish                                                | sv       |       248244
 | Serbian                                                | sr       |       247840
 | Tatar                                                  | tt       |       225690
 | Irish                                                  | ga       |       220921
 | Serbo-Croatian                                         | sh       |       207479
 | Portuguese                                             | pt       |       201865
 | Bokmål                                                 | nb       |       195547
 | Ukrainian                                              | uk       |       184518
 | Italian                                                | it       |       183832
 | Russian                                                | ru       |       170050
 | Indonesian                                             | id       |       168084
 | Nynorsk                                                | nn       |       166730
 | Czech                                                  | cs       |       166222
 | Persian                                                | fa       |       161291
 | Arabic                                                 | ar       |       159230
 | Romanian                                               | ro       |       153656
 | Malay                                                  | ms       |       144800
 | Catalan                                                | ca       |       142003
 | Finnish                                                | fi       |       128732
 | Basque                                                 | eu       |       126466
 | Danish                                                 | da       |       124127
 | Slovene                                                | sl       |       105178
 | Slovak                                                 | sk       |        98387
 | Vietnamese                                             | vi       |        96144
 | Occitan                                                | oc       |        75838
 | Japanese                                               | ja       |        73285
 | Tagalog                                                | tl       |        66680
 | Bangla                                                 | bn       |        66638
 | Uzbek                                                  | uz       |        66214
 | Galician                                               | gl       |        61933
 | Hungarian                                              | hu       |        55853
 | Lithuanian                                             | lt       |        48272
 | Hindi                                                  | hi       |        48070
 | Welsh                                                  | cy       |        48048
 | Modern Greek                                           | el       |        47780
 | Georgian                                               | ka       |        46271
 | Armenian                                               | hy       |        45436
 | Urdu                                                   | ur       |        43751
 | Telugu                                                 | te       |        41619
 | Albanian                                               | sq       |        41411
 | Croatian                                               | hr       |        40964
 | Volapük                                                | vo       |        40236
 | Bulgarian                                              | bg       |        39928
 | Esperanto                                              | eo       |        35325
 | Burmese                                                | my       |        35206
 | Belarusian                                             | be       |        34125
 | Yoruba                                                 | yo       |        31440
 | Javanese                                               | jv       |        31025
 | Estonian                                               | et       |        30747
 | Gujarati                                               | gu       |        29622
 | Haitian Creole                                         | ht       |        29294
 | Kazakh                                                 | kk       |        28714
 | Malagasy                                               | mg       |        27926
 | Tajik                                                  | tg       |        27539
 | Sundanese                                              | su       |        27342
 | Ido                                                    | io       |        26292
 | Latvian                                                | lv       |        25371
 | Azerbaijani                                            | az       |        23344
 | Hebrew                                                 | he       |        21787
 | Korean                                                 | ko       |        20930
 | Swahili                                                | sw       |        17893
 | Tamil                                                  | ta       |        17497
 | Kurdish                                                | ku       |        15750
 | Afrikaans                                              | af       |        15474
 | Luxembourgish                                          | lb       |        15028
 | Breton                                                 | br       |        14865
 | Bosnian                                                | bs       |        14614
 | Kyrgyz                                                 | ky       |        13876
 | Zulu                                                   | zu       |        13519
 | Macedonian                                             | mk       |        13405
 | Aragonese                                              | an       |        13082
 | Scottish Gaelic                                        | gd       |        13037
 | Kongo                                                  | kg       |        12162
 | Kannada                                                | kn       |        11976
 | Corsican                                               | co       |        11822
 | Romansh                                                | rm       |        11404
 | Sardinian                                              | sc       |        11333
 | Icelandic                                              | is       |        11120
 | Interlingua                                            | ia       |        10517
 | Interlingue                                            | ie       |        10364
 | Walloon                                                | wa       |        10197
 | Thai                                                   | th       |        10087
 | Wolof                                                  | wo       |         9408
 | Punjabi                                                | pa       |         8940
 | Marathi                                                | mr       |         8736
 | Latin                                                  | la       |         8568
 | Malayalam                                              | ml       |         7453
 | Limburgish                                             | li       |         7315
 | Sinhala                                                | si       |         7031
 | Hausa                                                  | ha       |         7011
 | Ossetian                                               | os       |         5849
 | Māori                                                  | mi       |         5571
 | Chuvash                                                | cv       |         4510
 | Igbo                                                   | ig       |         4491
 | Bashkir                                                | ba       |         4369
 | Cornish                                                | kw       |         4156
 | West Frisian                                           | fy       |         3317
 | Samoan                                                 | sm       |         3120
 | Nepali                                                 | ne       |         2922
 | Greenlandic                                            | kl       |         2646
 | ... | ... | ...

## 📄 Data Source & Licensing

This API uses data derived from **Wikidata**.

- **Source:** Wikidata (https://www.wikidata.org)
- **License:** Creative Commons CC0 1.0 Universal (Public Domain)
- **Attribution:** Data originates from Wikidata contributors
- **Disclaimer:** This project is not affiliated with, endorsed by, or sponsored by the Wikimedia Foundation

Wikidata data is provided "as is" without warranty of any kind.
