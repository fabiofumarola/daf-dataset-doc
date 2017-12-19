# AGID FSE: Monitoraggio indicatore Utilizzo per Aziende Sanitarie

## Descrizione del dataset


**Tipo di dataset:** ordinary

**Tipo di flusso:** batch

**Tipo di file:** JSON

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi
| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| id | long | id del record |
| paid | int | identificativo interno della PA di appartenenza |
| pa | string | denominazione della PA di appartenenza |
| data_aggiornamento | date | |
| trimestre | int | trimestre di riferimento |
| anno | int | anno di riferimento |
| valido_al | date | |
| indicatore_dati | Array | |
| indicatore_dati.id | long | id del record |
| indicatore_dati.paid | int | identificativo interno della PA (regione) di appartenenza |
| indicatore_dati. monitoraggio_indicatore_b_aziende_sanitarie_id | |
| indicatore_dati.f1_valore | int | |
| indicatore_dati.f1_num_tot | int | |
| indicatore_dati.f2_valore | int | |
| indicatore_dati.f2_num_tot | int | |
| indicatore_dati.aziende_sanitarie_id | long | identificativo dell'azienda sanitaria |
| indicatore_dati.pa | string | denominazione dell'azienda sanitaria |

## Esempio del flusso

```
[
  {
    "id": 49,
    "paid": 14,
    "data_aggiornamento": "2016-10-26",
    "trimestre": 1,
    "anno": 2016,
    "valido_al": "2016-04-30",
    "pa": "Regione Sardegna",
    "indicatore_dati": [
      {
        "id": 1227,
        "paid": 14,
        "monitoraggio_indicatore_b_aziende_sanitarie_id": 49,
        "f1_valore": 0,
        "f1_num_tot": 864,
        "f2_valore": 0,
        "f2_num_tot": 1,
        "aziende_sanitarie_id": 1414,
        "pa": "AZIENDA OSPEDALIERA G.BROTZU"
      },
      {
        "id": 1228,
        "paid": 14,
        "monitoraggio_indicatore_b_aziende_sanitarie_id": 49,
        "f1_valore": 0,
        "f1_num_tot": 558,
        "f2_valore": 0,
        "f2_num_tot": 1,
        "aziende_sanitarie_id": 1416,
        "pa": "AZIENDA OSPEDALIERO UNIVERSITARIA CAGLIARI"
      },
      ...
  },
  ...
]
```

