# Comune Roma: Incidenti stradali

## Descrizione del dataset

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** JSON

**Scheda:** http://dati.comune.roma.it/cms/it/dettaglio_incidente_stradale.page;jsessionid=W3KSJ6qr12qwdrLea7DZ4rSW?contentId=DTS7343

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| ID | string | identificativo protocollo incidente |
| Gruppo | | |
| DataOraIncidente | | |
| Localizzazione1 | | |
| Localizzazione2 | | |
| Strada02 | | |
| Strada1 | | |
| Strada2 | | |
| Chilometrica | | |
| DaSpecificare | | |
| NaturaIncidente | | |
| ParticolaritaStrade | | |
| TipoStrada | | |
| FondoStradale | | |
| Pavimentazione | | |
| Segnaletica | | |
| CondizioneAtmosferica | | |
| Traffico | | |
| Visibilita | | |
| Illuminazione | | |
| NUM_FERITI | | |
| NUM_RISERVATA | | |
| NUM_MORTI | | |
| NUM_ILLESI | | |
| Longitudine | | |
| Latitudine | | |
| CONFERMATO | | |

## Esempio del flusso

```
[
  {
    "ID": "3414740",
    "Gruppo": "20",
    "DataOraIncidente": "2017-08-01 00:01:00.000",
    "Localizzazione1": "Provinciale",
    "Localizzazione2": "in prossimità",
    "Strada02": "della chilometrica",
    "Strada1": "VIA TIBERINA",
    "Strada2": null,
    "Chilometrica": "4.8",
    "DaSpecificare": null,
    "NaturaIncidente": "Ribaltamento senza urto contro ostacolo fisso",
    "ParticolaritaStrade": "Curva senza visuale libera",
    "TipoStrada": "Una carreggiata a doppio senso",
    "FondoStradale": "Asciutto",
    "Pavimentazione": "Asfaltata",
    "Segnaletica": "Verticale ed orizzontale",
    "CondizioneAtmosferica": "Sereno",
    "Traffico": "Scarso",
    "Visibilita": "Sufficiente",
    "Illuminazione": "Inesistente",
    "NUM_FERITI": "0",
    "NUM_RISERVATA": "0",
    "NUM_MORTI": "0",
    "NUM_ILLESI": "1",
    "Longitudine": null,
    "Latitudine": null,
    "CONFERMATO": "0"
  },
  ...
]
```

