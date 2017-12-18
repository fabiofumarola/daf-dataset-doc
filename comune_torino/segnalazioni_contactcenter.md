# Comune di Torino: Segnalazioni contact center

## Descrizione del dataset
Segnalazioni al contact center della polizia municipale

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** CSV

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| CA_IdCaso | string | identificativo della segnalazione | 
| data_esposto | date | data della segnalazione | 
| CA_Via1Denominazione | string | nome della strada | 
| CA_NumCivico | string | numero civico | 
| descrizione_esposto | sting | descrizione della segnalazione | 
| categoria | string | categoria | 
| TD_descrizione | string | descrizione | 
| sottocategoria_criminologica | string | sottocategoria | 
| long | double | longitudine | 
| lat | double | latitudine | 

## Esempio del flusso

```
12845;02/01/2016;GALLUPPI/PASQUALE (VIA);12;alimentazione piccioni da parte di persona anziana;Qualità Urbana;Decoro e degrado urbano;Decoro e degrado urbano;7.66146;45.0442
12846;01/01/2016;BALTIMORA/(VIA);54;"cane che abbaia continuamente dalle ore 07,00 piano 2; l'esponente è al piano 3";Convivenza Civile;disturbi da Animali;disturbi da Animali;7.64325;45.04442
12847;01/01/2016;COAZZE/(VIA);18;degrado dovuto a deiezioni canine ed erbacce;Qualità Urbana;Decoro e degrado urbano;Decoro e degrado urbano;7.65322;45.07454
12848;02/01/2016;CHANOUX/PIETRO ABATE (VIA);4;conflitti causati da abbaire di cane;Convivenza Civile;disturbi da Animali;disturbi da Animali;7.61373;45.07387

```

