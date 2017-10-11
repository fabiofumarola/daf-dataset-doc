# Comune di Milano: Iscritti scuole d'infanzia

## Descrizione del dataset
Numero di iscritti a scuole d'infanzia per civico

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** GEOJSON

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
|IDCIVICO|Testo|identificativo civico
|CODVIA|Numerico|codice via
|NUMCIV|Numerico
|BARRATO|Testo
|CODSEDE|Numerico|codice sede scuola d'infanzia
|TOTISCRITT|Numerico|numero iscritti alla scuola d'infanzia per civico di residenza

## Esempio del flusso

```
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          1515499.6034500245,
          5034753.091524641
        ]
      },
      "properties": {
        "IDCIVICO": "0097001",
        "CODVIA": 97,
        "NUMCIV": 1,
        "BARRATO": "",
        "CODSEDE": 1011,
        "TOTISCRITT": 1
      }
    },
  ...]
}
```

