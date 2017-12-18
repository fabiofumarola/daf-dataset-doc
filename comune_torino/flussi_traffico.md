# Comune di Torino: Stato del traffico (flussi) in tempo reale

## Descrizione del dataset
Conteggio dei veicoli transitanti alle sezioni di misura dell’area urbana di Torino, rilevati a mezzo di spire induttive o di sensori aerei. I flussi sono da intendersi “indicativi” dello stato del traffico, e non rappresentano con precisione il numero di veicoli transitati. Per maggiori informazioni sul formato dati: progetto SIMONE http://simone.5t.torino.it


**Tipo di flusso:** stream

**Tipo di file:** XML

**Scheda:** http://www.5t.torino.it/wp-content/uploads/2016/04/flussi_traffico_rt.pdf

**URL del flusso:** http://opendata.5t.torino.it/get_fdt

**XML Schema:** http://www.5t.torino.it/simone/ns/traffic_data.xsd 


## Elementi

### traffic_data

Attributi:
- *datatype*: misura / previsione / profilo
- *generation_time*: istante di generazione del feed
- *start_time*: istante di inizio del periodo di aggregazione, in formato standard ISO 8601
- *end_time*: istante di fine del periodo di aggregazione, in formato standard ISO 8601
- *source*: identificativo della fonte dei dati

### traffic_data >> location_reference

### traffic_data >> FDT_data
Flussi di traffico lungo un arco TMC o attraverso una sezione di misura. Il nodo LCD è quello di inizio dell'arco interessato, nella direzione di percorrenza specificata.

Attributi:
- *source*: identificativo della fonte dei dati
- *station_id*: identificativo della stazione di misura (se disponibile)
- *diagnostic*: stato diagnostico del dispositivo
- *lcd1*: Codifica TMC del nodo iniziale dell’arco
- *Road_LCD*: Codifica TMC della strada su cui insiste la stazione di misura
- *Road_name*: Sigla o nome della strada su cui insiste la stazione di misura
- *offset*: distanza dall'inizio dell'arco lungo il verso di percorrenza [m]
- *direction*: direzione di percorrenza TMC (positiva o negativa)
- *lat*
- *lng*
- *heading*: Direzione (angoli nord) di attraversamento della sezione di misura
- *row*: numero di corsie della sezione di misura
- *occupation*: tasso di occupazione dei sensori
- *accuracy*: validità della misura (percentuale)
- *period*: periodo di aggregazione in minuti


### traffic_data >> FDT_data >> speedflow
Dati di flusso e velocità rilevati da una sezione, per tipologia di veicolo

Attributi:
- *VehicleType*: Tipologia di veicolo cui si riferisce il conteggio (all, light, heavy)
- *flow*: Flusso veicolare (veicoli/ora)
- *speed*: Velocità media (Km/h)
- *harmspeed*: Velocità media armonica (Km/h)


## Esempio del flusso

```
<traffic_data xmlns="http://www.5t.torino.it/simone/ns/traffic_data" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://www.5t.torino.it/simone/ns/traffic_data http://www.5t.torino.it/simone/ns/traffic_data.xsd" datatype="misura" generation_time="2017-06-23T13:11:00+02:00" start_time="2017-06-23T13:05:00+02:00" end_time="2017-06-23T13:10:00+02:00" source="matrix.FDT">
	<location_reference>
		<WGS84_info/>
	</location_reference>
	<FDT_data lcd1="40202" Road_LCD="40201" Road_name="Corso Vinzaglio(TO)" offset="55" direction="positive" lat="45.06766" lng="7.66662" accuracy="0" period="5">
		<speedflow flow="564.00" speed="20.67"/>
	</FDT_data>

	// ...

</traffic_data>
```

