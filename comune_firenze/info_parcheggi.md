# Comune Firenze: Informazioni sui parcheggi

## Descrizione del dataset

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** JSON

**Scheda:** http://opendata.comune.fi.it/mobilita_sicurezza/dataset_0372.html

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
|parkName|string|Nome parcheggio|
|address|string|Indirizzo del parcheggio
|city|string|Città|
|country|string|Nazione
|zipCode|string|Codice postale
|latitude
|longitude
|phoneNumbers|Array di <*phoneName*, *number*>
|baseInfos|Array di <*infoName*, *value*>

## Esempio del flusso

```
{
  "parkName": "Parterre",
  "address": "Via Madonna Della Tosse, 9",
  "city": "Firenze",
  "country": "Italia",
  "zipCode": "50129",
  "latitude": "43.78483",
  "longitude": "11.263201",
  "phoneNumbers": [
    {
      "phoneName": "Telefono",
      "number": "+39 055 50302209"
    },
    {
      "phoneName": "Fax",
      "number": "+39 055 50302219"
    }
  ],
  "baseInfos": [
    {
      "infoName": "Orario di apertura",
      "value": "24/24H"
    },
    {
      "infoName": "Posti paganti",
      "value": "656"
    },
    {
      "infoName": "Posti disponibili",
      "value": "1006"
    },
    {
      "infoName": "Posti venduti",
      "value": "300"
    },
    {
      "infoName": "Posti riservati disabili",
      "value": "20"
    },
    {
      "infoName": "Posti a disposizione",
      "value": "30"
    }
  ],
  "contents": [
    {
      "title": "Tariffe",
      "value": "- Prima ora non frazionabile: \u0080 2,00\r\n- Seconda ora e tutte le ore successive frazionabili alla 1/2 ora: \u0080 2,00\r\n- Tariffa giornaliera: \u0080 10,00 primo giorno, \u0080 15,00 secondo giorno e \u0080 20,00 dal terzo giorno si sosta in poi"
    },
    {
      "title": "Abbonamenti Autovetture",
      "value": "- Abbonamento settimanale 24h: \u0080 70,00*\r\n- Abbonamento mensile 24h ordinario: (\u0080 180,00) PROMOZIONE LAVORI TRAMVIA \u0080 130,00*\r\n- Abbonamento mensile 24h riservato ai soli residenti: (\u0080 130,00) PROMOZIONE LAVORI TRAMVIA  80,00*\r\n- Abbonamento mensile 24h Luxury: coming soon\r\n- Abbonamento mensile diurno valido esclusivamente nella fascia oraria dalle ore 8,00 alle ore 20,00 dal lunedì al sabato, eccetto domeniche e festivi: \u0080 80,00*\r\n- Abbonamento mensile notturno valido esclusivamente nella fascia oraria dalle ore 20,00 alle ore 08,00 tutti i giorni della settimana:  50,00*\r\n- Tessera a scalare dal valore di \u0080 120,00 Euro al costo di \u0080 100,00*\r\n*salvo disponibilità, tariffa attivabile esclusivamente con pagamento anticipato. Validità - mese solare, ovvero dal primo allultimo giorno del mese solare di riferimento indipendentemente dalla data di acquisto. L\u0092abbonamento mensile potrà essere utilizzato anche in un mese successivo a quello dell\u0092acquisto."
    },
    {
      "title": "Abbonamenti moto",
      "value": "- Abbonamento mensile 24h ordinario: \u0080 30,00*\r\n*salvo disponibilità, tariffa attivabile esclusivamente con pagamento anticipato. Validità - mese solare, ovvero dal primo allultimo giorno del mese solare di riferimento indipendentemente dalla data di acquisto. Labbonamento mensile potrà essere utilizzato anche in un mese successivo a quello dellacquisto."
    }
  ]
}
```

