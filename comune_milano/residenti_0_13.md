# Comune di Milano: Asili nido

## Descrizione del dataset

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** GEOJSON

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| IDSTRUTTUR | Testo | identificativo univoco struttura |
| SEDE | Numerico | identificativo univoco della sede |
| NOMINATIVO | Testo | denominazione della struttura |
| INDIRIZZO | Testo |  indirizzo completo (tipo via, via, civico) |
| TIPO_STRUT | Testo | tipologia di gestione |
| TELEFONO | Testo | numero telefonico |
| MODALITA | Testo | modalità di erogazione del servizio (classi) |
| CLASSEETA | Testo | tipologia di sezione per età |
| UNITAEDUCA | Testo | denominazione dell'unità educativa |
| DIREZIONET | Testo |  direzione educativa territoriale di appartenenza |
| ZONA | Testo | zona (ora municipio) di appartenenza |
| X | Numerico | coordinate WGS84 |
| Y | Numerico | coordinate WGS84 |
| CATEGORIA | Testo | categoria da PGT (vuoto) |
| TIPOLOGIA | Testo | tipologia da PGT (vuoto) |
| SOTTOTIPO | Testo | tipologia da PGT (vuoto) |

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
        "IDSTRUTTUR": "39499",
        "SEDE": 632,
        "NOMINATIVO": "SS. TRINITA', 5 (MICRONIDO)",
        "INDIRIZZO": "SS. TRINITA', 5 (MICRONIDO)",
        "TIPO_STRUT": "APPALTATO",
        "TELEFONO": "tel. D.D. 02/3494449 -",
        "MODALITA": "MICRO NIDO",
        "CLASSEETA": "MEDIO/GRANDI",
        "UNITAEDUCA": "1A",
        "DIREZIONET": "1",
        "ZONA": "1",
        "X": 1513886.42681,
        "Y": 5036200.8567,
        "CATEGORIA": null,
        "TIPOLOGIA": null,
        "SOTTOTIPO": null
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          1513886.42681,
          5036200.8567
        ]
      }
    },
    
  ...]
}
```

