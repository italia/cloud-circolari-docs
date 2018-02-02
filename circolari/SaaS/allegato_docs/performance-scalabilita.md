## Performance e scalabilità

Il Fornitore SaaS è tenuto a dichiarare prima la qualità e l’affidabilità del servizio offerto durante tutto il ciclo di vita della soluzione SaaS. Le pattuizioni relative alla qualità del servizio costituiscono parte integrante del contratto di fornitura, all’interno del quale deve essere ricompresa una specifica sezione relativa ai "livelli di servizio garantiti" ovvero al Service Level Agreement (SLA).

Gli accordi relativi ai *livelli di servizio garantiti* (SLA) devono essere specificati mediante la quantificazione di un insieme di valori *obiettivo* (SLO) o intervalli di valori riferibili ad altrettanti specifici *indicatori* di performance, affidabilità, risultato (SLI). Il Fornitore SaaS si impegna a rispettare gli obietti inoltre a monitorare costantemente tali indicatori e a fornire all’Acquirente l’accesso ad opportuni strumenti di monitoraggio.

La sezione del contratto di fornitura relativa ai *livelli di servizio garantiti* deve includere le *penali compensative* che il Fornitore SaaS dovrà corrispondere all’Acquirente in caso  di mancato rispetto di uno o più valori obiettivo (SLO). I metodi di quantificazione e le condizioni di riconoscimento delle penali compensative devono essere inclusi nel contratto ed essere allineati ai valori e alle condizioni di mercato riscontrabili per servizi analoghi o appartenenti alla medesima categoria.

Inoltre, per quanto concerne i livelli di servizio garantiti (SLA) nel loro complesso, devono essere osservate le seguenti prescrizioni:

* deve essere inclusa la definizione chiara e non ambigua di tutti gli indicatori (SLI) e dei relativi valori obiettivo (SLO);

* lo SLA deve essere consultabile pubblicamente mediante l’accesso ad un apposito URL Web;

* devono essere riportate all’interno del SLA le definizioni di tutti i termini specifici riferiti al servizio offerto o di quelli particolarmente rilevanti per la comprensione dell’accordo;

* deve essere previsto esplicitamente che, se successivamente all’avvio della fornitura si dovesse rendere necessaria una qualsiasi modifica ai livelli di servizio garantiti, questa dovrà essere preventivamente notificata all’Acquirente per ottenerne la sua approvazione;

* il Fornitore SaaS deve produrre e inviare al consumatore un report periodico (almeno con cadenza mensile), contenente il riepilogo dell’andamento dei livelli di servizio nel periodo e che evidenzi gli eventuali sforamenti rispetto agli SLO e le penali compensative maturate.

Il Fornitore SaaS deve implementare delle politiche e dei piani operativi per garantire la continuità del servizio (business continuity). Inoltre deve gestire tempestivamente il ripristino dell’operatività del servizio in seguito ad eventi catastrofici o imprevisti (disaster recovery).

Il Fornitore SaaS deve dichiarare quali sono le condizioni massime di carico sopportabili dal servizio sia in termini di numero di utenti concorrenti che utilizzano il sistema e/o volume di richieste processabili. Nel caso in cui sia prevista la scalabilità automatica dell’applicativo, il fornitore deve specificare e garantire quali sono le condizioni e i tempi di attivazione delle istanze aggiuntive.

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
    <td>RPS1</td>
    <td>La disponibilità del servizio è adeguata all’utilizzo previsto e corrispondente a quella dichiarata dal Fornitore SaaS.

Il Fornitore SaaS deve assicurare la disponibilità e fruibilità del servizio nella sua interezza: non possono esserci parti di servizio non disponibili o non utilizzabili appieno.

SLI previsto: SLI01</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RPS2</td>
    <td>Devono essere presenti funzionalità automatiche e su richiesta di backup e ripristino dei dati e delle configurazioni software.

SLI previsti: SLI17, SLI18, SLI19</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)</td>
  </tr>
  <tr>
    <td>RPS3</td>
    <td>Il Fornitore SaaS deve  disporre di un piano di continuità operativa (business continuity) in cui sono previste azioni orientate al ripristino dell’operatività del servizio (disaster recovery) al verificarsi di eventi catastrofici/imprevisti. Il piano di ripristino raccoglie tutte le procedure necessarie al ripristino del servizio e dei dati ad esso relativi. </td>
    <td>Dichiarazione Fornitore SaaS
Verifica documentale</td>
  </tr>
  <tr>
    <td>RPS4</td>
    <td>Il Fornitore SaaS deve descrivere il comportamento della soluzione SaaS nell’eventualità  di un evento catastrofico, fornendo una valutazione  del rischio relativamente ai seguenti eventi:
 perdita o inconsistenze di dati
 alterazioni o non accessibilità di dati
perdita delle transazioni
 perdita delle chiavi crittografiche per decifrare i dati
impossibilità di ripristinare il servizio da un backup precedente
impossibilità di operare il servizio nella sua pienezza</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)
 </td>
  </tr>
  <tr>
    <td>Tempi di risposta del servizio</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RPS5</td>
    <td>I tempi di risposta del servizio sono corrispondenti a quelli dichiarati dal Fornitore SaaS e non sono presenti scostamenti significativi, e comunque entro precisi limiti prevedibili e noti a priori, al variare del numero di utenti connessi e del carico di lavoro sottoposto al servizio.

</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)
 </td>
  </tr>
  <tr>
    <td>Capacità di elaborazione</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RPS6</td>
    <td>Le capacità di elaborazione e di evadere completamente le richieste sottoposte dagli utilizzatori al servizio devono essere adeguate all’utilizzo previsto per la soluzione SaaS e corrispondenti a quelle dichiarate dal Fornitore SaaS.

</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)
 </td>
  </tr>
  <tr>
    <td>RPS7</td>
    <td>Nel caso di servizio dispiegato in configurazione multi-tenant, la capacità di elaborazione deve mantenersi inalterata (o comunque entro precisi limiti prevedibili e noti a priori) al variare del numero di tenant attivi.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)
 </td>
  </tr>
  <tr>
    <td>Scalabilità del servizio</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RPS9</td>
    <td>Il Fornitore SaaS deve dichiarare quali sono le condizioni massime di carico sopportabili dal servizio sia in termini di numero di utenti concorrenti e/o numero di richieste processabili (oppure volume di dati processabili).</td>
    <td>Dichiarazione Fornitore SaaS</td>
  </tr>
  <tr>
    <td>RPS10</td>
    <td>Nel caso in cui sia prevista la scalabilità automatica della soluzione SaaS, il Fornitore SaaS deve specificare e garantire quali siano le condizioni e i tempi di attivazione delle istanze aggiuntive che vengono attivate per sopportare i maggiori carichi.

SLI previsti: SLI06</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)
 </td>
  </tr>
  <tr>
    <td>RPS11</td>
    <td>La scalabilità automatica o semi-automatica del servizio deve attivarsi correttamente al verificarsi delle condizioni operative prestabilite e deve garantire che non si verifichino interruzioni apprezzabili nell’erogazione del servizio.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)
 </td>
  </tr>
  <tr>
    <td>RPS12</td>
    <td>I precedenti requisiti di scalabilità devono essere garantiti sia nel caso di scalabilità crescente che nel caso di decrescita delle risorse allocate. In particolare in fase di decrescita le istanze SaaS/PaaS/IaaS non più necessarie devono risultare correttamente disattivate in modo da non comportare costi di utilizzo.</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)
 </td>
  </tr>
  <tr>
    <td>Performance dei dispositivi client</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>RPS13</td>
    <td>I requisiti di performance precedenti devono valere per tutti i tipi di dispositivi client supportati (PC, tablet, mobile, ecc.).</td>
    <td>Dichiarazione Fornitore SaaS
Verifica tecnica (se prevista)
 </td>
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

```eval_rst
.. discourse::
   :topic_identifier: 2249
```
