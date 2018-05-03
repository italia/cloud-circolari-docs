## Introduzione

Il presente documento allegato alla Circolare è stato redatto al fine di
definire nel dettaglio i requisiti di cui all’art. 4 della Circolare che i CSP
devono rispettare per ottenere la qualificazione dei servizi SaaS da parte di AgID.

I servizi SaaS soggetti a qualificazione riguardano applicativi software
erogati secondo il paradigma SaaS e compatibili con il *Cloud della PA*. 
Dal punto di vista tecnico sono dunque individuati i seguenti soggetti che
svolgono diversi ruoli durante e/o successivamente al processo di qualificazione:

* **Fornitore Cloud**, un CSP che eroga e amministra le risorse Cloud
  infrastrutturali di tipo IaaS e/o PaaS utilizzate dai servizi applicativi
  SaaS per l’erogazione del servizio e rispetto alle quali devono essere
  compatibili;

* **Fornitore SaaS**, un CSP che richiede la qualificazione della propria
  soluzione SaaS affinché sia disponibile all’acquisto da parte delle PA;

* **Acquirente**, PA che acquisisce e utilizza i servizi SaaS ed indirettamente
  le risorse IaaS e/o PaaS sottostanti erogate dal Fornitore Cloud.

E’ opportuno notare che le figure del Fornitore Cloud e del Fornitore SaaS
possono in alcuni casi specifici coincidere con lo stesso soggetto.

Si intende, preliminarmente, fornire un quadro di riferimento riguardante le
modalità di progettazione e realizzazione di una soluzione SaaS da parte dei
CSP e il ciclo di vita di un servizio SaaS. Le definizioni del ciclo di vita e
dei modelli di deployment che seguono sono altresì utili per contestualizzare e
inquadrare i requisiti richiesti per la qualificazione delle soluzioni SaaS.

**Ciclo di vita di un servizio SaaS**

Una soluzione SaaS prevede un tipico *ciclo di vita* attraverso il
quale viene resa disponibile agli utilizzatori (Acquirenti) da parte del
Fornitore SaaS:

* *Provisioning(Predisposizione)*, ossia la predisposizione delle risorse Cloud
  infrastrutturali necessarie all’installazione ed erogazione della soluzione
  SaaS. Le attività di predisposizione sono eseguite a cura del Fornitore SaaS
  nell’ambito dell’infrastruttura Cloud messa a disposizione dal Fornitore Cloud.
  Tipicamente si tratta di risorse virtuali di tipo computazionale, di storage e
  di rete; più in generale possono essere comprese risorse di tipo IaaS e/o PaaS;
* *Deployment (Dispiegamento)*, fase in cui avviene da parte del Fornitore SaaS
  l’installazione e la configurazione dei moduli e componenti applicativi che
  costituiscono la soluzione SaaS;
* *Esercizio*, fase in cui la soluzione SaaS è fruibile da parte
  dell’Acquirente che è in grado di utilizzarla secondo quanto previsto
  contrattualmente;
* *Manutenzione*, fase costituita da brevi periodi temporali in cui la
  soluzione SaaS esce dalla fase di esercizio risultando non fruibile da parte
  dell’Acquirente in occasione di attività di aggiornamento, manutenzione o
  risoluzione di malfunzionamenti da parte del Fornitore SaaS oppure del
  Fornitore Cloud; al termine di tali brevi periodi si avrà nuovamente una
  regolare fase di esercizio;
* *Disattivazione*, fase di terminazione della fornitura in seguito alla quale
  la soluzione SaaS non sarà più utilizzabile dall’Acquirente.

### Modelli architetturali delle soluzioni SaaS

Esistono diversi modelli architetturali  per l’erogazione delle soluzioni SaaS
che si sono sviluppati nel tempo e a cui i fornitori di soluzioni software
fanno tipicamente riferimento durante l’implementazione o il porting del loro
software in modalità SaaS. Tali modelli architetturali sono riepilogati anche
nella raccomandazione ITU "Recommendation ITU-T X.1602 (2016)" e identificati
come livelli di maturità delle applicazioni SaaS.

L’inquadramento rispetto al modello architetturale è importante per poter
identificare e verificare le principali caratteristiche di sicurezza,
interoperabilità e scalabilità dell’applicazione SaaS.

Si richiamano i quattro seguenti modelli architetturali delle soluzioni SaaS;
ciascun modello copre le caratteristiche del precedente ed include proprietà
più estese e avanzate.

**1. Modello "Custom SaaS application"**

Il modello Custom è simile al tradizionale modello di application service
provisioning (ASP), in cui ciascun acquirente (o cliente) viene associato ad
una specifica istanza applicativa dedicata e quindi dimensionata e
personalizzata, anche in termini di middleware, gestione dei dati e sistema
operativo. Rispetto al modello ASP classico si ha come differenza principale il
fatto che vengono usati dei server virtuali in ambiente cloud.

![image alt text](/_static/images/Allegato_A_Qualificazione_SaaS_v6_1.png)

Fanno riferimento a questo modello le applicazioni preesistenti presso il
fornitore, oppure presso l’acquirente, di cui viene fatto il porting verso il
paradigma Cloud minimizzando gli interventi di adattamento e di re-factoring
dell’applicazione. Le applicazioni che vengono esplicitamente pensate per il
paradigma Cloud e che vengono riprogettate non dovrebbero mai adottare questo
modello.

Il forte limite di questo modello è rappresentato dalla difficoltà con cui può
scalare ed adattarsi alle variazioni di domanda dell’utenza. Inoltre l’elevata
personalizzazione e la conseguente rigidità di gestione lo rendono un modello
con costi operativi tipicamente elevati (in primis per il fornitore e di
riflesso anche per l’acquirente).

Rispetto ai cinque elementi essenziali identificati da NIST, le caratteristiche
di *resource pooling* e *rapid elasticity *risultano notevolmente limitate in
questo modello.

**2. Modello "Configurable SaaS application"**

In questo modello l’applicazione risulta essere più standardizzata pur
permettendo un certo livello di personalizzazione ("configurazione" di aspetto
e comportamento), ma viene comunque dispiegata ed eseguita su risorse virtuali
dedicate ed indipendenti. Un tipico esempio è quello dei servizi software
offerti dai fornitori di hosting Web per poter costruire siti Web, Blog, Forum,
ecc. in modalità self service. Ciascun cliente potrà configurare il software
secondo le proprie preferenze, potrà scegliere anche il tipo di sistema
operativo. Ciascuna istanza applicativa risulta essere una copia di un
pacchetto software standard dispiegata ed eseguita su risorse virtuali
assegnate esclusivamente al cliente (in questo ultimo aspetto si mantiene la
similitudine col modello precedente). 

![image alt text](/_static/images/Allegato_A_Qualificazione_SaaS_v6_2.png)

Dal punto di vista del fornitore SaaS è presente una maggiore flessibilità di
gestione per cui le modifiche al codice del pacchetto software potranno essere
applicate a tutti i clienti simultaneamente. Questo modello è molto simile al
precedente con alcuni aspetti meno rigidi, ma comunque non abbraccia appieno la
filosofia e i vantaggi offerti dal paradigma Cloud di tipo SaaS.

**3. Modello "Multi-tenant SaaS application"**

Una singola istanza applicativa è in grado di servire contemporaneamente più
clienti, i quali accedono alla medesima istanza applicativa in esecuzione su
risorse virtuali condivise. L’isolamento dei dati e degli utenti avviene a
livello applicativo e di gestione dei dati (DBMS), utilizzando gli opportuni
meccanismi di autenticazione, autorizzazione e sicurezza. Tipici esempi di
questo modello sono i software di CRM (ad es. SalesForce) e di Business
Intelligence erogati in modalità SaaS. 

![image alt text](/_static/images/Allegato_A_Qualificazione_SaaS_v6_3.png)

In questo modello viene esaltato l’uso efficiente delle risorse software,
computazionali e di storage, con l’evidente vantaggio di riuscire a servire un
maggior numero di clienti da parte dei provider. Efficienze che si riflettono
anche nella possibilità di abbassare i costi di esercizio e di vendita. Tutto
ciò senza andare a discapito della scalabilità e delle performance, che vengono
comunque garantite tramite lo sfruttamento dell’elasticità delle risorse Cloud
ed un opportuno impiego di tecniche di partizionamento dei dati e di calcolo
parallelo.

In questo modello si estrinsecano tutte le caratteristiche essenziali del Cloud
computing secondo la definizione NIST. Il livello multi-tenant si sposa bene
con i modelli di deployment Public, Private e Community.

**4. Modello "Scalable SaaS application"**

Nel modello scalabile la dinamicità e la scalabilità dell’ambiente sono messi
in primo piano. Questo permette di avere configurazioni più flessibili. I
clienti potranno avere la loro istanza applicativa in esecuzione su risorse
condivise o dedicate (o un misto delle due) in maniera trasparente e
configurabile. Il sistema di load balancing permette di implementare le
politiche di allocazione (delle nuove istanze applicative) in funzione di una
moltitudine di criteri (uno dei più importanti è la qualità del servizio). Da
notare che le istanze applicative possono essere aggiunte e rimosse
dinamicamente in qualunque momento ed in base alle esigenze. Anche le risorse
virtuali necessarie alle applicazioni sono allocate in modo dinamico.
L’allocazione di nuove istanze applicative o di risorse virtuali non richiede
nessuna modifica architetturale del sistema che è già stato realizzato in modo
da adattarsi dinamicamente. Tutto ciò permette di offrire ed attuare SLA
diversificati per i vari clienti.

![image alt text](/_static/images/Allegato_A_Qualificazione_SaaS_v6_4.png)

Infine è da tenere presente che il modello scalabile, per via delle
caratteristiche di dinamicità evidenziate si presta ad essere utilizzato (senza
richiedere riconfigurazioni o modifiche sostanziali) anche in modalità ibrida
(ad es. misto di Public e Private cloud) oppure in modalità multi-cloud in cui
diversi cloud provider offrono le risorse virtuali. Un altro scenario è quello
del cloud bursting, in cui si ha un misto di Private e Public Cloud oppure una
modalità multi-cloud, dove le risorse di un fornitore vengono impiegate
automaticamente solo in caso di necessità di espansione del sistema e di
maggiori performance.

