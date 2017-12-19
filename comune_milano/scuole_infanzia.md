# Comune di Milano: Asili nido

## Descrizione del dataset
Scuole infanzia

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** GEOJSON

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| TEL_POLO | string | |
| COD_VIA| | |
| CIVICO | string | |
| BARRATO| string | |
| X | | |
| Y | | |
| DENOMINAZ| string | |
| CATEGORIA| string | |
| TIPOLOGIANFANZIA | string | |
| SOTTOTIPONFANZIA | string | |
| TIPO_U | string | |
| MATRICECI ESISTENTI| string | |
| PROPRIETANO| string | |
| TIPO_PROP| string | |
| GESTORENO| string | |
| TIPO_GEST| string | |
| RAPPORTOTA | string | |
| STATO | string | |
| CAP_MAX| | |
| NUM_ISCR | | |
| NUM_FREQ | | |
| NUM_NAMM | | |
| DISABILI | | |
| NUM_AULE | | |
| SUP_A_DID| | |
| SUP_A_TEC| | |
| SUP_A_VAN| | |
| SUP_FOND | | |
| SUP_COP| | |
| SLP | | |
| PIANI | | |
| MENSA | | |
| STAT_MAN | | |
| TIPO_EDIF| | |
| GIARDINO | | |
| GIOCHI_E | | |
| STAT_EXT | | |
| COD_SEDE | | |
| COD_POLO | | |
| AUTONOMIA| | |
| SEDE_AUTO| string | |
| DIRIGENTE| | |
| PERS_AUX | | |
| EDU_COM| | |
| PERS_EXT | | |
| PARK_ADD | | |
| PARK_UT| | |
| MULTIFUNZ| | |
| COMPLESSO| | |
| COST_P | | |
| TEL_DIR| | |
| TEL_SEGR | string | |
| FAX | | |
| MAIL | | |
| WWW | | |
| INFO | | |
| INDIRIZZO| string | |
| COMBO | string | |
| ISCR_S | | |
| ISCR_P | | |
| POSIZGIURI | string | |

## Esempio del flusso

```
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "TEL_POLO": "028356078",
        "COD_VIA": 5182,
        "CIVICO": "21",
        "BARRATO": null,
        "X": 1513946.325,
        "Y": 5033472.879,
        "DENOMINAZ": "COMUNALE",
        "CATEGORIA": "ISTRUZIONE",
        "TIPOLOGIA": "SCUOLE PER L'INFANZIA",
        "SOTTOTIPO": "SCUOLE PER L'INFANZIA",
        "TIPO_U": "MINORI",
        "MATRICE": "SERVIZI PUBBLICI ESISTENTI",
        "PROPRIETA": "COMUNE DI MILANO",
        "TIPO_PROP": "COMUNALE",
        "GESTORE": "COMUNE DI MILANO",
        "TIPO_GEST": "PUBBLICA",
        "RAPPORTO": "GESTIONE DIRETTA",
        "STATO": "IN ESERCIZIO",
        "CAP_MAX": 0,
        "NUM_ISCR": 0,
        "NUM_FREQ": 0,
        "NUM_NAMM": 0,
        "DISABILI": null,
        "NUM_AULE": 0,
        "SUP_A_DID": 0,
        "SUP_A_TEC": 0,
        "SUP_A_VAN": 0,
        "SUP_FOND": 0,
        "SUP_COP": 0,
        "SLP": 0,
        "PIANI": 1,
        "MENSA": null,
        "STAT_MAN": null,
        "TIPO_EDIF": null,
        "GIARDINO": null,
        "GIOCHI_E": null,
        "STAT_EXT": null,
        "COD_SEDE": 1007,
        "COD_POLO": 0,
        "AUTONOMIA": null,
        "SEDE_AUTO": "VIA ARENA 21",
        "DIRIGENTE": null,
        "PERS_AUX": 2,
        "EDU_COM": 0,
        "PERS_EXT": 0,
        "PARK_ADD": 0,
        "PARK_UT": 0,
        "MULTIFUNZ": null,
        "COMPLESSO": null,
        "COST_P": 0,
        "TEL_DIR": null,
        "TEL_SEGR": "028645342",
        "FAX": null,
        "MAIL": null,
        "WWW": null,
        "INFO": null,
        "INDIRIZZO": "VIA ARENA 21",
        "COMBO": "5182 21",
        "ISCR_S": 6,
        "ISCR_P": 6,
        "POSIZGIURI": "PARITARIE"
      },
    
  ...]
}
```

