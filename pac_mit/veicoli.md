# Ministero Infrastrutture e Trasporti: Veicoli

## Descrizione del dataset
Questo dataset contiene il parco circolante dei veicoli su strada (categorie Autoveicoli e Motoveicoli) estratto dall'archivio nazionale dei veicoli gestito dalla Motorizzazione.

**Tipo di dataset:** standard/ordinary?

**Tipo di flusso:** batch

**Tipo di file:** CSV

**Scheda:** anche se il tracciato è diverso, è possibile far riferimento alla scheda degli open data http://dati.mit.gov.it/catalog/dataset/parco-circolante-dei-veicoli

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| progressivo | number | numero progressivo del veicolo come record nel dataset |
| tipo veicolo | string | tipo di veicolo ( A = Autoveicolo , M = Motoveicolo) |
| destinazione | string | destinazione del veicolo . Per destinazione del veicolo s'intende la sua utilizzazione in base alle caratteristiche tecniche.  (Per  A gli autoveicoli: AUTOVEICOLO IN SERVIZIO PUBBLICO DI LINEA INTEGRATIVO, AUTOVEICOLO USO ESCLUSIVO DI POLIZIA, AUTOVETTURA PER TRASPORTO DI PERSONE, AUTOBUS PER TRASPORTO DI PERSONE, AUTOCARRO PER TRASPORTO DI COSE, AUTOCARAVAN, AUTOVEICOLO PER USO SPECIALE, TRAS.SPECIFICO PERSONE PART.CONDIZIONI, AUTOVEIC.TRASP.PROMISCUO PERSONE/COSE,TRATTORE STRADALE PER RIMORCHIO,TRATTORE PER SEMIRIMORCHIO . Per M i Motoveicoli: QUADRICICLO PER TRASPORTO DI PERSONE, QUADRICICLO PER TRASPORTO DI COSE, QUADRICICLO PER USO SPECIALE, QUADRICICLO TRASPORTO SPECIFICO, MOTOVEICOLO USO ESCLUSIVO DI POLIZIA, TRICICLO PER TRASPORTO PROMISCUO, TRICICLO PER USO SPECIALE, TRICICLO PER TRASPORTO SPECIFICO, MOTOCICLO PER TRASPORTO PERSONE, TRICICLO PER TRASPORTO COSE, TRICICLO PER TRASPORTO DI PERSONE. |
| uso | string | tipo d'uso del veicolo. Per uso del veicolo s'intende la sua utilizzazione economica. I veicoli possono essere adibiti a uso proprio o a uso di terzi. (Proprio, Di terzi da noleggio con conducente, di terzi da locare senza conducente, Di terzi, Di terzi con autorizzazione vincolate, Di terzi con autorizzazione libera, Uso speciale ) |
| progressivo persona fisica | number | numero progressivo della persona fisica |
| progressivo persona giuridica | number | numero progressivo della persona giuridica |
| codice fiscale proprietario | string | codice fisca del proprietario se persona fisica |
| Partita IVA | string | partita IVA del proprietario se persona giuridica |
| comune residenza | string | comune dove risiede l'intestatario del veicolo |
| provincia residenza | string | provincia dove risiede l'intestatario del veicolo |
| età  intestatario | string | età dell'intestatario del veicolo alla data di produzione del dataset |
| sesso | string | sesso dell'intestatario del veicolo |
| marca | string | marca del veicolo |
| cilindrata | string | cilindrata del veicolo misurata in centimetro cubo (cm3) .  |
| alimentazione | string | alimentazione del motore del veicolo , ossia il tipo di combustibile (GASOLIO/METANO, GASOLIO/GPL, BENZINA, BENZINA/OLIO, BENZINA/WANK, ELETTRICA,GASOLIO, GPL, BENZINA/GPL, BENZINA/METANO, METANO, MISCELA,PETROLIO,IBRIDO BENZINA/ELETTRICO, IBRIDO GASOLIO/ELETTRICO, BENZINA/ETANOLO) |
| data immatricolazione | string | data di immatricolazione del veicolo |
| classe euro | string | classe ambientale di appartenenza (categoria Euro) di autoveicoli  (pre-Euro 1, Euro 1, Euro 2, Euro 3, Euro 4, Euro 5, Euro 6) e motoveicoli (pre-Euro 1, Euro 1, Euro 2, Euro 3) definita dalle direttive europee rispettate nell'anno di produzione e che Ã¨ riportata nel libretto di circolazione. |
| emissioni co2 | string | emissione CO2 del veicolo misurate in g/km ossia grammi al chilometro. |
| massa complessiva | string | massa complessiva del veicolo misurata attraverso il suo peso in chilogrammi (Kg). Si definisce massa complessiva la massa del veicolo in ordine di marcia (tara) piÃ¹ tutto il suo carico (portata). |
| revisone in regola s/n | string | stato dell'obbligo di revisione del veicolo (S= SI , N=NO) ai fini della circolazione. |
| assicurazione in regola s/n | string | stato dell'obbligo dell'assicurazione del veicolo (S= SI , N=NO) ai fini della circolazione."


## Esempio del flusso

```

```

