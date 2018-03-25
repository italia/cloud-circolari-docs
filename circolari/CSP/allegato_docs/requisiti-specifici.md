## Requisiti specifici

Il Fornitore Cloud deve dimostrare di essere in grado di erogare i servizi
proposti dal punto di vista tecnologico, rispettando i requisiti specifici
concernenti le seguenti tematiche:

* sicurezza, privacy e protezione dei dati (RSI)
* performance (RPE), 
* interoperabilità e portabilità (RIP), 
* conformità legislativa (RCL).

### Sicurezza, Privacy e protezione dei dati

**RSI1**: Il Fornitore Cloud dichiara di esserere in possesso della
certificazione secondo lo standard ISO/IEC 27001 estesa con i controlli degli
standard ISO/IEC 27017 e ISO/IEC 27018. La certificazione deve essere stata
rilasciata da organismi nazionali di accreditamento riconosciuti dalla Unione
Europea.


### Performance 

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

Per quanto concerne i livelli di servizio garantiti nel loro
complesso, devono essere osservate le seguenti prescrizioni:

* deve essere inclusa la definizione chiara e non ambigua di tutti gli
  indicatori (SLI) e dei relativi valori obiettivo (SLO);
* il SLA deve essere consultabile pubblicamente mediante l’accesso ad un
  apposito URL Web;
* devono essere riportate all’interno del SLA le definizioni di tutti i termini
  specifici riferiti al servizio offerto o di quelli particolarmente rilevanti
  per la comprensione dell’accordo;
* il Fornitore Cloud deve dichiarare esplicitamente e preventivamente il
  periodo di tempo minimo e massimo di conservazione dei dati di monitoraggio
  degli SLI associati a ciascun servizio erogato;
* il Fornitore Cloud comunica al consumatore, tramite report periodico,
  l’andamento degli indicatori (SLI) dei livelli di servizio, evidenziando eventuali 
  anomalie rispetto agli obiettivi dichiarati in fase di qualificazione (SLO).

**RPE1** - Il Fornitore Cloud descrive la performance del servizio utilizzando
gli indicatori nella tabella "Performance" oppure altri indicatori non presenti
in tabella.

**RPE2** - Nel caso in cui sia prevista la scalabilità automatica del servizio
(o di alcune sue componenti), il Fornitore dichiara gli indicatori associati
alle caratteristiche di elasticità e scalabilità.

**RPE3** - Dove prevista la scalabilità automatica del servizio (o di sue componenti) deve
attivarsi correttamente al verificarsi delle condizioni operative prestabilite
(eventualmente configurabili) e deve garantire che non si verifichino
interruzioni nell’erogazione del servizio.

### Interoperabilità e portabilità

I servizi IaaS e PaaS qualificati devono consentire l’interoperabilità
con altri servizi dello stesso tipo, mediante l'utilizzo di standard aperti
(ad es. Open Virtualization Format) ed opportune *Application Programming
Interface* (API). 

Il Fornitore Cloud deve consentire all'Acquirente di poter migrare le
proprie applicazioni verso un altro Fornitore Cloud in maniera semplice e sicura,
garantendo la possibilita di estrarre ed eventualmente eliminare permanentemente 
i propri dati in qualsiasi momento mediante opportuna interfaccia di gestione
ed API. Il Fornitore Cloud garantisce l'assenza di ogni tipo *lock-in* 
dell’Acquirente nei confronti del Fornitore Cloud.


**RIP1** - I servizi IaaS/PaaS espongono opportune Application Programming
Interface (API) di tipo SOAP e/o REST associate alle funzionalità del servizio,
per la gestione e la configurazione del servizio.

**RIP2** - Il Fornitore Cloud rende disponibile una adeguata documentazione
tecnica delle API che ne chiarisca l’utilizzo.

**RIP3** - In caso di aggiornamento delle funzionalità del servizio e/o delle
relative API il Fornitore Cloud garantisce tracciabilità delle diverse versioni
delle API disponibili, allo scopo di consentire evoluzioni non distruttive
(versioning). Anche la documentazione tecnica delle API dovrà essere
tempestivamente aggiornata.

**RIP4** - Il Fornitore Cloud garantisce la possibilità di tracciare le
richieste SOAP/REST ricevute dal servizio e il loro esito (logging e
accounting), anche al fine della non ripudiabilità della comunicazione.

**RIP5** - Il Fornitore Cloud garantisce all'Acquirente la possibilità di
estrarre in qualsiasi momento una copia completa dei dati e metadati
memorizzati (in formato pubblico e aperto) come, a titolo esemplificativo ma
non esaustivo: volumi, object e block storage, dump di DB, ecc.



### Conformità legislativa

Il Fornitore Cloud mette a disposizione dell’Acquirente  gli
strumenti e le informazioni necessarie per consentirgli il rispetto della normativa
Europea ed Italiana nell'ambito dell'utilizzo dei servizi e
dell'infrastruttura qualificata.

**RCL1** - Il Fornitore Cloud deve indicare per quali aspetti il servizio
proposto è conforme agli obblighi e agli adempimenti previsti dalla normativa
(europea e italiana) in materia di protezione dei dati personali.

**RCL2** - Il Fornitore Cloud rende nota la localizzazione dei data center
propri e/o dell’infrastruttura Cloud utilizzata per erogare anche parzialmente
il servizio e/o all’interno dei quali transiteranno anche temporaneamente i
dati gestiti dal servizio (ivi compresi i siti di disaster recovery e di
backup), specificando quando sia all'interno del territorio nazionale,
all'interno della UE o extra UE.

**RCL3** - Il Fornitore Cloud, in caso di localizzazione dei data center in
territorio extra UE, dichiara l'applicabilità di accordi bilaterali (Privacy
Shield EU-USA, ecc.) volti alla salvaguardia dei dati elaborati, conservati ed
a vario titolo gestiti per erogare il servizio.


