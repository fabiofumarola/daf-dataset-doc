# AGID IPA: Unità organizzative

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
cod_ou	cod_aoo	des_ou	comune	Cap	provincia	Regione	Indirizzo	Tel	nome_resp	cogn_resp	mail_resp	tel_resp	cod_amm	cod_ou_padre	Fax	cod_uni_ou	mail1	tipo_mail1	mail2	tipo_mail2	mail3	tipo_mail3
serfin	aooac	Settore Risorse Finanziarie	Moncalieri	10024	TO	Piemonte	Piazza Vittorio Emanuele II snc	0116401370	Cinzia	Miglietta	cinzia.miglietta@comune.moncalieri.to.it	0116401238	c_f335	null		E6QQA8	ragioneria@cert.comune.moncalieri.to.it	pec	protocollo@cert.comune.moncalieri.to.it	pec	null	null
sertec	aooac	Settore Servizi Ambientali e Reti	Moncalieri	10024	TO	Piemonte	Piazza Vittorio Emanuele II snc	0116401203	Teresa	Pochettino	teresa.pochettino@comune.moncalieri.to.it	0116401426	c_f335	null		LSNGG6	protocollo@cert.comune.moncalieri.to.it	pec	null	null	null	null
comlav	aooac	Settore Gestione e Sviluppo del Territorio	Moncalieri	10024	TO	Piemonte	Piazza Vittorio Emanuele II snc	0116401406	Nicola	Palla	nicola.palla@comune.moncalieri.to.it	0116401415	c_f335	null		B1L66B	protocollo@cert.comune.moncalieri.to.it	pec	null	null	null	null
adsrm01	adsrm	Ufficio I - Affari Generali e Personale	Roma	00186	RM	Lazio	Via dei Portoghesi, 12		Marzia	Serafino		0668210331	avvst	null	0668211273	AEI7C6	ufficio1.affarigenerali@avvocaturastato.it	altro	ufficio1.affarigenerali@mailcert.avvocaturastato.it	pec	null	null
adsrm03	adsrm	Ufficio III - Ragioneria	Roma	00186	RM	Lazio	Via del Clementino, 91/A Roma		Stefano	Arisi		066829246	avvst	null	0668897604	GFKF80	ufficio3.ragioneria@avvocaturastato.it	altro	ufficio3.ragioneria@mailcert.avvocaturastato.it	pec	null	null
adsrm04	adsrm	Ufficio IV - Economato	Roma	00186	RM	Lazio	Via dei Portoghesi, 12		Ugo	Centore		066829326	avvst	null	066829477	M0SGGF	ufficio4.economato@avvocaturastato.it	altro	ufficio4.economato@mailcert.avvocaturastato.it	pec	null	null
adsrm05	adsrm	Ufficio V - Archivio e Impianti	Roma	00186	RM	Lazio	Via dei Portoghesi, 12		Clara	Gerra Collina		066829275	avvst	null	0696514000	NDE5FN	roma@mailcert.avvocaturastato.it	pec	null	null	null	null
adsrm06	adsrm	Ufficio VI - Collaborazione Professionale	Roma	00186	RM	Lazio	Via dei Portoghesi, 12		Concetta	D'Addazio		066829382	avvst	null	0668897656	BKOBQ2	concetta.daddazio@avvocaturastato.it	altro	null	null	null	null
adsrm07	adsrm	Ufficio VII - Attivita' Esterna e Agenda	Roma	00186	RM	Lazio	Via dei Portoghesi, 12		Ida	Conti		066829483	avvst	null	066829227	M8GBF6	ufficio7.attivitaesterna@avvocaturastato.it	altro	ufficio7.attivitaesterna@mailcert.avvocaturastato.it	pec	null	null
adsrm08	adsrm	Ufficio VIII - Liquidazione e Recupero Onorari	Roma	00186	RM	Lazio	Via del Clementino, 91/A Roma		Franca	Colonia		0668897566	avvst	null	0668897579	IOFABO	ufficio8.liquidazione@avvocaturastato.it	altro	ufficio8.liquidazione@mailcert.avvocaturastato.it	pec	null	null
adsrm09	adsrm	Ufficio IX - Documentazione Giuridica	Roma	00186	RM	Lazio	Via dei Portoghesi, 12		Tommaso	Capezzone	tommaso.capezzone@avvocaturastato.it	066829436	avvst	null	0668897641	A4OGLC	ufficio9.documentazione@avvocaturastato.it	altro	ufficio9.documentazione@mailcert.avvocaturastato.it	pec	null	null
adsrm10	adsrm	Ufficio X - Rilevazione ed Elaborazione Dati	Roma	00186	RM	Lazio	Via del Clementino, 91/A Roma		Antonia	Consiglio		066829410	avvst	null	066829719	OGQALD	ufficio10.ced@avvocaturastato.it	altro	null	null	null	null
7	RSERVIZI	Albo Spedizione Notifiche	Riva del Garda	38066	TN	Trentino Alto Adige	Piazza Tre Novembre, 5	0464573888	Lorenza	Moresco		0464573888	c_h330	null	0464552410	CB47F2	morescolorenza@comune.rivadelgarda.tn.it	altro	null	null	null	null
226	RSERVIZI	Asili	Riva del Garda	38066	TN	Trentino Alto Adige	Piazza Tre Novembre, 5	0464573888	Anna	Cattoi		0464573821	c_h330	null	0464552410	AFBQRJ	cattoianna@comune.rivadelgarda.tn.it	altro	null	null	null	null
45	RSERVIZI	Attivita' Economiche 	Riva del Garda	38066	TN	Trentino Alto Adige	Piazza Tre Novembre, 5	0464573888	Giorgio	Matteotti		0464573861	c_h330	null	0464552410	4HFK5R	matteottigiorgio@comune.rivadelgarda.tn.it	altro	null	null	null	null
16	RSERVIZI	Biblioteca	Riva del Garda	38066	TN	Trentino Alto Adige	Piazza Garibaldi 5	0464573806	Anna	Cattoi		0464573821	c_h330	null	0464573807	FG3B4P	cattoianna@comune.rivadelgarda.tn.it	altro	biblioteca@comune.rivadelgarda.tn.it	altro	null	null
57	RSERVIZI	Contabilita'	Riva del Garda	38066	TN	Trentino Alto Adige	Piazza Tre Novembre, 5	0464573888	Paolo	Faitelli		0464573830	c_h330	null	0464552410	OSCMAC	faitellipaolo@Comune.rivadelgarda.tn.it	altro	null	null	null	null
50	RSERVIZI	Demografici Anagrafe	Riva del Garda	38066	TN	Trentino Alto Adige	Piazza Tre Novembre, 5	0464573888	Fausto	Bortolameotti	bortolameottifausto@comune.rivadelgarda.tn.it	0464573884	c_h330	null	0464573881	6MGB19	demografici@pec.comune.rivadelgarda.tn.it	pec	null	null	null	null
52	RSERVIZI	Demografici Elettorale	Riva del Garda	38066	TN	Trentino Alto Adige	Piazza Tre Novembre, 5	0464573888	Fausto	Bortolameotti	bortolameottifausto@comune.rivadelgarda.tn.it	0464573884	c_h330	null	0464552410	EBII9H	demografici@pec.comune.rivadelgarda.tn.it	pec	null	null	null	null


```

