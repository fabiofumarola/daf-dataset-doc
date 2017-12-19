# Comune di Milano: Grafo stradale

## Descrizione del dataset

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** GEOJSON

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| OBJECTID | int | identificativo |
| ID | long | |
| FEATTYP | | |
| FT | | |
| F_JNCTID | | nodo iniziale di un tronco stradale |
| F_JNCTTYP | | |
| T_JNCTID | | nodo finale di un tronco stradale |
| T_JNCTTYP | | |
| PJ | | |
| METERS | | |
| FRC | | |
| NETCLASS | | |
| NETBCLASS | | |
| NET2CLASS | | |
| NAME | string | nome della strada |
| NAMELC | | |
| SOL | | |
| NAMETYP | | |
| CHARGE | | |
| SHIELDNUM | | |
| RTETYP | | |
| RTEDIR | | |
| RTEDIRVD | | |
| PROCSTAT | | |
| FOW | | |
| SLIPRD | | |
| FREEWAY | | |
| BACKRD | | |
| TOLLRD | | |
| RDCOND | | |
| STUBBLE | | |
| PRIVATERD | | |
| CONSTATUS | | |
| ONEWAY | | |
| F_BP | | |
| T_BP | | |
| F_ELEV | | |
| T_ELEV | | |
| KPH | | |
| POSACCUR | | |
| CARRIAGE | | |
| LANES | | |
| RAMP | | |
| ADAS | | |
| TRANS | | |
| DYNSPEED | | |
| SPEEDCAT | | |
| NTHRUTRAF | | |
| ROUGHRD | | |
| PARTSTRUC | | |
| MINUTES | | |
| Shape_Leng | | |

## Esempio del flusso

```
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "LineString",
        "coordinates": [
          [
            1508293.8667217083,
            5032761.0475349
          ],
          [
            1508293.8002457432,
            5032761.440713674
          ],
          [
            1508294.7334606443,
            5032762.961002955
          ]
        ]
      },
      "properties": {
        "OBJECTID": 1,
        "ID": 113800020018000,
        "FEATTYP": 4110,
        "FT": 0,
        "F_JNCTID": 113800200335000,
        "F_JNCTTYP": 0,
        "T_JNCTID": 113800200306000,
        "T_JNCTTYP": 0,
        "PJ": 0,
        "METERS": 82.7,
        "FRC": 6,
        "NETCLASS": 0,
        "NETBCLASS": 0,
        "NET2CLASS": 4,
        "NAME": "Via Cristoforo Colombo",
        "NAMELC": "ITA",
        "SOL": 0,
        "NAMETYP": 17,
        "CHARGE": "",
        "SHIELDNUM": "",
        "RTETYP": 0,
        "RTEDIR": "",
        "RTEDIRVD": "",
        "PROCSTAT": 1,
        "FOW": 3,
        "SLIPRD": 0,
        "FREEWAY": 0,
        "BACKRD": 0,
        "TOLLRD": "",
        "RDCOND": 1,
        "STUBBLE": 0,
        "PRIVATERD": 0,
        "CONSTATUS": "",
        "ONEWAY": "",
        "F_BP": 0,
        "T_BP": 0,
        "F_ELEV": 0,
        "T_ELEV": 0,
        "KPH": 35,
        "POSACCUR": 0,
        "CARRIAGE": "",
        "LANES": 0,
        "RAMP": 0,
        "ADAS": 0,
        "TRANS": 0,
        "DYNSPEED": 0,
        "SPEEDCAT": 6,
        "NTHRUTRAF": 0,
        "ROUGHRD": 0,
        "PARTSTRUC": 0,
        "MINUTES": 0.142,
        "Shape_Leng": 2.18262248529
      }
    },
  ...]
}
```

