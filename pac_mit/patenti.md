# Ministero Infrastrutture e Trasporti: Patenti

## Descrizione del dataset

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** CSV

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| id | number | progressivo numerico del record |
| progressivo posizione anagrafica | number | progressivo record proprietario |
| codice fiscale | string | codice fiscale o partita IVA del proprietario |
| data_nascita | number | anno di nascita del proprietario della patente |
| provincia_residenza | string | provincia di residenza del proprietario della patente |
| comune residenza | string | comune di residenza del proprietario della patente |
| stato_estero_nascita | string | stato estero di nascita del proprietario della patente |
| sesso | string (valori ammessi: F, M) | sesso del proprietario della patente. Nel caso di sesso non formalmente esatto viene riportato blank |
| categoria_patente | string (valori ammessi: AMS, CS, AM, C, BS, AS, D, BE , B, CE, F, DS, CATEGORIA NON CODIFICATA) | categoria di patente più elevata conseguita alla data dell'estrazione |
| data_rilascio | date (dd/mm/yyyy) | nel caso di assenza della data di rilascio è stata riportata la data di emissione, nel caso di mancanza di entrambe è stata riportata la data di primo conseguimento della categoria più alta della patente |
| abilitato_a | string (valori ammessi: S, N) | indica se indipendentemente dalla categoria massima, la patente ha una delle abilitazioni A2,A3,A4 |
| data_abilitazione_a | date (dd/mm/yyyy) | è la data di conseguimento della categoria più alta della patente, indipendentemente dalla data di rilascio della stessa |
| data_scadenza| date (dd/mm/yyyy) | data di scadenza della patente |
| stato_estero_primo_rilascio | string | stato estero primo rilascio della patente |
| punti_patente | number | numero di punti rimanenti alla data di estrazione |


## Esempio del flusso

```

```

