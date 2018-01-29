**Allegato alla CIRCOLARE N. XX del YY gennaio 2018**

# Requisiti per la qualificazione dei Cloud Service Provider per la PA 

## Acronimi e definizioni

<table>
  <tr>
    <td>Termine o abbreviazione</td>
    <td>Descrizione</td>
  </tr>
  <tr>
    <td>AgID, Agenzia</td>
    <td>Agenzia per l’Italia Digitale</td>
  </tr>
  <tr>
    <td>Codice /Codice dell’Amministrazione Digitale/CAD</td>
    <td>Decreto Legislativo 7 marzo 2005, n. 82 e s.m.i. </td>
  </tr>
  <tr>
    <td> Cloud della PA</td>
    <td> Il Cloud della PA è composto da Cloud SPC, dai PSN e dagli altri CSP che saranno
         qualificati come compatibili con i requisiti Cloud della PA
   </td>
  </tr>
  <tr>
    <td>Cloud</td>
    <td>Insieme di infrastrutture tecnologiche remote utilizzate come risorsa virtuale per la memorizzazione e/o l’elaborazione nell’ambito di un servizio</td>
  </tr>
  <tr>
    <td>Cloud SPC o SPC Cloud</td>
    <td>Contratto Quadro stipulato da CONSIP con il RTI aggiudicatario della Gara SPC Cloud Lotto 1 (https://www.cloudspc.it)</td>
  </tr>
  <tr>
    <td>CSP</td>
    <td>Cloud Service Provider, fornitore di servizi Cloud</td>
  </tr>
  <tr>
    <td>CSC</td>
    <td>Cloud Service Consumer acquirente e fruitore di servizi erogati in modalità Cloud.</td>
  </tr>
  <tr>
    <td>CSN</td>
    <td>Cloud Service Partner, è un soggetto terzo che può svolgere attività di supporto o di consulenza per conto del CSP, del CSC o di entrambi. </td>
  </tr>
  <tr>
    <td>Fornitore Cloud, CSP, Fornitore</td>
    <td>Soggetto richiedente la qualificazione CSP</td>
  </tr>
  <tr>
    <td>Giorni</td>
    <td>Giorni solari</td>
  </tr>
  <tr>
    <td>Marketplace SaaS </td>
    <td>Piattaforma digitale che permette la selezione e l'acquisto di applicazioni software erogate in Cloud secondo il modello Software-as-a-Service</td>
  </tr>
  <tr>
    <td>Provisioning</td>
    <td>Predisposizione delle risorse Cloud infrastrutturali funzionale all’erogazione di servizi Cloud. Le attività di predisposizione sono eseguite a cura del Fornitore Cloud, tipicamente si tratta di attività automatizzate su risorse virtuali di tipo computazionale, di storage e di rete che vengono attivate e configurate opportunamente.</td>
  </tr>
  <tr>
    <td>Pubbliche amministrazioni/Amministrazioni/PA</td>
    <td>Le Amministrazioni, come meglio definite all’art. 2, comma 2 del Codice dell’Amministrazione Digitale.</td>
  </tr>
  <tr>
    <td>PSN</td>
    <td>Soggetto titolare dell’insieme di infrastrutture IT (centralizzate o distribuite), ad alta disponibilità, di proprietà pubblica, eletto a Polo Strategico Nazionale dalla Presidenza del Consiglio dei Ministri, e qualificato da AgID ad erogare  ad altre amministrazioni, in maniera continuativa e sistematica,   servizi infrastrutturali on-demand, servizi di disaster recovery e business continuity, servizi di gestione della sicurezza IT ed assistenza ai fruitori dei servizi erogati.</td>
  </tr>
  <tr>
    <td>  Platform as a Service,
  PaaS</td>
    <td>Una categoria di servizi cloud in cui le funzionalità cloud offerte sono di tipo programmatico ovvero il CSC può amministrare, dispiegare ed eseguire applicazioni Cloud utilizzando uno o più linguaggi di programmazione, uno o più ambienti di sviluppo/esecuzione supportati dal CSP.</td>
  </tr>
  <tr>
    <td>Infrastructure as a Service, IaaS</td>
    <td>Una categoria di servizi cloud in cui le funzionalità cloud offerte sono di tipo infrastrutturale, tali funzionalità consentono all CSC di disporre autonomamente in modo programmatico di risorse di computing, di storage e networking.</td>
  </tr>
  <tr>
    <td>SLI</td>
    <td>Service Level Indicator, una misura quantitativa definita di un determinato aspetto del livello di servizio (ad es. numero di richieste al secondo, latency, throughput, availability, etc)</td>
  </tr>
  <tr>
    <td>SLO</td>
    <td>Service Level Objective, un valore o un intervallo di valori di riferimento per un livello di servizio misurato da un indicatore (SLI)</td>
  </tr>
  <tr>
    <td>SLA</td>
    <td>Service Level Agreement, un accordo formale che prevede le conseguenze del mancato raggiungimento degli obiettivi (SLO) prefissati relativamente alla qualità del servizio.</td>
  </tr>
  <tr>
    <td>Dati Derivati</td>
    <td>Dati che risiedono sotto il controllo del Cloud Service Provider, originati dall’interazione con il servizio Cloud da parte del Cloud Service Customer. I dati derivati includono tipicamente dati di logging, contenenti informazioni su chi ha utilizzato il servizio, quando lo ha utilizzato e che funzionalità ha utilizzato; possono anche includere informazioni circa il numero di utenti autorizzati e le loro identità; includono tutte le configurazioni e customizzazioni supportate dal servizio.</td>
  </tr>
  <tr>
    <td>Circolare</td>
    <td>Circolare AgID sui "Criteri per la qualificazione dei Cloud Service Provider pubblici per  la  PA".</td>
  </tr>
  <tr>
    <td>MePA</td>
    <td>
      Il Mercato Elettronico della P.A. (MePA) è il mercato digitale gestito da
      CONSIP in cui le Amministrazioni abilitate possono acquistare  per valori
      inferiori alla soglia comunitaria, i beni e servizi offerti da fornitori
      abilitati a presentare i propri cataloghi sul sistema.
    </td>
  </tr>
</table>


Si richiamano inoltre i concetti e le definizioni relativi al *Cloud computing*
pubblicati dal National Institute of Standards and Technologies nel documento
[NIST Special Publication 800-145 "The NIST Definition of Cloud
Computing"](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf)
e quanto definito negli Standard [ISO/IEC
17788:2014](http://standards.iso.org/ittf/PubliclyAvailableStandards/c060544_ISO_IEC_17788_2014.zip)
e [ISO/IEC
17789:2014](http://standards.iso.org/ittf/PubliclyAvailableStandards/c060545_ISO_IEC_17789_2014.zip)
in particolare i concetti di:

* Software as a Service (SaaS), Platform as a service (PaaS), Infrastructure as a Service (IaaS)
* Private Cloud, Community Cloud, Public Cloud, Hybrid Cloud
* le caratteristiche essenziali del Cloud computing: on-demand self-service,
  broad network access, resource pooling, rapid elasticity, measured service.

## Introduzione

Il presente documento definisce nel dettaglio i requisiti, di cui all’art. 3
della Circolare, che il Fornitore Cloud e le soluzioni IaaS/PaaS da esso
proposte devono rispettare per ottenere la qualificazione da parte di AgID
quale "CSP qualificato per il *Cloud della PA*".  Nella richiesta di
qualificazione il Fornitore Cloud può includere uno o più servizi Cloud. Resta
inteso che tutti i servizi per i quali è stata fatta richiesta di
qualificazione devono possedere i requisiti di cui al presente allegato e
dovranno essere conformi alla vigente disciplina nazionale e europea in materia
di protezione dei dati personali (regolamento GDPR - General Data Protection
Regulation - Regolamento UE 2016/679).

Vengono qualificati quei Cloud Service Provider che intendono offrire alla
Pubblica Amministrazione uno o più servizi Cloud appartenenti alle seguenti
categorie: 

* IaaS 
* PaaS

La procedura di qualificazione inizia con la richiesta da parte del Fornitore
Cloud o un suo Partner e procede per mezzo di  verifiche amministrative e
documentali descritte nel presente allegato.

Sono individuati i seguenti soggetti come attori del processo di qualificazione:

* *Fornitore Cloud o CSP*, che fornisce, gestisce e amministra i servizi  Cloud
  infrastrutturali di tipologia IaaS e/o PaaS, che sono  oggetto della
  qualificazione;
* *Acquirente o CSC*, PA che acquisisce e/o  utilizza i servizi Cloud in
  maniera diretta o indiretta mediante l’acquisto di soluzioni SaaS di terzi o
  dello stesso Fornitore Cloud.
* *Partner o CSN*, è un soggetto terzo che può svolgere attività di supporto
  e/o di consulenza per conto del CSP o del CSC. Qualora il partner agisse per
  conto del Fornitore Cloud per mezzo di opportuna delega e dandone visibilità,
  può richiedere la qualificazione per conto del CSP.
* *AgID o Agenzia*, Agenzia per l’Italia Digitale in qualità di soggetto
  responsabile della procedura di qualificazione.

## Requisiti delle soluzioni Cloud

AgID, come indicato all’art. 3 della Circolare, ha classificato i requisiti per
la qualificazione dei Cloud Service Provider e delle soluzioni Cloud come
segue:

* Requisiti preliminari (RP),
* Requisiti organizzativi (RO),
* Requisiti specifici.

Nell’ambito del presente allegato i *requisiti specifici* vengono ulteriormente
raggruppati in:

* sicurezza (RS), 
* privacy e protezione dei dati personali (RPP)
* performance e scalabilità (RPS), 

* interoperabilità e portabilità (RIP), 
* conformità legislativa  (RCL).

### Tipologie di verifiche previste

Nelle sezioni che seguono sono definiti tutti i requisiti previsti per le
soluzioni IaaS/PaaS secondo la classificazione sopra richiamata. 

Le tipologie di verifiche previste sono:

* *Dichiarazione del Fornitore Cloud* - il cui accertamento consiste
  nell’acquisizione da parte di AgID di un atto formale nel quale il Fornitore
  Cloud (a seconda dei casi): 
    * dichiara espressamente la sussistenza di quanto specificato nel requisito;
    * si assume l’obbligo di agire secondo quanto richiesto dal requisito al
      verificarsi di determinate condizioni. 
   
   Nel caso in cui sia previsto un obbligo di agire, la verifica può consistere
   nell’accertare che l’obbligo sia stato riportato correttamente in uno o più
   atti formali (ad esempio, nel contratto di fornitura). Nel caso in cui sia richiesto di
   dichiarare informazioni puntuali e/o descrittive, la verifica consiste
   nell’acquisizione delle specifiche informazioni tramite compilazione da parte
   del Fornitore Cloud dei moduli di registrazione (form) presenti sulla
   piattaforma informatica che supporta il processo di qualificazione.

* *Verifica documentale* - il cui accertamento consiste nella verifica del
  possesso da parte del Fornitore Cloud di idonea documentazione comprovante il
soddisfacimento del requisito. Durante la sottomissione della richiesta di
qualificazione verrà espressamente richiesta la produzione di tale
documentazione. La verifica documentale comprende anche il caso in cui al
Fornitore Cloud sia richiesto di produrre una documentazione tecnica
(manualistica, guida operativa, ecc.) o una certificazione tecnica da
consegnare all’Acquirente nella fase di avvio della fornitura.

## Requisiti preliminari

Al Fornitore Cloud viene richiesto di produrre la documentazione necessaria al
fine di dimostrare: 

* di aver gestito in passato ed essere in grado di gestire "situazioni
  critiche" quali: operazioni di disaster recovery, verifica dell’integrità dei
  dati e eventuale recupero;

* di disporre di un adeguato sistema di gestione della qualità applicato
  all’erogazione dei servizi offerti. 

La tabella seguente riporta i requisiti preliminari e il tipo di verifica
richiesta per ognuno di essi.

<table>
  <tr>
    <td>Codice Requisito</td>
    <td>Requisito</td>
    <td>Elementi di riscontro</td>
  </tr>
  <tr>
    <td>Informazioni necessarie per l’istruttoria</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>


RP1</td>
    <td>Produrre l’elenco dei servizi per i quali si richiede la
        qualificazione, fornendo le informazioni di dettaglio richieste nella "scheda
        tecnica del servizio" e negli ulteriori requisiti che prevedono una
        dichiarazione da parte del Fornitore.
    </td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td>Esperienza del Fornitore Cloud nell’ambito dei servizi IaaS/PaaS</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RP2</td>
    <td>
       Produrre una documentazione storica (almeno 2 case studies negli ultimi 24
       mesi) che fornisca evidenza della gestione di “situazioni critiche” e
       conseguente ripristino dell’infrastruttura (rapporti post mortem).
       Nel caso in cui non si siano registrate “situazioni critiche” negli
       ultimi 24 mesi, può essere prodotta analoga documentazione riferita ai test di
       DR.
    </td>
    <td>Dichiarazione Fornitore Cloud, Verifica documentale</td>
  </tr>
  <tr>
    <td>RP3</td>
    <td>Specificare il sistema e le procedure adottate per la gestione della
        qualità aziendale che vengono applicati anche ai servizi oggetto di
        qualificazione. 
    </td>
    <td>Dichiarazione Fornitore Cloud Verifica Documentale</td>
  </tr>
</table>


## Requisiti organizzativi

Per quanto concerne le soluzioni IaaS/PaaS oggetto di qualificazione, al
Fornitore Cloud viene richiesto di  produrre la documentazione necessaria al
fine di dimostrare il possesso dei seguenti requisiti organizzativi,:

* di disporre un servizio di *supporto clienti* strutturato (24x7) ed in grado
  di coprire le esigenze operative che possono manifestarsi nel contesto
  dell’erogazione dei servizi proposti. 

* di aver adottato procedure formali che disciplinano attività quali: 
    * gestione del cambiamento (change management); 
    * gestione delle configurazioni (configuration management);
    * gestione degli incidenti (sicurezza e infrastruttura);

* di garantire trasparenza e semplicità dell’offerta economica nelle soluzioni contrattuali.

Gli standard di riferimento per questo insieme di requisiti sono quelli che
appartengono alla famiglia ISO/IEC 20000, in particolare gli standard ISO/IEC
20000-1 e ISO/IEC TR 20000-9.

Al fine di garantire un’adeguata gestione della fornitura il Fornitore Cloud
deve permettere all’Acquirente di di amministrare in maniera strutturata e
automatizzata le fasi di acquisto e di gestione/configurazione di ciascun
servizio e, ove applicabile, di tutte le risorse/elementi/funzionalità
associate (ad es. selezione dei template PaaS, configurazione dei server
virtuali, gestione delle risorse di rete, ecc.), garantendo controlli di
coerenza durante tutto il processo. Tali prerogative dovranno essere rese
disponibili almeno attraverso:

* uno strumento (console o pannello) fruibile in modalità Web-based e con accesso sicuro; 
* la disponibilità di API invocabili da remoto in modalità SOAP/REST.

Analoghi strumenti, possibilmente integrati con i precedenti e tra di loro,
dovranno essere messi a disposizione al fine di consentire all’Acquirente il
monitoraggio delle performance e dell’utilizzo delle risorse (compreso
l’accesso ai log), nonché per la gestione amministrativa degli ordini e il
controllo dei costi. Si vedano a tal proposito i requisiti RO11 e RO12.

La tabella seguente riporta i requisiti organizzativi e il tipo di verifica
richiesta per ognuno di essi.

<table>
  <tr>
    <td>Codice Requisito</td>
    <td>Requisito</td>
    <td>Elementi di riscontro</td>
  </tr>
  <tr>
    <td>Supporto clienti e assistenza tecnica</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RO1</td>
    <td>Il Fornitore Cloud deve mettere a disposizione dell’Acquirente un servizio di supporto tecnico disponibile 24/7 e accessibile mediante opportuni e diversificati canali di comunicazione e adeguati sistemi di gestione (issue tracking), al fine di consentire all’Acquirente di effettuare le eventuali segnalazioni di malfunzionamenti e potenziali pericoli per la sicurezza e la fruibilità del servizio, in completa autonomia.</td>
    <td>Dichiarazione Fornitore Cloud
</td>
  </tr>
  <tr>
    <td>RO2</td>
    <td>Il Fornitore Cloud deve assicurare la massima trasparenza nella
        gestione delle segnalazioni,  garantendo all’Acquirente piena visibilità dei
        processi di issue tracking e assistenza tecnica.
        Il Fornitore Cloud deve definire le tempistiche per la presa in carico e
        gestione delle segnalazioni in funzione delle diverse priorità, dichiarando i
        livelli di servizio garantiti.
        SLI previsti: SLI09, SLI10, SLI11, SLI12
    </td>
    <td>Dichiarazione, Fornitore Cloud</td>
  </tr>
  <tr>
    <td>RO3</td>
    <td>I servizi proposti devono essere accompagnati dalla documentazione
        tecnica, dalle guide d’uso e/o altro materiale di supporto, ivi compresa la
        documentazione dettagliata delle API e delle interfacce CLI e GUI se previste
        dal servizio.
    </td>
    <td>Dichiarazione Fornitore Cloud, Verifica documentale </td>
  </tr>
  <tr>
    <td>Gestione del cambiamento (change management)</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RO4</td>
    <td>Al fine di garantire che vengano utilizzate procedure e metodi standard
        per la gestione tempestiva ed efficiente di ogni cambiamento applicativo e di
        infrastruttura, il Fornitore Cloud deve garantire e dare evidenza del fatto che
        i servizi offerti siano sottoposti ad un ben definito processo di gestione del
        cambiamento.
        Quanto dichiarato deve essere coerente con le certificazioni richieste
        in ambito della sicurezza  (ISO 27001, ISO 27017 e ISO 27018)
    </td>
    <td>Dichiarazione Fornitore Cloud, Verifica documentale</td>
  </tr>
  <tr>
    <td>RO5</td>
    <td>Il Fornitore Cloud deve garantire una comunicazione puntuale
        all’Acquirente dei cambiamenti e delle migliorie introdotti in seguito ad
        aggiornamenti apportati alle modalità di funzionamento e fruizione dei servizi
        Cloud erogati.
    </td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td>RO6</td>
    <td>Il Fornitore Cloud deve garantire che la documentazione tecnica sia
        prontamente aggiornata e resa disponibile in seguito ad aggiornamenti apportati
        ai servizi Cloud.
    </td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td>Gestione della configurazione (configuration management)</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RO7</td>
    <td>Il Fornitore Cloud deve garantire che i servizi offerti siano soggetti
        ad un processo di gestione della configurazione che consente, mediante
        procedure standard e relativi tool, il controllo di tutte le componenti
        (hardware e software) del servizio. 
        Quanto dichiarato deve essere coerente con le certificazioni richieste
        in ambito della sicurezza  (ISO 27001, ISO 27017 e ISO 27018)
    </td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td>Gestione degli Incidenti (incident & problem management)</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RO8</td>
    <td>Il Fornitore Cloud deve garantire che la  gestione degli incidenti
        avvenga mediante procedure standard conformi con lo standard di sicurezza ISO
        27001 (e.g. ISO 27002/ ISO 27035). 
        Quanto dichiarato deve essere coerente con le certificazioni richieste
        in ambito della sicurezza  (ISO 27001, ISO 27017 e ISO 27018)
    </td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td>Best practice e trasparenza</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RO9</td>
    <td>Il Fornitore Cloud nell’ambito del contratto con l’Acquirente deve
        dichiarare tutti i livelli di servizio offerti utilizzando le metriche
        descritte nella tabella degli indicatori per i livelli di servizio che trovano
        applicazione.
        I livelli di servizio devono essere espressi rispetto a parametri
        tecnici oggettivi e misurabili.</td>
    <td>Dichiarazione Fornitore Cloud, Verifica documentale</td>
  </tr>
  <tr>
    <td>RO10</td>
    <td>Il Fornitore Cloud deve obbligatoriamente dichiarare i livelli di
        servizio garantiti per quanto riguarda la disponibilità del servizio, le
        performance e le tempistiche di gestione dei malfunzionamenti che possano
        compromettere l’utilizzabilità del servizio da parte dell’Acquirente.
        SLI previsti: SLI01, SLI12, SLI20
    </td>
    <td>Dichiarazione Fornitore Cloud, Verifica documentale</td>
  </tr>
  <tr>
    <td>RO11</td>
    <td>Il Fornitore Cloud deve documentare e rendere disponibile l’accesso a
        strumenti di monitoraggio e di logging, filtrando e restringendo opportunamente
        i risultati agli eventi di interesse dell’Acquirente.
    </td>
    <td>Dichiarazione Fornitore Cloud, Verifica documentale</td>
  </tr>
  <tr>
    <td>RO12</td>
    <td>Il calcolo dei costi imputati all’Acquirente deve essere trasparente e
        accurato, rispettare le condizioni contrattuali ed essere monitorabile
        dall’Acquirente in tempo reale. In aggiunta il Fornitore Cloud dovrà rendere
        disponibile all’Acquirente un set minimo di funzioni (API) che permettano di
        acquisire le informazioni sulle metriche di "billing".
    </td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
</table>


Il fornitore potrà dichiarare e documentare il possesso di ulteriori requisiti
di tipo organizzativo e/o altre certificazioni tecniche che abbiano attinenza
con i servizi Cloud sottoposti alla procedura di qualificazione.

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
    <td>I servizi Cloud offerti devono essere certificati secondo lo standard ISO/IEC 27001</td>
    <td>Dichiarazione Fornitore Cloud, Verifica documentale</td>
  </tr>
  <tr>
    <td>RSI2</td>
    <td>Al fine di garantire adeguati livelli di  sicurezza per i servizi Cloud
        della PA, il Fornitore Cloud deve certificare i servizi offerti in base allo
        standard  ISO/IEC 27017
    </td>
    <td>Dichiarazione Fornitore Cloud, Verifica documentale</td>
  </tr>
  <tr>
    <td>RSI3</td>
    <td>Ai fini di garantire la protezione dei dati personali nell’ambito dei
        servizi Cloud, il Fornitore deve certificare i propri servizi mediante lo standard ISO/IEC 27018.
        (ISO/IEC 27018 è uno standard "auditabile" quindi il certificato di
        conformità deve essere rilasciato da un ente terzo)
    </td>
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
(SLI), ovvero delle metriche che quantificano e/o qualificano alcune grandezze
specifiche del servizio. Si definiscono invece  *obiettivi del livello di
servizio *(SLO) i valori  (o intervalli) massimi e/o minimi degli indicatori
(SLI) che si intendono come garantiti dal servizio. 

Gli accordi contrattuali relativi ai *livelli di servizio *(SLA) vengono
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
    <td>Disponibilità e continuità del servizio</td>
    <td></td>
    <td></td>
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
    <td>Tempi di risposta del servizio</td>
    <td></td>
    <td></td>
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
    <td>Performance delle componenti Infrastructure</td>
    <td></td>
    <td></td>
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
        latenza massima rispetto alle risorse compute(*)
        SLI previsti: SLI01, SLI05
        *nel caso di risorse storage utilizzate per servizi di backup* nel caso di risorse storage utilizzate in 
        associazione a risorse compute*
    </td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td>Performance delle componenti Platform</td>
    <td></td>
    <td></td>
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

Punti da trattare:

* portabilità e interoperabilità tra diversi formati di VM
* portabilità dei dati
* portabilità dei Container

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

I servizi Cloud devono esporre opportune *Application Programming Interface
*(API). Tali API dovranno rifarsi alle migliori pratiche di gestione (API
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
    <td>Interoperabilità del servizio</td>
    <td></td>
    <td></td>
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
    <td>Portabilità del servizio e dei dati</td>
    <td></td>
    <td></td>
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
    <td>Riservatezza dei dati</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RCL1</td>
    <td>Il Fornitore Cloud deve indicare per quali aspetti il servizio offerto è conforme al regolamento GDPR (General Data Protection Regulation- Regolamento UE 2016/679).</td>
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


## Appendice 1 - Impegni contrattuali

Nella tabella che segue si riepilogano i requisiti dai quali scaturiscono
specifici impegni contrattuali e adempimenti formali che dovranno governare il
rapporto di fornitura tra Fornitore Cloud e Acquirente. Per rispettare appieno
i requisiti di qualificazione di cui al presente allegato, le clausole
contrattuali presenti nei contratti di fornitura dovranno essere conformi ai
principi e agli impegni di seguito richiamati.

<table>
  <tr>
    <td>Clausola</td>
    <td>Requisiti</td>
    <td>Adempimenti aggiuntivi</td>
  </tr>
  <tr>
    <td>CL2</td>
    <td>
RO5 – Comunicazione tempestiva di aggiornamenti e modifiche al servizio
RO6 – Aggiornamento tempestivo della documentazione e della manualistica</td>
    <td> </td>
  </tr>
  <tr>
    <td>CL3</td>
    <td>RO9 – Dichiarazione di tutti i livelli di servizio garantiti che trovano applicazione
RO10 – Livelli di servizio garantiti relativamente a disponibilità, performance e gestione malfunzionamenti
RO2 – Livelli di servizio garantiti relativamente alla gestione delle richieste di assistenza</td>
    <td> </td>
  </tr>
  <tr>
    <td>
CL4</td>
    <td>RO11 – Accesso a strumenti di monitoraggio e di logging opportunamente documentato</td>
    <td> </td>
  </tr>
  <tr>
    <td>
CL5
</td>
    <td>RO12 – Monitoraggio in tempo reale delle risorse utilizzate e dei costi imputati</td>
    <td> </td>
  </tr>
  <tr>
    <td>
CL9</td>
    <td>RPS3 – Piano di continuità operativa</td>
    <td>Documento tecnico facente parte della fornitura</td>
  </tr>
  <tr>
    <td>

CL10</td>
    <td>RPS4 – Responsabilità del Fornitore Cloud nel caso di perdita o inconsistenza dei dati a seguito di ripristino da un evento catastrofico o a seguito di migrazione del servizio per altri motivi</td>
    <td> </td>
  </tr>
  <tr>
    <td>


CL11</td>
    <td>RPE – Tempi di risposta del servizio che non subiscono fluttuazioni eccessive al variare del numero di utenti e del carico di lavoro
</td>
    <td>Scheda tecnica del servizio</td>
  </tr>
  <tr>
    <td>




CL12</td>
    <td>RPS7 – Capacità di processamento del servizio che non subisce fluttuazioni eccessive al variare del numero di utenti e del carico di lavoro

RPS8 – Capacità di processamento del servizio che non subisce fluttuazioni eccessive al variare del numero di tenant attivi (nel caso di configurazione multi-tenant)</td>
    <td> </td>
  </tr>
  <tr>
    <td>


CL15</td>
    <td>RIP1 – Presenza API di tipo SOAP/REST
RIP2 – Documentazione tecnica API
RIP3 – Versioning delle API
RIP4 – Limitazioni volumetriche per l’utilizzo delle API  
RIP5 – Tracciabilità delle richieste SOAP/REST</td>
    <td>Documento tecnico facente parte della fornitura</td>
  </tr>
  <tr>
    <td>




CL16</td>
    <td>RIP6 – Possibilità di estrarre i dati gestiti dal servizio in qualsiasi momento, anche dopo il termine della fornitura (periodo di phase-out di almeno due mesi)
RIP7 – Migrazione dei dati del servizio (reversibilità)
RIP8 – Garanzie sulla proprietà e disponibilità dei dati in caso di fallimento/acquisizione del Fornitore Cloud</td>
    <td> </td>
  </tr>
  <tr>
    <td>CL19</td>
    <td>RCL1 – Conformità rispetto al regolamento GDPR</td>
    <td> </td>
  </tr>
  <tr>
    <td>
CL20</td>
    <td>RCL2 – Comunicazione degli eventuali stati esteri in cui risiedono i data center attraverso cui si eroga il servizio</td>
    <td> </td>
  </tr>
</table>


## Appendice 2 - Scheda tecnica del Servizio

 

<table>
  <tr>
    <td> </td>
  </tr>
  <tr>
    <td>Nome del servizio</td>
  </tr>
</table>


 

<table>
  <tr>
    <td>Descrizione generale</td>
  </tr>
  <tr>
    <td>Max 800 caratteri</td>
  </tr>
</table>

<table>
  <tr>
    <td>Elenco delle caratteristiche funzionali</td>
  </tr>
  <tr>
    <td>10 punti elenco + max 200 caratteri/td>
  </tr>
</table>

<table>
  <tr>
    <td>Ambito di applicazione</td>
    <td></td>
  </tr>
  <tr>
    <td>Soggetto richiedente</td>
    <td>Per conto proprio (CSP) / CSN delegato da un CSP</td>
  </tr>
  <tr>
    <td>Cloud deployment model</td>
    <td>Public/Private/Hybrid</td>
  </tr>
  <tr>
    <td>Cloud platform</td>
    <td>Openstack/Amazon AWS/Microsoft Azure/Google Cloud/IBM Bluemix/…..</td>
  </tr>
  <tr>
    <td>Eventuali Servizi correlati</td>
    <td> </td>
  </tr>
  <tr>
    <td>Dipendenze e prerequisiti</td>
    <td> </td>
  </tr>
</table>

<table>
  <tr>
    <td>Supporto Clienti</td>
    <td></td>
  </tr>
  <tr>
    <td>e-mail</td>
    <td> </td>
  </tr>
  <tr>
    <td>Online ticketing</td>
    <td> </td>
  </tr>
  <tr>
    <td>Telefono</td>
    <td> </td>
  </tr>
  <tr>
    <td>Web chat</td>
    <td> </td>
  </tr>
  <tr>
    <td>Tempi di risposta e di risoluzione garantiti</td>
    <td> </td>
  </tr>
  <tr>
    <td>Assistenza on site</td>
    <td>(descrivere se prevista)</td>
  </tr>
  <tr>
    <td>Assistenza remota</td>
    <td>(descrivere se prevista)</td>
  </tr>
</table>

<table>
  <tr>
    <td>Attivazione e disattivazione del servizio</td>
    <td></td>
  </tr>
  <tr>
    <td>Tempi di attivazione e disattivazione</td>
    <td></td>
  </tr>
  <tr>
    <td>Processo di attivazione</td>
    <td></td>
  </tr>
  <tr>
    <td>Processo di disattivazione</td>
    <td></td>
  </tr>
  <tr>
    <td>Estrazione dei dati a seguito di disattivazione</td>
    <td>(descrivere tempistiche e modalità)</td>
  </tr>
  <tr>
    <td>Formati in cui i dati saranno disponibili</td>
    <td> </td>
  </tr>
  <tr>
    <td>Estrazione e formati di altri asset (in seguito a disattivazione)</td>
    <td>(descrivere tempistiche, modalità e formati di VM, Container descriptor files, ecc.)</td>
  </tr>
</table>

<table>
  <tr>
    <td>Reti pubbliche disponibili</td>
    <td></td>
  </tr>
  <tr>
    <td>Rete SPC</td>
    <td>Si/No</td>
  </tr>
  <tr>
    <td>GARR</td>
    <td>Si/No</td>
  </tr>
  <tr>
    <td>Altro</td>
    <td> </td>
  </tr>
  <tr>
    <td> </td>
    <td> </td>
  </tr>
</table>

<table>
  <tr>
    <td>Utilizzo del servizio</td>
    <td></td>
  </tr>
  <tr>
    <td>Web Browser</td>
    <td>Si/No</td>
  </tr>
  <tr>
    <td>Browser supportati</td>
    <td>(elenco dei browser supportati)</td>
  </tr>
  <tr>
    <td>Applicativo da installare</td>
    <td>Si/No</td>
  </tr>
  <tr>
    <td>App Mobile</td>
    <td>Si/No</td>
  </tr>
  <tr>
    <td>Differenze nella fruizione del servizio tra la versione Mobile e la versione Desktop</td>
    <td> </td>
  </tr>
  <tr>
    <td>Accesso via SSH</td>
    <td> </td>
  </tr>
  <tr>
    <td>Accesso via RDP</td>
    <td> </td>
  </tr>
  <tr>
    <td>Altro tipo di accesso</td>
    <td> </td>
  </tr>
  <tr>
    <td>Documentazione</td>
    <td> </td>
  </tr>
  <tr>
    <td>API</td>
    <td>URL    
Autenticazione  
Altre info  
  </td>
  </tr>
  <tr>
    <td>Funzionalità invocabili tramite API e funzionalità che non sono accessibili via API</td>
    <td> </td>
  </tr>
  <tr>
    <td>Documentazione delle API</td>
    <td>URL Web 
PDF           
 </td>
  </tr>
  <tr>
    <td>Presenza di un ambiente di test delle API (sandbox)</td>
    <td>URL    
Autenticazione   
Altro  
 </td>
  </tr>
  <tr>
    <td> </td>
    <td> </td>
  </tr>
</table>


 

 

<table>
  <tr>
    <td>Scalabilità</td>
    <td></td>
  </tr>
  <tr>
    <td>Presente/Assente</td>
    <td> </td>
  </tr>
  <tr>
    <td>Automatica/Manuale</td>
    <td> </td>
  </tr>
  <tr>
    <td>Modalità e condizioni previste per la scalabilità del servizio</td>
    <td>(descrizione)</td>
  </tr>
</table>


 

<table>
  <tr>
    <td>Metriche e statistiche di utilizzo</td>
    <td></td>
  </tr>
  <tr>
    <td>Metriche disponibili</td>
    <td> </td>
  </tr>
  <tr>
    <td>Statistiche disponibili</td>
    <td> </td>
  </tr>
  <tr>
    <td>Report disponibili</td>
    <td> </td>
  </tr>
</table>


 

<table>
  <tr>
    <td>Conformità legislativa</td>
    <td></td>
  </tr>
  <tr>
    <td>Localizzazione dei data centers</td>
    <td>Italia/EU/Extra EU
Elenco nazioni estere 
 </td>
  </tr>
  <tr>
    <td>Conformità GDPR</td>
    <td>Si/No/Parziale
Elementi non conformi 
Tempistiche di adeguamento previste   
 </td>
  </tr>
</table>


 

<table>
  <tr>
    <td>Portabilità dei dati del servizio</td>
    <td></td>
  </tr>
  <tr>
    <td>Dati esportabili</td>
    <td> </td>
  </tr>
  <tr>
    <td>Formati dei dati esportabili</td>
    <td> </td>
  </tr>
  <tr>
    <td>Dati derivati (configurazioni, template, log, ecc.)</td>
    <td> </td>
  </tr>
  <tr>
    <td> </td>
    <td> </td>
  </tr>
</table>


 

 

<table>
  <tr>
    <td>Livelli di servizio garantiti</td>
    <td></td>
  </tr>
  <tr>
    <td>Disponibilità</td>
    <td> </td>
  </tr>
  <tr>
    <td>Tempi di risposta</td>
    <td> </td>
  </tr>
  <tr>
    <td>Capacità di processa mento/carico</td>
    <td> </td>
  </tr>
  <tr>
    <td>Altri indicatori</td>
    <td>Elencare:
 </td>
  </tr>
  <tr>
    <td>Scostamenti massimi tollerabili</td>
    <td>(per ciascun indicatore per cui sono previsti)</td>
  </tr>
  <tr>
    <td>Disponibilità di monitoraggio in tempo reale sullo stato del servizio</td>
    <td>Si/No</td>
  </tr>
  <tr>
    <td>Disponibilità di notifiche via SMS/email degli eventi di indisponibilità del servizio</td>
    <td>Si/No</td>
  </tr>
</table>


 

 

<table>
  <tr>
    <td>Misure di sicurezza e protezione dei dati</td>
    <td></td>
  </tr>
  <tr>
    <td>Controllo da parte dell’utilizzatore sulla localizzazione dei siti in cui verranno memorizzati e processati i dati</td>
    <td> 
Si/No</td>
  </tr>
  <tr>
    <td>Standard di sicurezza dei data center utilizzati per erogare il servizio</td>
    <td>Elenco</td>
  </tr>
  <tr>
    <td>Approccio utilizzato per eseguire test di penetrazione</td>
    <td> </td>
  </tr>
  <tr>
    <td>Frequenza con cui sono eseguiti i test di penetrazione</td>
    <td> </td>
  </tr>
  <tr>
    <td>Approcci utilizzati per proteggere i dati memorizzati dal servizio</td>
    <td> </td>
  </tr>
  <tr>
    <td>Presenza di procedure per la cancellazione permanente dei dati</td>
    <td>Si/No</td>
  </tr>
  <tr>
    <td>Approcci utilizzati per la protezione dei dati in transito nelle reti esterne</td>
    <td>(Ad es. VPN, IPSEC, HTTPS, ecc.)</td>
  </tr>
  <tr>
    <td>Approcci utilizzati per la protezione dei dati in transito nelle reti interne</td>
    <td>(Ad es. VPN, IPSEC, HTTPS, ecc.)</td>
  </tr>
  <tr>
    <td>Meccanismi di autenticazione degli utenti supportati</td>
    <td> </td>
  </tr>
  <tr>
    <td>Possibilità di configurazione/
customizzazione dei meccanismi di autenticazione</td>
    <td>Si/No
(eventuale descrizione)</td>
  </tr>
  <tr>
    <td>Disponibilità di autenticazione a 2 fattori</td>
    <td>Si/No</td>
  </tr>
  <tr>
    <td>Politiche di accesso alle informazioni di audit</td>
    <td>
      * In tempo reale Si/No
      * Differenziata tra utilizzatori e fornitore  	Si/No
      * Tempo minimo e massimo di conservazione delle informazioni di audit
      * Tempo minimo e massimo di conservazione dei log del servizio
    </td>
  </tr>
  <tr>
    <td> </td>
    <td> </td>
  </tr>
  <tr>
    <td> </td>
    <td> </td>
  </tr>
</table>


 

<table>
  <tr>
    <td>Standard e certificazioni</td>
    <td></td>
  </tr>
  <tr>
    <td>Elenco standard</td>
    <td> </td>
  </tr>
  <tr>
    <td>Elenco certificazioni</td>
    <td> </td>
  </tr>
  <tr>
    <td> </td>
    <td> </td>
  </tr>
  <tr>
    <td> </td>
    <td> </td>
  </tr>
</table> 

<table>
  <tr>
    <td>Prezzi e imputazione dei costi</td>
    <td></td>
  </tr>
  <tr>
    <td>Prezzo del servizio</td>
    <td> </td>
  </tr>
  <tr>
    <td>Unità di misura</td>
    <td> </td>
  </tr>
  <tr>
    <td>Altre condizioni</td>
    <td> </td>
  </tr>
  <tr>
    <td> </td>
    <td> </td>
  </tr>
</table>


```eval_rst
.. disqus::
```
