# SOSE: FC01C Comuni - Servizi di Anagrafe, Stato Civile, Elettorale, Leva e Servizio Statistico - Fabbisogni, caratteristiche e prestazioni

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
| CAT_DET_COD_2 |  | Prezzi degli input
| CAT_DET_COD_3 |  | Fattori esogeni di carico
| CAT_DET_COD_4 |  | Demografia
| COEFF_TEORICO |  | Coefficiente di Fabbisogno Standard per il Comune |
| IND1 |  | Spesa storica del servizio anagrafe per abitante(€)
| IND3 |  | Spesa storica vs fabbisogno standard(%)
| IND4 |  | Livello servizi offerti vs livello servizi standard(%)
| IND5 |  | Certificati rilasciabili allo sportello per 1.000 abitanti(numero)
| IND6 |  | Documenti personali per 1.000 abitanti(numero)
| IND7 |  | Certificati di Stato Civile per 1.000 abitanti(numero)
| IND8 |  | Tasso migratorio anagrafico per 1.000 abitanti(numero)
| IND9 |  | Certificati elettorali emessi per 1.000 abitanti(numero)
| IND10 |  | Ore di apertura settimanale al pubblico(h)
| LQP_COD_1 |  | Differenza tra spesa storica e fabbisogno standard in % rispetto al fabbisogno standard |
| LQP_COD_2 |  | Differenza tra livello dei servizi storico e livello dei servizi standard in % rispetto al livello dei servizi standard |
| LQP_COD_3 |  | Flag Comune non valutabile |
| LQP_COD_4 |  | Flag percentile anomalo (differenza % minore del 5^ percentile o maggiore del 95^ percentile) |
| LQP_COD_5 |  | Posizione del Comune rispetto alla spesa |
| LQP_COD_6 |  | Posizione del Comune rispetto al livello dei servizi |
| LQP_COD_S |  | Misura (da 0 a 10) della capacità del Comune di soddisfare la domanda di servizi espressa dai cittadini, tenendo conto della spesa e dei servizi offerti rispetto allo standard |


## Esempio del flusso

```
"ANNO";"COMUNE_CAT_COD";"CAT_DET_COD_1";"CAT_DET_COD_2";"CAT_DET_COD_3";"CAT_DET_COD_4";"COEFF_TEORICO";"IND1";"IND3";"IND4";"IND5";"IND6";"IND7";"IND8";"IND9";"IND10";"LQP_COD_1";"LQP_COD_2";"LQP_COD_3";"LQP_COD_4";"LQP_COD_5";"LQP_COD_6";"LQP_COD_S"
"2010";"A052";"0.048257035";"1.00435503";"0.127699145";"-0.18031121";"0.000470223";"17.56699591";"39.34050207";"32.83150003";"953.2006455";"98.7334344";"274.0476307";"11.24749376";"56.33527312";"30";"39.34050207";"32.83150003";"0";"0";"8";"9";"6.6"
"2010";"A146";"0.721140685";"0.26990943";"0.010007682";"-0.001057796";"2.56511E-05";"19.50464396";"-55.42773309";"6.385816243";"133.1360947";"130.1775148";"88.75739645";"29.58579882";"65.0887574";"20";"-55.42773309";"6.385816243";"0";"0";"2";"7";"7.8"
"2010";"A182";"0.01077034";"1.131758394";"0.095655055";"-0.238183789";"0.002063475";"10.02210079";"-16.28677948";"51.6608098";"626.3868098";"126.8698708";"233.9820153";"39.96135512";"41.45831343";"24";"-16.28677948";"51.6608098";"0";"0";"4";"10";"8.8"
"2010";"A189";"0.704063162";"0.343144313";"0.039441966";"-0.086649441";"2.9443E-05";"5.508419689";"-73.78851974";"0.648253966";"375";"182.2916667";"57.29166667";"-6.510416667";"50.78125";"24";"-73.78851974";"0.648253966";"0";"0";"2";"6";"7.2"
"2010";"A197";"0.455492246";"0.614451366";"0.03667183";"-0.106615443";"4.16185E-05";"68.08463508";"131.8696819";"2.008544613";"735.3689567";"86.51399491";"226.4631043";"-1.272264631";"35.62340967";"30";"131.8696819";"2.008544613";"0";"1";"10";"6";"4"
"2010";"A211";"0.550857625";"0.581037991";"0.043675207";"-0.175570823";"3.62363E-05";"0";"";"";"542.0466059";"83.08004053";"25.32928065";"-5.06585613";"112.4620061";"18";"";"";"1";"0";"";"";""
"2010";"A227";"0.626386006";"0.404374494";"0.039347328";"-0.070107829";"3.01009E-05";"0";"";"";"1150.097466";"204.6783626";"58.47953216";"0";"29.23976608";"30";"";"";"1";"0";"";"";""
"2010";"A245";"0.690962944";"0.387209106";"0.032845468";"-0.111017517";"2.62037E-05";"0.061668229";"-99.83770233";"-3.004124209";"1034.990792";"208.1031308";"69.98158379";"60.77348066";"90.23941068";"40";"-99.83770233";"-3.004124209";"0";"1";"1";"5";"7"
"2010";"A436";"0.15312439";"0.957447984";"0.072359198";"-0.182931572";"0.000146465";"14.78453674";"14.67721385";"-5.457014431";"577.6155718";"88.56447689";"70.2351987";"23.51987024";"48.66180049";"20";"14.67721385";"-5.457014431";"0";"0";"7";"5";"4.6"
"2010";"A523";"0.758034612";"0.264229536";"0.021116711";"-0.043380859";"2.37554E-05";"0";"";"";"731.292517";"91.83673469";"37.41496599";"91.83673469";"0";"36";"";"";"1";"0";"";"";""
"2010";"A605";"0.363730939";"0.758943915";"0.016056148";"-0.138731002";"5.52671E-05";"20.65344101";"-3.424777417";"-12.297059";"49.93065187";"92.92649098";"81.13730929";"12.48266297";"46.46324549";"30";"-3.424777417";"-12.297059";"0";"0";"5";"3";"4.2"
"2010";"A689";"0.305838043";"0.88070536";"0.047623426";"-0.234166829";"6.61467E-05";"18.50047326";"7.251723584";"15.86219753";"432.8287606";"96.97256386";"185.9035005";"20.34058657";"70.00946074";"21";"7.251723584";"15.86219753";"0";"0";"6";"8";"6.8"
"2010";"A708";"0.461284795";"0.724154924";"0.051353315";"-0.236793033";"4.60542E-05";"0.434537246";"-96.96574707";"17.57895342";"403.1354983";"82.30683091";"117.581187";"1.679731243";"61.03023516";"30";"-96.96574707";"17.57895342";"0";"0";"1";"8";"8.8"
"2010";"A738";"0.669028107";"0.387069202";"0.026078483";"-0.082175791";"2.79471E-05";"1.816367265";"-94.09073124";"5.938835596";"467.9487179";"230.7692308";"363.2478632";"8.547008547";"81.1965812";"25";"-94.09073124";"5.938835596";"0";"0";"2";"7";"7.8"
"2010";"A793";"0.496295319";"0.588952078";"0.015597877";"-0.100845273";"3.87252E-05";"49.74935897";"81.85225626";"-11.53850284";"211.1398964";"101.0362694";"38.86010363";"25.90673575";"41.4507772";"24";"81.85225626";"-11.53850284";"0";"0";"9";"3";"2.6"
"2010";"A813";"0.898021647";"0.172914838";"0.00934677";"-0.080283255";"1.90458E-05";"0";"";"";"421.686747";"60.24096386";"60.24096386";"66.26506024";"60.24096386";"19";"";"";"1";"0";"";"";""
"2010";"A889";"0.346158127";"0.768907005";"0.068913831";"-0.183978963";"5.99278E-05";"28.78065844";"69.43326695";"-2.846540298";"423.0171073";"191.2908243";"198.0300674";"15.55209953";"139.9688958";"21";"69.43326695";"-2.846540298";"0";"0";"9";"5";"3.8"
"2010";"A998";"0.337745674";"0.756295115";"0.049903723";"-0.143944512";"6.27839E-05";"14.08432056";"-18.21049757";"0.882999492";"528.5359801";"86.35235732";"200.9925558";"-6.451612903";"36.72456576";"28";"-18.21049757";"0.882999492";"0";"0";"4";"6";"6.4"

```

