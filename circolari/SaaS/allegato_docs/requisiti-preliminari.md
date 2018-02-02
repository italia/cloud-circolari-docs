## Requisiti preliminari

Nelle soluzioni SaaS che utilizzano PSN o Cloud SPC I fornitori dovranno indicare  il livello di automazione di cui l’applicazione dispone per ogni fase del ciclo di vita dell’applicazione. È necessario che le soluzioni SaaS  siano in grado di interagire mediante API (Application Programming Interface) con la piattaforma Cloud su cui risiedono e che tale capacità di interazione consenta di sfruttare appieno le potenzialità e i servizi della piattaforma Cloud ospitante. 

Le soluzioni SaaS devono poter disporre dinamicamente delle risorse di calcolo, di storage e di rete di tipo IaaS/PaaS, sia per l'attivazione dei servizi (durante le fasi di provisioning e deployment) che, in seguito, per l'adattamento alle variazioni di carico, alle necessità di ripristino da eventuali malfunzionamenti e per la disattivazione dei servizi (cioè nelle fasi di esercizio, manutenzione e disattivazione).

Tipicamente queste funzionalità sono accessibili in modalità programmatica usando le API che le piattaforme Cloud mettono a disposizione. A livello applicativo sarà quindi necessario utilizzare le chiamate API messe a disposizione dalla piattaforma Cloud sottostante relativamente a funzionalità IaaS/PaaS quali: autenticazione, gestione di risorse computazionali, risorse di storage, risorse di rete, funzionalità di logging, acquisizione di metriche/KPIs, eccetera.

Il Fornitore della soluzione SaaS, operando in qualità di amministratore delle risorse Cloud  (PaaS/IaaS) deve garantire il corretto funzionamento e la **massima trasparenza** di tutti i processi e le interazioni tra la piattaforma Cloud e l’applicazione SaaS.

Nelle soluzioni SaaS che utilizzano risorse cloud erogate basate su PSN o Cloud SPC il fornitore deve rendere disponibili tutte le informazioni relative all’implementazione ed erogazione del servizio. Tali informazioni vengono dichiarate dal Fornitore SaaS e acquisite da AgID tramite la piattaforma informatica di supporto al processo di qualificazione SaaS. 

La produzione di tali informazioni è obbligatoria per il Fornitore SaaS e costituisce un requisito preliminare per la qualificazione (requisito RP5) qualora il Fornitore faccia richiesta di test e collaudo della soluzione SaaS (si veda l’art. 4 (Fase 3) della Circolare).

Elenco dettagliato dei requisiti preliminari:

<table>
  <tr>
    <td>Codice Requisito</td>
    <td>Requisito</td>
    <td>Elementi di riscontro</td>
  </tr>
  <tr>
    <td colspan="3"> <strong>Piena capacità di interfacciarsi con la piattaforma Cloud</strong> </td>
  </tr>
  <tr>
    <td>RP1</td>
    <td>È necessario specificare se la soluzione SaaS  è in grado  operare, mediante processi di automazione,   funzionalità infrastrutturali della piattaforma Cloud  consentendo di:
·         instanziare le risorse infrastrutturali (IaaS/PaaS) utili ad erogare il servizio;
·         dismettere risorse (IaaS/PaaS) non più necessarie per l’erogazione del servizio e di conseguenza evitare consumi inutili di tali risorse;
·         implementare (se richiesto dall’Acquirente) una soluzione ad elevata disponibilità utilizzando risorse della piattaforma Cloud utili alla realizzazione di questa funzionalità.
</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RP2</td>
    <td>Specificare se  la soluzione SaaS  è in grado di estrarre autonomamente dalla piattaforma IaaS/PaaS  le metriche e i KPI utili a controllare l’erogazione del servizio, in particolare per non eccedere i limiti prefissati di consumo delle risorse computazionali, di storage e di rete (banda e accessi); nonché per esporre trasparentemente all’Acquirente i dati sui consumi di tali risorse. Il Fornitore deve dichiarare se e  quali KPI/ metriche  vengono estratte e in che modo sono utilizzate.
</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)
 </td>
  </tr>
  <tr>
    <td>RP3</td>
    <td>Specificare se la soluzione SaaS in grado di accedere a funzionalità di recupero del logging/tracing relativo all’esecuzione di processi di sistema erogati dalla piattaforma Cloud, utili  nella risoluzione di potenziali problemi connessi ai servizi erogati.
</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RP4</td>
    <td>Specificare se la soluzione SaaS  è in grado di gestire compartimenti logici e/o fisici che garantiscono  la segregazione delle risorse tra più istanze del servizio in uso a diversi Acquirenti.

Si applica solo nel caso di soluzione SaaS multi-tenant.
</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td colspan="3"> <strong>Produzione delle informazioni necessarie per l’istruttoria di qualificazione <strong></td>
  </tr>
  <tr>
    <td>RP5</td>
    <td>Il Fornitore SaaS deve dichiarare:
 i requisiti necessari per poter garantire l’esecuzione dell’applicazione su piattaforma Cloud, espressi direttamente in termini di caratteristiche delle istanze IaaS e/o PaaS sottostanti che dovranno essere attivate e configurate in fase di provisioning;
 l’organizzazione architetturale dei moduli e componenti principali della soluzione SaaS;
lo stack software su cui è basata la soluzione applicativa, includendo il sistema operativo, il middleware, gli SDK o framework di programmazione, le librerie e le API di terze parti eventualmente utilizzate;
le modalità principali di fruizione del servizio (client Web, client Mobile, Thin client, ecc);
le modalità programmatiche di fruizione del servizio (Web service REST, Web service SOAP, ecc.);

Più in generale, il Fornitore SaaS deve fornire tutte le informazioni richieste nella scheda tecnica del servizio. Inoltre, deve indicare esplicitamente le tipologie di licenze software di eventuali librerie, API e componenti software di terze parti utilizzati.
Questo requisito è richiesto solo nel caso la soluzione sia installata su PSN o Cloud SPC.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica documentale</td>
  </tr>
  <tr>
    <td>
RP6</td>
    <td>Il Fornitore SaaS deve rendere disponibile un account di test ed un URL utilizzabili da AgID per effettuare ogni tipo di verifica (anche a campione) che si renderà necessaria per il rilascio ed il mantenimento della qualificazione.</td>
    <td>Dichiarazione Fornitore SaaS</td>
  </tr>
  <tr>
    <td colspan="3"> <strong>Amministrazione delle risorse Infrastrutturali  IaaS/PaaS </strong></td>
  </tr>
  <tr>
    <td>


RP7</td>
    <td>Il Fornitore SaaS, durante tutto il ciclo di vita della soluzione SaaS opera in qualità di amministratore unico di tutte le risorse Cloud di tipo PaaS/IaaS utilizzate dal servizio che eroga.
</td>
    <td>Dichiarazione Fornitore SaaS
Verifica documentale</td>
  </tr>
</table>

```eval_rst
.. discourse::
   :topic_identifier: 2245
```
