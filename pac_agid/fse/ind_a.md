# AGID FSE: Monitoraggio indicatore Attuazione

## Descrizione del dataset


**Tipo di dataset:** ordinary

**Tipo di flusso:** batch

**Tipo di file:** JSON

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP

**Note**: per ora questi sono dati di test


## Elementi
| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| id | long | id del record |
| paid | int | identificativo interno della PA di appartenenza |
| pa | string | denominazione della PA di appartenenza |
| data_inizio_lavori | date | |
| data_fine_lavori | date | |
| data_aggiornamento | date | |
| percentuale | float | |
| f1_data_inizio_lavori | date | |
| f1_data_fine_lavori | date | |
| f1_percentuale | float | |
| f1_note | string | |
| f2_data_inizio_lavori | date | |
| f2_data_fine_lavori | date | |
| f2_percentuale | float | |
| f2_note | string | |
| f3_data_inizio_lavori | date | |
| f3_data_fine_lavori | date | |
| f3_percentuale | float | |
| f3_note | string | |
| f4_data_inizio_lavori | date | |
| f4_data_fine_lavori | date | |
| f4_percentuale | float | |
| f4_note | string | |
| f5_data_inizio_lavori | date | |
| f5_data_fine_lavori | date | |
| f5_percentuale | float | |
| f5_note | string | |
| f6_data_inizio_lavori | date | |
| f6_data_fine_lavori | date | |
| f6_percentuale | float | |
| f6_note | string | |
| f7_data_inizio_lavori | date | |
| f7_data_fine_lavori | date | |
| f7_percentuale | float | |
| f7_note | string | |



## Esempio del flusso

```
[
  {
    "id": 24,
    "paid": 20,
    "data_inizio_lavori": "2014-01-01",
    "data_fine_lavori": "2017-12-31",
    "data_aggiornamento": "2016-10-26",
    "percentuale": 78,
    "f1_data_inizio_lavori": "2014-01-01",
    "f1_data_fine_lavori": "2017-12-31",
    "f1_percentuale": 87,
    "f1_note": "Da perfezionare l'anagrafe degli operatori sanitari e delle strutture accreditate",
    "f2_data_inizio_lavori": "2014-01-01",
    "f2_data_fine_lavori": "2017-12-31",
    "f2_percentuale": 82,
    "f2_note": "Da completare la gestione del consenso specifico e dei meccanismi di oscuramento dei documenti contenuti nel FSE. Da integrare i meccanismi di autenticazione forte previsti da SPID",
    "f3_data_inizio_lavori": "2014-01-01",
    "f3_data_fine_lavori": "2017-12-31",
    "f3_percentuale": 90,
    "f3_note": "Da integrare i meccanismi di autenticazione via carta operatore",
    "f4_data_inizio_lavori": "2014-01-01",
    "f4_data_fine_lavori": "2017-12-31",
    "f4_percentuale": 90,
    "f4_note": "Da integrare i meccanismi di autenticazione via carta operatore",
    "f5_data_inizio_lavori": "2014-01-01",
    "f5_data_fine_lavori": "2017-12-31",
    "f5_percentuale": 50,
    "f5_note": "In fase di implementazione mediante il riuso dell'infrastruttura di interoperabilità adottata dalla Regione Veneto",
    "f6_data_inizio_lavori": "2014-01-01",
    "f6_data_fine_lavori": "2017-12-31",
    "f6_percentuale": 99,
    "f6_note": null,
    "f7_data_inizio_lavori": "2014-01-01",
    "f7_data_fine_lavori": "2017-12-31",
    "f7_percentuale": 50,
    "f7_note": "La funzionalità informatica è stata completata e testata su circa 800 assistiti. E' in fase di estensione alla popolazione residente in Provincia autonoma di Trento",
    "pa": "Provincia Autonoma di Trento"
  },
  ...
]
```

