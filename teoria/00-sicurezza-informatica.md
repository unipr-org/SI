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
Con il termine Cybercrime si intende l'esecuzione di crimini, mediante l’ausilio di mezzi informatici e di telecomunicazione, con lo scopo di acquisire illegalmente informazioni e di tramutarle in denaro.

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
- **ICQ**: Abbreviazione di "I Seek You". ICQ è il sistema di messaggistica istantanea più usato dai carder, soprattutto nella cultura Internet dell’Europa dell’Est.  
- **IRC**: Abbreviazione di "Internet Relay Chat". IRC è un sistema globale di server che consente chat testuali in tempo reale, scambio di file e altre interazioni.  
- **IDs**: Slang per documenti di identità. I carder commercializzano una varietà di documenti, tra cui bollette, diplomi, patenti di guida, passaporti o qualsiasi cosa utilizzabile come documento di identità.  
- **MSR (Magnetic Strip Reader)**: Dispositivo usato per copiare informazioni di carte di pagamento e/o per codificare informazioni della banda magnetica su carte di plastica.  
- **Phishing**: Estrazione di informazioni da un obiettivo utilizzando un "amo" (solitamente un'email che si spaccia per una comunicazione ufficiale). I phisher inviano email di massa per ottenere dati da utilizzare a scopi fraudolenti.  
- **POS (Point of Sale)**: Terminale attraverso cui si strisciano le carte di credito per comunicare con i processori che approvano o rifiutano le transazioni.  
- **Proxies**: Server proxy utilizzati per mascherare l'identità su Internet. I carder usano ampiamente proxy, socks, http, https, e VPN (Virtual Private Networks) per nascondere il proprio indirizzo IP durante attività fraudolente online.  
- **Track 1/Track 2 data**: Informazioni memorizzate sulla banda magnetica di una carta di pagamento che contengono i dati del conto.

## Hat
- **Black-hat**: Hacker che violano i sistemi informatici per scopi personali o criminali. Rubano informazioni e spesso le rivendono a paesi stranieri. Agiscono deliberatamente sul “lato oscuro” dell’hacking.
- **Grey-hat**: Hacker che non si identificano né come black-hat né come white-hat. Possono aver commesso intrusioni in passato ma scelgono di non perseguire attività criminali.
- **White-hat**: Hacker “etici” con le competenze dei black-hat, ma che collaborano con autorità e aziende per combattere i crimini informatici. Non violano sistemi per scopi illeciti o economici.

## Hacker’s Profiling Project (HPP)

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
La valutazione delle fonti è un fattore importante del processo OSINT. Ci sono delle domande che ci dobbiamo porre per determinare l’affidabilità delle fonti (who, when, where, what, why).

Nomenclatura OSINT:
- I2P: è una rete di copertura anonima, una rete dentro la rete. Il suo scopo è di proteggere le comunicazioni dal controllo a tappeto e dal monitoraggio di terze parti come gli ISP.
- Freenet: è una rete decentralizzata, creata per resistere alla censura, che sfrutta le risorse (banda passante, spazio su disco) dei suoi utenti per permettere la pubblicazione e la fruizione di qualsiasi tipo di informazione. Costruita pensando ad anonimato e sicurezza, non alla velocità di trasmissione.
- Google Dorks: ricerche che possono essere fatte indicando specifiche parole chiave che istruiscono il motore affinché imposti speciali filtri.
- Meta Search Engine: un motore di ricerca definito metasearch utilizza altri motori di ricerca e aggrega i loro dati.
- Dati EXIF: metadati delle fotografie.
- Wayback Machine: progetto con lo scopo di archiviare e rendere disponibili pagine web e le loro modifiche nel tempo.
- FOCA (Fingerprinting Organizations with Collected Archives): strumento utilizzato principalmente per trovare i metadati e le informazioni nascoste nei documenti esaminati.
- MALTEGO: software che offre la possibilità di raccogliere informazioni tramite la consultazione di dati pubblicamente accessibili e raggrupparle, in formato grafico, attraverso l’utilizzo di trasformazioni.