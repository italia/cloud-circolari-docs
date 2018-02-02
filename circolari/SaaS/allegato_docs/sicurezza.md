## Sicurezza

Il Fornitore SaaS, prima della messa in esercizio della soluzione SaaS, deve garantire che il codice applicativo sia stato sviluppato seguendo i principi dello sviluppo sicuro.  Il fornitore deve dichiarare se il software viene sottoposto a periodiche verifiche di sicurezza secondo il framework OWASP, in particolare a seguito di operazioni di manutenzione del servizio (aggiornamenti e modifiche).

Il Fornitore SaaS può utilizzare componenti software realizzate da terze parti per implementare la propria applicazione (middleware, librerie o una qualsiasi delle componenti dello stack applicativo). In questi casi egli deve necessariamente rendersi garante anche della sicurezza di queste componenti. Deve essere quindi garantita la sicurezza dell’intera supply chain relativa all’applicazione SaaS (includendo anche il sistema operativo).

Deve essere presente un sistema di Identity & Access Management con una o più figure di amministrazione e diverse figure con privilegi di accesso differenziati e gerarchici. Il trattamento sicuro dei dati è indispensabile per prevenire possibili perdite di dati oppure l’accesso non protetto ai dati da parte di persone non autorizzate. Una gestione accurata delle credenziali di accesso permette di evitare la compromissione dell’applicazione stessa o dell’ambiente in cui è ospitata. Le informazioni in transito tra le varie componenti del sistema devono essere adeguatamente protette e cifrate.

Le risorse IaaS/PaaS e i software ospitati nella piattaforma Cloud (di base, middleware e applicativi) devono essere protetti dal traffico di rete indesiderato e/o dannoso, garantendo la sicurezza dei dati, del software e degli account utente, nonché prestazioni di rete non degradate.

Il Fornitore SaaS deve dotarsi di una adeguata organizzazione e di procedure operative in grado di gestire attività continue e documentabili di aggiornamenti e migliorie in tema di sicurezza. Deve inoltre gestire tempestivamente eventuali situazioni emergenziali.

Il Fornitore SaaS deve garantire che il verificarsi di incidenti di sicurezza oppure gravi disfunzioni del servizio (ad esempio nel caso di denial of service) siano prontamente rilevati e gestiti.

Di seguito è riportato il dettaglio dei requisiti di sicurezza e delle verifiche previste durante la procedura di qualificazione.

<table>
  <tr>
    <td>Codice Requisito</td>
    <td>Requisito</td>
    <td>Elementi di riscontro</td>
  </tr>
  <tr>
    <td>Sicurezza del codice e delle interfacce</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RS1</td>
    <td>Il Fornitore SaaS deve indicare se la soluzione SaaS  è stata sottoposta e ha superato i test OWASP.</td>
    <td>Dichiarazione Fornitore SaaS
</td>
  </tr>
  <tr>
    <td>RS2</td>
    <td>Il codice binario ed eventualmente il codice sorgente (se disponibile) devono essere sottoposti a verifiche che tendono ad identificare eventuali vulnerabilità o la presenza di codice malevolo (worm, trojans, ecc.) prima della messa in esercizio della soluzione SaaS. Le medesime verifiche vanno ripetute in occasione di operazioni di manutenzione del servizio (aggiornamenti e modifiche).</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RS3</td>
    <td>Il Fornitore SaaS può utilizzare componenti software realizzate da terze parti per implementare la propria applicazione (middleware, librerie, componenti da cui l’applicazione dipende). In questi casi egli deve necessariamente rendersi garante anche della sicurezza di queste componenti. Deve essere in sostanza garantita la sicurezza dell’intera supply chain relativa alla soluzione SaaS (includendo anche il sistema operativo).</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RS4</td>
    <td>Occorre scegliere accuratamente le componenti di terze parti da utilizzare, assicurarsi di aver utilizzato la fonte originale del software e che non ci siano stati passaggi intermedi capaci di alterare il contenuto originale. Accertarsi che non siano presenti vulnerabilità note nel software utilizzato o che queste siano state opportunamente gestite e neutralizzate. Ripetere periodicamente i controlli e le verifiche sulle componenti software di terze parti e apportare prontamente i fix necessari e/o rimuovere le dipendenze da componenti con accertate vulnerabilità.</td>
    <td>Dichiarazione Fornitore SaaS</td>
  </tr>
  <tr>
    <td>RS5</td>
    <td>È necessario prevedere per gli endpoint del servizio SaaS (ad esempio di tipo REST oppure di tipo SOAP) le stesse misure di autenticazione e autorizzazione previste per gli eventuali client Web o Mobile. Inoltre è necessario garantire la sicurezza delle comunicazioni con tali interfacce tramite l’adozione del protocollo HTTPS.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>Sicurezza del traffico di rete</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RS6</td>
    <td>Le risorse IaaS/PaaS e i software ospitati nella piattaforma Cloud (di base, middleware e applicativi) devono essere protetti dal traffico di rete indesiderato e/o dannoso, garantendo la sicurezza dei dati, del software e degli account utente, nonché prestazioni di rete non degradate.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RS7</td>
    <td>Il Fornitore SaaS deve mettere in atto misure di network e domain isolation (firewall, ACL, controller di dominio) per mantenere l’isolamento tra i diversi domini applicativi.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RS8</td>
    <td>Devono essere attuate da parte del Fornitore SaaS misure per prevenire e contrastare le intrusioni nella rete e la congestione della stessa (intrusion detection, monitoraggio e filtering del traffico di rete anomalo), evitando che possano avere successo eventuali attacchi di denial of service (DoS) o distributed denial of service (DDoS).</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RS9</td>
    <td>Nella gestione e monitoraggio del traffico di rete di cui al requisito RS8 devono essere inclusi meccanismi per bloccare il traffico di rete da e verso URL presenti in una blacklist. Il Fornitore SaaS deve curare l’aggiornamento periodico della blacklist.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>Trattamento sicuro dei dati e delle credenziali</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RS10</td>
    <td>Il Fornitore SaaS deve assicurare una attenta gestione delle chiavi e dei codici di accesso usati per la soluzione SaaS e le sue componenti costitutive (database, sistemi di code e messaggi, servizi accessori, ecc.).</td>
    <td>Dichiarazione Fornitore SaaS
 </td>
  </tr>
  <tr>
    <td>RS11</td>
    <td>Qualora la soluzione SaaS, oppure alcune delle sue componenti, effettuino degli accessi amministrativi alle risorse IaaS/PaaS sottostanti per motivi di monitoraggio o di gestione elastica delle stesse deve essere garantita una gestione accurata sia delle credenziali di amministratore dell’applicazione SaaS che delle credenziali amministrative della piattaforma IaaS/PaaS sottostante, evitando in tal modo la compromissione delle risorse Cloud utilizzate.</td>
    <td>Dichiarazione Fornitore SaaS</td>
  </tr>
  <tr>
    <td>RS12</td>
    <td>Nel caso di applicazione che accorpa più acquirenti sullo stesso sistema, separati logicamente gli uni dagli altri (multi-tenant), occorre impedire che un acquirente possa accedere ai dati degli altri accidentalmente oppure aggirando i controlli (data isolation).</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)
 </td>
  </tr>
  <tr>
    <td>RS13</td>
    <td>Le informazioni in transito tra le varie componenti del sistema devono essere adeguatamente protette e cifrate. Lo stesso principio vale per le informazioni in transito tra il front-end e il back-end dell’applicazione (ad esempio tra il browser dell’utente e il back-end applicativo, oppure tra il client Mobile e il back-end applicativo). Quando la natura della soluzione SaaS o i dati trattati lo richiedono deve essere implementata anche la cifratura lato client (client-side encryption).</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>Gestione sicura delle identità e degli accessi</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RS14</td>
    <td>Il Fornitore SaaS deve garantire che non si possano verificare abusi nell’uso delle funzionalità dell’applicazione e nell’accesso ai dati (eventualmente in grado di compromettere la sicurezza), inoltre la soluzione SaaS deve essere associata ad un sistema di gestione delle identità e degli accessi.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RS15</td>
    <td>Il sistema di Identity & Access Management deve prevedere una o più figure di amministrazione e diverse figure con privilegi di accesso differenziati e gerarchici.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RS16</td>
    <td>Deve essere implementato il tracciamento degli accessi al servizio e dell’accesso ai dati (transaction audit) con monitoraggio continuo delle informazioni per rilevare in tempo reale eventuali attività sospette.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>Gestione degli incidenti e degli aggiornamenti di sicurezza</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RS17</td>
    <td>Il Fornitore SaaS deve definire le modalità e i tempi di risposta e gestione di ad eventuali incidenti che hanno impatto sul servizio offerto.

SLI previsti: SLI13, SLI14, SLI15, SLI16</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RS18</td>
    <td>Deve essere sempre attivo un sistema di monitoraggio e di alerting relativo a possibili incidenti di sicurezza e/o di violazioni delle policy. Questo sistema deve prevedere la pronta applicazione delle necessarie contromisure in maniera automatica e/o tramite l’intervento di un operatore.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RS19</td>
    <td>Le informazioni relative alle problematiche occorse devono essere registrate, insieme alle attività poste in essere per rimediarvi, e devono essere messe a disposizione degli acquirenti dei servizi.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RS20</td>
    <td>Qualora le risorse IaaS/PasS, i dati e/o i software ospitati, oppure le loro configurazioni dovessero risultare alterati o utilizzati impropriamente a seguito di un incidente di sicurezza occorre mettere in atto le opportune attività di security assessment and audit prima di porre il servizio nuovamente in esercizio, al fine di valutare lo stato complessivo della sicurezza e la possibilità di procedere con l’utilizzo del servizio in modo protetto e sicuro.</td>
    <td>Dichiarazione Fornitore SaaS
 </td>
  </tr>
  <tr>
    <td>RS21</td>
    <td>Il Fornitore SaaS deve documentare le attività sulle patch di sicurezza applicate, relative a aggiornamenti del software, alle procedure e politiche di sicurezza, rendendo disponibile tale documentazione agli acquirenti dei servizi per la consultazione.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica documentale</td>
  </tr>
</table>

```eval_rst
.. discourse::
   :topic_identifier: 2248
```
