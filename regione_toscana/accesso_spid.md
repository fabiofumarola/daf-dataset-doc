# Regione Toscana: Dati accesso SPID

## Descrizione del dataset

**Tipo di dataset:** standard

**Tipo di flusso:** batch

**Tipo di file:** CSV

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP; ognuno contiene i dati relativi all'ultimo periodo temporale (append)


## Elementi

### id
id identificativo unico dell'evento (per permette di distinguere duplicat o effettuare update)

### timestamp
momento dell'accesso (spesso in numero di millisecondi UNIX like) )

### anno_nascita 
anno di nascita dell'utente (solo le ultime due cifre)

### genere
Genere gender

### tipo_credenziale
tipo di credenziale utilizzata 

### risorsa
risorsa acceduta

### cod_nazione 
nazone da cui è stato effettuato l'accesso 

### nome_nazione
codice  iso nazione countryName 

### cod_provincia
suddivisione/provincia codice iso

### nome_provincia
suddivisione/provincia 

### nome_citta
nome della città

### latitude 

### longitude

### loc_accuration
LocationAccuracyRadius espressa in chilometri 


## Esempio del flusso

```
RT-1322348947;1489569300052;64;M;SPID2;RT Genio Civile Sismica;IT;Italy;GE;Provincia di Genova;Genoa;44.4264;8.9152;1
RT333429685;1452255960031;80;M;SPID1;RT SampleSite ARPA3 SPID;null;null;null;null;null;null;null;null
RT1340684395;1452260520003;80;M;SPID1;RT SampleSite ARPA3 SPID;null;null;null;null;null;null;null;null
RT792104202;1452267960059;80;M;SPID1;RT SampleSite ARPA3 SPID;null;null;null;null;null;null;null;null
RT454126474;1452268260042;80;M;SPID1;RT SampleSite ARPA3 SPID;null;null;null;null;null;null;null;null
RT-135824291;1469005260053;60;F;SPID2;RT STAR;IT;Italy;MS;Province of Massa-Carrara;Marina di Carrara;44.0333;10.0333;50
RT665296610;1488876420037;67;M;SPID2;RT Ap@ci;IT;Italy;PO;Provincia di Prato;Prato;43.8833;11.1;10
RT2043110193;1488903120013;75;F;SPID2;RT PdA  Cancelleria Telematica;IT;Italy;CE;Provincia di Caserta;Sessa Aurunca;41.2333;13.9333;200
RT-251015616;1496154480059;94;M;SPID2;RT STAR;IT;Italy;FI;Province of Florence;Florence;43.7667;11.25;50
RT-171323025;1496162220023;64;M;SPID2;RT Gestione Tasse Automobilistiche Regione Toscana;IT;Italy;null;null;null;43.1479;12.1097;500
RT-898160639;1496210460009;58;M;SPID2;RT IRIS - fascicolo posizioni debitorie.;IT;Italy;FI;Province of Florence;Scandicci;43.75;11.1833;50
RT-780562977;1496212800033;72;M;SPID2;RT IRIS - fascicolo posizioni debitorie.;IT;Italy;VI;Provincia di Vicenza;Lonigo;45.4195;11.371;200

```

