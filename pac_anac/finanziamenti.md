# ANAC: Finanziamenti

## Descrizione del dataset



**Tipo di dataset:** standard/ordinary?

**Tipo di flusso:** batch

**Tipo di file:** CSV

**Scheda:** [struttura data lake](resources/ANAC_UPSI_StrutturaDataLakeANAC_V1.pdf)

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| CODICE_SISTEMA | VARCHAR |
| CODICE_TRACCIATO | VARCHAR |
| ID_FINANZIAMENTO | |
| CIG  | |
| FONDI_BILANCIO_SA | |
| FONDI_AMMINISTRAZIONE_COMPETENTE | |
| ENTRATE_VINCOLATE_EU | |
| ENTRATE_VINCOLATE_NAZIONALE | |
| ENTRATE_VINCOLATE_REGIONALE | |
| ENTRATE_VINCOLATE_LOCALE | |
| ENTRATE_VINCOLATE_ALTRI_PUBBLICI| |
| ENTRATE_VINCOLATE_PRIVATI | |
| MUTUO | |
| TRASFERIMENTO_IMMOBILI | |
| ECONOMIA | |
| APPORTO_CAPITALI_PRIVATI | |
| SFRUTTAMENTO_ECONOMICO_FINANZIARIO_DEL_BENE | |
| ALTRO | |
| NON_DISPONIBILE
| OPERAZIONE
| DATA_INSERIMENTO
| DATA_FINE
| BATCH_ID

## Esempio del flusso

```
ANAC,AN6,125343,1200000140,NULL,NULL,NULL,NULL,232931.3248,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,L,2017-07-18 20:26:46.0,2099-12-31 00:00:00.0,1
ANAC,AN6,198717,4200000009,NULL,NULL,NULL,NULL,NULL,242735.74,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,L,2017-07-18 20:26:46.0,2099-12-31 00:00:00.0,1
ANAC,AN6,198720,4200000020,NULL,NULL,NULL,NULL,NULL,6992827.41,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,L,2017-07-18 20:26:46.0,2099-12-31 00:00:00.0,1
ANAC,AN6,198723,4200000036,NULL,NULL,NULL,NULL,NULL,619749.28,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,L,2017-07-18 20:26:46.0,2099-12-31 00:00:00.0,1
ANAC,AN6,198726,4200000052,NULL,NULL,NULL,NULL,1293375.37,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,L,2017-07-18 20:26:46.0,2099-12-31 00:00:00.0,1
ANAC,AN6,198729,4200000076,NULL,NULL,NULL,NULL,NULL,149590.54,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,L,2017-07-18 20:26:46.0,2099-12-31 00:00:00.0,1
ANAC,AN6,198732,4200000089,NULL,NULL,NULL,NULL,NULL,570685.87,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,L,2017-07-18 20:26:46.0,2099-12-31 00:00:00.0,1
ANAC,AN6,198735,4200000093,NULL,NULL,NULL,NULL,NULL,337804.1,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,L,2017-07-18 20:26:46.0,2099-12-31 00:00:00.0,1

```

