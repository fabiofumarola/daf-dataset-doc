# Comune Roma: Incidenti stradali - pedoni coinvolti

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
| TipoPersona | | |
| AANascita | | |
| Sesso | | |
| TipoLesione | | |
| Deceduto | | |
| DecedutoDopo | | |

## Esempio del flusso

```
[
  {
    "IDProtocollo": "3439363",
    "TipoPersona": "Pedone",
    "AANascita": "0",
    "Sesso": "M",
    "TipoLesione": "Rimandato",
    "Deceduto": "0",
    "DecedutoDopo": "NON DECEDUTO"
  },
  {
    "IDProtocollo": "3432210",
    "TipoPersona": "Pedone",
    "AANascita": "1972",
    "Sesso": "F",
    "TipoLesione": "Rimandato",
    "Deceduto": "0",
    "DecedutoDopo": "NON DECEDUTO"
  },
  ...
]
```

