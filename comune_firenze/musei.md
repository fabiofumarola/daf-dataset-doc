# Comune Firenze: Musei

## Descrizione del dataset

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** GEOJSON

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP ogni giorno


## Elementi



## Esempio del flusso

```
{
  "type": "FeatureCollection",
  "totalFeatures": 97,
  "features": [
    {
      "type": "Feature",
      "id": "musei.1",
      "geometry": {
        "type": "Point",
        "coordinates": [
          1681474.224,
          4849348.769
        ]
      },
      "geometry_name": "SHAPE",
      "properties": {
        "ID": 1,
        "IDOBJSTAT": 1,
        "NOME": "BASILICA DI SAN LORENZO",
        "ETICHETTA": "BASILICA DI SAN LORENZO",
        "INDIRIZZO": "Piazza di San Lorenzo",
        "CIVICO": "1",
        "TELEFONO": "055 2140542",
        "TIPO": "Chiesa",
        "FIRENZE_CARD": "NO",
        "LINK": "www.operamedicealaurenziana.it"
      }
    },

    ...
  ],
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::3003"
    }
  }
```

