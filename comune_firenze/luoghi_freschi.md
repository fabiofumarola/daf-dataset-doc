# Comune Firenze: Luoghi freschi

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
  "totalFeatures": 16,
  "features": [
    {
      "type": "Feature",
      "id": "luoghi_freschi_fi.7",
      "geometry": {
        "type": "Point",
        "coordinates": [
          1684550.3791,
          4847836.618
        ]
      },
      "geometry_name": "shape",
      "properties": {
        "id": 7,
        "nome": "Centro anziani \"LiberetÃ  Reims\"",
        "indirizzo": "Via Reims,  22",
        "telefono": "055 689843",
        "orario": "TUTTI I GIORNI  dalle 15.00-18.30",
        "note": "chiusura 15 Agosto"
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

