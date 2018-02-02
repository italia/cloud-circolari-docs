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
    <td colspan="3"><strong>Supporto clienti e assistenza tecnica</strong></td>
  </tr>
  <tr>
    <td>RO1</td>
    <td>Il Fornitore Cloud deve mettere a disposizione dell’Acquirente un servizio di supporto tecnico disponibile 24/7 e accessibile mediante opportuni e diversificati canali di comunicazione e adeguati sistemi di gestione (issue tracking), al fine di consentire all’Acquirente di effettuare le eventuali segnalazioni di malfunzionamenti e potenziali pericoli per la sicurezza e la fruibilità del servizio, in completa autonomia.</td>
    <td>Dichiarazione Fornitore Cloud</td>
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
    <td colspan="3"> <strong>Gestione del cambiamento (change management)</strong></td>
  </tr>
  <tr>
    <td>RO4</td>
    <td>Al fine di garantire che vengano utilizzate procedure e metodi standard
        per la gestione tempestiva ed efficiente di ogni cambiamento applicativo e di
        infrastruttura, il Fornitore Cloud deve garantire e dare evidenza del fatto che
        i servizi offerti siano sottoposti ad un ben definito processo di gestione del
        cambiamento.
        <br/><br/><small>Quanto dichiarato deve essere coerente con le certificazioni e le <em>best practises</em> richieste in ambito della sicurezza  (ISO/IEC 27001, ISO/IEC 27017 e ISO/IEC 27018)</small></td>
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
    <td colspan="3"><strong>Gestione della configurazione (configuration management)</strong></td>
  </tr>
  <tr>
    <td>RO7</td>
    <td>Il Fornitore Cloud deve garantire che i servizi offerti siano soggetti
        ad un processo di gestione della configurazione che consente, mediante
        procedure standard e relativi tool, il controllo di tutte le componenti
        (hardware e software) del servizio. 
        <br/><br/><small>Quanto dichiarato deve essere coerente con le certificazioni e le <em>best practises</em> richieste in ambito della sicurezza  (ISO/IEC 27001, ISO/IEC 27017 e ISO/IEC 27018)</small></td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td colspan="3"><strong>Gestione degli Incidenti (incident & problem management)</strong></td>
  </tr>
  <tr>
    <td>RO8</td>
    <td>Il Fornitore Cloud deve garantire che la  gestione degli incidenti
        avvenga mediante procedure standard coerenti con gli  standard di sicurezza internazionali.
         (p.e. ISO/IEC 27002,  ISO/IEC 27035). 
         <br/><br/><small>Quanto dichiarato deve essere coerente con le certificazioni e le <em>best practises</em> richieste in ambito della sicurezza  (ISO/IEC 27001, ISO/IEC 27017 e ISO/IEC 27018)</small></td>
    <td>Dichiarazione Fornitore Cloud</td>
  </tr>
  <tr>
    <td colspan="3"><strong>Best practice e trasparenza</strong></td>
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

```eval_rst
.. discourse::
   :topic_identifier: 2271
```
