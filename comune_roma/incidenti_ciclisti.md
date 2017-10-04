# Comune Roma: Incidenti stradali - ciclisti coinvolti

## Descrizione del dataset

**Tipo di dataset:** 

**Tipo di flusso:** batch

**Tipo di file:** CSV

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| Protocollo | string | |
| Gruppo | int | |
| DataOraIncidente | data/ora| |
| Localizzazione1 | string | |
| STRADA1 | string | |
| Localizzazione2 | string | |
| STRADA2 | string | |
| Strada02 | string | |
| Chilometrica | string | |
| DaSpecificare | string | |
| NaturaIncidente | string | |
| particolaritastrade | string | |
| TipoStrada | string | |
| FondoStradale | string | |
| Pavimentazione | string | |
| Segnaletica | string | |
| CondizioneAtmosferica | string | |
| Traffico | string | |
| Visibilita | string | |
| Illuminazione | string | |
| NUM_FERITI | int | |
| NUM_RISERVATA | int | |
| NUM_MORTI | int | |
| NUM_ILLESI | int | |
| Longitudine | string | |
| Latitudine | string | |
| Confermato | string | |
| Progressivo | string | |
| TipoVeicolo | string | |
| StatoVeicolo | string | |
| Marca | string | |
| Modello | string | |
| TipoPersona | string | |
| AnnoNascita | int | |
| Sesso | string | |
| Tipolesione | string | |
| Deceduto | string | |
| DecedutoDopo | string | |
| CinturaCascoUtilizzato | string | |
| Airbag | string | |

## Esempio del flusso

```
Protocollo;Gruppo;DataOraIncidente;Localizzazione1;STRADA1;Localizzazione2;STRADA2;Strada02;Chilometrica;DaSpecificare;NaturaIncidente;particolaritastrade;TipoStrada;FondoStradale;Pavimentazione;Segnaletica;CondizioneAtmosferica;Traffico;Visibilita;Illuminazione;NUM_FERITI;NUM_RISERVATA;NUM_MORTI;NUM_ILLESI;Longitudine;Latitudine;Confermato;Progressivo;TipoVeicolo;StatoVeicolo;Marca;Modello;TipoPersona;AnnoNascita;Sesso;Tipolesione;Deceduto;DecedutoDopo;CinturaCascoUtilizzato;Airbag;
3441750;6;01/09/2017 02:50:00;Strada Urbana;VIA TARANTO;in prossimità;;del civico n.;66/c;;Veicolo in marcia contro veicoli in sosta;Rettilineo;Una carreggiata a doppio senso;Asciutto;Asfaltata;Verticale ed orizzontale;Sereno;Scarso;Sufficiente;Sufficiente;0;0;0;4;12,51528;41,88447;-1;1;Autovettura privata;In marcia / fermata / arresto;BMW;118 D;Conducente;1995;M;Illeso;0;;;
3441750;6;01/09/2017 02:50:00;Strada Urbana;VIA TARANTO;in prossimità;;del civico n.;66/c;;Veicolo in marcia contro veicoli in sosta;Rettilineo;Una carreggiata a doppio senso;Asciutto;Asfaltata;Verticale ed orizzontale;Sereno;Scarso;Sufficiente;Sufficiente;0;0;0;4;12,51528;41,88447;-1;1;Autovettura privata;In marcia / fermata / arresto;BMW;118 D;Passeggero;1995;M;Illeso;0;;;
3441778;1;01/09/2017 00:05:00;Strada Urbana;PASSEGGIATA DEL GIANICOLO;da specificare;;;;fronte RAMPA DELLA QUERCIA;Veicolo in marcia contro ostacolo accidentale;Curva a visuale libera;Una carreggiata a doppio senso;Viscido da liquidi oleosi;Asfaltata;Verticale ed orizzontale;Sereno;Scarso;Sufficiente;Sufficiente;1;0;0;0;;;0;1;Motociclo a solo;In marcia / fermata / arresto;Honda;Silver Wing 400;Conducente;1971;M;Rimandato;0;NON DECEDUTO;;
3441820;12;01/09/2017 07:20:00;Strada Urbana;VIALE UMBERTO TUPINI;da specificare;;;;prossimità viale America;Veicolo in marcia contro veicolo in sosta;Pendenza;Una carreggiata a doppio senso;Bagnato (pioggia);Asfaltata;Verticale ed orizzontale;Pioggia in atto;Normale;Buona;Ore Diurne;1;0;0;0;12,46183;41,8328;-1;1;Motociclo a solo;In marcia / fermata / arresto;Kimco;People;Conducente;1962;F;Rimandato;0;NON DECEDUTO;Non accertato;
3441823;9;01/09/2017 07:15:00;Strada Urbana;PIAZZA ZAMA;da specificare;;;;fonte civico 09;Scontro laterale fra veicoli in marcia;Rotatoria;Una carreggiata a senso unico di marcia;Bagnato (pioggia);Asfaltata;Orizzontale;Pioggia in atto;Scarso;Buona;Ore Diurne;0;0;0;2;12,50979;41,87645;-1;1;Autovettura privata;In marcia / fermata / arresto;Peugeot; 2008;Conducente;1953;M;Illeso;0;;Non accertato;Inesploso
3441823;9;01/09/2017 07:15:00;Strada Urbana;PIAZZA ZAMA;da specificare;;;;fonte civico 09;Scontro laterale fra veicoli in marcia;Rotatoria;Una carreggiata a senso unico di marcia;Bagnato (pioggia);Asfaltata;Orizzontale;Pioggia in atto;Scarso;Buona;Ore Diurne;0;0;0;2;12,50979;41,87645;-1;2;Autovettura privata;In marcia / fermata / arresto;Chevrolet;Matiz;Conducente;1970;M;Illeso;0;;Non accertato;Inesploso
3441889;9;01/09/2017 07:00:00;Strada Urbana;VIA LANUVIO;in corrispondenza;;del civico n.;46;;Veicolo in marcia contro veicoli in sosta;Curva senza visuale libera;Una carreggiata a senso unico di marcia;Bagnato (pioggia);Asfaltata;Assente;Nuvoloso;Scarso;Buona;Ore Diurne;0;0;0;1;12,53258;41,86432;-1;1;Autovettura privata;In marcia / fermata / arresto;Renault;Twingo;Conducente;1974;M;Illeso;0;;Non accertato;Inesploso
```

