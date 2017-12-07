# SOSE: FC06B Comuni - Servizio di Asilo Nido - Fabbisogni, caratteristiche e prestazioni

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
| CAT_DET_COD_1 |  | Servizi offerti
| CAT_DET_COD_2 |  | Prezzi degli input
| CAT_DET_COD_3 |  | Scelte organizzative
| COEFF_TEORICO |  | Coefficiente di Fabbisogno Standard per il Comune |
| IND1 |  | Spesa storica del servizio Asili Nido per abitante(€)
| IND3 |  | Spesa storica vs fabbisogno standard(%)
| IND4 |  | Livello servizi offerti vs livello servizi standard(%)
| IND5 |  | Spesa del servizio Asili Nido per bambino frequentante(€)
| IND6 |  | Entrata media da utenza per bambino frequentante(€)
| IND7 |  | Bambini frequentanti per educatore(numero)
| IND8 |  | Bambini che usufruiscono del servizio di refezione(%)
| IND9 |  | Bambini che usufruiscono del servizio Asili nido(%)
| LQP_COD_1 |  | Differenza tra spesa storica e fabbisogno standard in % rispetto al fabbisogno standard |
| LQP_COD_2 |  | Differenza tra livello dei servizi storico e livello dei servizi standard in % rispetto al livello dei servizi standard |
| LQP_COD_3 |  | Flag Comune non valutabile |
| LQP_COD_4 |  | Flag percentile anomalo (differenza % minore del 5^ percentile o maggiore del 95^ percentile) |
| LQP_COD_5 |  | Posizione del Comune rispetto alla spesa |
| LQP_COD_6 |  | Posizione del Comune rispetto al livello dei servizi |
| LQP_COD_S |  | Misura (da 0 a 10) della capacità del Comune di soddisfare la domanda di servizi espressa dai cittadini, tenendo conto della spesa e dei servizi offerti rispetto allo standard |


## Esempio del flusso

```
"ANNO";"COMUNE_CAT_COD";"CAT_DET_COD_1";"CAT_DET_COD_2";"CAT_DET_COD_3";"COEFF_TEORICO";"IND1";"IND3";"IND4";"IND5";"IND6";"IND7";"IND8";"IND9";"LQP_COD_1";"LQP_COD_2";"LQP_COD_3";"LQP_COD_4";"LQP_COD_5";"LQP_COD_6";"LQP_COD_S"
"2010";"A052";"0.420479163";"0.488713338";"0.0908075";"0.000357017";"16.23058583";"-35.2559283";"77.04228087";"4834.362319";"1570.623188";"8.117647059";"100";"15";"-35.2559283";"77.04228087";"0";"0";"3";"9";"8.6"
"2010";"A146";"0";"0";"0";"0";"0";"";"";"";"";"";"";"0";"";"";"3";"0";"";"";""
"2010";"A182";"0.502865802";"0.416300369";"0.080833829";"0.002443365";"37.31743425";"0.514450938";"-13.69440732";"9683.568306";"1700.125683";"5.464285714";"100";"14.86596263";"0.514450938";"-13.69440732";"0";"0";"6";"5";"5"
"2010";"A189";"0";"0";"0";"0";"0";"";"";"";"";"";"";"0";"";"";"3";"0";"";"";""
"2010";"A197";"0.340889298";"0.634562615";"0.024548088";"1.22072E-05";"23.90524968";"5.980870427";"79.3046149";"2333.75";"0";"";"0";"50";"5.980870427";"79.3046149";"0";"0";"6";"9";"7.4"
"2010";"A211";"0.412365505";"0.502355498";"0.085278997";"1.46394E-05";"10.34610351";"-51.71303013";"-25.29992805";"261.5707196";"1338.461538";"10";"94.87179487";"185.7142857";"-51.71303013";"-25.29992805";"0";"0";"2";"4";"6"
"2010";"A227";"0";"0";"0";"0";"0";"";"";"";"";"";"";"0";"";"";"3";"0";"";"";""
"2010";"A245";"0.412365505";"0.502355498";"0.085278997";"4.87981E-06";"8.948471986";"-51.71302683";"-25.29992805";"87.19023987";"1338.461538";"10";"94.87179487";"557.1428571";"-51.71302683";"-25.29992805";"0";"0";"2";"4";"6"
"2010";"A436";"0.433685589";"0.477383652";"0.08893076";"0.000472195";"51.29009585";"-52.88202788";"195.7695692";"5351.266667";"1150.5";"20";"100";"43.16546763";"-52.88202788";"195.7695692";"0";"2";"2";"10";"9.6"
"2010";"A523";"0";"0";"0";"0";"0";"";"";"";"";"";"";"0";"";"";"3";"0";"";"";""
"2010";"A605";"0.378383359";"0.604684043";"0.016932597";"3.26651E-06";"0";"";"";"0";"2854.875";"";"100";"34.7826087";"";"";"1";"0";"";"";""
"2010";"A689";"0";"0";"0";"0";"0";"";"";"";"";"";"";"0";"";"";"3";"0";"";"";""
"2010";"A708";"0";"0";"0";"0";"0";"";"";"";"";"";"";"0";"";"";"3";"0";"";"";""
"2010";"A738";"0";"0";"0";"0";"0";"";"";"";"";"";"";"0";"";"";"3";"0";"";"";""
"2010";"A793";"0";"0";"0";"0";"0";"";"";"";"";"";"";"0";"";"";"3";"0";"";"";""
"2010";"A813";"0";"0";"0";"0";"0";"";"";"";"";"";"";"0";"";"";"3";"0";"";"";""
"2010";"A889";"0.391941996";"0.545010207";"0.063047797";"6.66385E-05";"0.257201646";"-99.48006958";"174.0452499";"27.77777778";"0";"";"55.55555556";"41.86046512";"-99.48006958";"174.0452499";"0";"3";"1";"10";"10"
"2010";"A998";"0";"0";"0";"0";"0";"";"";"";"";"";"";"0";"";"";"3";"0";"";"";""

```

