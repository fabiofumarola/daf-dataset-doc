# Ministero Infrastrutture e Trasporti: Patenti

## Descrizione del dataset
Il dataset contiene l'elenco delle patenti di guida, ossia delle autorizzazioni amministrative alla guida di autoveicoli e motoveicoli, provenienti dall'archivio nazionale abilitati alla guida su strada gestito dalla Motorizzazione.

**Tipo di dataset:** standard/ordinary?

**Tipo di flusso:** batch

**Tipo di file:** CSV

**Scheda:** anche se il tracciato è diverso, è possibile far riferimento alla scheda degli open data relativo alle patenti attive http://dati.mit.gov.it/catalog/dataset/patenti

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| PROGRESSIVO_RECORD | number | progressivo numerico del record interno al MIT|
| PROGRESSIVO_POSIZ_ANAGRAFICA | number | progressivo record proprietario |
| CODICE_FISCALE | string | codice fiscale o partita IVA del proprietario |
| DATA_NASCITA | number | anno di nascita del proprietario della patente |
| PROVINCIA_RESIDENZA | string | provincia di residenza del proprietario della patente |
| COMUNE_RESIDENZA | string | comune di residenza del proprietario della patente |
| STATO_ESTERO_NASCITA | string | stato estero di nascita del proprietario della patente |
| SESSO | string (valori ammessi: F, M) | sesso del proprietario della patente. Nel caso di sesso non formalmente esatto viene riportato blank |
| CATEGORIA_PATENTE | string (valori ammessi: AMS, CS, AM, C, BS, AS, D, BE , B, CE, F, DS, CATEGORIA NON CODIFICATA) | categoria di patente più elevata conseguita alla data dell'estrazione |
| DATA_ABILITAZIONE | date (dd/mm/yyyy) | nel caso di assenza della data di rilascio è stata riportata la data di emissione, nel caso di mancanza di entrambe è stata riportata la data di primo conseguimento della categoria più alta della patente |
| ABILITATO_CAT_A | string (valori ammessi: S, N) | indica se indipendentemente dalla categoria massima, la patente ha una delle abilitazioni A2,A3,A4 |
| DATA_RILASCIO | date (dd/mm/yyyy) | |
| DATA_SCADENZA | date (dd/mm/yyyy) | |
| PUNTI | number | numero di punti rimanenti alla data di estrazione |
| UFFICIO_PROVINCIALE_EMITTENTE | string | |
| DATA_RINNOVO | date (dd/mm/yyyy) | |
| MOTIVO_RICHIESTA_DOCUMENTO | string | |


## Esempio del flusso

```
"PROGRESSIVO_RECORD","PROGRESSIVO_POSIZ_ANAGRAFICA","CODICE_FISCALE","DATA_NASCITA","PROVINCIA_RESIDENZA","COMUNE_RESIDENZA","STATO_ESTERO_NASCITA","SESSO","CATEGORIA_PATENTE","DATA_ABILITAZIONE","ABILITATO_CAT_A","DATA_RILASCIO","DATA_SCADENZA","PUNTI","UFFICIO_PROVINCIALE_EMITTENTE","DATA_RINNOVO","MOTIVO_RICHIESTA_DOCUMENTO"
1,47974568,,"08/10/1940","NOVARA","NOVARA","LIBIA","F","B","31/12/1985","S","31/12/1985",,,30,,
2,43542746,,"02/06/1940","TORINO","TORINO",,"M","C","24/11/1959","S","24/11/1959",,,30,,
3,43906962,,"12/05/1934","ASTI","ASTI",,"M","B","14/05/1976","S","14/05/1976","26/04/2006",,30,"26/04/2001",
4,43620167,,,"TORINO","TORINO",,"M","C","11/10/1969","S","11/10/1969",,,30,,
5,41854120,,,"ALESSANDRIA","ALESSANDRIA",,"M","C","31/12/1985","S","31/12/1985",,,30,,
6,32528828,,,"NOVARA","NOVARA",,"M","C","31/12/1985","S","31/12/1985",,,30,,
7,41190997,,"20/05/1949","TORINO","TORINO",,"M","A","31/12/1985","S","31/12/1985",,,30,,
8,43733394,,"29/05/1925","TORINO","TORINO",,"M","A","31/12/1985","S","31/12/1985","13/12/2002",,30,"13/12/1999",
9,43423867,,"06/09/1933","TORINO","TORINO",,"M","B","17/07/1961","S","17/07/1961","27/06/2002",,30,"27/06/1997",
10,43680718,,"15/11/1930","VERCELLI","VERCELLI",,"M","CATEGORIA NON CODIFICATA",,"N","26/02/1970",,,30,,
11,43595157,"SRCMTR46S64D514P","24/11/1946","VERCELLI","GATTINARA",,"F","B","31/12/1985","S","31/12/1985","24/11/2017",,30,"19/09/2012",
12,43430245,"VTICML44R01A089A","01/10/1944","ALESSANDRIA","CASTELNUOVO SCRIVIA",,"M","B","31/12/1985","S","31/12/1985","01/10/2018",,30,"17/01/2013",
13,43437349,"MCAMFL52P68A089A","28/09/1952","TORINO","PINEROLO",,"F","B","27/01/2004","N","27/01/2004","28/09/2019",,30,"13/12/2013",
14,58056492,"CRPMRA55P56D514I","16/09/1955","TORINO","TORINO",,"F","B","18/03/2008","N","18/03/2008","16/09/2018",,30,"18/02/2013",
15,40535264,,"21/06/1925","VERCELLI","SANTHIA'",,"F","B","30/06/2005","N","16/03/1960","07/05/2011",,28,"07/05/2008","SMARRIMENTO"
16,43339625,"BRBSLL40R55L482O","15/10/1940","TORINO","TORINO",,"F","B","31/12/1985","S","31/12/1985","02/11/2009",,30,"02/11/2004",
17,43683978,,"28/04/1944","ASTI","MOMBALDONE",,"F","B","31/12/1985","S","31/12/1985",,,30,,
18,43717567,,"30/01/1935","NOVARA","PARUZZARO",,"M","D","31/12/1985","S","31/12/1985",,,30,,
19,43682093,"LMUGPP37B27G282J","27/02/1937","TORINO","RIVALTA DI TORINO",,"M","B","31/12/1985","S","31/12/1985","28/04/2013",,30,"28/04/2010","ESAMI"
20,43427996,,"20/01/1941","TORINO","TORINO",,"M","B","01/07/1965","S","01/07/1965",,,30,,"ESAMI"

```

