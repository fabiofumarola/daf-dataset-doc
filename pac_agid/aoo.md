# AGID IPA: Aree Organizzative Omogenee

## Descrizione del dataset


**Tipo di dataset:** standard/ordinary?

**Tipo di flusso:** batch

**Tipo di file:** CSV

**Scheda:** http://www.indicepa.gov.it/documentale/n-opendata.php#header

**Modalità di ingestion su DAF:** scarico su SFTP/chiamata periodica a servizio?


## Elementi

Vedi [metadati](resources/Metadati_Open_Data.pdf)


## Esempio del flusso

```
cod_amm	cod_aoo	des_aoo	dat_istituz	Comune	Cap	Provincia	Regione	Indirizzo	Tel	nome_resp	cogn_resp	mail_resp	tel_resp	Fax	mail1	tipo_mail1	mail2	tipo_mail2	mail3	tipo_mail3
055	ASLUMBRIA2	Direzione Generale - Ufficio Protocollo	2013-01-01	Terni	05100	TR	Umbria	V.le D. Bramante n. 37	07442041	Piero	Carsili				aslumbria2@postacert.umbria.it	pec	null	null	null	null
058	ABS	Area Coordinamento Tecnica e Gestione Risorse Materiali	2013-04-05	Tivoli	00019	RM	Lazio	Via Acquaregna 1/15		Daniela	Mezzapiastra	area.risorsematerialietecnica@aslromag.it	0774701060		acquisizione.beni@pec.aslromag.it	pec	null	null	null	null
058	DIP-Prevenzione	Dipartimento di Prevenzione	2013-04-05	Tivoli	00019	RM	Lazio	Via Acquaregna 1/15		Giancarlo	Micarelli	giancarlo.micarelli@aslromag.it	07743589021		direzione.dipartimento.prevenzione@pec.aslromag.it	pec	null	null	null	null
092	AOO-AOB	Azienda Ospedaliera Brotzu	2012-12-04	Cagliari	09134	CA	Sardegna	Piazzale A. Ricchi, 1	0705391	Graziella	Pintus				protocollo.generale@pec.aobrotzu.it	pec	null	null	null	null
093	protgen	Protocollo Generale	2015-01-01	Pordenone	33170	PN	Friuli Venezia Giulia	Via Vecchia Ceramica, 1		Alberto	Fontana				aas5.protgen@certsanita.fvg.it	pec	null	null	null	null
a13_f952	ASLNO	Azienda Sanitaria Locale NO di Novara	2003-12-30	Novara	28100	NO	Piemonte	Viale Roma, 7	0321374532	CLAUDIO	TERUGGI	claudio.teruggi@asl.novara.it	0321374518	0321374519	protocollogenerale@pec.asl.novara.it	pec	null	null	null	null
a1_025	AULSS_1_Dolomiti_Belluno	AULSS_1_Dolomiti_Belluno	2010-05-26	Belluno	32100	BL	Veneto	Via Feltre n. 57	0437516111	Antonella	FABBRI	antonella.fabbri@ulss.belluno.it	0437516712	043727717	protocollo.aulss1@pecveneto.it	pec	null	null	null	null
a1_na	NA1AOO1	Protocollo Generale ASL Napoli 1 Centro	2009-03-31	Napoli	80145	NA	Campania	VIA COMUNALE DEL PRINCIPE 13/A		Liliana	Lodato	liliana.lodato@aslnapoli1centro.it			aslnapoli1centro@pec.aslna1centro.it	pec	null	null	null	null
a1_ss	ASL1SS_DIPPRE	ASSLSS - Dipartimento di Prevenzione	2008-06-09	Sassari	07100	SS	Sardegna	Via Rizzeddu		FRANCESCO	SGARANGELLA				dip.prevenzione@pec.aslsassari.it	pec	null	null	null	null
a1_ss	ASL1SS_DIPSMD	ASSLSS - Dipartimento Salute Mentale e Dipendenze	2008-06-09	Sassari	07100	SS	Sardegna	Via Amendola, 55		MARIA SERENA	ZEDDA				dip.salutementale@pec.aslsassari.it	pec	null	null	null	null
a1_ss	ASL1SS_DIRAMM	ASSLSS - Direzione Amministrativa	2008-06-09	Sassari	07100	SS	Sardegna	Via Catalocchino, 11		ANDREA	MARRAS				dir.amministrativa@pec.aslsassari.it	pec	null	null	null	null
a1_ss	ASL1SS_DIRGEN	ASSLSS - Direzione Generale	2008-06-09	Sassari	07100	SS	Sardegna	Via Catalocchino, 11		FULVIO	MOIRANO				dir.generale@pec.aslsassari.it	pec	null	null	null	null
a1_ss	ASL1SS_DIRSAN	ASSLSS - Direzione Sanitaria	2008-06-09	Sassari	07100	SS	Sardegna	Via Catalocchino, 11		FRANCESCO	ENRICHENS				dir.sanitaria@pec.aslsassari.it	pec	null	null	null	null
a1_ss	ASL1SS_DIRSANPOA	ASSLSS - Direzione Sanitaria PO AHO	2008-06-09	Alghero	07041	SS	Sardegna	Via Don Minzoni		ELIO	MANCA				dir.medica.poaho@pec.aslsassari.it	pec	null	null	null	null
a1_ss	ASL1SS_DISANAHO	ASSLSS - Distretto Sanitario di Alghero	2008-06-09	Alghero	07041	SS	Sardegna	Via degli Orti, 93		MARIA SERENA	ZEDDA				distretto.aho@pec.aslsassari.it	pec	null	null	null	null
a1_ss	ASL1SS_DISANOZ	ASSLSS - Distretto Sanitario di Ozieri	2008-06-09	Ozieri	07014	SS	Sardegna	Via Colle Cappuccini		ANTONIO	SABA	antosaba@aslsassari.it			distretto.oz@pec.aslsassari.it	pec	null	null	null	null
a1_ss	ASL1SS_DISANSS	ASSLSS - Distretto Sanitario di Sassari	2008-06-09	Sassari	07100	SS	Sardegna	Via Zanfarino, 44		NICOLO'	LICHERI	nlicheri@aslsassari.it			distretto.ss@pec.aslsassari.it	pec	null	null	null	null
a1_ss	ASL1SS_GESTDURC	ASSLSS - Gestione DURC	2008-06-09	Sassari	07100	SS	Sardegna	Via Monte Grappa, 82		MARIA DOLORES	SODDU				gestione.durc@pec.aslsassari.it	pec	null	null	null	null
a1_ss	ASL1SS_SERFFORM	ASSLSS - Servizio Formazione	2008-06-09	Sassari	07100	SS	Sardegna	Ex Ospedale San Camillo strada statale Sassari-Sorso		MARIA	PISANU				serv.formazione@pec.aslsassari.it	pec	null	null	null	null


```

