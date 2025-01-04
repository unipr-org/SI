```table-of-contents
title: 
style: nestedList # TOC style (nestedList|nestedOrderedList|inlineFirstLevel)
minLevel: 0 # Include headings from the specified level
maxLevel: 0 # Include headings up to the specified level
includeLinks: true # Make headings clickable
debugInConsole: false # Print debug info in Obsidian console
```
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

## Nomenclatura
- I2P: è una rete di copertura anonima, una rete dentro la rete. Il suo scopo è di proteggere le comunicazioni dal controllo a tappeto e dal monitoraggio di terze parti come gli ISP.
- Freenet: è una rete decentralizzata, creata per resistere alla censura, che sfrutta le risorse (banda passante, spazio su disco) dei suoi utenti per permettere la pubblicazione e la fruizione di qualsiasi tipo di informazione. Costruita pensando ad anonimato e sicurezza, non alla velocità di trasmissione.
- Google Dorks: ricerche che possono essere fatte indicando specifiche parole chiave che istruiscono il motore affinché imposti speciali filtri.
- Meta Search Engine: un motore di ricerca definito metasearch utilizza altri motori di ricerca e aggrega i loro dati.
- Dati EXIF: metadati delle fotografie.
- Wayback Machine: progetto con lo scopo di archiviare e rendere disponibili pagine web e le loro modifiche nel tempo.
- FOCA (Fingerprinting Organizations with Collected Archives): strumento utilizzato principalmente per trovare i metadati e le informazioni nascoste nei documenti esaminati.
- MALTEGO: software che offre la possibilità di raccogliere informazioni tramite la consultazione di dati pubblicamente accessibili e raggrupparle, in formato grafico, attraverso l’utilizzo di trasformazioni.