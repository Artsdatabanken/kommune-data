[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md#pull-requests)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

Utdata fra lastejobb for Norske fylker og kommuner ikke inklusive kartdata.

## Kilde og bruk
### Dataene brukes blant annet av

* [Natur i Norge kart](https://github.com/Artsdatabanken/nin-kart-frontend)
* [Artsdatabanken åpne data](https://data.artsdatabanken.no/)
* [Egenskapsdata lastejobb](https://github.com/Artsdatabanken/nin-egenskapsdata-lastejobb-kverna)

### Baserer seg på åpne data fra (takk til)

* [Statistisk sentralbyrå](https://ssb.no)
* [Wikipedia](https://no.wikipedia.org)

### Bygges av

* [kommune-lastejobb](https://github.com/Artsdatabanken/kommune-lastejobb) (lastejobb)

## Om datasettet

Eksempel på innhold i utdata

### Kommune
```json
{
  "1001": {
    "wikidata": "http://www.wikidata.org/entity/Q2415",
    "bilde": {
      "image": [
        "http://commons.wikimedia.org/wiki/Special:FilePath/Kristiansand%2C%20Norway.jpg"
      ],
      "banner": [
        "http://commons.wikimedia.org/wiki/Special:FilePath/Bannerkristiansand.JPG"
      ],
      "coa": "http://commons.wikimedia.org/wiki/Special:FilePath/Kristiansand%20komm.svg"
    },
    "label": "Kristiansand",
    "wikipedia": "https://no.wikipedia.org/wiki/Kristiansand",
    "url": "http://www.kristiansand.kommune.no/",
    "naboer": ["0928", "0926", "1014", "1018", "1017"]
  }
}
```

### Fylke

```json
{
  "NO-03": {
    "wikidata": "http://www.wikidata.org/entity/Q585",
    "bilde": {
      "image": [
        "http://commons.wikimedia.org/wiki/Special:FilePath/Oslo%20city%20in%2010%20images.jpg"
      ],
      "banner": [
        "http://commons.wikimedia.org/wiki/Special:FilePath/Oslo%20banner%20Akershus%20castle.jpg"
      ],
      "coa": "http://commons.wikimedia.org/wiki/Special:FilePath/Oslo%20komm.svg"
    },
    "label": "Oslo",
    "inception": "1048-01-01T00:00:00.000Z",
    "wikipedia": "https://no.wikipedia.org/wiki/Oslo",
    "elevation": "23",
    "url": "http://www.oslo.kommune.no/",
    "naboer": ["NO-02", "NO-05", "NO-06"]
  }
}
```

