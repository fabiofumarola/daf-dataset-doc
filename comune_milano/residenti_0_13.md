# Comune di Milano: Residenti 0-13

## Descrizione del dataset
Residenti per civico per classi d'età scolare

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** GEOJSON

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
|IDCIVICO|string|identificativo civico
|_00_02|int|residenti per civico di età compresa fra 0 e 2 anni
|_03_05|int|residenti per civico di età compresa fra 3 e 5 anni
|_06_10|int|residenti per civico di età compresa fra 6 e 10 anni
|_11_13|int|residenti per civico di età compresa fra 11 e 13 anni
|13|int|residenti per civico di età compresa tra 14 e 18 anni

## Esempio del flusso

```
{
  "type": "FeatureCollection",
  "crs": {
    "type": "name",
    "properties": {
      "name": "urn:ogc:def:crs:EPSG::3003"
    }
  },
  "features": [
    {
      "type": "Feature",
      "properties": {
        "13": 2,
        "IDCIVICO": "0001014",
        "_00_02": 0,
        "_03_05": 0,
        "_06_10": 2,
        "_11_13": 0
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          1514996.8485003,
          5034477.716552178
        ]
      }
    },
  ...]
}
```

