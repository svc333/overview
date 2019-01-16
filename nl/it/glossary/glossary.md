---


copyright:
  years: 2016, 2018
lastupdated: "2018-11-15"


---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Termini del glossario per {{site.data.keyword.cloud_notm}} 
{: #glossary}

Questo glossario fornisce termini e definizioni per {{site.data.keyword.cloud_notm}}.
{:shortdesc}

In questo glossario vengono utilizzati i seguenti riferimenti incrociati:

- *Vedere* rimanda il lettore da un termine non preferenziale a uno preferenziale oppure da un'abbreviazione a una forma estesa del termine.
- *Vedi anche* ti rimanda a termini correlati o contrari.

<!--If you do not want letter links at the top of your 
glossary, delete the text between these comment tags.
[A](#glossa)
[B](#glossb)
[C](#glossc)
[D](#glossd)
[E](#glosse)
[F](#glossf)
[G](#glossg)
[H](#glossh)
[I](#glossi)
[J](#glossj)
[L](#glossl)
[M](#glossm)
[N](#glossn)
[O](#glosso)
[P](#glossp)
[R](#glossr)
[S](#glosss)
[T](#glosst)
[U](#glossu)
[V](#glossv)
[W](#glossw)

-->

## A
{: #glossa}

### access control list
{: #x2012793}

Un elenco che gestisce, in un modo che non prevede l'utilizzo di stati, il traffico in entrata e in uscita per un sottoinsieme tramite l'utilizzo di regole. Un ACL (access control list) aiuta a fornire la sicurezza a livello di sottorete.

### token di accesso
{: #x2113001}

Un valore di cui si serve l'utilizzatore per ottenere l'accesso alle risorse protette per conto dell'utente, invece di utilizzare le credenziali del provider di servizi dell'utente.

### azione
{: #x2012974}

Un frammento di codice che può essere richiamato esplicitamente o eseguito in risposta a un evento. Vedi anche [feed](#x3129185), [richiama](#x2057232).

### affinità
{: #x2149238}

Due o più istanze del gruppo di contenitori in esecuzione sullo stesso nodo di rete. Vedi anche [anti-affinità](#x8888040).

### anti-affinità
{: #x8888040}

Due o più istanze del gruppo di contenitori che vengono eseguite su diversi nodi di rete per garantire una maggiore disponibilità per un'applicazione. Vedi anche [affinità](#x2149238).

### API
{: #x2008805}

Vedi [application programming interface](#x2000186).

### app
{: #x4281528}

Un'applicazione di dispositivo web o mobile. Vedi anche [applicazione mobile](#x4258535), [applicazione web](#x2116500).

### application programming interface (API)
{: #x2000186}

Un'interfaccia che consente a un programma applicativo scritto in un linguaggio di alto livello di utilizzare funzioni o dati specifici del sistema operativo oppure un altro programma.

### risorsa utente
{: #x2262995}

Un'entità utilizzata o prodotta da un processo di sviluppo software o di sistema. Esempi di risorse utente includono progettazioni, requisiti, file di origine, piani, script,
simulazioni, modelli, piani di test e file eseguibili binari. In un contesto HTTP, le risorse utente dispongono di un URI e sono chiamate risorse.

### autenticazione (AuthN)
{: #x2014567}

Il processo di convalida dell'identità di un utente o di un server.

### AuthN
{: #x7470446}

Vedi [autenticazione](#x2014567).

### autorizzazione (AuthZ)
{: #x2014653}

Nella sicurezza di un computer, il diritto concesso ad un utente di comunicare con o utilizzare un sistema di computer.

### AuthZ
{: #x7470448}

Vedi [autorizzazione](#x2014653).

### zona di disponibilità
{: #x7018171}

Una posizione all'interno di una regione in cui è in esecuzione IBM Containers.


## B
{: #glossb}

### immagine di base
{: #x5366487}

Un'immagine che non ha alcuna immagine principale. Vedi anche [immagine](#x2024928), [immagine principale](#x8439210).

### servizio beta
{: #x7470455}

Un servizio che non è pronto per la produzione ed è a una
fase di sviluppo di prova. Vedi anche [servizio
sperimentale](#x7470450).

### eseguire il bind
{: #x2000361}

Stabilire una connessione tra componenti software su una rete utilizzando un protocollo concordato. Nei servizi web, l'operazione di bind si verifica quando il richiedente del servizio richiama o avvia un'interazione con il servizio al runtime utilizzando i dettagli di bind nella descrizione del servizio per individuare, contattare o richiamare il servizio.

### BLU Acceleration
{: #x7470463}

Una raccolta di tecnologie IBM Db2 progettate per operare principalmente con l'elaborazione di query di business intelligence principalmente in lettura. BLU Acceleration si articola in quattro importanti miglioramenti nella progettazione del database: elaborazione in memoria dinamica per colonne, compressione operativa, elaborazione vettoriale parallela e tralasciamento dei dati.

### Distribuzione blu-verde
{: #x7807335}

Una tecnica di distribuzione che consente la fornitura continua e minimizza
l'inattività eseguendo i due ambienti di produzione quasi identici denominati
Blu e Verde. Mentre uno degli ambienti (ad esempio, Blu) funge da
ambiente di produzione attivo, l'altro (ad esempio,Verde) può essere utilizzato
per effettuare i test finali e la distribuzione. Una volta che l'applicazione viene
distribuita in Verde, quest'ultimo diventa l'ambiente di produzione e
Blu diventa inattivo. Vedi anche [distribuzione Red-Black](#x8439181).

### contenitore tipo
{: #x7233930}

Un template che include un'applicazione e il suo ambiente di runtime associato e i servizi predefiniti per uno specifico dominio.

### illimitato
{: #x8439189}

Relativo a una piattaforma di sviluppo aperta e non proprietaria che include modelli di sviluppo cloud pubblico, cloud dedicato e cloud locale. Vedi anche [cloud dedicato](#x8439199), [cloud locale](#x8439194), [cloud pubblico](#x4585370).

### pacchetto di build
{: #x7233925}

Una raccolta di script che preparano il tuo codice all'esecuzione su IBM Cloud. I pacchetti di build esaminano le applicazioni distribuite e scaricano e configurano quindi le eventuali applicazioni dipendenti.


## C
{: #glossc}

### CA
{: #x2015942}

Vedi [autorità di certificazione](#x2016383).

### autorità di certificazione (CA)
{: #x2016383}

Un'organizzazione o società attendibile di terze parti che emette i certificati digitali. L'autorità
di certificazione in genere verifica l'identità dei singoli utenti a cui viene concesso il certificato univoco. Vedi anche [certificato intermedio](#x3753781), [Secure Sockets Layer](#x2038004), [radice attendibile](#x2042234).

### richiesta firma certificato (CSR)
{: #x3530521}

Un messaggio elettronico inviato da un'organizzazione a un'autorità di certificazione (CA) per ottenere un certificato. La richiesta include una chiave pubblica ed è firmata con una chiave privata; la CA restituisce un certificato dopo averlo firmato con la propria chiave privata.

### CLI
{: #x2008863}

Vedi [interfaccia riga di comando](#x2051424).

### client
{: #x2000644}

Un computer o un programma software che richiede servizi da un server. Vedi anche [host](#x2002243).

### elaborazione cloud
{: #x3877850}

Una piattaforma di calcolo in cui gli utenti possono accedere ad applicazioni o risorse di elaborazione, come i servizi, da qualsiasi luogo tramite i propri dispositivi connessi. Un'interfaccia utente semplificata o una API (Application Programming Interface), o entrambe le cose, formano l'infrastruttura che supporta tali servizi in modo trasparente agli utenti.

### portabilità cloud
{: #x4585297}

La capacità di spostare applicazioni e servizi in ambiente di elaborazione cloud pubblici o privati o da diversi provider cloud.

### interfaccia riga di comando (CLI)
{: #x2051424}

Una interfaccia computer in cui l'input e l'output sono basati su testo.

### componente
{: #x2017871}

Nella gestione controllo origine, un raggruppamento di risorse utente correlate in un flusso o uno spazio di lavoro repository. Un componente può contenere qualsiasi numero di cartelle e file.

### calcola
{: #x3723424}

L'infrastruttura o le risorse che servono come base per la creazione di applicazioni nel cloud.

### contenitore
{: #x2010901}

Un costrutto di sistema che consente agli utenti di eseguire simultaneamente istanze del sistema operativo logiche separate. I contenitori utilizzano livelli di file system per ridurre al minimo le dimensioni delle immagini e promuovere il riutilizzo. Vedi anche [immagine](#x2024928), [livello](#x2028320), [registro](#x2064940).

### credenziale
{: #x2018813}

Informazioni acquisite durante l'autenticazione che descrivono un utente, associazioni di gruppi o altri attributi di identità correlati alla sicurezza, e che vengono utilizzate per eseguire servizi quali l'autorizzazione, la verifica o la delega. Ad esempio, un ID utente ed una password sono credenziali che consentono l'accesso alle risorse di rete e di sistema.

### CSR
{: #x2140147}

Vedi [richieste di firma certificato](#x3530521).

### dominio personalizzato
{: #x5728384}

La parte personalizzata dell'URL selezionata dall'utente per indirizzare le richieste all'applicazione. Il dominio personalizzato è parte integrante della rotta. Il dominio personalizzato può essere un dominio condiviso, un dominio secondario condiviso
o un dominio e un host condivisi. Vedi anche [dominio](#x2021210), [host](#x2002243), [rotta](#x2037338), [dominio secondario](#x2040080), [Uniform Resource Locator](#x2042491).


## D
{: #glossd}

### daemon
{: #x2019215}

Un programma che viene eseguito in modalità non presidiata per
eseguire funzioni continue o periodiche, come il controllo della rete.

### dashboard
{: #x2363941}

Un componente interfaccia utente che fornisce all'utente un riepilogo comprensivo di informazioni pertinenti da più origini.

### archivio dati
{: #x2052849}

Un'ubicazione, come un file, una directory o un sistema di database, dove sono memorizzati i dati.

### DEA
{: #x2019805}

Vedi [Droplet Execution Agent](#x7470348).

### cloud dedicato
{: #x8439199}

Un ambiente di elaborazione cloud privato che fornisce l'infrastruttura con hardware a singolo tenant. Vedi anche [illimitato](#x8439189).

### distribuzione
{: #x2104544}

Un processo che richiama l'output di una build, impacchetta l'output con le proprietà di configurazione e installa il package in un'ubicazione predefinita in modo che possa essere testato o eseguito. Vedi anche [preparare](#x2067189).

### DevOps
{: #x5784896}

Una metodologia software che integra lo sviluppo delle applicazioni e le operazioni IT in modo che i team possano distribuire il codice più velocemente per la produzione e interagire in modo continuo in base al feedback del mercato.

### dominio
{: #x2021210}

Parte della gerarchia di denominazione che specifica la rotta. Ad esempio,
esempio.com. In IBM Cloud, i domini sono associati alle organizzazioni. Gli oggetti di dominio
non sono associati direttamente alle applicazioni. Vedi anche [dominio personalizzato](#x5728384), [host](#x2002243), [organizzazione](#x2032585), [rotta](#x2037338), [dominio secondario](#x2040080), [Uniform Resource Locator](#x2042491).

### droplet
{: #x7470343}

Un archivio in Cloud Foundry che contiene un'applicazione e le sue dipendenze di runtime e framework, prima della distribuzione al cloud.

### Droplet Execution Agent (DEA)
{: #x7470348}

Il componente Cloud Foundry che è responsabile per la distribuzione delle
applicazioni.


## E
{: #glosse}

### endpoint
{: #x2026820}

L'indirizzo di una API o di un servizio in un ambiente. Una API presenta
un endpoint e, al tempo stesso, richiama gli endpoint di altri servizi. Consulta anche [rotta](#x2037338).

### servizio sperimentale
{: #x7470450}

Un servizio che non è pronto per la produzione e che può essere rimosso dalla produzione in qualsiasi momento. Vedi anche [servizio
beta](#x7470455).


## Ve
{: #glossf}

### federare
{: #x2763229}

Consente di unire due o più entità. Ad esempio, il dominio registrato di un'azienda può essere federato con un ID IBM.

### feed
{: #x3129185}

Un pezzo di codice che configura un'origine eventi esterna per l'attivazione di eventi trigger. Vedi anche [azione](#x2012974).

### condivisione file
{: #x2022902}

Nell'ambiente cloud IBM, un sistema di archiviazione permanente in cui gli utenti archiviano e condividono i file. In IBM Containers, gli utenti possono montare i volumi Docker sulle condivisioni file.

### attiva
{: #x2239904}

Consente di attivare un trigger.

### Indirizzo IP mobile
{: #x6326428}

Un indirizzo IP pubblico e instradabile che utilizza la NAT (network address translation) 1-a-1 in modo che un server possa comunicare con internet pubblico e sottorete privata in un ambiente cloud. Gli indirizzi IP mobili sono associati a un'istanza, ad esempio un'istanza del server virtuale, un programma di bilanciamento del carico oppure un gateway VPN, mediante una vNIC (virtual network interface card).

### framework
{: #x2023472}

Un'architettura per un'applicazione che fornisce una struttura standard per
un'applicazione e una funzionalità generale ed estensibile.  Un framework abilita e semplifica un'implementazione congruente di tecnologie complesse per lo sviluppo di applicazioni.


## G
{: #glossg}

### GB-ora
{: #x7470477}

La quantità cumulativa di memoria (in gigabyte) in esecuzione per tutte le istanze dell'applicazione per uno specifico pacchetto di build all'ora.

### globally unique identifier (GUID)
{: #x2390455}

Un numero determinato algoritmicamente che identifica in modo univoco un'entità in un sistema.

### GUID
{: #x2390457}

Vedi [globally unique identifier](#x2390455).


## H
{: #glossh}

### chiamata API heavy
{: #x7690468}

Un'operazione client che scrive, elimina o inserisce dati. Le chiamate API heavy
utilizzano una maggiore quantità di risorse rispetto alle chiamate API light perché
influenzano i dati. Vedere anche [chiamata
API light](#x7690463).

### host
{: #x2002243}

Un computer che è connesso a una rete e che fornisce un punto di accesso a tale rete. L'host può essere un client, un server o entrambi contemporaneamente. Vedi anche [client](#x2000644), [dominio personalizzato](#x5728384), [dominio](#x2021210), [rotta](#x2037338), [dominio secondario](#x2040080), [Uniform Resource Locator](#x2042491).

### metodo HTTP
{: #x2024674}

Un'azione utilizzata da HTTP (Hypertext Transfer Protocol). I metodi HTTP includono GET, POST e PUT.

### HTTPS
{: #x2193603}

Vedi [Hypertext Transfer Protocol
Secure](#x2237225).

### cloud ibrido
{: #x4585327}

Un ambiente di elaborazione cloud formato da più risorse pubbliche e
private.

### Hypertext Transfer Protocol Secure (HTTPS)
{: #x2237225}

Un protocollo Internet utilizzato da browser e server Web per trasferire e visualizzare documenti ipermediali su Internet in modo sicuro.


## I
{: #glossi}

### IaaS
{: #x4585337}

Vedi [infrastructure as a service](#x4585332).

### IAM
{: #x2193801}

Consulta [Identity and Access Management](#x7547040).

### IBM Cloud
{: #x7301758}

Una piattaforma a standard aperti e basata sul cloud per sviluppare, gestire ed eseguire app di tutti i tipi, come ad esempio dispositivi smart, Big Data, mobili e web. Le funzionalità includono Java, lo sviluppo back-end mobile e il monitoraggio di applicazioni, oltre a funzioni dai partner di ecosistema e open source&mdash;il tutto fornito come un servizio nel cloud.

### Identity and Access Management (IAM)
{: #x7547040}

Il processo di controllo dell'accesso di utenti autorizzati ai dati e alle applicazioni, mentre si aiutano le aziende a rispettare vari requisiti normativi.

### immagine
{: #x2024928}

Un file system e i relativi parametri di esecuzione che vengono utilizzati all'interno di un runtime del contenitore per creare un contenitore. Il file system è costituito da una serie di livelli, combinati in fase di runtime, creati come l'immagine viene creata dai successivi aggiornamenti. L'immagine non conserva lo stato quando viene eseguito il contenitore. Vedi anche [immagine di base](#x5366487), [contenitore](#x2010901), [livello](#x2028320), [spazio dei nomi](#x2031005), [immagine principale](#x8439210), [repository di immagini privato](#x8439215), [registro](#x2064940).

### infrastructure as a service (IaaS)
{: #x4585332}

L'offerta di un'infrastruttura di computer, comprese le funzionalità server, di collegamento in rete, di data center e di archiviazione, come un servizio in outsourcing.

### instance
{: #x2002531}

Un'entità formata da risorse riservate per un'applicazione o un servizio specifici.

### certificato intermedio
{: #x3753781}

Un certificato subordinato emesso dall'autorità di certificazione (CA) radice attendibile
specificamente per emettere certificati server per l'entità finale. Il risultato è una catena di certificati che inizia dalla CA radice
attendibile, passa per quello intermedio e termina con il certificato SSL emesso per l'organizzazione. Vedi anche [autorità di certificazione](#x2016383), [radice attendibile](#x2042234).

### Internet delle cose (IoT)
{: #x6714341}

La rete globale di endpoint che possono acquisire o generare i dati. Ad esempio, uno smartphone, uno smart watch e un server di backend potrebbero tutti comunicare tra loro, scambiandosi i dati o anche con ulteriori dispositivi all'interno della rete.

### richiama
{: #x2057232}

Consente di attivare un'azione. Vedi anche [azione](#x2012974).

### IoT
{: #x6714346}

Vedi [Internet delle cose](#x6714341).


## J
{: #glossj}

### file JAR
{: #x2406009}

Un file di archivio Java.

### JavaScript Object Notation (JSON)
{: #x3292165}

Un formato di interscambio di dati leggero, basato sull'annotazione object-literal di JavaScript. JSON è un linguaggio di programmazione neutrale ma utilizza le convenzioni da diversi linguaggi.

### JSON
{: #x4267096}

Vedi [JavaScript Object Notation](#x3292165).


## L
{: #glossl}

### livello
{: #x2028320}

Una versione modificata di un'immagine principale. Le immagini sono costituite da livelli, dove la versione modificata viene sovrapposta all'immagine principale per creare la nuova immagine. Vedi anche [contenitore](#x2010901), [immagine](#x2024928).

### LDAP
{: #x2481619}

Vedi [Lightweight Directory Access
Protocol](#x2028538).

### chiamata API light
{: #x7690463}

Un'operazione client che si limita a leggere i dati. Le chiamate API light utilizzano
una minore quantità di risorse rispetto alle chiamate API heavy perché eseguono una
singola funzione. Vedi anche [chiamata API heavy](#x7690468).

### Lightweight Directory Access Protocol (LDAP)
{: #x2028538}

Un protocollo aperto che utilizza il TCP/IP per fornire l'accesso alle
directory che supportano un modello X.500 e che non incorre nei requisiti di
risorse del più complesso X.500 DAP (Directory Access Protocol). Ad esempio,
LDAP può essere utilizzato per individuare persone, organizzazioni e altre risorse in una
directory Internet o intranet.

### cloud locale
{: #x8439194}

Un ambiente di elaborazione cloud nel data center del client. Il cloud locale è in loco, fornendo latenza e sicurezza migliorate. Vedi anche [illimitato](#x8439189).


## Lu
{: #glossm}

### MBaaS
{: #x7044865}

Vedi [mobile backend as a service](#x7044858).

### app mobile
{: #x7636517}

Vedi [applicazione mobile](#x4258535).

### applicazione mobile (app mobile)
{: #x4258535}

Un'applicazione progettata per una piattaforma mobile. Simili
alle applicazioni web, le applicazioni mobili forniscono delle funzioni che
vanno oltre la visualizzazione statica di informazioni, ad esempio consentendo all'utente di filtrare notizie quasi in tempo reale. Vedi anche [applicazione](#x4281528).

### mobile backend as a service (MBaaS)
{: #x7044858}

Un modello di elaborazione che connette applicazioni mobili ai servizi di elaborazione cloud e fornisce funzioni quali la gestione utente, le notifiche di push e l'integrazione con i social network mediante un SDK e una API unificata.

### cloud mobile
{: #x4585344}

Un'infrastruttura in cui l'archiviazione e l'elaborazione dei dati per le applicazioni viene scaricata da un dispositivo mobile nel cloud. Con l'elaborazione cloud mobile, le applicazioni non sono limitate a uno specifico vettore e sono invece accessibili tramite il web.


## N
{: #glossn}

### spazio dei nomi
{: #x2031005}

Un nome univoco che identifica il repository di immagini della tua organizzazione nel registro IBM Cloud. Vedi anche [immagine](#x2024928), [repository di immagini privato](#x8439215).

### NAT (Network Address Translation)
{: #x2031199}

Un metodo di indirizzamento utilizzato per abilitare un indirizzo IP a comunicare con molti altri indirizzi IP, come quelli su una sottorete privata tramite una tabella di ricerca. NAT (Network address translation) ha due tipi principali: 1-to-1 e many-to-1.


## O
{: #glosso}

### OAuth
{: #x6013335}

Un protocollo di autorizzazione basato su HTTP che fornisce alle applicazioni la possibilità di accedere a una risorsa protetta per conto del proprietario della risorsa, creando un'interazione di approvazione tra il proprietario della risorsa, il client e il server di risorse.

### in loco
{: #x6969434}

Vedi [installato in loco](#x4561212).

### installato in loco (in loco)
{: #x4561212}

Relativo al software installato ed eseguito sui computer locali di un utente o un'organizzazione.

### org
{: #x7470494}

Vedi [organizzazione](#x2032585).

### organizzazione (org)
{: #x2032585}

La metodologia di raggruppamento per gli utenti in IBM Cloud. Le org sono utilizzate per
gestire le quote. Gli utenti in un'organizzazione condividono le quote di istanze di servizi e memoria. Vedi anche [dominio](#x2021210), [spazio](#x2039442).


## P
{: #glossp}

### PaaS
{: #x2029790}

Vedi [platform as a service](#x2029786).

### immagine principale
{: #x8439210}

Un'immagine che fornisce una base per un'altra immagine. Ad esempio, Ubuntu Linux è l'immagine principale dell'immagine IBM Liberty. Vedi anche [immagine di base](#x5366487), [immagine](#x2024928).

### platform as a service (PaaS)
{: #x2029786}

L'offerta di una piattaforma di elaborazione, comprendente applicazioni, middleware ottimizzato, strumenti di sviluppo e ambienti di runtime Java e Web 2.0, in un ambiente basato sul cloud.

### cloud privato
{: #x4585362}

Un ambiente di elaborazione cloud in cui l'accesso è limitato ai membri delle reti di aziende e partner. Vedi anche [cloud pubblico](#x4585370).

### repository di immagini privato
{: #x8439215}

La combinazione del registro IBM Cloud di un'organizzazione e il relativo spazio dei nomi. Il repository di immagini privato viene utilizzato quando si fa riferimento a un'immagine in un comando. Vedi anche [immagine](#x2024928), [spazio dei nomi](#x2031005).

### chiave privata
{: #x2034701}

Un modello algoritmico utilizzato per crittografare messaggi che possono essere decrittografati
solo mediante la chiave pubblica corrispondente. Inoltre, la chiave privata viene utilizzata per decrittografare i messaggi crittografati con la chiave pubblica corrispondente. La chiave privata è conservata sul sistema dell'utente e protetta da password.

### risorsa privata
{: #x9439035}

Una voce che è visibile solo ai proprietari dell'account e ai rispettivi account inclusi. Quando le risorse vengono create, sono private per impostazione predefinita. Vedi anche [risorsa pubblica](#x9439040).

### servizio privato
{: #x7690456}

Un servizio visibile solo ai membri di una specifica organizzazione IBM Cloud.

### cloud pubblico
{: #x4585370}

Un ambiente di elaborazione cloud in cui l'accesso a risorse standardizzate, quali l'infrastruttura, l'hardware a più tenant e i servizi, è disponibile ai sottoscrittori in base a un criterio di pagamento basato sull'utilizzo. Vedi anche [illimitato](#x8439189), [cloud privato](#x4585362).

### gateway pubblico
{: #x9594389}

La connessione di una sottorete, con tutte le istanze del server virtuale collegate, a internet. Un gateway pubblico utilizza una NAT (network address translation) many-to-1, il che significa che migliaia di istanze del server virtuale con indirizzi privati possono utilizzare un indirizzo IP pubblico per comunicare pubblicamente su internet.

### risorsa pubblica
{: #x9439040}

Una voce visibile a chiunque nel catalogo IBM Cloud. Le risorse pubbliche possono essere create da qualsiasi provider (IBM o di terze parti). Vedi anche [risorsa privata](#x9439035).

### push (eseguire il)
{: #x2035465}

Inviare le informazioni da un server ad un client. Quando un server esegue il push del contenuto, la transazione viene avviata dal server e non da una richiesta da parte del client.

### notifica di push
{: #x5599582}

Un avviso che indica una modifica o un aggiornamento su un'icona dell'applicazione mobile.


## R
{: #glossr}

### principalmente in lettura
{: #x7470468}

Relativo ai dati che vengono modificati in modo dinamico.

### distribuzione Red-Black
{: #x8439181}

Una tecnica di distribuzione che determina una fornitura continua abilitando test, sviluppo e distribuzione sincronizzati. Inizialmente, lo sviluppo viene eseguito su un ambiente non attivo (Black) mentre l'ambiente attivo continua a prendere il traffico (Red). Quando viene avviata la distribuzione, entrambi gli ambienti diventano attivi (Red-Red) finché l'instradamento non viene disabilitato sull'ambiente della versione precedente che era attivo prima e quindi rimosso (Black) mentre il nuovo ambiente funge da solo ambiente attivo. Vedi anche [Distribuzione Blue-Green](#x7807335).

### regione
{: #x2091391}

Un territorio geografico definito. Una regione può essere una specifica area identificata da un codice postale, una città, uno stato, un gruppo di stati o un gruppo di nazioni. Ogni regione può essere una serie di altre regioni o una serie di codici postali che costituiscono la regione.

### registro
{: #x2064940}

Un repository pubblico o privato che contiene immagini utilizzate per creare
contenitori. Vedi anche [contenitore](#x2010901), [immagine](#x2024928).

### Representational State Transfer (REST)
{: #x3220976}

Uno stile di architettura software per sistemi distribuiti ipermediali come il World Wide Web. Il termine viene spesso utilizzato anche per descrivere qualsiasi interfaccia semplice
che utilizzi XML (o YAML, JSON, testo semplice) su HTTP senza un ulteriore livello di messaggistica, come SOAP.

### risorsa
{: #x2004267}

Un componente fisico o logico di cui può essere eseguito il provisioning,
o che può essere riservato, per un'istanza di servizio o applicazione.  Esempi di risorse includono database, account e processore, memoria e i limiti di archiviazione.

### gruppo di risorse
{: #x2161955}

L'ambiente e i vincoli che vengono rispettati delle istanze della risorsa contenute. Un utente può essere associato a un gruppo di risorse per abilitare la collaborazione.

### REST
{: #x3220987}

Vedi [Representational State Transfer](#x3220976).

### rotta
{: #x2037338}

L'URL utilizzato per indirizzare le richieste a un'applicazione. Una rotta è
formata da un host (o dominio secondario) facoltativo e un dominio
specificati quando si distribuisce un'applicazione. Ad esempio, nell'instradamento myapp.example.com,
myapp è l'host ed example.com è il dominio. Una
rotta può essere associata a una o più applicazioni. A meno che non venga specificato un dominio personalizzato,
nell'instradamento alla tua applicazione, IBM Cloud utilizza un dominio condiviso predefinito. Consulta anche [dominio personalizzato](#x5728384), [dominio](#x2021210), [endpoint](#x2026820), [host](#x2002243), [dominio secondario](#x2040080), [Uniform Resource Locator](#x2042491).

### regola
{: #x2037526}

- Un criterio che associa un trigger a un'azione, per cui ogni attivazione del trigger comporta la chiamata dell'azione corrispondente con l'evento trigger utilizzato come input.
- Una serie di istruzioni condizionali che abilitano i sistemi di computer a identificare relazioni ed eseguire in modo conforme delle risposte automatizzate.

### runtime
{: #x2391929}

La serie di risorse utilizzate per eseguire l'applicazione. Vedi anche [starter](#x7470511).


## Do
{: #glosss}

### SaaS
{: #x4585391}

Vedi [software as a service](#x4585386).

### ingrandire
{: #x2004442}

Aumentare la capacità della piattaforma (o del sistema) aggiungendo un maggior numero di istanze di applicazioni o servizi.

### ambito
{: #x2037763}

Nella gestione delle identità, la serie di entità che possono essere influenzate da una politica o da un ACI (access control item).

### Secure Sockets Layer (SSL)
{: #x2038004}

Un protocollo di sicurezza che fornisce la privacy delle comunicazioni. Con SSL,
le applicazioni client/server possono comunicare in un modo progettato per evitare intrusioni, manomissioni e contraffazioni dei messaggi. Vedi anche [autorità di certificazione](#x2016383).

### servizio
{: #x2038343}

Un'estensione cloud che fornisce una funzionalità pronta per l'uso, come ad esempio
software web, di messaggistica e database per l'esecuzione di codice o funzionalità di monitoraggio o gestione delle applicazioni. I servizi di norma non richiedono installazione o manutenzione e possono essere combinati per creare delle applicazioni.

### sessione
{: #x2004539}

Il periodo di tempo successivo all'avvio di un'applicazione su un dispositivo mobile dopo il quale al prodotto di assicurazione della qualità viene segnalato di avviare la raccolta della modalità di funzionamento e dei problemi della applicazione.

### single sign-on (SSO)
{: #x2213318}

Un processo di autenticazione in cui un utente può accedere a più di un sistema o di un'applicazione, immettendo un unico ID utente e un'unica password.

### software as a service (SaaS)
{: #x4585386}

Un modello di distribuzione software per mezzo del quale il software, compresi processi, applicazioni aziendali e strumenti di collaborazione, viene fornito come un servizio ai clienti tramite il cloud.

### SOR
{: #x2214822}

Vedi [system of record](#x6735061).

### spazio
{: #x2039442}

Un sottogruppo all'interno di un'organizzazione IBM Cloud. Agli utenti membri di un'organizzazione viene dato accesso a uno o più dei suoi spazi, con le autorizzazioni associate a uno specifico ruolo (come sviluppatore, responsabile o revisore). Qualsiasi membro dello spazio può visualizzare le applicazioni ma solo i membri con il ruolo di sviluppatore possono creare applicazioni e aggiungere istanze di servizio allo spazio. Le applicazioni e le istanze di servizio sono associate agli spazi. Vedere anche [organizzazione](#x2032585).

### SSL
{: #x2483907}

Vedi [Secure Sockets Layer](#x2038004).

### SSO
{: #x3456450}

Vedi [single sign-on](#x2213318).

### preparare
{: #x2067189}

Per distribuire un'applicazione, un servizio o un'istanza a un'ubicazione predefinita per l'esecuzione o il test prima della distribuzione a un ambiente di produzione. Vedi anche
[distribuzione](#x2104544).

### stanza
{: #x2094743}

Una sezione di un pacchetto software che definisce un'azione specifica da eseguire su quel pacchetto software o una serie di condizioni per le quali
eseguire le azioni sul pacchetto software. Il pacchetto software completo è una stanza contenente una gerarchia di numerose stanze differenti.

### starter
{: #x7470511}

Un template che include servizi predefiniti e codice applicativo configurato
con uno specifico pacchetto di build.Uno starter può essere del codice applicativo scritto in uno
specifico linguaggio di programmazione oppure una combinazione di codice applicativo e di una serie di servizi. Vedi anche [runtime](#x2391929).

### dominio secondario
{: #x2040080}

Un dominio che rappresenta una parte di un dominio più ampio. Vedi anche [dominio personalizzato](#x5728384), [dominio](#x2021210), [host](#x2002243), [rotta](#x2037338), [Uniform Resource Locator](#x2042491).

### sottorete
{: #x4282974}

Vedi [rete secondaria](#x2040149).

### rete secondaria (sottorete)
{: #x2040149}

Una rete divisa in sottogruppi indipendenti più piccoli che continuano ad essere interconnessi.

### system of engagement
{: #x6528306}

Un sistema IT (information technology) che incorpora tecnologie che incoraggiano
l'interazione degli utenti tramite email, sistemi di collaborazione e collegamento
in rete.  Un system of engagement spesso utilizza le tecnologie cloud per estendere l'utilizzo dei system of record. Vedi anche [system of record](#x6735061).

### system of record (SOR)
{: #x6735061}

Un sistema di archiviazione delle informazioni (come un database o un'applicazione) che memorizza i record di business e automatizza i processi standard. Vedi
anche [system of engagement](#x6528306).


## Ma
{: #glosst}

### template
{: #x2041200}

Una struttura predefinita per una risorsa utente.

### terza parte
{: #x2877945}

Relativo a un prodotto o a un servizio fornito da una società che non sia IBM.

### tile
{: #x2092493}

Una rappresentazione visiva di un'applicazione in esecuzione che fornisce lo stato su un dashboard.

### trigger
{: #x2005384}

Un meccanismo che avvia le azioni. I trigger possono essere attivati esplicitamente da un utente o attivati per conto di un utente da un'origine eventi esterna.

### radice attendibile
{: #x2042234}

Un certificato firmato da un'autorità di certificazione (CA) attendibile. Vedi anche [autorità di certificazione](#x2016383), [certificato intermedio](#x3753781).


## U
{: #glossu}

### Uniform Resource Identifier (URI)
{: #x2116436}

Un indirizzo univoco che viene utilizzato per identificare il contenuto sul web. La forma più comune di URI è l'indirizzo di una pagina Web, che rappresenta una forma particolare o un sottoinsieme di URI noto come URL (Uniform
Resource Locator). Un URI generalmente descrive in che modo accedere alla risorsa, al computer che contiene la risorsa e l'ubicazione della risorsa
su tale computer.

### Uniform Resource Locator (URL)
{: #x2042491}

L'indirizzo univoco di una risorsa informativa, accessibile in una rete quale ad esempio Internet. L'URL include il nome abbreviato del protocollo utilizzato
per accedere alla risorsa di informazioni e le informazioni utilizzate dal protocollo per individuare la risorsa di informazioni. Vedi anche [dominio personalizzato](#x5728384), [dominio](#x2021210), [host](#x2002243), [rotta](#x2037338), [dominio secondario](#x2040080).

### URI
{: #x2116461}

Vedi [Uniform Resource Identifier](#x2116436).

### URL
{: #x2042718}

Vedi [Uniform Resource Locator](#x2042491).

### gerarchia utente
{: #userhierarchy}

Una relazione di gestione utenti per gli utenti dell'infrastruttura classica che invitano altri utenti in un account. Tali utenti invitano poi altri utenti nell'account e così via. Quando un utente dell'infrastruttura classica invita un altro utente nell'account, diventa l'utente principale. Quando un utente secondario dell'utente principale invita altri utenti nell'account, tali utenti diventano dei discendenti dell'utente principale originale, che viene ora considerato il loro predecessore.


## V
{: #glossv}

### virtuale
{: #x2043123}

Relativo all'esistenza non fisica in sé, bensì simulata da software.

### macchina virtuale (VM)
{: #x2043165}

Un'implementazione software di una macchina che esegue programmi come una macchina reale. Vedi anche [server virtuale](#x2455638).

### virtual private network (VPN)
{: #x2043188}

Un'estensione di una intranet aziendale nel framework esistente
di una rete pubblica o privata. Una VPN garantisce che i dati inviati tra
due endpoint della connessione restino protetti.

### server virtuale
{: #x2455638}

Un server che condivide le proprie risorse con altri server per supportare applicazioni. Vedi anche [macchina virtuale](#x2043165).

### VM
{: #x2043253}

Vedi [macchina virtuale](#x2043165).

### VPN
{: #x2484351}

Vedi [virtual private network](#x2043188).


## Me
{: #glossw}

### WAR
{: #x2844389}

Vedi [archivio web](#x2116506).

### file WAR
{: #x2406005}

Vedi [archivio web](#x2116506).


### app web
{: #x7636628}

Vedi [applicazione web](#x2116500).

### applicazione web (app web)
{: #x2116500}

Un'applicazione accessibile mediante un browser web che fornisce alcune funzioni oltre alla visualizzazione statica delle informazioni, ad esempio consentendo all'utente di eseguire la query di un database. I componenti comuni di un'applicazione web
includono pagine HTML, pagine JSP e servlet. Vedi anche [applicazione](#x4281528).

### archivio web (WAR)
{: #x2116506}

Un formato file compresso, definito dallo standard Java EE, per la memorizzazione di tutte le risorse richieste per l'installazione e l'esecuzione di un'applicazione web in un unico file.

### spazio di lavoro
{: #x2096037}

Un contesto che contiene una raccolta di risorse utente che possono essere modificate da un utente con autorizzazioni appropriate.

## Z
{: #glossz}

### zona
{: #x2070723}

Un dominio di errore indipendente. Una zona è un'astrazione concepita per aiutare con una tolleranza di errore migliorata e una riduzione della latenza.
