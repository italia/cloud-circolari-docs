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

```eval_rst
.. tabularcolumns:: |p{3cm}|p{8cm}|p{3.5cm}|

.. rst-class:: longtable

   +------------------+--------------------------------------------------------------------------------------------------+-----------------------------------------------------+
   | Codice Requisito | Requisito                                                                                        | Elementi di riscontro                               |
   +------------------+--------------------------------------------------------------------------------------------------+-----------------------------------------------------+
   | RSI1             | I servizi Cloud offerti devono essere certificati secondo lo standard ISO/IEC 27001.             | Dichiarazione Fornitore Cloud, Verifica documentale |
   +------------------+--------------------------------------------------------------------------------------------------+-----------------------------------------------------+
   | RSI2             | Al fine di garantire adeguati livelli di  sicurezza e riservatezza dei dati per i servizi Cloud  | Dichiarazione Fornitore Cloud, Verifica documentale |
   |                  | della PA, il Fornitore Cloud deve rendere coerenti i servizi offerti alle best practices         |                                                     |
   |                  | proposte dallo standard  ISO/IEC 27017.                                                          |                                                     |
   |                  |                                                                                                  |                                                     |
   |                  |                                                                                                  |                                                     |
   |                  | (ISO/IEC 27017 è uno standard "auditabile", il certificato di                                    |                                                     |
   |                  | conformità deve essere rilasciato da un ente terzo)                                              |                                                     |
   +------------------+--------------------------------------------------------------------------------------------------+-----------------------------------------------------+
   | RSI3             | Al fine di garantire adeguati livelli di sicurezza e riservatezza dei dati per i servizi Cloud   | Dichiarazione Fornitore Cloud, Verifica documentale |
   |                  | della PA, il Fornitore Cloud deve rendere coerenti i servizi offerti alle best practices         |                                                     |
   |                  | proposte dallo standard  ISO/IEC 27018.                                                          |                                                     |
   |                  |                                                                                                  |                                                     |
   |                  |                                                                                                  |                                                     |
   |                  | (ISO/IEC 27018 è uno standard "auditabile", il certificato di                                    |                                                     |
   |                  | conformità deve essere rilasciato da un ente terzo)                                              |                                                     |
   +------------------+--------------------------------------------------------------------------------------------------+-----------------------------------------------------+
```



 

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

```eval_rst
.. tabularcolumns:: |p{3cm}|p{8cm}|p{3.5cm}|

.. rst-class:: longtable

   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | Codice Requisito | Requisito                                                                                                                                                                                                                                                                                                                                 | Elementi di riscontro          |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | Disponibilità e continuità del servizio                                                                                                                                                                                                                                                                                                                                                       |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | RPE1             | La disponibilità del servizio deve essere adeguata all’utilizzo previsto e corrispondente a quella dichiarata dal Fornitore Cloud.                                                                                                                                                                                                        | Dichiarazione, Fornitore Cloud |
   |                  | Il Fornitore Cloud deve assicurare la disponibilità e fruibilità del servizio                                                                                                                                                                                                                                                             |                                |
   |                  | nella sua interezza: non possono esserci parti di servizio non disponibili o                                                                                                                                                                                                                                                              |                                |
   |                  | non utilizzabili appieno.                                                                                                                                                                                                                                                                                                                 |                                |
   |                  | SLI previsti: SLI01, SLI02, SLI03                                                                                                                                                                                                                                                                                                         |                                |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | Tempi di risposta del servizio                                                                                                                                                                                                                                                                                                                                                                |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | RPE2             | I tempi di risposta del servizio devono essere corrispondenti a quelli                                                                                                                                                                                                                                                                    | Dichiarazione Fornitore Cloud  |
   |                  | dichiarati dal Fornitore senza scostamenti significativi, e comunque entro                                                                                                                                                                                                                                                                |                                |
   |                  | precisi limiti prevedibili e noti a priori, al variare del numero di utenti                                                                                                                                                                                                                                                               |                                |
   |                  | connessi e del carico di lavoro sottoposto al servizio.                                                                                                                                                                                                                                                                                   |                                |
   |                  | SLI previsti: SLI04, SLI05                                                                                                                                                                                                                                                                                                                |                                |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | Performance delle componenti Infrastructure                                                                                                                                                                                                                                                                                                                                                   |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | RPE3             | Servizi che includono la componente Compute Il Fornitore deve                                                                                                                                                                                                                                                                             | Dichiarazione Fornitore Cloud  |
   |                  | dichiarare i valori dei seguenti indicatori per i quali è previsto un livello                                                                                                                                                                                                                                                             |                                |
   |                  | di servizio garantito:                                                                                                                                                                                                                                                                                                                    |                                |
   |                  | disponibilità, massima durata dei periodi di indisponibilità (outage                                                                                                                                                                                                                                                                      |                                |
   |                  | length), tempo medio e massimo di reboot delle VM                                                                                                                                                                                                                                                                                         |                                |
   |                  | SLI previsti: SLI01, SLI13                                                                                                                                                                                                                                                                                                                |                                |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | RPE4             | Servizi che includono la componente Network                                                                                                                                                                                                                                                                                               | Dichiarazione Fornitore Cloud  |
   |                  | Il Fornitore deve dichiarare i valori dei seguenti indicatori per i                                                                                                                                                                                                                                                                       |                                |
   |                  | quali è previsto un livello di servizio garantito:                                                                                                                                                                                                                                                                                        |                                |
   |                  | disponibilità, numero massimo di pacchetti persi (packet loss),                                                                                                                                                                                                                                                                           |                                |
   |                  | larghezza di banda (bandwith), latenza massima,                                                                                                                                                                                                                                                                                           |                                |
   |                  | variazione minima e massima della latenza con cui vengono ricevuti i                                                                                                                                                                                                                                                                      |                                |
   |                  | pacchetti                                                                                                                                                                                                                                                                                                                                 |                                |
   |                  | SLI previsti: SLI01, SLI05                                                                                                                                                                                                                                                                                                                |                                |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | RPE5             | Servizi che includono la componente Storage Il Fornitore deve                                                                                                                                                                                                                                                                             | Dichiarazione Fornitore Cloud  |
   |                  | dichiarare i valori dei seguenti indicatori per i quali è previsto un livello                                                                                                                                                                                                                                                             |                                |
   |                  | di servizio garantito:                                                                                                                                                                                                                                                                                                                    |                                |
   |                  | disponibilità, quantità di dati trasferibili al secondo (sia in input che in output), tempo massimo di ripristino dei dati (max restore time)(*)                                                                                                                                                                                          |                                |
   |                  | latenza massima rispetto alle risorse compute(**)                                                                                                                                                                                                                                                                                         |                                |
   |                  | SLI previsti: SLI01, SLI05                                                                                                                                                                                                                                                                                                                |                                |
   |                  |                                                                                                                                                                                                                                                                                                                                           |                                |
   |                  | \* nel caso di risorse storage utilizzate per servizi di backup                                                                                                                                                                                                                                                                           |                                |
   |                  |                                                                                                                                                                                                                                                                                                                                           |                                |
   |                  | \*\* nel caso di risorse storage utilizzate in associazione a risorse compute                                                                                                                                                                                                                                                             |                                |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | Performance delle componenti Platform                                                                                                                                                                                                                                                                                                                                                         |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | RPE6             | Il Fornitore deve dichiarare i valori dei seguenti indicatori per i quali è previsto un livello di servizio garantito:                                                                                                                                                                                                                    | Dichiarazione Fornitore Cloud  |
   |                  | disponibilità (oppure tempo cumulativo di indisponibilità mensile),                                                                                                                                                                                                                                                                       |                                |
   |                  | tempi massimi di risposta delle componenti PaaS (ad es. database, load balancer, componenti DevOps, middleware),                                                                                                                                                                                                                          |                                |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | RPE7             | Nel caso in cui sia prevista la scalabilità automatica della soluzione PaaS (o di alcune sue componenti), il Fornitore deve specificare e garantire quali siano le condizioni e i tempi di attivazione delle istanze aggiuntive che vengono attivate.                                                                                     | Dichiarazione Fornitore Cloud  |
   |                  |                                                                                                                                                                                                                                                                                                                                           |                                |
   |                  | SLI previsti: SLI06                                                                                                                                                                                                                                                                                                                       |                                |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | RPE8             | La scalabilità automatica del servizio (o di sue componenti) deve attivarsi correttamente al verificarsi delle condizioni operative prestabilite (eventualmente configurabili) e deve garantire che non si verifichino interruzioni nell’erogazione del servizio.                                                                         | Dichiarazione Fornitore Cloud  |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
   | RPE9             | I precedenti requisiti di scalabilità (RPE7 e RPE8) devono essere garantiti sia nel caso di scalabilità crescente che nel caso di decrescita delle risorse allocate. In particolare in fase di decrescita le istanze PaaS/IaaS non più necessarie devono risultare correttamente disattivate in modo da non comportare costi di utilizzo. | Dichiarazione Fornitore Cloud  |
   +------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------+
```



Dettaglio degli indicatori dei livelli di servizio garantiti:

```eval_rst
.. tabularcolumns:: |p{2cm}|p{5cm}|p{7.5cm}|

.. rst-class:: longtable

   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | Codice SLI | Indicatore                                | Descrizione                                                                                                                                   |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI01      | Nome:  Availability                       | La disponibilità può essere calcolata come il tempo totale su un insieme di intervalli temporali definiti meno il tempo di inattività totale. |
   |            | Origine: ISO/IEC 19086-1 / 19086-2        |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI13      | Nome: Time to Service recovery            | Il tempo che intercorre tra l’interruzione del servizio e il suo ripristino.                                                                  |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI14      | Nome:  Mean Time to Service recovery      | Il valore medio su un determinato periodo di tempo di una serie di valori "Time to Service recovery"                                          |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI15      | Nome:  Maximum Time to Service recovery   | Il valore massimo su un determinato periodo di tempo di una serie di valori “Time to Service recovery”                                        |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI16      | Nome:  Numero di Service Failures         | Il numero totale di interruzioni di servizio su un arco temporale.                                                                            |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI05      | Nome: Service Bandwidth                   | La quantità di dati che possono essere trasferiti in un determinato periodo di tempo.                                                         |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI06      | Nome: Elasticity speed                    | Questa quantità descrive quanto velocemente reagisce il servizio alla richiesta di nuove risorse.                                             |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI07      | Nome: Data retention period               | Il periodo di tempo in cui i dati del cliente vengono mantenuti dopo la notifica di cessazione del servizio.                                  |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI08      | Nome: Log retention period                | l periodo di tempo in cui i file di log relativi al servizio vengono conservati dopo la notifica di cessazione del servizio.                  |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI09      | Nome: Support hours                       | Le ore di funzionamento per ogni piano di supporto.                                                                                           |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI10      | Nome: Service Incident Support hours      | Le ore durante le quali il cliente può ottenere supporto specificamente per incidenti legati al servizio.                                     |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI11      | Nome: Maximum First Support Response Time | Il tempo massimo tra la segnalazione del cliente e la risposta iniziale del fornitore.                                                        |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI12      | Nome: Maximum Incident Resolution Time    | Il tempo massimo per risolvere un incidente                                                                                                   |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI17      | Nome:  Backup Interval                    | Il tempo che intercorre tra un backup e l’altro                                                                                               |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI18      | Nome:  Retention period of backup data    | Il periodo di tempo in cui vengono mantenuti i backup da parte del fornitore                                                                  |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI19      | Nome:  Backup restoration testing         | Il numero di test di restore eseguiti durante un determinato periodo di tempo.                                                                |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
   | SLI20      | Nome:  Recovery Time Objective            | Il tempo massimo necessario a ripristinare completamente il servizio dopo un’interruzione                                                     |
   |            | Origine: ISO/IEC 19086-1                  |                                                                                                                                               |
   +------------+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
```



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

```eval_rst
.. tabularcolumns:: |p{3cm}|p{8cm}|p{3.5cm}|

.. rst-class:: longtable

   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | Codice Requisito | Requisito                                                                                                                                                                                                                                                                                                                                                                                   | Elementi di riscontro         |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | Interoperabilità del servizio                                                                                                                                                                                                                                                                                                                                                                                                                  |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | RIP1             | Le soluzioni IaaS/PaaS devono esporre opportune Application Programming Interface (API) di tipo SOAP e/o REST associate alle funzionalità del servizio, per la  gestione e la configurazione del servizio.                                                                                                                                                                                  | Dichiarazione Fornitore Cloud |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | RIP2             | Il Fornitore Cloud deve rendere disponibile una adeguata documentazione tecnica delle API che ne chiarisca l’utilizzo.                                                                                                                                                                                                                                                                      | Dichiarazione Fornitore Cloud |
   |                  |                                                                                                                                                                                                                                                                                                                                                                                             | Verifica documentale          |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | RIP3             | In caso di aggiornamento delle funzionalità del servizio e/o delle relative API deve essere possibile la tracciabilità delle diverse versioni delle API disponibili, allo scopo di consentire evoluzioni non distruttive (versioning). Anche la documentazione tecnica delle API dovrà essere tempestivamente aggiornata.                                                                   | Dichiarazione Fornitore Cloud |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | RIP4             | Devono essere implementate delle limitazioni sul numero di richieste che è possibile sottomettere alle API, collegate alle caratteristiche delle API stesse e della classe di utilizzatori (throttling).                                                                                                                                                                                    | Dichiarazione Fornitore Cloud |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | RIP5             | Deve essere implementata la tracciabilità delle richieste SOAP/REST ricevute e del loro esito (logging e accounting), anche al fine della non ripudiabilità della comunicazione.                                                                                                                                                                                                            | Dichiarazione Fornitore Cloud |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | Portabilità del servizio e dei dati                                                                                                                                                                                                                                                                                                                                                                                                            |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | RIP7             | Deve essere sempre possibile da parte dell’Acquirente, su richiesta oppure in modalità self-service, l’estrazione di una copia completa dei dati memorizzati e gestiti dal servizio (in formato standard, non proprietario e riutilizzabile), ivi compresi i dati derivati quali log e statistiche di utilizzo, nonché le configurazioni del servizio.                                      | Dichiarazione Fornitore Cloud |
   |                  | Tali prerogative devono essere garantite per un periodo di almeno due mesi (phase out) a partire dalla cessazione della fornitura (anche nel caso in cui la cessazione sia stata determinata dalla revoca della qualifica da parte di AgID).                                                                                                                                                |                               |
   |                  |                                                                                                                                                                                                                                                                                                                                                                                             |                               |
   |                  | SLI previsti: SLI07 e SLI08                                                                                                                                                                                                                                                                                                                                                                 |                               |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | RIP8             | Deve essere sempre possibile la migrazione dei dati del servizio verso un altro Fornitore Cloud con conseguente eliminazione permanente dei dati di proprietà dell’Acquirente al termine della procedura di migrazione (inclusi i dati derivati e i dati di backup).                                                                                                                        | Dichiarazione Fornitore Cloud |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | RIP9             | La proprietà dei dati deve essere mantenuta dall’Acquirente anche in seguito ad operazioni di acquisizione o fallimento del Fornitore Cloud. In caso di fallimento, chiusura dell’attività o dismissione del servizio, il Fornitore Cloud deve garantire all’Acquirente di poter recuperare i dati (in formato standard, non proprietario e riutilizzabile) e di poter migrare il servizio. | Dichiarazione Fornitore Cloud |
   |                  | Il periodo di tempo a disposizione dell’Acquirente dovrà consentirgli di completare il recupero dei dati e la migrazione del servizio e non potrà comunque essere inferiore a due mesi.                                                                                                                                                                                                     |                               |
   |                  |                                                                                                                                                                                                                                                                                                                                                                                             |                               |
   |                  | SLI previsti: SLI07 e SLI08                                                                                                                                                                                                                                                                                                                                                                 |                               |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
```



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

```eval_rst

.. tabularcolumns:: |p{3cm}|p{8cm}|p{3.5cm}|

.. rst-class:: longtable

   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | Codice Requisito | Requisito                                                                                                                                                                                                                                                                                                                                         | Tipo di verifica              |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | Riservatezza dei dati                                                                                                                                                                                                                                                                                                                                                                                |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | RCL1             | Il Fornitore Cloud deve indicare per quali aspetti il servizio offerto                                                                                                                                                                                                                                                                            | Dichiarazione Fornitore Cloud |
   |                  | è conforme al regolamento GDPR (General Data Protection Regulation -                                                                                                                                                                                                                                                                              |                               |
   |                  | Regolamento UE 2017/679)                                                                                                                                                                                                                                                                                                                          |                               |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | RCL2             | Il Fornitore Cloud deve rendere noti gli eventuali Stati esteri in cui sono dislocati i data center, propri e/o dell’infrastruttura Cloud utilizzata per erogare anche parzialmente il servizio e/o all’interno dei quali transiteranno anche temporaneamente i dati gestiti dal servizio (ivi compresi i siti di disaster recovery e di backup). | Dichiarazione Fornitore Cloud |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
   | RCL3             | Il Fornitore Cloud, nei casi applicabili, dichiara la conformità ad accordi bilaterali (Privacy Shield EU-USA ecc.) volti alla salvaguardia dei dati elaborati, conservati ed a vario titolo gestiti per erogare il servizio.                                                                                                                     | Dichiarazione Fornitore Cloud |
   +------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-------------------------------+
```


```eval_rst
.. discourse::
   :topic_identifier: 2272
```
