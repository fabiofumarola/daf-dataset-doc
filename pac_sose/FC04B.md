# SOSE: FC04B Comuni - Funzioni per il servizio del Trasporto Pubblico Locale e servizi connessi - Fabbisogni, caratteristiche e prestazioni

## Descrizione del dataset


**Tipo di dataset:** standard/ordinary?

**Tipo di flusso:** batch

**Tipo di file:** CSV

**Scheda:** 

**Modalità di ingestion su DAF:** scarico su SFTP


## Elementi

| Nome | Tipo   | Descrizione                     |
|------|--------|---------------------------------|
| ANNO | number | Anno di analisi  |
| COMUNE_CAT_COD | string  | codice catastale del comune |
| CAT_DET_COD_1 |  | Popolazione residente
| CAT_DET_COD_2 |  | Morfologia e territorio
| CAT_DET_COD_3 |  | Economia locale
| CAT_DET_COD_4 |  | Prezzi degli input
| CAT_DET_COD_5 |  | Fattori esogeni di carico
| CAT_DET_COD_6 |  | Veicoli, traffico e strade
| CAT_DET_COD_7 |  | Demografia
| COEFF_TEORICO |  | Coefficiente di Fabbisogno Standard per il Comune |
| IND1 |  | Spesa storica del servizio trasporti per abitante(€)
| IND3 |  | Spesa storica vs fabbisogno standard(%)
| IND4 |  | Livello servizi offerti vs livello servizi standard(%)
| IND5 |  | Km percorsi per km di rete stradale comunale(km)
| IND6 |  | Eta' media dei mezzi su gomma(numero)
| IND7 |  | Velocita' commerciale (Km/h)
| IND8 |  | Passeggeri per Km ogni 1.000 abitanti(numero)
| IND9 |  | Addetti alla guida sul totale addetti(%)
| IND10 |  | Eta' media dei mezzi su rotaia(numero)
| IND11 |  | Eta' media dei mezzi di navigazione(numero)
| IND12 |  | Km notturni percorsi su km totali(%)
| IND13 |  | Fermate per km di rete stradale dei mezzi(numero)
| LQP_COD_1 |  | Differenza tra spesa storica e fabbisogno standard in % rispetto al fabbisogno standard |
| LQP_COD_2 |  | Differenza tra livello dei servizi storico e livello dei servizi standard in % rispetto al livello dei servizi standard |
| LQP_COD_3 |  | Flag Comune non valutabile |
| LQP_COD_4 |  | Flag percentile anomalo (differenza % minore del 5^ percentile o maggiore del 95^ percentile) |
| LQP_COD_5 |  | Posizione del Comune rispetto alla spesa |
| LQP_COD_6 |  | Posizione del Comune rispetto al livello dei servizi |
| LQP_COD_S |  | Misura (da 0 a 10) della capacità del Comune di soddisfare la domanda di servizi espressa dai cittadini, tenendo conto della spesa e dei servizi offerti rispetto allo standard |


## Esempio del flusso

```
"ANNO";"COMUNE_CAT_COD";"CAT_DET_COD_1";"CAT_DET_COD_2";"CAT_DET_COD_3";"CAT_DET_COD_4";"CAT_DET_COD_5";"CAT_DET_COD_6";"CAT_DET_COD_7";"COEFF_TEORICO";"IND1";"IND3";"IND4";"IND5";"IND6";"IND7";"IND8";"IND9";"IND10";"IND11";"IND12";"IND13";"LQP_COD_1";"LQP_COD_2";"LQP_COD_3";"LQP_COD_4";"LQP_COD_5";"LQP_COD_6";"LQP_COD_S"
"2010";"A052";"0.053360101";"0.021574788";"0.186145393";"0.348719358";"0.042540243";"0.106794479";"0.240865638";"0.000118457";"2.814859868";"";"";"276.3114586";"";"0";"0";"";"";"";"0";"";"";"";"2";"0";"";"";""
"2010";"A146";"0";"0.043591887";"0.073925264";"0.281584845";"0";"0.331726332";"0.269171672";"3.56E-06";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A182";"0.265562163";"0.143243245";"0.112666095";"0.227300554";"0.025850204";"0.095680416";"0.129697323";"0.001521074";"3.359256217";"-78.7248687";"-16.07368353";"2381.718455";"12";"18";"0.016313655";"49.79423868";"";"";"0";"2.109375";"-78.7248687";"-16.07368353";"0";"0";"2";"5";"6.6"
"2010";"A189";"0";"0.039291292";"0.101571976";"0.376175052";"0";"0.250882898";"0.232078781";"4.26E-06";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A197";"0";"0.059680088";"0.120169858";"0.382740907";"0";"0.152489853";"0.284919293";"4.10E-06";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A211";"0";"0.012221032";"0.114730885";"0.425469925";"0";"0.178275714";"0.269302444";"3.58E-06";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A227";"0";"0.030836938";"0.117028988";"0.322911113";"0";"0.290259187";"0.238963774";"4.16E-06";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A245";"0";"0.012401637";"0.198057802";"0.431757599";"0";"0.145054309";"0.212728654";"1.30E-06";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A436";"0";"0.037689286";"0.168188513";"0.393628055";"0";"0.1484642";"0.252029946";"2.67E-05";"1.62715655";"-61.36091849";"-24.71148494";"10844.40481";"10";"0";"0.087488475";"74.28571429";"";"";"1.279288161";"2.368421053";"-61.36091849";"-24.71148494";"0";"0";"3";"5";"6.2"
"2010";"A523";"0";"0.040576718";"0.051935742";"0.255940903";"0";"0.473817462";"0.177729175";"3.93E-06";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A605";"0";"0.018672113";"0.104228009";"0.413930458";"0";"0.178886624";"0.284282796";"5.41E-06";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A689";"0";"0.021328476";"0.24462649";"0.377619528";"0";"0.148838696";"0.20758681";"1.10E-05";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A708";"0";"0.015845739";"0.122548605";"0.435433821";"0";"0.178469016";"0.247702818";"5.45E-06";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A738";"0";"0.033684149";"0.293243925";"0.30403308";"0";"0.211566264";"0.157472582";"4.71E-06";"1.658682635";"";"";"0";"";"";"";"";"";"";"";"";"";"";"2";"0";"";"";""
"2010";"A793";"0";"0.017393029";"0.101534743";"0.373006947";"0";"0.266164215";"0.241901066";"4.42E-06";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A813";"0";"0.042927331";"0.063127317";"0.426208225";"0";"0.270095286";"0.197641841";"6.13E-07";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A889";"0";"0.027444108";"0.169680638";"0.413706124";"0";"0.146235658";"0.242933473";"7.40E-06";"0";"";"";"0";"";"";"";"";"";"";"";"";"";"";"3";"0";"";"";""
"2010";"A998";"0";"0.042489281";"0.184027688";"0.379960327";"0";"0.166892219";"0.226630485";"1.03E-05";"1.965654555";"";"";"0";"10";"";"";"74.28571429";"";"";"";"2.368421053";"";"";"2";"0";"";"";""

```

