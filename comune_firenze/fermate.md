# Comune Firenze: Fermate TPL

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
  "totalFeatures": 2249,
  "features": [
    {
      "type": "Feature",
      "id": "traspubbloc_fermate.fid--9b2e259_15dc89a2829_6efc",
      "geometry": {
        "type": "Point",
        "coordinates": [
          11.255805,
          43.779178
        ]
      },
      "geometry_name": "geom",
      "properties": {
        "id_fermata": "700002",
        "codice_fermata": "FM0002",
        "nome_fermata": "SAN ZANOBI",
        "tipo": null,
        "linee": "14B, 6B, 17C, 17B, 14CB, 11, 23N, 14C, 6A, 1, 23, 6L",
        "id_linee": "1&10&16&3&36&9"
      }
    },

    ...
  ],
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::4326"
    }
  }
```

