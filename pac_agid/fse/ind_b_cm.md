# AGID FSE: Monitoraggio indicatore Utilizzo per Cittadini e Medici

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
| m_data_aggiornamento | date | |
| f1_c_valore_f2_m_num_tot | | |
| f1_c_num_tot | | |
| f2_c_valore | | |
| f2_c_num_tot | | |
| f1_m_valore | | |
| f1_m_num_tot | | |
| f2_m_valore | | |
| trimestre | int | trimestre di riferimento |
| anno | int | anno di riferimento |
| valido_al | date | |
| c_data_aggiornamento | date | |

## Esempio del flusso

```
[
  {
    "id": 14,
    "paid": 8,
    "c_data_aggiornamento": "2016-06-30",
    "f1_c_valore_f2_m_num_tot": 31168,
    "f1_c_num_tot": 1575211,
    "f2_c_valore": 7435,
    "f2_c_num_tot": 12163,
    "trimestre": 1,
    "anno": 2016,
    "valido_al": "2016-06-30",
    "f1_m_valore": 124,
    "f1_m_num_tot": 1328,
    "f2_m_valore": 5000,
    "m_data_aggiornamento": "2016-06-30",
    "pa": "Regione Liguria"
  },
  {
    "id": 15,
    "paid": 2,
    "c_data_aggiornamento": "2016-06-30",
    "f1_c_valore_f2_m_num_tot": 40,
    "f1_c_num_tot": 576619,
    "f2_c_valore": null,
    "f2_c_num_tot": null,
    "trimestre": 1,
    "anno": 2016,
    "valido_al": "2016-06-30",
    "f1_m_valore": 10,
    "f1_m_num_tot": 477,
    "f2_m_valore": null,
    "m_data_aggiornamento": "2016-06-30",
    "pa": "Regione Basilicata"
  },
  ...
]
```

