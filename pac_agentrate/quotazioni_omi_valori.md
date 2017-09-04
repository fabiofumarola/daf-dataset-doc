# Agenzia Entrate: Quotazioni immobiliari - valori

## Descrizione del dataset
Le quotazioni immobiliari semestrali individuano, per ogni delimitata zona territoriale omogenea (zona OMI) di ciascun comune, un intervallo minimo/massimo, per unità di superficie in euro a metro quadro. Quando per una stessa tipologia sono valorizzati più stati di conservazione è comunque specificato quello prevalente. In particolare:
 - per box, posti auto e autorimesse non risulta significativo il diverso apprezzamento del mercato secondo lo stato conservativo
 - per negozi e centri commerciali il giudizio O/ N /S è da intendersi riferito alla posizione commerciale e non allo stato conservativo dell'unità immobiliare.

Le quotazioni OMI, disponibili in un semestre, sono relative ai comuni censiti negli archivi catastali. È quindi possibile che l’elenco dei comuni presenti in Banca Dati differisca nei diversi semestri per effetto di variazioni circoscrizionali (soppressione/costituzione di nuovi comuni).


**Tipo di dataset:** standard/ordinary?

**Tipo di flusso:** batch

**Tipo di file:** CSV

**Scheda:** http://www.agenziaentrate.gov.it/wps/content/Nsilib/Nsi/Home/Servizi+online/Servizi+OMI/Forniture+dati+OMI/

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| Area_territoriale | |
| Regione | |
| Prov | |
| Comune_ISTAT | |
| Comune_cat | |
| Sez | |
| Comune_amm | |
| Comune_descrizione | |
| Fascia | |
| Zona | |
| LinkZona | |
| Cod_Tip | |
| Descr_Tipologia | |
| Stato | |
| Stato_prev | |
| Compr_min | |
| Compr_max | |
| Sup_NL_compr | |
| Loc_min | |
| Loc_max | |
| Sup_NL_loc


## Esempio del flusso

```
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;B;B1;AL00000001;20;Abitazioni civili;NORMALE;P;890;1050;L;3,1;4,2;L;
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;B;B1;AL00000001;13;Box;NORMALE;P;1100;1600;L;4,4;6,2;L;
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;B;B1;AL00000001;14;Posti auto coperti;NORMALE;P;700;1000;L;2,7;3,8;L;
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;B;B1;AL00000001;15;Posti auto scoperti;NORMALE;P;600;800;L;2,5;3,3;L;
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;B;B1;AL00000001;9;Magazzini;NORMALE;P;900;1300;L;4,8;5,7;L;
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;B;B1;AL00000001;5;Negozi;NORMALE;P;800;1200;L;8;10,8;L;
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;B;B1;AL00000001;6;Uffici;NORMALE;P;1100;1550;L;4,8;5,7;L;
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;B;B1;AL00000001;10;Laboratori;NORMALE;P;1400;1700;L;7;8,5;L;
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;C;C1;AL00000003;20;Abitazioni civili;NORMALE;P;940;1100;L;2,9;4,3;L;
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;C;C1;AL00000003;13;Box;NORMALE;P;850;1150;L;3,3;4,5;L;
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;C;C1;AL00000003;14;Posti auto coperti;NORMALE;P;650;750;L;2,6;3,2;L;
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;C;C1;AL00000003;15;Posti auto scoperti;NORMALE;P;500;600;L;2,2;3,1;L;
NORD-OVEST;PIEMONTE;AL;1006003;A2AA; ;A182;ALESSANDRIA;C;C1;AL00000003;1;Ville e Villini;NORMALE;P;800;1200;L;3,3;4,5;L;
```

