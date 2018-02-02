## Requisiti specifici

Il Fornitore Cloud deve dimostrare di essere in grado di erogare i servizi
proposti dal punto di vista tecnologico, rispettando i requisiti specifici
concernenti le seguenti tematiche:

* sicurezza, privacy e protezione dei dati (RSI)
* performance (RPE), 
* interoperabilità e portabilità (RIP), 
* conformità legislativa (RCL).

### Sicurezza, Privacy e protezione dei dati

Di seguito è riportato il dettaglio dei requisiti di sicurezza, privacy e
protezione dei dati e delle verifiche previste durante la procedura di
qualificazione.

<table>
  <tr>
    <td>Codice Requisito</td>
    <td>Requisito</td>
    <td>Elementi di riscontro</td>
  </tr>
  <tr>
    <td>RSI1</td>
    <td>I servizi Cloud offerti devono essere certificati secondo lo standard ISO/IEC 27001.</td>
    <td>Dichiarazione Fornitore Cloud, Verifica documentale</td>
  </tr>
  <tr>
    <td>RSI2</td>
    <td>Al fine di garantire adeguati livelli di  sicurezza e riservatezza dei dati per i servizi Cloud
        della PA, il Fornitore Cloud deve rendere coerenti i servizi offerti alle <em>best practices</em>
        proposte dallo standard  ISO/IEC 27017.
        <br/><br/><small>(ISO/IEC 27017 è uno standard "auditabile", il certificato di
        conformità deve essere rilasciato da un ente terzo)</small></td>
    <td>Dichiarazione Fornitore Cloud, Verifica documentale</td>
  </tr>
  <tr>
    <td>RSI3</td>
    <td>Al fine di garantire adeguati livelli di sicurezza e riservatezza dei dati per i servizi Cloud
        della PA, il Fornitore Cloud deve rendere coerenti i servizi offerti alle <em>best practices</em>
        proposte dallo standard  ISO/IEC 27018. 
        <br/><br/><small>(ISO/IEC 27018 è uno standard "auditabile", il certificato di
        conformità deve essere rilasciato da un ente terzo)</small></td>
    <td>Dichiarazione Fornitore Cloud, Verifica documentale</td>
  </tr>
</table>


 

### Performance 

Il Fornitore Cloud è tenuto a definire la qualità e l’affidabilità del servizio
durante tutto il suo ciclo di vita. Le pattuizioni relative alla qualità del
servizio costituiscono parte integrante del contratto di fornitura, all’interno
del quale deve essere compresa una specifica sezione relativa ai "livelli di
servizio garantiti" ovvero il Service Level Agreement (SLA).

I livelli di servizio sono definiti dagli *indicatori del livello di servizio*
(**SLI**), ovvero delle metriche che quantificano e/o qualificano alcune grandezze
specifiche del servizio. Si definiscono invece  *obiettivi del livello di servizio* (**SLO**)
i valori  (o intervalli) massimi e/o minimi degli indicatori
(SLI) che si intendono come garantiti dal servizio. 

Gli accordi contrattuali relativi ai *livelli di servizio* (**SLA**) vengono
definiti tramite un’opportuna combinazione degli *obiettivi* (SLO) che il
fornitore intende mantenere per ogni indicatore (SLI).

Il Fornitore Cloud si impegna a monitorare costantemente tali indicatori ed a
fornire all’Acquirente l’accesso ad opportuni strumenti di monitoraggio.

La sezione del contratto di fornitura relativa ai *livelli di servizio
garantiti* deve includere le *penali compensative* che il Fornitore Cloud dovrà
corrispondere all’Acquirente in caso  di mancato rispetto di uno o più valori
obiettivo (SLO). I metodi di quantificazione e le condizioni di riconoscimento
delle penali compensative devono essere inclusi nel contratto ed essere
allineati ai valori e alle condizioni di mercato riscontrabili per servizi
analoghi o appartenenti alla medesima categoria.

Inoltre, per quanto concerne i livelli di servizio garantiti (SLA) nel loro
complesso, devono essere osservate le seguenti prescrizioni:

* deve essere inclusa la definizione chiara e non ambigua di tutti gli
  indicatori (SLI) e dei relativi valori obiettivo (SLO);
* il SLA deve essere consultabile pubblicamente mediante l’accesso ad un
  apposito URL Web;
* devono essere riportate all’interno del SLA le definizioni di tutti i termini
  specifici riferiti al servizio offerto o di quelli particolarmente rilevanti
  per la comprensione dell’accordo;
* deve essere previsto esplicitamente che, se successivamente all’avvio della
  fornitura si dovesse rendere necessaria una qualsiasi modifica ai livelli di
  servizio garantiti, questa dovrà essere preventivamente notificata
  all’Acquirente per ottenerne la sua approvazione;
* il Fornitore Cloud deve dichiarare esplicitamente e preventivamente il
  periodo di tempo minimo e massimo di conservazione dei dati di monitoraggio
  degli SLI associati a ciascun servizio erogato;
* il Fornitore Cloud deve produrre e inviare al consumatore un report periodico
  (con periodicità almeno mensile), contenente il riepilogo dell’andamento dei
  livelli di servizio nel periodo e che evidenzi gli eventuali sforamenti
  rispetto agli SLO e le penali compensative maturate.

Il Fornitore Cloud deve implementare delle politiche e dei piani operativi per
garantire la continuità del servizio (business continuity). Inoltre deve
gestire tempestivamente il ripristino dell’operatività del servizio in seguito
ad eventi catastrofici o imprevisti (disaster recovery).

Il Fornitore Cloud deve dichiarare quali sono le condizioni massime di carico
sopportabili dal servizio sia in termini di numero di utenti concorrenti che
utilizzano il sistema e/o volume di richieste processabili. 

<table>
  <tr>
    <td>Codice Requisito</td>
    <td>Requisito</td>
    <td>Elementi di riscontro</td>
  </tr>
  <tr>
    <td colspan="3"> <strong>Disponibilità e continuità del servizio</strong></td>
  </tr>
  <tr>
    <td>RPE1</td>
    <td>La disponibilità del servizio deve essere adeguata all’utilizzo previsto e corrispondente a quella dichiarata dal Fornitore Cloud.
        Il Fornitore Cloud deve assicurare la disponibilità e fruibilità del servizio
        nella sua interezza: non possono esserci parti di servizio non disponibili o
        non utilizzabili appieno. 
        SLI previsti: SLI01, SLI02, SLI03
    </td>
    <td>Dichiarazione, Fornitore Cloud</td>
  </tr>
  <tr>
    <td colspan="3"><strong>Tempi di risposta del servizio</strong></td>
  </tr>
  <tr>
    <td>RPE2</td>
    <td>I tempi di risposta del servizio devono essere corrispondenti a quelli
        dichiarati dal Fornitore senza scostamenti significativi, e comunque entro
        precisi limiti prevedibili e noti a priori, al variare del numero di utenti
        connessi e del carico di lavoro sottoposto al servizio.
        SLI previsti: SLI04, SLI05
    </td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td colspan="3"><strong>Performance delle componenti Infrastructure</strong></td>
  </tr>
  <tr>
    <td>RPE3</td>
    <td>Servizi che includono la componente Compute Il Fornitore deve
        dichiarare i valori dei seguenti indicatori per i quali è previsto un livello
        di servizio garantito:
        disponibilità, massima durata dei periodi di indisponibilità (outage
        length), tempo medio e massimo di reboot delle VM
        SLI previsti: SLI01, SLI13 
    </td>
    <td>Dichiarazione Fornitore Cloud </td>
  </tr>
  <tr>
    <td>RPE4</td>
    <td>Servizi che includono la componente Network
        Il Fornitore deve dichiarare i valori dei seguenti indicatori per i
        quali è previsto un livello di servizio garantito:
        disponibilità, numero massimo di pacchetti persi (packet loss),
        larghezza di banda (bandwith), latenza massima,
        variazione minima e massima della latenza con cui vengono ricevuti i
        pacchetti
        SLI previsti: SLI01, SLI05
    </td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td>RPE5</td>
    <td>Servizi che includono la componente Storage Il Fornitore deve
        dichiarare i valori dei seguenti indicatori per i quali è previsto un livello
        di servizio garantito: 
        disponibilità, quantità di dati trasferibili al secondo (sia in input che in output), tempo massimo di ripristino dei dati (max restore time)(*)
        latenza massima rispetto alle risorse compute(**)
        SLI previsti: SLI01, SLI05
        * nel caso di risorse storage utilizzate per servizi di backup
        ** nel caso di risorse storage utilizzate in associazione a risorse compute
    </td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td colspan="3"> <strong>Performance delle componenti Platform</strong></td>
  </tr>
  <tr>
    <td>RPE6</td>
    <td>Il Fornitore deve dichiarare i valori dei seguenti indicatori per i quali è previsto un livello di servizio garantito:
disponibilità (oppure tempo cumulativo di indisponibilità mensile),
tempi massimi di risposta delle componenti PaaS (ad es. database, load balancer, componenti DevOps, middleware),</td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td>RPE7</td>
    <td>Nel caso in cui sia prevista la scalabilità automatica della soluzione PaaS (o di alcune sue componenti), il Fornitore deve specificare e garantire quali siano le condizioni e i tempi di attivazione delle istanze aggiuntive che vengono attivate.

SLI previsti: SLI06</td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td>RPE8</td>
    <td>La scalabilità automatica del servizio (o di sue componenti) deve attivarsi correttamente al verificarsi delle condizioni operative prestabilite (eventualmente configurabili) e deve garantire che non si verifichino interruzioni nell’erogazione del servizio.</td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td>RPE9</td>
    <td>I precedenti requisiti di scalabilità (RPE7 e RPE8) devono essere garantiti sia nel caso di scalabilità crescente che nel caso di decrescita delle risorse allocate. In particolare in fase di decrescita le istanze PaaS/IaaS non più necessarie devono risultare correttamente disattivate in modo da non comportare costi di utilizzo.</td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
</table>


Dettaglio degli indicatori dei livelli di servizio garantiti:

<table>
  <tr>
    <td>Codice SLI</td>
    <td>Indicatore</td>
    <td>Descrizione</td>
  </tr>
  <tr>
    <td>SLI01</td>
    <td>Nome:  Availability
Origine: ISO/IEC 19086-1 / 19086-2</td>
    <td>La disponibilità può essere calcolata come il tempo totale su un insieme di intervalli temporali definiti meno il tempo di inattività totale.</td>
  </tr>
  <tr>
    <td>SLI13</td>
    <td>Nome: Time to Service recovery
Origine: ISO/IEC 19086-1</td>
    <td>Il tempo che intercorre tra l’interruzione del servizio e il suo ripristino.</td>
  </tr>
  <tr>
    <td>SLI14</td>
    <td>Nome:  Mean Time to Service recovery
Origine: ISO/IEC 19086-1</td>
    <td>Il valore medio su un determinato periodo di tempo di una serie di valori "Time to Service recovery"</td>
  </tr>
  <tr>
    <td>SLI15</td>
    <td>Nome:  Maximum Time to Service recovery
Origine: ISO/IEC 19086-1</td>
    <td>Il valore massimo su un determinato periodo di tempo di una serie di valori “Time to Service recovery”</td>
  </tr>
  <tr>
    <td>SLI16</td>
    <td>Nome:  Numero di Service Failures
Origine: ISO/IEC 19086-1</td>
    <td>Il numero totale di interruzioni di servizio su un arco temporale.</td>
  </tr>
  <tr>
    <td>SLI05</td>
    <td>Nome: Service Bandwidth  
Origine: ISO/IEC 19086-1</td>
    <td>La quantità di dati che possono essere trasferiti in un determinato periodo di tempo.</td>
  </tr>
  <tr>
    <td>SLI06</td>
    <td>Nome: Elasticity speed  
Origine: ISO/IEC 19086-1</td>
    <td>Questa quantità descrive quanto velocemente reagisce il servizio alla richiesta di nuove risorse.</td>
  </tr>
  <tr>
    <td>SLI07</td>
    <td>Nome: Data retention period  
Origine: ISO/IEC 19086-1</td>
    <td>Il periodo di tempo in cui i dati del cliente vengono mantenuti dopo la notifica di cessazione del servizio.</td>
  </tr>
  <tr>
    <td>SLI08</td>
    <td>Nome: Log retention period  
Origine: ISO/IEC 19086-1</td>
    <td>l periodo di tempo in cui i file di log relativi al servizio vengono conservati dopo la notifica di cessazione del servizio.</td>
  </tr>
  <tr>
    <td>SLI09</td>
    <td>Nome: Support hours  
Origine: ISO/IEC 19086-1</td>
    <td>Le ore di funzionamento per ogni piano di supporto.</td>
  </tr>
  <tr>
    <td>SLI10</td>
    <td>Nome: Service Incident Support hours  
Origine: ISO/IEC 19086-1</td>
    <td>Le ore durante le quali il cliente può ottenere supporto specificamente per incidenti legati al servizio.</td>
  </tr>
  <tr>
    <td>SLI11</td>
    <td>Nome: Maximum First Support Response Time   
Origine: ISO/IEC 19086-1</td>
    <td>Il tempo massimo tra la segnalazione del cliente e la risposta iniziale del fornitore.</td>
  </tr>
  <tr>
    <td>SLI12</td>
    <td>Nome: Maximum Incident Resolution Time   
Origine: ISO/IEC 19086-1</td>
    <td>Il tempo massimo per risolvere un incidente</td>
  </tr>
  <tr>
    <td>SLI17</td>
    <td>Nome:  Backup Interval
Origine: ISO/IEC 19086-1</td>
    <td>Il tempo che intercorre tra un backup e l’altro</td>
  </tr>
  <tr>
    <td>SLI18</td>
    <td>Nome:  Retention period of backup data
Origine: ISO/IEC 19086-1</td>
    <td>Il periodo di tempo in cui vengono mantenuti i backup da parte del fornitore</td>
  </tr>
  <tr>
    <td>SLI19</td>
    <td>Nome:  Backup restoration testing
Origine: ISO/IEC 19086-1</td>
    <td>Il numero di test di restore eseguiti durante un determinato periodo di tempo.</td>
  </tr>
  <tr>
    <td>SLI20</td>
    <td>Nome:  Recovery Time Objective
Origine: ISO/IEC 19086-1</td>
    <td>Il tempo massimo necessario a ripristinare completamente il servizio dopo un’interruzione</td>
  </tr>
</table>


### Interoperabilità e portabilità

Le soluzioni IaaS e PaaS devono consentire l’interoperabilità dei sistemi tra
diversi ambienti Cloud in uso presso il medesimo Acquirente. Devono inoltre
essere presenti caratteristiche di portabilità atte ad evitare il lock-in
dell’Acquirente rispetto al Fornitore Cloud, nonché rispetto a specifici
servizi (oppure feature) offerti.

A tal proposito i servizi che erogano virtual machines devono prevedere
opportuni meccanismi di compatibilità e/o convertibilità da e verso formati
basati su standard (ad es. Open Virtualization Format). Gli strumenti di
importazione/esportazione e i tool di conversione devono essere messi a
disposizione dal Fornitore Cloud ed essere corredati da opportuna
documentazione.

Anche per quanto riguarda i servizi basati su virtualizzazione di tipo
"Container", occorre evitare il lock-in e garantire la massima portabilità,
attuando i seguenti principi:

* stack tecnologico per i container non strettamente correlato ad altre
  componenti a corredo quali orchestration engine, container catalogue, ecc. 
* stack tecnologico non strettamente legato ad un particolare fornitore
  commerciale 
* container interoperabili e compatibili con un’ampia varietà di sistemi
  operativi, architetture hardware, public Clouds.

I servizi Cloud devono esporre opportune *Application Programming Interface*
(API). Tali API dovranno rifarsi alle migliori pratiche di gestione (API
management), prevedendo in particolare la tracciabilità delle versioni
disponibili, la tracciabilità delle richieste ricevute ed evase, la
documentazione degli endpoint SOAP e/o REST disponibili e delle rispettive
modalità di invocazione.

Deve essere sempre possibile la migrazione dell’Acquirente verso un altro
Fornitore Cloud. L’Acquirente deve essere messo nella condizione di poter
estrarre ed eventualmente eliminare permanentemente i propri dati in qualsiasi
momento mediante interfaccia di gestione e mediante API.  

La proprietà dei dati deve essere mantenuta dall’Acquirente durante tutto il
ciclo di vita del servizio, anche in seguito ad operazioni di acquisizione o
fallimento del Fornitore.

<table>
  <tr>
    <td>Codice Requisito</td>
    <td>Requisito</td>
    <td>Elementi di riscontro</td>
  </tr>
  <tr>
    <td colspan="3"> <strong>Interoperabilità del servizio</strong></td>
  </tr>
  <tr>
    <td>RIP1</td>
    <td>Le soluzioni IaaS/PaaS devono esporre opportune Application Programming Interface (API) di tipo SOAP e/o REST associate alle funzionalità del servizio, per la  gestione e la configurazione del servizio.</td>
    <td>Dichiarazione Fornitore Cloud
</td>
  </tr>
  <tr>
    <td>RIP2</td>
    <td>Il Fornitore Cloud deve rendere disponibile una adeguata documentazione tecnica delle API che ne chiarisca l’utilizzo.</td>
    <td>Dichiarazione Fornitore Cloud
Verifica documentale</td>
  </tr>
  <tr>
    <td>RIP3</td>
    <td>In caso di aggiornamento delle funzionalità del servizio e/o delle relative API deve essere possibile la tracciabilità delle diverse versioni delle API disponibili, allo scopo di consentire evoluzioni non distruttive (versioning). Anche la documentazione tecnica delle API dovrà essere tempestivamente aggiornata.</td>
    <td>Dichiarazione Fornitore Cloud
 </td>
  </tr>
  <tr>
    <td>RIP4</td>
    <td>Devono essere implementate delle limitazioni sul numero di richieste che è possibile sottomettere alle API, collegate alle caratteristiche delle API stesse e della classe di utilizzatori (throttling).</td>
    <td>Dichiarazione Fornitore Cloud
 </td>
  </tr>
  <tr>
    <td>RIP5</td>
    <td>Deve essere implementata la tracciabilità delle richieste SOAP/REST ricevute e del loro esito (logging e accounting), anche al fine della non ripudiabilità della comunicazione.</td>
    <td>Dichiarazione Fornitore Cloud
 </td>
  </tr>
  <tr>
    <td colspan="3"> <strong>Portabilità del servizio e dei dati</strong></td>
  </tr>
  <tr>
    <td>RIP7</td>
    <td>Deve essere sempre possibile da parte dell’Acquirente, su richiesta oppure in modalità self-service, l’estrazione di una copia completa dei dati memorizzati e gestiti dal servizio (in formato standard, non proprietario e riutilizzabile), ivi compresi i dati derivati quali log e statistiche di utilizzo, nonché le configurazioni del servizio.
Tali prerogative devono essere garantite per un periodo di almeno due mesi (phase out) a partire dalla cessazione della fornitura (anche nel caso in cui la cessazione sia stata determinata dalla revoca della qualifica da parte di AgID).

SLI previsti: SLI07 e SLI08</td>
    <td>Dichiarazione Fornitore Cloud
 </td>
  </tr>
  <tr>
    <td>RIP8</td>
    <td>Deve essere sempre possibile la migrazione dei dati del servizio verso un altro Fornitore Cloud con conseguente eliminazione permanente dei dati di proprietà dell’Acquirente al termine della procedura di migrazione (inclusi i dati derivati e i dati di backup).</td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td>RIP9</td>
    <td>La proprietà dei dati deve essere mantenuta dall’Acquirente anche in seguito ad operazioni di acquisizione o fallimento del Fornitore Cloud. In caso di fallimento, chiusura dell’attività o dismissione del servizio, il Fornitore Cloud deve garantire all’Acquirente di poter recuperare i dati (in formato standard, non proprietario e riutilizzabile) e di poter migrare il servizio.
Il periodo di tempo a disposizione dell’Acquirente dovrà consentirgli di completare il recupero dei dati e la migrazione del servizio e non potrà comunque essere inferiore a due mesi.

SLI previsti: SLI07 e SLI08</td>
    <td>Dichiarazione Fornitore Cloud
 </td>
  </tr>
</table>


### Conformità legislativa

Il Fornitore Cloud dovrà mettere a disposizione dell’Acquirente tutti gli
strumenti necessari per consentirgli di essere conforme alla legislazione
corrente.

Per consentire all’Acquirente di venire a conoscenza e valutare potenziali
incompatibilità o restrizioni legislative, il Fornitore Cloud deve rendere noti
gli eventuali Stati esteri in cui sono dislocati i data center  tramite i quali
verrà erogato anche parzialmente il servizio e/o all’interno dei quali
transiteranno anche temporaneamente i dati gestiti dal servizio.

Dettaglio dei requisiti per la conformità legislativa:

<table>
  <tr>
    <td>Codice Requisito</td>
    <td>Requisito</td>
    <td>Tipo di verifica</td>
  </tr>
  <tr>
    <td colspan="3"><strong>Riservatezza dei dati</strong></td>
  </tr>
  <tr>
    <td>RCL1</td>
    <td>Il Fornitore Cloud deve indicare per quali aspetti il servizio offerto
        è conforme al regolamento GDPR (General Data Protection Regulation -
        Regolamento UE 2017/679)
    </td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td>
RCL2</td>
    <td>Il Fornitore Cloud deve rendere noti gli eventuali Stati esteri in cui sono dislocati i data center, propri e/o dell’infrastruttura Cloud utilizzata per erogare anche parzialmente il servizio e/o all’interno dei quali transiteranno anche temporaneamente i dati gestiti dal servizio (ivi compresi i siti di disaster recovery e di backup).</td>
    <td>Dichiarazione Fornitore Cloud
</td>
  </tr>
  <tr>
    <td>RCL3</td>
    <td>Il Fornitore Cloud, nei casi applicabili, dichiara la conformità ad accordi bilaterali (Privacy Shield EU-USA ecc.) volti alla salvaguardia dei dati elaborati, conservati ed a vario titolo gestiti per erogare il servizio.</td>
    <td>Dichiarazione Fornitore Cloud
</td>
  </tr>
</table>

```eval_rst
.. discourse::
   :topic_identifier: 2272
```
