# Comune Roma: Incidenti stradali - persone coinvolte

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
| IDVeicolo | | |
| Progressivo | | |
| TipoPersona | | |
| AnnoNascita | | |
| Sesso | | |
| TipoLesione | | |
| Deceduto | | |
| CinturaCascoUtilizzato | | |
| Airbag | | |
| DecedutoDopo | | |

## Esempio del flusso

```
[
  {
    "IDProtocollo": "3414364",
    "IDVeicolo": "1254473",
    "Progressivo": "2",
    "TipoPersona": "Conducente",
    "AnnoNascita": "1977",
    "Sesso": "F",
    "TipoLesione": "Rifiuta cure immediate",
    "Deceduto": "0",
    "CinturaCascoUtilizzato": null,
    "Airbag": null,
    "DecedutoDopo": "NON DECEDUTO"
  },
  {
    "IDProtocollo": "3415567",
    "IDVeicolo": "1252306",
    "Progressivo": "1",
    "TipoPersona": "Passeggero",
    "AnnoNascita": "1998",
    "Sesso": "M",
    "TipoLesione": "Rimandato",
    "Deceduto": "0",
    "CinturaCascoUtilizzato": "Non utilizzato",
    "Airbag": "Esploso",
    "DecedutoDopo": "NON DECEDUTO"
  },
  ...
]
```

