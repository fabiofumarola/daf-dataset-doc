# Ministero Infrastrutture e Trasporti: Anagrafica codici DATEX

## Descrizione del dataset
Il DATEX costituisce  il protocollo di scambio europeo per le informazioni di traffico, è ancora utilizzato da un numero significativo di fonti CCISS che hanno definito le loro convenzioni con il Ministero precedentemente al 2011, anno in cui è stato deprecato e sostituito con il Datex II. Sono in corso gli accordi che consentono e consentiranno alle fonti il passaggio a Datex II, la cui documentazione è disponibile all’indirizzo: http://www.datex2.eu/


Nota: il flusso [eventi di traffico CCISS](eventi_cciss.md) impiega alcuni codici DATEX II

**Tipo di dataset:** 

**Tipo di flusso:** 

**Tipo di file:** CSV

**Scheda:** 

**Modalità di ingestion su DAF:** caricameto su SFTP

## Elementi (eventiResponse)

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
|codice|string||
|descrizione|string||


## Esempio del flusso

```
ACM,Incidente a catena
AJC,Caravan ripiegato su se stesso
AOL,Mezzo pesante ribaltato
ASP,Veicolo di traverso
VSA,Rallentamenti per curiosi
ACX,Incidente risolto
AJT,Traino ripiegato su se stesso
ACW,Rilievi su luogo incidente
```

