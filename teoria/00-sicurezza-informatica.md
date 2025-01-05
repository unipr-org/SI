```table-of-contents
title: 
style: nestedList # TOC style (nestedList|nestedOrderedList|inlineFirstLevel)
minLevel: 0 # Include headings from the specified level
maxLevel: 0 # Include headings up to the specified level
includeLinks: true # Make headings clickable
debugInConsole: false # Print debug info in Obsidian console
```
---

# Sicurezza informatica
Con il termine Cybercrime si intende l'esecuzione di crimini, mediante l'ausilio di mezzi informatici e di telecomunicazione, con lo scopo di acquisire illegalmente informazioni e di tramutarle in denaro.

Nomenclatura:
- **AV**: Antivirus.
- **Carder**: Termine slang usato per descrivere individui che utilizzano informazioni rubate di conti di carte di credito per effettuare transazioni fraudolente.  
- **Carding**: Traffico e uso fraudolento di informazioni rubate di conti di carte di credito.  
- **Cashing**: Atto di ottenere denaro commettendo frodi. Questo può avvenire in diversi modi, ad esempio incassando bonifici Western Union, ordini di pagamento postali, o fondi su WebMoney; utilizzando dati della banda magnetica con PIN per prelievi da bancomat o account PayPal; oppure aprendo un conto bancario con un documento falso per prelevare denaro da un conto di carta di credito.  
- **CC**: Slang per "carta di credito".  
- **Change of Billing (COB o COBs)**: Atto di cambiare l'indirizzo di fatturazione di un conto di credito per farlo corrispondere a un punto di smistamento postale. Questo permette al carder di avere il pieno controllo del conto compromesso e aumenta la probabilità che il conto non venga rifiutato durante transazioni online.  
- **CVV2**: Codice di sicurezza della carta di credito. Visa, MasterCard e Discover richiedono questo codice, che è un numero di 3 cifre sul retro della carta.  
- **DDoS**: Acronimo per "Distributed Denial of Service Attack". L'obiettivo di un attacco DDoS è bloccare un sito web bersaglio, almeno temporaneamente, sovraccaricandolo di traffico.  
- **DLs**: Slang per patenti di guida false o di fantasia.  
- **Drop**: Intermediario utilizzato per nascondere la fonte di una transazione (indirizzi, telefoni, ecc.).  
- **Dumps**: Informazioni copiate di carte di pagamento, almeno i dati della traccia 1, ma solitamente sia della traccia 1 che della traccia 2.  
- **Dump checking**: Utilizzo di software specifici o la codifica dei dati della traccia su una carta di plastica per testare se il dump è approvato o rifiutato. Questo dà ai carder maggiore sicurezza sulla qualità dei dump e sulla loro accettazione nei negozi.  
- **Full info(s)**: Termine che descrive il possesso di indirizzi, numeri di telefono, numeri di previdenza sociale, PIN, report creditizi, e così via. Le "Full Info(s)" sono usate dai carder per prendere il controllo dell'identità di una persona o per venderla.  
- **Holos**: Slang per "ologrammi". Gli ologrammi sono importanti per chi realizza carte di credito false per imitare una caratteristica di sicurezza esistente.  
- **ICQ**: Abbreviazione di "I Seek You". ICQ è il sistema di messaggistica istantanea più usato dai carder, soprattutto nella cultura Internet dell'Europa dell'Est.  
- **IRC**: Abbreviazione di "Internet Relay Chat". IRC è un sistema globale di server che consente chat testuali in tempo reale, scambio di file e altre interazioni.  
- **IDs**: Slang per documenti di identità. I carder commercializzano una varietà di documenti, tra cui bollette, diplomi, patenti di guida, passaporti o qualsiasi cosa utilizzabile come documento di identità.  
- **MSR (Magnetic Strip Reader)**: Dispositivo usato per copiare informazioni di carte di pagamento e/o per codificare informazioni della banda magnetica su carte di plastica.  
- **Phishing**: Estrazione di informazioni da un obiettivo utilizzando un "amo" (solitamente un'email che si spaccia per una comunicazione ufficiale). I phisher inviano email di massa per ottenere dati da utilizzare a scopi fraudolenti.  
- **POS (Point of Sale)**: Terminale attraverso cui si strisciano le carte di credito per comunicare con i processori che approvano o rifiutano le transazioni.  
- **Proxies**: Server proxy utilizzati per mascherare l'identità su Internet. I carder usano ampiamente proxy, socks, http, https, e VPN (Virtual Private Networks) per nascondere il proprio indirizzo IP durante attività fraudolente online.  
- **Track 1/Track 2 data**: Informazioni memorizzate sulla banda magnetica di una carta di pagamento che contengono i dati del conto.

## Hat
- **Black-hat**: Hacker che violano i sistemi informatici per scopi personali o criminali. Rubano informazioni e spesso le rivendono a paesi stranieri. Agiscono deliberatamente sul “lato oscuro” dell'hacking.
- **Grey-hat**: Hacker che non si identificano né come black-hat né come white-hat. Possono aver commesso intrusioni in passato ma scelgono di non perseguire attività criminali.
- **White-hat**: Hacker “etici” con le competenze dei black-hat, ma che collaborano con autorità e aziende per combattere i crimini informatici. Non violano sistemi per scopi illeciti o economici.

## Hacker's Profiling Project (HPP)

| **ID dell'attaccante**              | **Hacker solitario / di gruppo**           | **Obiettivo**                     | **Motivazioni / Scopi**                                                             |
| ----------------------------------- | ------------------------------------------ | --------------------------------- | ----------------------------------------------------------------------------------- |
| **Wanna Be Lamer**                  | GRUPPO                                     | Utente finale                     | Per moda, è "figo" => per vantarsi e mettersi in mostra                             |
| **Script Kiddie**                   | GRUPPO: ma agiscono da soli                | PMI / Vulnerabilità specifiche    | Per sfogare la loro rabbia / attirare l'attenzione dei media                        |
| **Cracker**                         | SOLITARIO                                  | Aziende                           | Per dimostrare il loro potere / attirare l'attenzione dei media                     |
| **Ethical Hacker**                  | SOLITARIO / GRUPPO (solo per divertimento) | Fornitori / Tecnologia            | Per curiosità (per imparare) e scopi altruistici                                    |
| **Quiet, Paranoid, Skilled Hacker** | SOLITARIO                                  | Su necessità                      | Per curiosità (per imparare) => scopi egoistici                                     |
| **Cyber-Warrior**                   | SOLITARIO                                  | Aziende "simbolo" / Utenti finali | Per profitto                                                                        |
| **Industrial Spy**                  | SOLITARIO                                  | Aziende / Corporazioni            | Per profitto                                                                        |
| **Government Agent**                | SOLITARIO / GRUPPO                         | Governo / Terroristi sospetti   | Spionaggio / Controspionaggio / Test di vulnerabilità / Monitoraggio delle attività |
| **Military Hacker**                 | SOLITARIO / GRUPPO                         | Governo / Aziende strategiche     | Monitoraggio / controllo / sabotaggio di sistemi                                    |

## Fasi del cybercrime
Attori principali:
- **Hackers**: eseguono attacchi informatici.
- **Command**: coordinano le operazioni.
- **E-launderers**: gestiscono il riciclaggio dei guadagni illeciti.

 Fasi operative:
1. **Fase 1**:
   - Eseguire attacchi informatici.
   - Sviluppare malware.
   - Creare botnet.

2. **Fase 2**:
   - Furto di identità (ID-theft).
   - Raccolta di informazioni personali.
   - Raccolta di informazioni finanziarie.

3. **Fase 3**:
   - Commettere crimini elettronici (e-crimes).
   - Operazioni bancarie online (e-banking).
   - E-commerce illecito.

4. **Fase 4**:
   - Ottenere i proventi.
   - Creare una rete per il riciclaggio online (e-laundering).
   - Trasferire guadagni illeciti.

Economia sommersa:
- **Attività principali**:
  - Commercio di beni rubati.
  - Scambio di informazioni rubate, malware, strumenti, competenze e abilità

---

# OSINT
L'**O**pen **S**ource **INT**elligence consiste nella ricerca di informazioni tratte da fonti liberamente disponibili e si differenzia dalle altre attività di Intelligence in quanto le informazioni non sono ottenute "illegalmente".

Esistono quattro distinte categorie di *open source information and intelligence*:
- Open Source Data (OSD): "I dati sono la stampa grezza, la trasmissione, il debriefing orale o altre forme di informazioni da una fonte primaria".
- Open Source Information (OSI): "OSI è composto dai dati grezzi che possono essere messi insieme, generalmente da un processo editoriale che fornisce un po' di filtraggio e convalida, nonché la gestione delle presentazioni".
- Open Source Intelligence (OSINT): "OSINT è un'informazione che è stata deliberatamente scoperta, discriminata, distillata e diffusa a un pubblico selezionato, generalmente il comandante e il suo personale diretto, al fine di rispondere a una domanda specifica".
- Validated OSINT (OSINT-V): "OSINT-V è un'informazione a cui può essere attribuito un altissimo grado di certezza. Può essere prodotto solo da un professionista dell'intelligence di tutte le fonti, con accesso a fonti di intelligence classificate, ecc.".

In ambito militare, l'OSINT consiste nella "raccolta, selezione, distillazione e diffusione di informazioni non classificate ad una comunità ristretta ed in relazione a specifici argomenti".

Le informazioni recuperabili tramite OSINT non sono utilizzabili soltanto per fini "negativi": possono essere utilmente impiegate per supportare decisioni strategiche, valutare campagne di marketing, verificare il "sentiment" e la reputazione online, migliorare la sicurezza dell'organizzazione, ecc.

> Esempi di OSINT: password visibili nelle dirette TV.

I problemi dell'OSINT sono le barriere culturali, la disinformazione delle notizie (fake, manipolate, ecc.), troppa fiducia nei tools automatici, Cognitive BIAS (pattern sistematico di deviazione dalla norma o dalla razionalità nel giudizio), traffico (generata una grande quantità di traffico che può essere sospetta).

L'immagine sottostante elenca e suddivide il mercato globale dell'OSINT per segmenti.

![[01.png]]

## Modalità di fare OSINT
Esistono tre modalità per fare OSINT:
- Manuale: la ricerca viene effettuata direttamente dall'operatore. Le scelte vengono fatte sul momento; raccolta e confronto oneroso, difficilmente scalabile ed elevato rischio di perdere informazioni; qualità del dato e validazione analista su molteplici basi di dati.
- Automatica: la ricerca viene effettuata tramite strumenti parametrizzabili. Deve essere effettuata una scrematura a posteriori; potenzialmente molto efficace, facilmente scalabile ed integrabile, richiede enormi investimenti (HW e SW); rischio di falsi positivi dovuti ad AI non evoluta come analista.
- Mix: utilizzo di operazioni automatiche e manuali validate ed analizzate dall'occhio critico dell'analista. Benefici dall'uso di tecniche automatiche per l'individuazione o la connessione di dati, parte critica e di eliminazione del rumore da parte dell'analista

## Fasi di OSINT
L'attività OSINT si divide in cinque fasi:
1. Planning & Direction: definisco obiettivi e fonti.
2. Collection: raccolgo i dati dalle fonti identificate nella fase 1.
3. Analysis & Collation: analizzo e confronto i dati raccolti.
4. Dissemination: diffusione dei report contenenti i dati precedentemente raccolti e rielaborati.
5. Feedback: misuro il gradimento del cliente. 

## Tipi di OSINT

![[02.png]]

Keyword nei motori di ricerca:
- AND: entrambe le parole devono essere presenti, e.g., green AND blue.
- OR: almeno una delle parole deve essere presente, e.g., green OR blue.
- `-` (Minus): escludere i risultati.
- `*` (Asterisk): wildcard, include delle derivazioni.
- `""` (Quotes): per cercare una parola o frase in maniera specifica.
- Altre keyword: ![[03.png]]

## Analisi delle fonti
La valutazione delle fonti è un fattore importante del processo OSINT. Ci sono delle domande che ci dobbiamo porre per determinare l'affidabilità delle fonti (who, when, where, what, why).

Nomenclatura OSINT:
- I2P: è una rete di copertura anonima, una rete dentro la rete. Il suo scopo è di proteggere le comunicazioni dal controllo a tappeto e dal monitoraggio di terze parti come gli ISP.
- Freenet: è una rete decentralizzata, creata per resistere alla censura, che sfrutta le risorse (banda passante, spazio su disco) dei suoi utenti per permettere la pubblicazione e la fruizione di qualsiasi tipo di informazione. Costruita pensando ad anonimato e sicurezza, non alla velocità di trasmissione.
- Google Dorks: ricerche che possono essere fatte indicando specifiche parole chiave che istruiscono il motore affinché imposti speciali filtri.
- Meta Search Engine: un motore di ricerca definito metasearch utilizza altri motori di ricerca e aggrega i loro dati.
- Dati EXIF: metadati delle fotografie.
- Wayback Machine: progetto con lo scopo di archiviare e rendere disponibili pagine web e le loro modifiche nel tempo.
- FOCA (Fingerprinting Organizations with Collected Archives): strumento utilizzato principalmente per trovare i metadati e le informazioni nascoste nei documenti esaminati.
- MALTEGO: software che offre la possibilità di raccogliere informazioni tramite la consultazione di dati pubblicamente accessibili e raggrupparle, in formato grafico, attraverso l'utilizzo di trasformazioni.

---

# Autodifesa

## Deep Web vs Dark Web
Il **Deep Web** comprende tutte le informazioni e i contenuti che non sono indicizzati dai motori di ricerca tradizionali, come Google o Bing.  
Questi motori utilizzano spider, strumenti automatizzati per scansionare il web e raccogliere i contenuti delle pagine. Tuttavia, alcuni fattori possono impedire agli spider di accedere e indicizzare determinati contenuti, tra cui:

- Blocchi di sicurezza.  
- Codici corrotti o mal configurati.  
- Configurazioni speciali (ad esempio file `.htaccess`).  
- Protezioni tramite password.  

Rientrano in questa categoria:
- Siti web di nuova creazione non ancora indicizzati.  
- Pagine web con contenuti dinamici.  
- Applicazioni web.  
- Siti privati aziendali.

Il **Dark Web** è un sottoinsieme del Deep Web, accessibile esclusivamente tramite software specifici che fungono da ponte tra Internet e le reti anonime, note come **DarkNet**.

Le darknet più comuni:
- **Tor**: uno dei più famosi, fornisce accesso alla rete Tor e garantisce l'anonimato degli utenti, consentendo loro di navigare sia sul Dark Web che sul normale World Wide Web in modo anonimo.  
- **I2P**: progettata per comunicazioni anonime tra utenti.  
- **Freenet**: focalizzata sulla condivisione sicura e anonima di file.

## By Design e By Default
Per **dato personale** si intende qualunque informazione relativa a persona fisica, persona giuridica, ente o associazione, identificati o identificabili, anche indirettamente, mediante riferimento a qualsiasi altra informazione, ivi compreso un numero di identificazione personale. Si considera tale il dato oggettivo, ma anche il dato valutativo.

Il **GDPR** introduce due approcci obbligatori per il trattamento dei dati personali: **By Design** e **By Default**.

**By Design**: significa analizzare il trattamento dei dati lungo tutto il loro ciclo di vita.  
L'obiettivo è tutelare i diritti dell'interessato fin dalla fase di progettazione e durante tutta la gestione dei dati, adottando misure tecniche e organizzative, come:
- **Minimizzazione dei dati**: raccogliere solo i dati strettamente necessari.  
- **Pseudonimizzazione**: separare i dati personali dall'identità dell'interessato per ridurre il rischio di accesso non autorizzato.

**By Default**: prevede di adottare configurazioni inizialmente “chiuse” per i sistemi informatici, ampliandole solo dopo una valutazione attenta dell'impatto di eventuali aperture.  
Le impostazioni predefinite devono garantire la massima protezione della privacy, affinché:
- I dati personali siano accessibili solo a chi è autorizzato.  
- Non vengano resi accessibili a un numero indefinito di persone senza esplicito intervento umano.

## Data breach
Con il termine **data breach** si intende un incidente di sicurezza in cui dati sensibili, protetti o riservati vengono consultati, copiati, trasmessi, rubati o utilizzati da un soggetto non autorizzato. Solitamente il data breach si realizza con una divulgazione di dati riservati o confidenziali all'interno di un ambiente privo di misure di sicurezze (da esempio, su web) in maniera involontaria o volontaria. Tale divulgazione può avvenire in seguito a:
- Perdita accidentale: ad esempio, data breach causato da smarrimento di una chiavetta USB contenente dati riservati.
- Furto: ad esempio, data breach causato da furto di un notebook contenente dati confidenziali.
- Infedeltà aziendale: ad esempio, data breach causato da una persona interna che avendo autorizzazione ad accedere ai dati ne produce una copia distribuita in ambiente pubblico.
- Accesso abusivo: ad esempio, data breach causato da un accesso non autorizzato ai sistemi informatici con successiva divulgazione delle informazioni acquisite.

## Cancellazione di file e Slack Space
Quando viene cancellato un file, viene solo messo un flag (l'operazione effettiva varia in base al file system) per indicare che il file è "deleted". I cluster utilizzati dal file cancellato vengono resi nuovamente disponibili per altri file.
L'operazione di cancellazione di un file **non ripulisce i cluster** del loro contenuto, permettendo così il recupero dei file cancellati se non sono stati **sovrascritti**.
Se il contenuto di un file non riempie completamente un cluster, possono rimanere parti del file che occupava precedentemente quel cluster. Questo spazio residuo viene chiamato **Slack Space**.

---

# Network Forensics
La parola **forensics** deriva dal latino *forens*, che significa "appartenente al pubblico". È correlata alle parole *forum* e *scientia*, che significano rispettivamente "nel foro" e "conoscenza".
> Nell'antica Roma, i procedimenti penali si svolgevano pubblicamente nel mercato (*forum*).

La scienza forense si riferisce all'applicazione di metodi scientifici nei procedimenti penali e civili.

Gli aspetti tecnici delle investigazioni forensi si sono evoluti in diverse **sotto-discipline**, in base alle particolari condizioni delle prove (e.g., tossicologia, analisi delle impronte digitali).

La **digital forensics** è una branca della scienza forense che si occupa del recupero e dell'indagine di materiali presenti in formato digitale.

## Principi fondamentali per la gestione delle prove elettroniche
1. **Integrità dei dati (Data integrity)**: Nessuna azione intrapresa deve modificare dispositivi elettronici o supporti, i quali potrebbero essere successivamente utilizzati in tribunale.

2. **Tracciabilità (Audit trail)**: Deve essere creato e conservato un registro (audit trail) o altra documentazione di tutte le azioni intraprese durante la gestione delle prove elettroniche. Un terzo indipendente dovrebbe essere in grado di esaminare tali azioni e ottenere gli stessi risultati.

3. **Supporto specialistico (Specialist support)**: Se si presume che durante un’operazione possano essere trovate prove elettroniche, la persona responsabile deve notificare tempestivamente specialisti o consulenti esterni.

4. **Formazione adeguata (Appropriate training)**: I primi soccorritori devono essere adeguatamente formati per cercare e sequestrare prove elettroniche nel caso in cui non siano presenti esperti sul posto.

5. **Legalità (Legality)**: La persona o l’agenzia responsabile del caso deve assicurarsi che vengano rispettati la legge, i principi forensi generali, quelli procedurali e i principi elencati. Questo vale per il possesso e l’accesso alle prove elettroniche.

## Metodologia OSCAR

La **network forensics** segue gli stessi principi di base della digital forensics, adottando la metodologia OSCAR, un framework che garantisce risultati costanti e appropriati.

![[04.png]]

### 1. Ottenere informazioni (Obtain)
Una delle prime azioni è raccogliere informazioni sull'incidente e sull'ambiente. Questo passaggio è cruciale per fornire al perito forense un quadro dettagliato dell'evento. È essenziale raccogliere dati come:
- Timestamp e timeline dell'evento;
- Persone coinvolte;
- Sistemi ed endpoint interessati dall'incidente.

### 2. Strategizzare (Strategize)
La pianificazione dell'indagine è fondamentale, poiché i log dei vari dispositivi possono differire per natura. Ad esempio, la volatilità dei log di un firewall è diversa da quella di dettagli come l'ARP di un sistema.  
Durante questa fase bisogna:
- Definire obiettivi chiari e una timeline;
- Identificare le fonti di evidenza;
- Analizzare il costo e il valore delle fonti;
- Prioritizzare l'acquisizione delle prove;
- Pianificare aggiornamenti periodici per il "cliente";
- Utilizzare la lista delle priorità per allocare risorse e personale.

### 3. Raccogliere le prove (Collect)
In questa fase, le prove vengono acquisite seguendo il piano stabilito. L'acquisizione richiede la documentazione di tutti i sistemi utilizzati, la cattura e il salvataggio dei flussi di dati su hard disk e la raccolta di log da server e firewall.

Best practice per la raccolta delle prove:
1. Creare copie delle prove e generare hash crittografici per la verifica:
   - Catturare pacchetti, copiare log, creare immagini dei dischi rigidi, ecc.
2. Non lavorare mai sulle prove originali; utilizzare sempre copie.
3. Usare strumenti standard del settore.
4. Documentare tutte le azioni: tutte le operazioni effettuate e i sistemi accessi devono essere registrati. La documentazione deve includere:
   - Orario, fonte delle prove, metodo di acquisizione e i nomi degli investigatori coinvolti.
5. Conservare e trasportare le prove: mantenere la **catena di custodia**, documentando ogni fase del sequestro, custodia, controllo, trasferimento, analisi e gestione delle prove (fisiche o elettroniche).

### 4. Analizzare i dati (Analyze)
Questa è la fase centrale dell'indagine, in cui si analizzano i dati per risolvere il caso. Si utilizzano tecniche sia automatiche che manuali, con strumenti specifici, per:
- Correlare dati provenienti da diverse fonti;
- Creare una timeline degli eventi;
- Eliminare falsi positivi;
- Formulare teorie supportate dalle prove.

> Gran parte del tempo in un'indagine forense è dedicata proprio all'analisi dei dati.

## Monitoraggio del traffico di rete

Una delle forme più basilari di cattura delle informazioni è l'uso di **taps** su cavi di rete o fibra ottica per intercettare il traffico.

La maggior parte dei fornitori di dispositivi di rete offre:
- **Network taps**: strumenti che permettono di duplicare il traffico di rete per l'analisi.
- **Porte SPAN (Switched Port Analyzer)**: porte che inoltrano tutto il traffico visto su una determinata porta o VLAN al sistema di analisi.

---

# Digital Forensics
La **Digital Forensics** è la scienza che studia come ottenere, preservare, analizzare e documentare le evidenze digitali (prove) dai dispositivi elettronici come: Tablet PC, Server, PDA, fax machine, digital camera, iPod, Smartphone (Mobile Forensics) e tutti gli altri dispositivi di memorizzazione.
Una **digital evidence** può essere definita come qualsiasi informazione avente valore probatorio che sia memorizzata o trasmessa in forma digitale.

Fasi della Computer Forensics:
1. **Identificazione, Raccolta e Acquisizione**: Prima fase in cui si identificano, raccolgono e acquisiscono i dati rilevanti per l'indagine (Live Forensics).
2. **Preservazione (Catena di Custodia)**: Garantire che i dati raccolti siano protetti e che la catena di custodia venga mantenuta, documentando ogni passaggio del trattamento delle prove (Forensics Copy).
3. **Analisi**: Estrarre i dati significativi per l'indagine e analizzarli. Questa fase prevede l'utilizzo di strumenti e tecniche per individuare informazioni rilevanti (Forensics Toolkit).
4. **Presentazione delle Prove**: Fase finale e più importante, durante la quale i risultati dell'indagine sono presentati in modo comprensibile anche ai non esperti (come avvocati, pubblici ministeri, giudici, ecc.). È una buona pratica redigere un documento in cui vengono analizzati e spiegati, passo dopo passo, tutti i dati raccolti e i risultati ottenuti.

## Antiforensics
La cifratura è un ottimo metodo di Antiforensics. Esistono anche altre tipologie di Antiforensics come la **steganografia** e la **cancellazione sicura dei file**.

Il termine **steganografia** deriva dal greco, e il suo significato letterale è "scrittura nascosta". È differente dalla crittografia in quanto, la steganografia nasconde un'informazione (l'esistenza di una informazione), mentre la crittografia la cifra (nasconde il contenuto dell'informazione). Le due tecniche possono essere abbinate e sono complementari. Utilizzando la crittografia vediamo il messaggio, ma cifrato, mentre l'obiettivo della steganografia è di nascondere un qualcosa (messaggio) all'interno di un contenitore noto. Per tecnica steganografica quindi si intende quel processo di occultamento di un' informazione (aka camouflage).