# Comune Firenze: Colonnine di ricarica

## Descrizione del dataset

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** GEOJSON

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP ogni 15 minuti


## Elementi



## Esempio del flusso

```
{
  "type": "FeatureCollection",
  "totalFeatures": 173,
  "features": [
    {
      "type": "Feature",
      "id": "colonnine_enel.fid--9b2e259_15dcc397ee8_-1a17",
      "geometry": {
        "type": "Point",
        "coordinates": [
          1681384.67735093,
          4849058.33609654
        ]
      },
      "geometry_name": "geom",
      "properties": {
        "serial_number": "16ZP22T2AA1S000003",
        "cucode": "CFirenze_00000221",
        "indirizzo": "Via Del Campidoglio, 2",
        "citta": "FIRENZE",
        "postal_code": "50100",
        "regione": "Toscana",
        "cpid": "6034",
        "stato": "ACTIVE",
        "stato_ricarica": "FINISHED",
        "maxcurrent": "10.0",
        "maxpower": "2300.0",
        "mincurrent": "10.0",
        "plug": "10",
        "plug_id": "2"
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

