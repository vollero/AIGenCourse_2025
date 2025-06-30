# Sviluppo di Materiale Didattico STEM con LLM
## Esempi di Complessità Crescente per Prompt

---

## ESEMPIO 1: MATEMATICA - Derivate
### Livello di Complessità: ⭐ (Principiante)

#### Prompt Semplice
```
Spiega cos'è una derivata
```

**Problemi del prompt semplice:**
- Troppo generico
- Non specifica il livello target
- Non indica il formato desiderato
- Non considera il contesto didattico

#### Prompt Complesso
```
Crea una lezione sulle derivate per studenti universitari del primo anno di ingegneria. 
Includi:
- Definizione intuitiva e formale
- 3 esempi pratici di calcolo
- Applicazioni nell'ingegneria
- Esercizi con soluzioni
```

#### Prompt Completo
```
CONTESTO: Preparazione materiale didattico per corso "Analisi Matematica I"
DESTINATARI: Studenti primo anno Ingegneria (18-19 anni, conoscenze: algebra, geometria analitica)
OBIETTIVO: Lezione introduttiva sulle derivate (90 minuti)

RICHIESTA: Crea materiale didattico strutturato che includa:

STRUTTURA DELLA LEZIONE:
1. Apertura motivazionale (10 min): problema reale che richiede il concetto di derivata
2. Sviluppo teorico (40 min):
   - Definizione intuitiva tramite velocità istantanea
   - Passaggio al limite e definizione formale
   - Interpretazione geometrica (retta tangente)
3. Esempi guidati (25 min): 4 derivate con difficoltà crescente
4. Applicazioni (10 min): 2 esempi dall'ingegneria
5. Consolidamento (5 min): riepilogo e anticipazioni

OUTPUT RICHIESTO:
- Slide principale con punti chiave
- Note per il docente con timing e spiegazioni dettagliate
- 3 esercizi guidati step-by-step
- 5 esercizi per casa con livelli di difficoltà indicati
- Lista di errori comuni e come evitarli
- Collegamento con lezioni precedenti e successive

FORMATO: Markdown con sezioni chiaramente delimitate
STILE: Linguaggio accessibile ma rigoroso, esempi concreti, analogie quando utili
```

---

## ESEMPIO 2: FISICA - Circuiti Elettrici
### Livello di Complessità: ⭐⭐ (Intermedio)

#### Prompt Semplice
```
Spiega i circuiti in corrente continua
```

#### Prompt Complesso
```
Progetta un laboratorio virtuale sui circuiti RC per studenti di Fisica II. 
Includi simulazioni, calcoli teorici, grafici e relazione finale.
Target: 3 ore di laboratorio.
```

#### Prompt Completo
```
CONTESTO: Laboratorio di Fisica II - Università di Ingegneria Elettronica
DESTINATARI: Studenti secondo anno (prerequisiti: Fisica I, Analisi I e II)
SESSIONE: Laboratorio pratico 3 ore + 2 ore elaborazione dati

OBIETTIVO FORMATIVO: 
Comprendere il comportamento dinamico dei circuiti RC attraverso approccio teorico-sperimentale

COMPETENZE DA SVILUPPARE:
- Analisi matematica di circuiti con elementi reattivi
- Uso di strumentazione (oscilloscopio, generatore di funzioni)
- Elaborazione dati sperimentali e confronto teoria-esperimento
- Stesura relazione tecnica

ESPERIMENTO: Carica e scarica di condensatore in circuito RC

MATERIALE DA PRODURRE:

1. GUIDA PRE-LABORATORIO (30 min preparazione):
   - Richiami teorici: leggi di Kirchhoff per circuiti dinamici
   - Equazione differenziale del circuito RC
   - Soluzione analitica per carica/scarica
   - Costante di tempo τ = RC e significato fisico
   - Domande di verifica prerequisiti

2. PROTOCOLLO SPERIMENTALE:
   - Schema circuito con componenti e valori
   - Procedura step-by-step per 4 misure diverse (variando R e C)
   - Tabelle per raccolta dati
   - Note di sicurezza e uso strumenti

3. ANALISI DATI:
   - Template per grafici (V vs t in scala lineare e semilogaritmica)
   - Metodi per estrazione costante di tempo dai dati
   - Calcolo incertezze e propagazione errori
   - Confronto valori teorici vs sperimentali

4. ESERCIZI DI APPROFONDIMENTO:
   - 3 problemi numerici con circuiti RC più complessi
   - 1 problema progettuale (dimensionare RC per specifica temporale)
   - Estensione a circuiti RLC (cenni)

5. TEMPLATE RELAZIONE:
   - Struttura standard relazione tecnica
   - Criteri di valutazione
   - Esempi di grafici ben formattati
   - Checklist completezza

OUTPUT AGGIUNTIVO:
- Slides riassuntive per discussione risultati (20 min)
- FAQ su errori comuni e troubleshooting
- Risorse per approfondimento
- Connessioni con applicazioni ingegneristiche reali

FORMATO: Materiale modulare in PDF + file Excel per analisi dati
```

---

## ESEMPIO 3: CHIMICA - Determinazione dell'Ordine di Reazione
### Livello di Complessità: ⭐⭐⭐ (Avanzato)

#### Prompt Semplice
```
Spiega come determinare l'ordine di reazione
```

**Problemi del prompt semplice:**
- Non specifica quale metodo utilizzare
- Non indica il livello matematico richiesto
- Non considera l'aspetto sperimentale
- Non include interpretazione dei dati

#### Prompt Complesso
```
Crea una lezione sulla determinazione dell'ordine di reazione per studenti di chimica fisica.
Includi il metodo delle velocità iniziali, elaborazione dati sperimentali,
grafici linearizzati e interpretazione dei risultati con esempi pratici.
```

#### Prompt Completo
```
CONTESTO: Preparazione materiale didattico per corso "Chimica Fisica - Cinetica"
DESTINATARI: Studenti III anno Chimica (prerequisiti: Analisi I, Chimica Generale, Termodinamica)
OBIETTIVO: Lezione su determinazione ordine di reazione con metodo velocità iniziali (100 minuti)

COMPETENZA SPECIFICA TARGET:
"Determinare sperimentalmente l'ordine di reazione utilizzando il metodo delle velocità iniziali,
elaborare dati con Excel/software, interpretare correttamente i risultati ottenuti"

PREREQUISITI VERIFICATI:
- Concetto di velocità di reazione
- Legge cinetica v = k[A]^m[B]^n
- Logaritmi e funzioni esponenziali
- Uso base Excel per grafici

REAZIONE MODELLO:
2 NO(g) + 2 H₂(g) → N₂(g) + 2 H₂O(g)
(Reazione con ordini diversi per visualizzare metodologia)

STRUTTURA LEZIONE (100 minuti):

1. Richiamo teorico mirato (15 min):
   - Definizione ordine di reazione (parziale e totale)
   - Legge cinetica: v₀ = k[A₀]^m[B₀]^n
   - Perché usare velocità iniziali (no interferenze prodotti)
   - Preview del metodo: variazione sistematica concentrazioni

2. Metodologia step-by-step (25 min):
   
   Setup sperimentale concettuale:
   - Serie esperimenti con [A] variabile, [B] costante
   - Serie esperimenti con [B] variabile, [A] costante
   - Misurazione v₀ per ogni esperimento
   
   Elaborazione matematica:
   - Rapporto velocità: v₀₂/v₀₁ = k[A₂]^m[B]^n / k[A₁]^m[B]^n = ([A₂]/[A₁])^m
   - Isolamento ordine: m = log(v₀₂/v₀₁) / log([A₂]/[A₁])
   - Stesso procedimento per ordine rispetto a B

3. Esempio guidato con dati reali (35 min):
   
   Dataset sperimentale:
   Exp | [NO]₀ (M) | [H₂]₀ (M) | v₀ (M/s)
   1   | 0.10      | 0.10      | 2.5×10⁻⁶
   2   | 0.20      | 0.10      | 1.0×10⁻⁵
   3   | 0.30      | 0.10      | 2.3×10⁻⁵
   4   | 0.10      | 0.20      | 5.0×10⁻⁶
   5   | 0.10      | 0.30      | 7.5×10⁻⁶
   
   Calcolo ordine rispetto a NO:
   - Confronto Exp 1 vs 2: m = log(1.0×10⁻⁵/2.5×10⁻⁶) / log(0.20/0.10) = log(4)/log(2) = 2
   - Verifica con Exp 1 vs 3: m = log(2.3×10⁻⁵/2.5×10⁻⁶) / log(0.30/0.10) ≈ 2
   
   Calcolo ordine rispetto a H₂:
   - Confronto Exp 1 vs 4: n = log(5.0×10⁻⁶/2.5×10⁻⁶) / log(0.20/0.10) = 1
   - Verifica con Exp 1 vs 5: n = log(7.5×10⁻⁶/2.5×10⁻⁶) / log(0.30/0.10) = 1
   
   Legge cinetica finale:
   v = k[NO]²[H₂]¹, ordine totale = 3

4. Elaborazione grafica con Excel (15 min):
   - Grafico log(v₀) vs log([NO]) → pendenza = ordine
   - Grafico log(v₀) vs log([H₂]) → pendenza = ordine
   - Calcolo coefficiente correlazione R²
   - Determinazione costante k dall'intercetta

5. Casi limite e interpretazione (8 min):
   - Ordine 0: velocità indipendente da concentrazione
   - Ordine 1: velocità proporzionale a concentrazione
   - Ordini non interi: meccanismi complessi
   - Quando il metodo non funziona (reazioni molto veloci)

6. Esercitazione guidata (2 min):
   - Dataset nuovo da elaborare in autonomia
   - Verifica risultati con docente

OUTPUT RICHIESTO:

MATERIALE DOCENTE:
- Dataset Excel con 3 esempi di complessità crescente
- Soluzioni complete con grafici Excel
- Checklist errori comuni nell'elaborazione
- Template Excel preformattato per studenti

MATERIALE STUDENTE:
- Guida step-by-step per elaborazione Excel
- Scheda formule essenziali plastificata
- 3 dataset per esercitazione autonoma
- Video tutorial Excel per grafici logaritmici
- Interpretazione fisica degli ordini di reazione

ESERCIZI GRADUALI:

Livello 1 - Ordini interi semplici:
- Reazioni con ordini 0, 1, 2 chiari
- Dati "puliti" senza incertezze

Livello 2 - Complessità intermedia:
- Ordini non interi (1.5, 2.5)
- Presenza di incertezze sperimentali

Livello 3 - Casi reali:
- Dati da letteratura con scatter
- Necessità di analisi statistica

SOFTWARE E STRUMENTI:
- Excel con add-in Analysis ToolPak
- Template grafico automatico
- Calcolatore online per verifica rapida
- Link a database cinetici (NIST)

VALUTAZIONE COMPETENZA:
- Problem solving: nuovo dataset in 20 minuti
- Interpretazione: spiegazione significato fisico ordini
- Technical skills: creazione grafico Excel autonoma
- Critical thinking: identificazione dati anomali

ERRORI COMUNI DA EVITARE:
- Confondere ordine con stechiometria
- Usare concentrazioni finali invece di iniziali
- Errori nei logaritmi (base 10 vs naturale)
- Sovra-interpretazione di R² in presenza di pochi punti

FORMATO: Lezione interattiva con laptop/Excel per ogni studente
FOLLOW-UP: Laboratorio pratico entro 1 settimana
ASSESSMENT: Quiz online con interpretazione grafici (48h post-lezione)
```

---

## ESEMPIO 4: INFERMIERISTICA - Misurazione della Pressione Arteriosa
### Livello di Complessità: ⭐⭐ (Intermedio)

#### Prompt Semplice
```
Spiega come misurare la pressione arteriosa
```

**Problemi del prompt semplice:**
- Non specifica la metodica (manuale vs automatica)
- Non considera errori comuni
- Non indica il contesto formativo
- Non include aspetti di interpretazione

#### Prompt Complesso
```
Crea una lezione sulla misurazione manuale della pressione arteriosa per studenti infermieri.
Includi tecnica corretta, posizionamento paziente, interpretazione valori,
errori frequenti e esercitazione pratica con feedback.
```

#### Prompt Completo
```
CONTESTO: Lezione per corso "Metodologie Infermieristiche di Base"
DESTINATARI: Studenti I anno Infermieristica (nessuna esperienza clinica precedente)
OBIETTIVO: Padronanza tecnica misurazione PA manuale con sfigmomanometro aneroide (90 minuti)

COMPETENZA SPECIFICA TARGET:
"Eseguire misurazione accurata PA manuale identificando correttamente 
toni di Korotkoff e ottenendo valori riproducibili (±4 mmHg)"

PREREQUISITI VERIFICATI:
- Conoscenza anatomia cardiovascolare base
- Funzionamento sistema circolatorio
- Concetti pressione sistolica/diastolica
- Uso fonendoscopio (ascolto toni cardiaci)

STRUTTURA LEZIONE (90 minuti):

1. Richiamo teorico (15 minuti):
   - Definizione pressione arteriosa sistolica/diastolica
   - Significato clinico valori normali/patologici
   - Fattori che influenzano la misurazione
   - Importanza accuratezza per decisioni cliniche

2. Dimostrazione step-by-step (20 minuti):
   
   Setup preparatorio:
   - Scelta bracciale dimensione corretta (40% circonferenza braccio)
   - Posizionamento paziente: seduto, braccio supportato, rilassato 5 min
   - Identificazione polso brachiale e posizionamento fonendoscopio
   
   Tecnica di misurazione:
   - Gonfiaggio rapido 20-30 mmHg oltre scomparsa polso radiale
   - Sgonfiaggio lento 2-3 mmHg/secondo
   - Identificazione Phase I Korotkoff (sistolica): primo tono chiaro
   - Identificazione Phase V Korotkoff (diastolica): scomparsa completa toni
   - Sgonfiaggio completo e attesa 1-2 minuti tra misurazioni

3. Pratica guidata a coppie (30 minuti):
   - Rotazione studenti: misuratore/paziente/osservatore
   - 3 misurazioni consecutive per ciascuno studente
   - Feedback immediato su tecnica da parte docente
   - Correzione errori in tempo reale

4. Focus errori comuni (15 minuti):
   - Bracciale troppo stretto/largo: effetto sui valori
   - Posizionamento scorretto: braccio pendente, non supportato
   - Gonfiaggio insufficiente: mancata rilevazione sistolica vera
   - Sgonfiaggio troppo rapido: sottostima sistolica, sovrastima diastolica
   - "White coat hypertension": effetto ansia da misurazione

5. Interpretazione valori (5 minuti):
   - Range normali: <120/80 mmHg
   - Ipertensione stadio 1: 130-139/80-89 mmHg
   - Ipertensione stadio 2: ≥140/90 mmHg
   - Quando ripetere misurazione vs allertare medico

6. Valutazione pratica (5 minuti):
   - Checklist competenze osservata
   - Auto-valutazione confidenza studente

OUTPUT RICHIESTO:

MATERIALI DOCENTE:
- Checklist osservazione tecnica (20 punti critici)
- Rubrica valutazione performance (4 livelli competenza)
- Guida gestione errori comuni con correzioni
- Timer per timing sgonfiaggio corretto

MATERIALI STUDENTE:
- Scheda tecnica plastificata step-by-step
- Tabella valori di riferimento per età
- Log-book per registrazione 10 misurazioni pratiche
- QR code per video-tutorial di ripasso

SETUP AULA:
- 1 sfigmomanometro aneroide ogni 2 studenti
- Fonendoscopi individuali (igiene)
- Bracciali varie dimensioni disponibili
- Poster gigante con posizionamento corretto

ESERCITAZIONE POST-LEZIONE:
- 10 misurazioni supervisionate su volontari diversi
- Documentazione valori e note tecniche
- Identificazione 2 situazioni di errore comune
- Peer-review con compagno di corso

CRITERI SUCCESSO:
- Ripetibilità: 3 misurazioni consecutive <5 mmHg differenza
- Accuratezza: confronto con misurazione docente esperto
- Tecnica: checklist 18/20 punti corretti
- Sicurezza: riconoscimento valori allarmanti

FORMATO: Lezione pratica hands-on con ratio 1:8 docente-studenti
FOLLOW-UP: Supervisione during prime 20 misurazioni in tirocinio
VALUTAZIONE: Esame pratico OSCE station (5 minuti per misurazione)
```

---

## ESEMPIO 5: CHIRURGIA GENERALE - Nodo Chirurgico a Mano
### Livello di Complessità: ⭐⭐ (Intermedio)

#### Prompt Semplice
```
Insegna i nodi chirurgici
```

#### Prompt Complesso
```
Crea una lezione sui nodi chirurgici manuali per studenti di medicina.
Includi nodo semplice e chirurgo, tecnica bimanuale, materiali diversi,
esercitazioni pratiche e valutazione competenze.
```

#### Prompt Completo
```
CONTESTO: Lezione pratica per corso "Metodologie in Chirurgia"
DESTINATARI: Studenti VI anno Medicina (tirocinio chirurgia)
OBIETTIVO: Padronanza nodo chirurgico bimanuale (nodo del chirurgo) (75 minuti)

COMPETENZA SPECIFICA TARGET:
"Eseguire nodo chirurgico bimanuale sicuro e riproducibile in <15 secondi
con tensione uniforme e tenuta >15N di resistenza"

PREREQUISITI VERIFICATI:
- Conoscenza anatomia chirurgica base
- Familiarità con strumentario chirurgico
- Destrezza manuale (test coordinazione)
- Principi asepsi e antisepsi

STRUTTURA LEZIONE (75 minuti):

1. Introduzione teorica (10 minuti):
   - Importanza nodo sicuro: tenuta, scorrimento, facilità esecuzione
   - Differenza nodo semplice vs chirurgo (doppio primo tempo)
   - Materiali sutura: caratteristiche fili (seta, vicryl, nylon)
   - Applicazioni cliniche: cute, fascia, vasi

2. Dimostrazione slow-motion (15 minuti):
   
   Setup iniziale:
   - Posizionamento mani: dominante dx, supporto sx
   - Lunghezza fili: corto 3-4 cm, lungo 15-20 cm
   - Tensione ottimale durante esecuzione
   
   Nodo Chirurgo Step-by-Step:
   - Primo tempo DOPPIO: 2 avvolgimenti filo lungo attorno corto
   - Trazione coordinata: mano dx verso corpo, sx verso esterno
   - Secondo tempo SINGOLO: 1 avvolgimento senso opposto
   - Trazione finale: chiusura sicura senza over-tightening
   - Controllo visivo: nodo squadrato, non twisted

3. Pratica individuale progressiva (35 minuti):
   
   Fase 1 - Slow Practice (15 min):
   - Ogni studente: 10 nodi lenti con auto-correzione
   - Focus: precisione movimento, posizione mani corretta
   - Docente circola: feedback individuale immediato
   
   Fase 2 - Speed Building (10 min):
   - Obiettivo: riduzione tempo graduale mantenendo qualità
   - Target intermedio: 30 secondi per nodo
   - Conteggio nodi riusciti vs falliti
   
   Fase 3 - Material Variation (10 min):
   - Pratica su fili diversi: seta 2-0, vicryl 3-0, nylon 4-0
   - Adattamento tensione per caratteristiche materiale
   - Riconoscimento "feel" del nodo sicuro per tipo filo

4. Test tenuta e qualità (10 minuti):
   - Dynamometer test: resistenza minima 15N
   - Visual inspection: nodo squadrato vs twisted
   - Slip test: trazione graduale fino a rottura
   - Self-assessment: confidenza esecuzione

5. Applicazione scenario clinico (5 minuti):
   - Simulazione: sutura cute braccio su manichino
   - Context: sutura lacerazioni traumatiche
   - Emphasis: velocità + sicurezza in ambiente pressure

OUTPUT RICHIESTO:

KIT STUDENTE:
- Trainer board con chiodini per fissaggio fili
- Set fili pratica: 10 pezzi seta 2-0 tagliati
- Misuratore tensione semplice (dinamometro basic)
- Card reference con sequenza fotografica step

MATERIALI DOCENTE:
- Video macro slow-motion proiettabile
- Set completo fili per demonstrations
- Checklist valutazione tecnica (12 criteri)
- Timer digitale per speed assessment

VALUTAZIONE IMMEDIATE:
- Performance rubric: tecnica + velocità + tenuta
- Peer assessment: studenti valutano reciprocamente
- Self-reflection: punti di miglioramento identificati
- Target post-lezione: 50 nodi practice nelle 48h successive

SETUP FISICO:
- Tavoli altezza chirurgica standard
- Illuminazione ottimale (500 lux minimo)
- Spazio individuale 60x40 cm per studente
- Smaltimento fili pratica (contenitori dedicati)

CRITERI SUCCESSO LEZIONE:
- Tecnica: esecuzione corretta 8/10 tentativi
- Velocità: <20 secondi per nodo a fine lezione
- Tenuta: >90% nodi superano test 10N
- Comprensione: identificazione errori propri/altrui

FOLLOW-UP OBBLIGATORIO:
- Daily practice log: 20 nodi/giorno x 5 giorni
- Video self-recording: invio 1 nodo perfetto
- Peer tutoring: insegnamento a studente anno precedente
- OR observation: focus su tecnica chirurghi durante tirocinio

FORMATO: Workshop pratico con supervisione 1:6 ratio
ASSESSMENT: Skill station durante esame pratico chirurgia (nodo <15 sec)
PREREQUISITO: Per accesso a suture procedures durante tirocinio
```

---

## LINEE GUIDA GENERALI PER PROMPT EFFICACI

### Elementi Chiave di un Prompt Completo

1. **CONTESTO SPECIFICO**
   - Istituzione e corso
   - Livello studenti e prerequisiti
   - Vincoli temporali e logistici

2. **OBIETTIVI CHIARI**
   - Competenze da sviluppare
   - Risultati di apprendimento misurabili
   - Connessioni con curriculum

3. **STRUTTURA DETTAGLIATA**
   - Organizzazione temporale
   - Sequenza logica dei contenuti
   - Bilanciamento teoria/pratica

4. **SPECIFICAZIONI OUTPUT**
   - Formato richiesto
   - Livello di dettaglio
   - Materiali accessori

5. **CONSIDERAZIONI PEDAGOGICHE**
   - Metodologia didattica
   - Stili di apprendimento
   - Modalità di valutazione

### Progressione della Complessità

**Prompt Semplice** → Richiesta generica, risultato spesso inadeguato

**Prompt Complesso** → Aggiunge contesto e specifiche, migliora qualità

**Prompt Completo** → Approccio sistematico, risultato professionale

### Best Practices

#### Per Domini STEM
- Iniziare sempre con contesto e destinatari
- Essere specifici su formato e lunghezza
- Includere esempi quando possibile
- Prevedere output modulari e riutilizzabili
- Considerare diversi stili di apprendimento
- Integrare valutazione nel design iniziale

#### Per Domini Clinici
**Elementi Specifici Healthcare:**
- Evidence-based guidelines integration
- Patient safety focus prioritario
- Competency-based progression
- Interprofessional collaboration
- Ethical considerations throughout
- Regulatory compliance awareness

**Progressione Clinica:**
- Simulation → Supervised practice → Independent practice
- Competency milestones chiari
- Portfolio development continuous
- Peer assessment integration
- Mentoring structured programs

**Valutazione Clinica:**
- Multi-method assessment approach
- Technical + non-technical skills
- Patient outcome correlation
- Professional development tracking
- Certification preparation integrated

---

## CONCLUSIONI

Questa guida dimostra come la formulazione del prompt influenzi dramatically la qualità dell'output prodotto da un sistema LLM per lo sviluppo di materiale didattico.

La progressione da prompt semplici a completi mostra l'importanza di:
- **Specificità del contesto** e dei destinatari
- **Obiettivi misurabili** e competenze concrete
- **Struttura temporale** realistica
- **Output definiti** e immediatamente utilizzabili
- **Considerazioni pedagogiche** appropriate al dominio

Un approccio metodico nella formulazione dei prompt trasforma un LLM da semplice assistente generico a potente strumento per la progettazione didattica professionale.

---

## Osservazioni

- Con l'eccezione del primo prompt completo (caso analisi matematica) quelli successivi sono troppo demanding dal punto di vista del materiale e non rispettano il principio di modularità.
- Partendo da questi prompt è possibile derivarne diversi, più modulari, che integrati rispondono al prompt complessivamente indicato.
