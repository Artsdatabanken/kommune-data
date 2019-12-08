# kommune-lastejobb

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md#pull-requests)

Egenskaper til Norske fylker og kommuner.

## Komponenter og dataflyt

### Dataflyt

[![Dataflyt](https://github.com/Artsdatabanken/naturvern-lastejobb/raw/master/doc/dataflyt.png)](https://artsdatabanken.github.io/naturvern-lastejobb/)

### Tegnforklaring

| Symbol                                                                                                   | Forklaring               |
| -------------------------------------------------------------------------------------------------------- | ------------------------ |
| ![Dataflyt](https://github.com/Artsdatabanken/nin-arkitektur-dokumentasjon/raw/master/image/api_24.png)  | API (HTTP REST)          |
| ![Dataflyt](https://github.com/Artsdatabanken/nin-arkitektur-dokumentasjon/raw/master/image/data_24.png) | Åpne data                |
| ![Dataflyt](https://github.com/Artsdatabanken/nin-arkitektur-dokumentasjon/raw/master/image/kart_24.png) | Kart                     |
| ![Dataflyt](https://github.com/Artsdatabanken/nin-arkitektur-dokumentasjon/raw/master/image/last_24.png) | Lastejobb / Konvertering |
| ![Dataflyt](https://github.com/Artsdatabanken/nin-arkitektur-dokumentasjon/raw/master/image/lib_24.png)  | Bibliotek                |
| ![Dataflyt](https://github.com/Artsdatabanken/nin-arkitektur-dokumentasjon/raw/master/image/tool_24.png) | Verktøy                  |
| ![Dataflyt](https://github.com/Artsdatabanken/nin-arkitektur-dokumentasjon/raw/master/image/www_24.png)  | Web-side/applikasjon     |

### Datakilder (takk til)

- [Kartverket](https://kartkatalog.geonorge.no/metadata/kartverket/administrative-enheter-kommuner/041f1e6e-bdbc-4091-b48f-8a5990f3cc5b)
- [Statistisk sentralbyrå](https://ssb.no)
- [Wikipedia](https://no.wikipedia.org)

### Lastejobb

- [kommune-lastejobb](https://github.com/Artsdatabanken/kommune-lastejobb)

### Leses av

- [nin-data-lastejobb](https://github.com/Artsdatabanken/nin-data-lastejobb)

### Bruk i sluttprodukter

- [Natur i Norge kart](https://github.com/Artsdatabanken/nin-kart-frontend)
- [Artsdatabanken åpne data](https://data.artsdatabanken.no/)

## Om datasettet

### Kommune

```json
{
  "item": "http://www.wikidata.org/entity/Q2415",
  "article": "https://no.wikipedia.org/wiki/Kristiansand",
  "url": "http://www.kristiansand.kommune.no/",
  "coa": "http://commons.wikimedia.org/wiki/Special:FilePath/Kristiansand%20komm.svg",
  "itemLabel": "Kristiansand",
  "code": "1001",
  "naboer": ["0926", "0928", "1014", "1017", "1018"],
  "images": [
    "http://commons.wikimedia.org/wiki/Special:FilePath/Kristiansand%2C%20Norway.jpg"
  ],
  "banners": [
    "http://commons.wikimedia.org/wiki/Special:FilePath/Bannerkristiansand.JPG"
  ]
}
```

### Fylke

```json
{
  "item": "http://www.wikidata.org/entity/Q585",
  "article": "https://no.wikipedia.org/wiki/Oslo",
  "code": "NO-03",
  "url": "http://www.oslo.kommune.no/",
  "coa": "http://commons.wikimedia.org/wiki/Special:FilePath/Oslo%20komm.svg",
  "banner": "http://commons.wikimedia.org/wiki/Special:FilePath/Oslo%20banner%20Akershus%20castle.jpg",
  "osm": "2775550",
  "inception": "1048-01-01T00:00:00.000Z",
  "elevation": 23,
  "flag": "http://commons.wikimedia.org/wiki/Special:FilePath/Flag%20of%20Oslo.svg",
  "itemLabel": "Oslo",
  "naboer": ["NO-02", "NO-05", "NO-06"],
  "images": [
    "http://commons.wikimedia.org/wiki/Special:FilePath/Oslo%20city%20in%2010%20images.jpg"
  ],
  "banners": [
    "http://commons.wikimedia.org/wiki/Special:FilePath/Oslo%20banner%20Akershus%20castle.jpg"
  ]
}
```
