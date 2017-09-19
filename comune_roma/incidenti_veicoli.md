# Comune Roma: Incidenti stradali - veicoli coinvolti

## Descrizione del dataset

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** JSON

**Scheda:** http://dati.comune.roma.it/cms/it/dettaglio_incidente_stradale.page;jsessionid=W3KSJ6qr12qwdrLea7DZ4rSW?contentId=DTS7343

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| IDProtocollo | | |
| Progressivo | | |
| IDVeicolo | | |
| TipoVeicolo | | |
| StatoVeicolo | | |
| Marca | | |
| Modello | | |

## Esempio del flusso

```
[
  {
    "IDProtocollo": "3405738",
    "Progressivo": "1",
    "IDVeicolo": "1256179",
    "TipoVeicolo": "Autovettura privata",
    "StatoVeicolo": "In marcia / fermata / arresto",
    "Marca": "Volkswagen",
    "Modello": "Polo"
  },
  ...
]
```

