# Ministero Infrastrutture e Trasporti: Eventi di traffico attivi CCISS

## Descrizione del dataset
Eventi di traffico certificati, normalmente con la specificazione della causa. Ogni notizia viene aggiornata, incrementandone la versione, fin quando non viene chiusa; la notizia viene rimossa dall'elenco restituito nel giro di un'ora.

Nota: è in corso la definizione di un nuovo servizio su nuova archittura (fine 2018)

**Tipo di dataset:** standard/ordinary?

**Tipo di flusso:** pull

**Tipo di file:** XML

**Scheda:** [specifiche Web Service](resources/SpecificheWS_CCISS_E015-1.0.pdf) (sviluppato per E015)

**URL del flusso:** https://ws.cciss.it/wse015/WS_CCISSEXPOService

**WSDL:** https://ws.cciss.it/wse015/WS_CCISSEXPOService?WSDL

**Modalità di ingestion su DAF:** polling WS a intervalli regolari (ogni 10 min). Accesso consentito previa autenticazione WS-Security

## Elementi (eventiResponse)

### EVENTI >> NOTIZIA
Risultato dell'estrazione contenente gli eventi di traffico (Tipo complesso *eventixmlType*), in particolare Notizia di traffico (Tipo complesso *notiziaxmlType*)

Attributi:
- *numero*: Numero di riferimento della notizia nella piattaforma RTTI-CCISS
- *versione*: Versione della notizia
- *data*: Data di creazione della versione della notizia
- *ora*: Orario di creazione della versione della notizia
- *priorità*: 

Di seguito gli elementi figli

| Nome | Attributo | Tipo   | Descrizione                     |
|------|-----------|--------|---------------------------------|
| locationDBVersion | | number | Versione database Tmc (referenziato nel glosssario E015 - GLS-000001 ) |
| luogo_punto | | number | Codice e descrizione della strada alla quale si riferisce la notizia |
| evento | | number | Codice evento secondo lo standard Datex |
| testo | | number | Corpo della notizia |
| localita | | number | Luogo di inizio o di fine della notizia (Tipo complesso *localitaxmlType*) |
|  | code | number | Codice Strada del punto di inizio o fine della notizia |
|  | lat | number | Latitudine del punto di inizio o fine della notizia in WGS84 |
|  | lng | number | Longitudine del punto di inizio o fine della notizia in WGS84 |
|  | reg | number | Regione del punto di inizio o fine della notizia |
|  | prov | number | Provincia del punto di inizio o fine della notizia |
|  | locid | number | Punto geografico secondo il database TMC (referenziato nel glosssario E015 - GLS-000001) |
|  |tipo | number | Tipo di localita (START, AFFECTED, END) |
| direzione | | number | Direzione di marcia (BACKWARD, FORWARD, NONE) |
| nomedirezione | | number | Descrizione della direzione di marcia |
| tipo | | number | Tipo di notizia: s- Statica; d-Dinamica (es: Lavori – Statica, Code – Dinamica) |

## Esempio del flusso

```
<S:Envelope xmlns:S="http://schemas.xmlsoap.org/soap/envelope/">
   <S:Body>
      <ns2:geteventiResponse xmlns:ns2="http://e015.dtt.it/">
         <EVENTI>
            <NOTIZIA numero="4e61dce1-61d4-4399-9495-8e22c32a10c4" versione="1" data="08/08/2017" ora="17:01" priorita="LOW">
               <locationDBVersion>Non TMC</locationDBVersion>
               <luogo_punto>Via di Porta Pertusa</luogo_punto>
               <evento>ACI</evento>
               <testo>Roma Via di Porta Pertusa
incidente

altezza di viale vaticano</testo>
               <localita code=" " lat="41.90145492553711" lng="12.446136474609375" reg="Lazio" prov="RM" locid=" " tipo="AFFECTED"/>
               <direzione>NONE</direzione>
               <nomedirezione>-</nomedirezione>
               <tipo>d</tipo>
            </NOTIZIA>
            <NOTIZIA numero="98c5b853-81a6-4ec3-bc0d-f59c5cda80fa" versione="1" data="08/08/2017" ora="17:00" priorita="LOW">
               <locationDBVersion>Non TMC</locationDBVersion>
               <luogo_punto>Via Cola di Rienzo</luogo_punto>
               <evento>ACI</evento>
               <testo>Roma Via Cola di Rienzo
incidente

altezza di via fabio massimo</testo>
               <localita code=" " lat="41.90908432006836" lng="12.469758033752441" reg="Lazio" prov="RM" locid=" " tipo="AFFECTED"/>
               <direzione>NONE</direzione>
               <nomedirezione>-</nomedirezione>
               <tipo>d</tipo>
            </NOTIZIA>
            <NOTIZIA numero="cee1fc53-2daf-4373-9bc1-342cc32aab50" versione="1" data="08/08/2017" ora="16:33" priorita="LOW">
               <locationDBVersion>4.1</locationDBVersion>
               <luogo_punto>Incrocio Uscita Via Livorno-Piazza Bologna</luogo_punto>
               <evento>CON</evento>
               <testo>Tangenziale Est (RM)
chiusura notturna causa lavori
a Incrocio Uscita Via Livorno-Piazza Bologna
 in direzione via salaria
dalle 23:00 del 09 ago 2017   alle 06:00 del 10 ago 2017
(circonvallazione nomentana)altezza cavalcavia di via livorno nel tratto compreso tra il civico 259 e via dei monti tiburtini con obbligo di direzione a destra sulla rampa per via livorno per i veicoli provenienti da san giovanni</testo>
               <localita code=" " lat="41.917198181152344" lng="12.52733039855957" reg="Lazio" prov="RM" locid="33061" tipo="START"/>
               <localita code=" " lat="41.91396522521973" lng="12.490149974822998" reg=" " prov=" " locid="33054" tipo="AFFECTED"/>
               <direzione>FORWARD</direzione>
               <nomedirezione>via salaria</nomedirezione>
               <tipo>s</tipo>
            </NOTIZIA>
...
```

