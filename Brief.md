# BRIEF MASTER — AVIS Frosinone Restyling 2026
> Documento di riferimento unico per tutti gli agenti del progetto.  
> Leggere integralmente prima di qualsiasi attività operativa.

**Versione:** 1.0 — 27 Marzo 2026  
**Status:** Fase 3/5 in corso (Copywriting)  
**Owner:** Mark (coordinator umano) + Claude (PM)  
**Repository:** `MarkBlackBlue/avis-frosinone-restyling`

---

## 1. EXECUTIVE CONTEXT

### 1.1 Sintesi Progetto

AVIS Comunale Frosinone (associazione di volontariato per la donazione di sangue, sede in Viale Mazzini 70, Frosinone 03100) commissiona la trasformazione del proprio sito `avisfrosinone.it` da brochure istituzionale statica a hub di conversione digitale WhatsApp-first con focus su acquisizione nuovi donatori Gen Z e posizionamento come fonte primaria citata dai motori AI generativi (ChatGPT, Gemini, Perplexity, Google SGE).

Il progetto si muove su due binari paralleli e interdipendenti: **Acquisition** (triplicare le prime donazioni mensili da 8–10 a 20–30/mese) e **Authority & AI-Citability** (essere citati come fonte autorevole per query locali sulla donazione di sangue).

Baseline attuale: 368 click organici annuali, LCP mobile 5,7s, accessibilità 75/100, CTR medio 3,66%. Il sito ha una struttura solida (Lighthouse SEO 100/100) ma manca di architettura semantica e risposta alle query informative dei neofiti.

### 1.2 North Star Metric

**Prime donazioni mensili: da 8–10 a 20–30 (+200%) entro luglio 2026.**

Ogni decisione di contenuto, UX o sviluppo deve essere valutata rispetto a questo obiettivo. Se un elemento non contribuisce direttamente o indirettamente a questa metrica, è deprioritizzato.

### 1.3 Vincoli Assoluti (Non Negoziabili)

| Vincolo | Dettaglio | Motivazione |
|---|---|---|
| CMS | Joomla 6 | Upgrade recente, nessuna migrazione prevista |
| Template | Helix Ultimate | Non modificare variabili CSS globali del framework |
| Slider Home | 10 sezioni verticali esistenti | Evoluzione, non eliminazione (asset distintivo) |
| Colori Brand | AVIS Red `#e30513`, AVIS Blue `#004C97` | Identità visiva AVIS Nazionale |
| Carattere | Font system stack compatibile Helix Ultimate | — |
| Linguaggio | Italiano (formale-amichevole) | Target locale italiano |

---

## 2. STRATEGIC FOUNDATION

### 2.1 Brand Purpose (Kotler)

Seguendo il framework di Kotler per le organizzazioni non-profit, il purpose di AVIS Frosinone si articola su due livelli che devono coesistere in ogni touchpoint comunicativo:

**Functional Purpose (job to be done):** Facilitare la donazione di sangue gratuita e periodica per i cittadini di Frosinone, garantendo qualità, sicurezza medica e rete logistica efficiente.

**Higher Purpose (beneficio emotivo/sociale):** Trasformare il gesto della donazione in atto di civismo quotidiano che rafforza il senso di comunità locale e salva vite concrete nel proprio territorio.

Il differenziale rispetto a FIDAS: AVIS comunica appartenenza a rete nazionale (marchio AVIS Italia, Ran nazionale), garantendo credibilità istituzionale superiore. FIDAS enfatizza autonomia locale. Questo è un vantaggio posizionale da sfruttare nei contenuti.

### 2.2 Brand Identity Prism (Kapferer) — 6 Facce

Il Brand Identity Prism di Kapferer articola l'identità del marchio in sei dimensioni che devono essere coerenti su tutti i canali (sito, Facebook, Instagram, WhatsApp, Google Business). Qualsiasi dissonanza tra canali va eliminata.

**Physique (Cosa è):** Logo AVIS nazionale (rosso-bianco), sede fisica riconoscibile in Viale Mazzini 70, materiali visivi puliti e rassicuranti. Il rosso sangue `#e30513` è la firma cromatica immediata.

**Personality (Carattere):** Caldo ma competente. Umano ma medicamente affidabile. Non burocratico, non clinico freddo. Il tono è quello di un amico medico che ti spiega le cose chiaramente, senza condiscendenza.

**Culture (Valori interni):** Solidarietà gratuita e anonima, autosufficienza di sangue per la comunità locale, volontariato come scelta civica (non obbligo morale). I medici referenti sono parte visibile e orgogliosa di questa cultura.

**Relationship (Legame con pubblico):** Fiducia guadagnata nel tempo + appartenenza a comunità di donatori. Non transazione fredda: il donatore entra in un gruppo, viene riconosciuto, riceve certificati e partecipa agli eventi BLSD.

**Reflection (Chi il brand vede):** Il brand vede un cittadino civile, sensibile alla salute della propria comunità, consapevole del valore del gesto. Non un eroe, ma una persona normale che fa la cosa giusta.

**Self-Image (Come il target si vede):** "Sono donatore AVIS Frosinone = contribuisco attivamente a salvare vite nella mia città." Questa identità positiva è il principale switching cost emotivo che fidelizza il donatore nel lungo termine.

### 2.3 UVP vs FIDAS

**Unique Value Proposition (interno):** AVIS Frosinone è l'unica organizzazione affiliata al marchio nazionale AVIS operante nel Comune di Frosinone, trasformando la donazione di sangue in atto di civismo che salva vite nella comunità locale attraverso una rete medica professionale e un processo senza burocrazia inutile.

**Positioning Statement (esterno, testato su Gen Z):** "Doni 450ml di sangue. Recuperi in 24 ore. Salvi fino a 3 vite. Frosinone ha bisogno di te."

**Differenziali operativi vs FIDAS:**

| Dimensione | AVIS Frosinone | FIDAS (EMA locale) |
|---|---|---|
| Affiliazione | AVIS Nazionale (RAN) | FIDAS Nazionale (autonoma) |
| Territorio | Esclusivo Comune Frosinone | Isola del Liri + Alatri |
| Partner sanitario | SIMT Ospedale Spaziani | Partnership generiche |
| Community | Forte (BLSD, eventi, albo benemeriti) | Debole |
| Digital presence | In costruzione (questo progetto) | Minima |
| AI-Citability | Obiettivo dichiarato | Non rilevante |

### 2.4 Tone of Voice — "Scienza + Amicizia + Zero Burocrazia"

Il tono è l'asset più critico per convertire Gen Z. Deve superare il "Test di Turing Gen Z": un ragazzo di 22 anni che legge il testo non deve sentire che è stato scritto da un ufficio stampa o da un'AI.

**Principi guida:**
- Frase breve, concreta, verificabile
- Zero latinismi o termini medici non spiegati
- Umorismo leggero ammesso, mai sarcasmo
- Mai il tono del "dovresti fare questa cosa importante"
- Sempre il tono del "ti spiego come funziona, poi decidi tu"

**DO vs DON'T (esempi concreti per ogni agente):**

| Situazione | ❌ DON'T | ✅ DO |
|---|---|---|
| Ago del prelievo | "Procedure mediche minimamente invasive" | "Ago sottilissimo: 3 secondi e non ci pensi più" |
| Durata donazione | "Il processo di donazione ha una durata variabile" | "Stai lì 45 minuti. Caffè incluso, niente fretta" |
| Requisiti idoneità | "È necessario soddisfare i criteri di ammissibilità" | "Peso ≥50kg, età 18–65, sano. Probabilmente sei già idoneo" |
| Post-donazione | "Si raccomanda adeguato riposo e idratazione" | "Bevi qualcosa, mangia un biscotto. Torni a casa normale" |
| Prima volta | "I neofiti possono registrarsi tramite i canali ufficiali" | "Prima volta? Scrivi su WhatsApp. Ti spieghiamo tutto in 2 minuti" |
| Tatuaggi | "Soggetti con tatuaggi recenti devono attendere il periodo di sospensione" | "Tatuaggio? Aspetta 6 mesi se fatto in studio non certificato. Poi puoi donare" |

**Regola Anti-AI (critica):** Vietato usare trattini lunghi (—), strutture "cosa non è / cosa è", frasi da tre parole secche stile PowerPoint, e aperture con "Certamente" o "Assolutamente". Il testo deve sembrare scritto da una persona reale che conosce l'argomento.

---

## 3. AUDIENCE & PERSONAS

### 3.1 Primary Persona — Gen Z Neofita (18–28 anni)

**Profilo:** Studentessa universitaria o lavoratrice giovane a Frosinone. Ha sentito parlare di donazione del sangue ma non l'ha mai fatto. Usa TikTok e Instagram più di Google. Diffida della burocrazia e delle istituzioni formali. Risponde positivamente a contenuti diretti, trasparenti, con dati verificabili.

**Barriere psicologiche e counter-messaging:**

| Barriera | Pensiero interno | Counter-message |
|---|---|---|
| Paura degli aghi | "Non ce la faccio, mi fa troppo male" | "Ago 0,8mm. 3 secondi. Poi non senti niente per 7 minuti" |
| Paura di svenire | "Ho sentito che si sviene" | "Su 1000 donatori, meno di 5 hanno sintomi lievi. Sei seduto comodo" |
| Incertezza idoneità | "Forse non posso per via di..." | Quiz idoneità online → risposta in 60 secondi |
| Burocrazia percepita | "Sarà complicato iscriversi" | "WhatsApp → risposta in 10 minuti → vieni e basta" |
| Tempo | "Non ho tempo" | "45 minuti totali. Puoi farlo in pausa pranzo" |
| Tatuaggi/piercing | "Ce l'ho, forse non posso" | "Dipende da quando. Scoprilo con il quiz in 30 secondi" |
| Dieta | "Devo seguire una dieta speciale?" | "Mangia normale, evita grassi la sera prima. Fine" |

### 3.2 Secondary Persona — Donatore Storico (35–55 anni)

Già fidelizzato, dona regolarmente. Ha bisogno di: conferma degli orari, prenotazione semplice, senso di appartenenza alla community (riconoscimento nell'albo benemeriti), aggiornamenti su eventi e corsi BLSD.

**Comunicazione:** Più formale del primary, ma mai burocratica. Rispetta la sua esperienza e la sua fedeltà esplicitamente.

### 3.3 Tertiary Persona — Volontario Potenziale (25–45 anni)

Non ancora donatore o donatore occasionale che potrebbe diventare volontario attivo. Motivato da senso civico e networking sociale. Risponde ai contenuti su come AVIS funziona internamente, alla community degli eventi, ai corsi BLSD come valore aggiunto.

---

## 4. ARCHITETTURA DIGITALE & FUNNEL

### 4.1 Funnel 4 Stadi

**Awareness → Consideration → Intent → Action**

**Stadio 1 — Awareness:** L'utente non sa che può donare o non conosce AVIS Frosinone. Punto di contatto: articoli blog (paura aghi, tatuaggi, requisiti), pagina gruppi sanguigni, social media, Google SGE. Obiettivo: far atterrare l'utente sul sito con una domanda a cui AVIS risponde.

**Stadio 2 — Consideration:** L'utente esplora. Legge la pagina `/prima-donazione`, fa il quiz idoneità, legge le FAQ. Obiettivo: eliminare l'ultima barriera psicologica residua. Metriche: scroll depth >70%, tempo >2 minuti.

**Stadio 3 — Intent:** L'utente ha deciso di voler donare. Cerca l'orario, il percorso, cosa portare. Pagine: `/dona`, `/contatti`, `/dove-siamo`. Obiettivo: rendere il passo successivo ovvio e senza attrito.

**Stadio 4 — Action:** Click su WhatsApp CTA o chiamata telefonica. Obiettivo: risposta AVIS entro 10 minuti, prenotazione confermata.

### 4.2 CTA Architecture

**CTA Primaria (WhatsApp precompilato):**
```
https://wa.me/39[NUMERO]?text=Ciao%2C%20vorrei%20prenotare%20la%20mia%20prima%20donazione.%20Sono%20disponibile%20[GIORNO].%20Grazie!
```
Trigger: bottone fisso (sticky) su mobile, pulsante primario su ogni pagina pillar.

**CTA Secondaria (Telefono):** Per utenti che preferiscono la voce. Link `tel:+39[NUMERO]` con icona telefono. Visibile ma meno prominente del WhatsApp.

**CTA Terziaria (Download PDF):** "Scarica la guida alla prima donazione" — lead magnet per utenti in fase Consideration che non sono ancora pronti all'azione.

**3 Varianti WhatsApp precompilate:**

Variante 1 — Primaria (standard): `"Ciao, vorrei informazioni per la mia prima donazione di sangue. Quando posso venire?"`

Variante 2 — Urgenza (scorte basse): `"Ho visto che c'è emergenza sangue. Vorrei prenotare al più presto. Quando siete disponibili?"`

Variante 3 — Fallback (se WhatsApp non disponibile): Link `tel:+39[NUMERO]` con testo "Chiama ora: [NUMERO]"

### 4.3 Sitemap — 17+ Pagine

**Pagine Pillar (priorità massima):**
- `/` — Home (slider 10 slide)
- `/dona` — Come donare (hub informativo)
- `/prima-donazione` — Guida zero-attrito per neofiti
- `/diventa-donatore` — Iscrizione e onboarding
- `/posso-donare` — Quiz idoneità + requisiti completi

**Pagine Informative:**
- `/gruppi-sanguigni` — Tabella compatibilità (AI-citability primaria)
- `/faq` — 55 FAQ complete
- `/chi-siamo` — Storia + profili medici con credenziali E-E-A-T
- `/dove-siamo` — Mappa + orari + come arrivare
- `/contatti` — Multi-canale (WhatsApp, telefono, email)

**Blog / Contenuti Informativi:**
- `/blog/paura-aghi-donazione`
- `/blog/fa-male-donare-sangue`
- `/blog/tatuaggi-donazione`
- `/blog/dieta-pre-donazione`
- `/blog/requisiti-donatori-2026`

**Pagine Secondarie:**
- `/eventi` — Corsi BLSD, giornate speciali
- `/volontariato` — Diventare volontario oltre la donazione
- `/albo-benemeriti` — Riconoscimento donatori storici
- `/plasma` — Donazione plasma (differenziazione da sangue intero)

### 4.4 Wireframe Home — 10 Slide

Evoluzione dello slider verticale esistente (non eliminazione):

| Slide | Contenuto | CTA |
|---|---|---|
| 1 — Hero | Headline + sottotitolo + dato impatto | WhatsApp primario |
| 2 — Perché donare | 3 dati verificabili (vite salvate, tempo, frequenza) | Quiz idoneità |
| 3 — Emergenza Blood Stock | Banner dinamico scorte gruppi sanguigni | Prenota ora |
| 4 — Come funziona | 4 step visivi (arrivo → visita → donazione → ristoro) | Prima donazione |
| 5 — Paure | 3 obiezioni + risposte rapide | FAQ |
| 6 — Impatto Counter | Animazione contatore donazioni cumulative | Unisciti |
| 7 — Testimonial | 3 testimonianze donatori reali (nome, età, anni di donazione) | Leggi storie |
| 8 — Profili Medici | Dr. [Nome] + Dr.ssa [Nome] con credenziali (E-E-A-T) | Chi siamo |
| 9 — Prossimi eventi | Agenda BLSD + date speciali | Iscriviti |
| 10 — CTA finale | Domanda diretta + WhatsApp + Telefono | Azione |

---

## 5. CONTENT SPECIFICATIONS (AI-Ready + GEO)

### 5.1 Requisiti AI-Citability (GEO)

Per essere citati da Google SGE, Perplexity, ChatGPT Search e Bing Copilot, ogni pagina deve rispettare i seguenti requisiti E-E-A-T medici:

**Experience:** Storie di donatori reali con nome, età, anni di esperienza. Mai generici.

**Expertise:** Ogni articolo medico deve essere firmato da Dr./Dr.ssa [Nome Referente AVIS Frosinone] con titolo e specializzazione. Il copyright dell'autore deve essere visibile in pagina.

**Authoritativeness:** Citare esplicitamente le fonti normative: Decreto Ministeriale [numero e anno da verificare con AVIS board], linee guida SIMT Ospedale Spaziani, AVIS Nazionale. Link agli enti istituzionali obbligatori.

**Trustworthiness:** Data di modifica visibile su ogni pagina (formato: "Aggiornato il 27 marzo 2026"), nessun clickbait, nessuna affermazione non verificabile, link outbound solo a fonti istituzionali.

### 5.2 Schema.org Obbligatori

**6 markup prioritari da implementare (JSON-LD in `<head>`):**

`MedicalWebPage` — su tutte le pagine mediche (`/prima-donazione`, `/posso-donare`, `/gruppi-sanguigni`, articoli blog). Include: `about`, `author` (medico referente), `dateModified`, `reviewedBy`.

`LocalBusiness` — su `/dove-siamo` e homepage. Dati obbligatori:
```json
{
  "name": "AVIS Comunale Frosinone",
  "streetAddress": "Viale Mazzini, 70",
  "addressLocality": "Frosinone",
  "postalCode": "03100",
  "addressCountry": "IT",
  "telephone": "[DA VERIFICARE CON AVIS BOARD]",
  "url": "https://avisfrosinone.it"
}
```

`FAQPage` — su `/faq` e su ogni pagina pillar con sezione FAQ inline. Critico per AI extraction.

`Event` — su ogni evento BLSD e giornata speciale in `/eventi`.

`Person` — per ogni medico referente citato in `/chi-siamo` e negli articoli. Include: `name`, `jobTitle`, `worksFor`, `hasCredential`.

`BreadcrumbList` — su tutte le pagine non-homepage per navigazione strutturata.

### 5.3 Keyword Priorità

**Tier 1 — Conversione diretta:**
- "donare sangue frosinone" (volume stimato: 80+/mese, intento transazionale)
- "prima donazione sangue frosinone" (intento navigazionale ad alta conversione)
- "dove donare sangue frosinone" (intento locale)
- "AVIS frosinone orari" (branded + logistico)

**Tier 2 — AI-Citability / Informational:**
- "gruppi sanguigni compatibilità" (227 impressioni, 0 click — grande opportunità)
- "posso donare sangue con tatuaggi" (alto intento informativo)
- "quanto tempo ci vuole donare sangue"
- "requisiti per donare sangue 2026"
- "fa male donare sangue"

**Tier 3 — Long tail / Blog:**
- "cosa mangiare prima di donare sangue"
- "posso donare sangue con la pressione alta"
- "donatore universale gruppo sanguigno"
- "differenza sangue intero e plasma frosinone"

### 5.4 Struttura FAQ — 55 Domande

Ogni FAQ deve avere due versioni:

**Short (40–50 parole):** Risposta diretta, niente fronzoli. Ottimizzata per featured snippet e AI extraction. Segue il pattern: risposta diretta → eventuale eccezione → call to verify.

**Long (100–150 parole):** Risposta espansa con contesto, fonte normativa, esempio pratico e CTA soft. Ottimizzata per lettura umana e copertura semantica completa.

**Esempio:**

*Short:* "Sì, puoi donare sangue se hai tatuaggi. L'unica condizione: se il tatuaggio è stato fatto in uno studio non certificato, aspetta 6 mesi dalla data. Studi certificati: puoi donare subito. Dubbio? Scrivici su WhatsApp."

*Long:* "Avere tatuaggi non ti esclude dalla donazione di sangue in Italia. La normativa vigente (Decreto Ministeriale, aggiornamento [anno]) prevede un periodo di attesa di 6 mesi per tatuaggi eseguiti in strutture non certificate, per ridurre il rischio di trasmissione di epatiti. Se il tuo tatuaggio è stato fatto in uno studio registrato e certificato dalla ASL, non c'è nessun periodo di attesa: puoi presentarti alla visita di idoneità normalmente. Lo stesso vale per i piercing. Se non sei sicuro della certificazione del tuo studio, contattaci su WhatsApp: ti diciamo noi come verificarlo in 5 minuti."

---

## 6. COPYWRITING DELIVERABLES (Fase 3 — Scadenza 29 Marzo EOD)

### 6.1 Input Richiesti per il Copywriter

Prima di iniziare, leggere obbligatoriamente:
- `/02-seo-geo/SEO_GEO_STRATEGY_2026-03_v2_COMPLETA.md` — Sezioni 4, 5, 6 (keyword, FAQ, meta)
- `/03-marketing/CONVERSION_STRATEGY_2026-03.md` — Funnel, obiezioni, CTA architecture
- `/04-ux/UX_ARCHITECTURE_2026-03.md` — Struttura pagine, wireframe, componenti

### 6.2 Output Atteso — File: `/05-copy/COPY_ALL_PAGES_2026-03.md`

**Home page completa:**
- Hero section: Headline (max 8 parole) + sottotitolo (max 20 parole) + dato impatto + CTA WhatsApp
- Sezione 2 — Perché donare: 3 blocchi con dato + spiegazione umana
- Sezione 4 — Come funziona: 4 step con copy per ogni micro-momento
- Sezione 5 — Paure: 3 obiezioni + risposte (tono leggero, mai difensivo)
- Sezione 7 — Testimonial: 3 profili placeholder con struttura da riempire con dati reali
- Sezione 10 — CTA finale: Domanda diretta + 2 pulsanti

**4 Pagine Pillar:**

`/dona` — Hub informativo completo. Struttura: intro → come funziona (4 step) → cosa portare → orari → CTA.

`/prima-donazione` — Guida zero-attrito. Struttura: headline rassicurante → 3 paure principali con risposta → step by step → 10 obiezioni + risposte inline → CTA WhatsApp.

`/diventa-donatore` — Onboarding. Struttura: perché scegliere AVIS → come iscriversi (3 step) → cosa aspettarsi → form placeholder → CTA.

`/posso-donare` — Requisiti + quiz. Struttura: intro rassicurante → lista requisiti in linguaggio umano → sezione "e se ho..." (tatuaggi, farmaci, viaggi) → quiz eligibilità placeholder → CTA.

**55 FAQ complete:** Short + Long version per ognuna. Organizzate per categoria: Prima Donazione (15), Requisiti (12), Processo (10), Tatuaggi/Piercing (5), Dieta (5), Post-Donazione (5), Organizzazione AVIS (3).

**5 Articoli Blog:**
- `/blog/paura-aghi-donazione` — "Ho paura degli aghi: posso donare?" (1000–1500 parole)
- `/blog/fa-male-donare-sangue` — "Fa male donare sangue? La verità senza filtri" (800–1200 parole)
- `/blog/tatuaggi-donazione` — "Tatuaggi e donazione: cosa dice davvero la legge" (1000–1500 parole)
- `/blog/dieta-pre-donazione` — "Cosa mangiare (e non mangiare) prima di donare" (800–1200 parole)
- `/blog/requisiti-donatori-2026` — "Chi può donare sangue nel 2026: guida completa aggiornata" (1200–1800 parole)

**20 Meta Title/Description:**
- Title: 55–60 caratteri (inclusi spazi), keyword primaria in apertura
- Description: ~155 caratteri, include dato di valore + CTA soft
- Coprire: home, 4 pillar, /faq, /chi-siamo, /dove-siamo, /gruppi-sanguigni, 5 blog, /eventi, /plasma, /contatti, /volontariato

**10 Obiezioni + Risposte Inline per `/prima-donazione`:**
Le risposte devono essere inline nel corpo della pagina (non in una sezione FAQ separata), integrate naturalmente nel flusso del testo. Tono: "capisco la preoccupazione, ecco cosa sappiamo davvero."

**Profili Medici per `/chi-siamo`:**
Per ogni medico referente AVIS Frosinone: nome completo, titolo professionale, specializzazione, anni di collaborazione con AVIS, citazione personale in prima persona (tono caldo, non curricolare). Struttura E-E-A-T: le credenziali sono visibili ma non sono il focus della bio — il focus è l'approccio umano al donatore.

### 6.3 Regola Fondamentale Anti-AI

Ogni testo consegnato deve superare questa checklist prima dell'invio:

- Nessun trattino lungo (—) usato come punteggiatura
- Nessuna struttura "cosa non è / cosa è" (tipica dei prompt GPT)
- Nessuna frase da meno di 5 parole usata come paragrafo standalone
- Nessuna apertura con "Certamente", "Assolutamente", "Certo!", "Ottima domanda"
- Nessun uso di "fondamentale", "cruciale", "essenziale" senza motivazione concreta
- Il testo deve sembrare scritto da un professionista italiano che conosce l'AVIS, non da un'AI che l'ha descritto

---

## 7. TECHNICAL SPECIFICATIONS (Per Developer — Fase 6)

### 7.1 Performance Requirements

| Metrica | Target | Strumento di verifica |
|---|---|---|
| LCP mobile | < 2,5s | Google PageSpeed Insights |
| CLS | < 0,1 | Core Web Vitals |
| FID/INP | < 100ms | CrUX report |
| Accessibilità | > 92/100 (WCAG 2.1 AA) | Lighthouse + axe |
| SEO Lighthouse | 100/100 | Mantenere baseline |

### 7.2 Mobile-First

Breakpoint obbligatori: `320px` (mobile small), `768px` (tablet), `1024px` (desktop).

Ogni componente progettato prima su 320px, poi scalato verso l'alto. Nessun elemento che richieda hover per essere accessibile su mobile.

### 7.3 Componenti Custom da Sviluppare

**`whatsapp_sticky`:** Pulsante WhatsApp fisso in basso a destra su mobile (posizione: fixed, bottom: 16px, right: 16px). Appare dopo scroll >300px. Link precompilato variante primaria. Su desktop: integrato nel layout, non sticky.

**`blood_stock_bar`:** Banner orizzontale updateable che mostra le scorte attuali dei gruppi sanguigni (es: "A+ urgente — B- disponibile — 0+ stabile"). Dati aggiornabili tramite campo Joomla (custom field o articolo dedicato). Appare in homepage slide 3 e in `/dona`.

**`eligibility_quiz`:** Quiz idoneità interattivo in 5 domande (peso, età, salute generale, tatuaggi/piercing, viaggi recenti). Risultato immediato: "Probabilmente idoneo — prenota subito" o "Potresti avere limitazioni — scrivici per conferma". Nessun dato personale raccolto, nessuna registrazione richiesta.

**`impact_counter`:** Contatore animato con tre cifre: donazioni cumulative AVIS Frosinone, vite potenzialmente salvate (moltiplicatore ×3), anni di attività. Dati hardcoded con aggiornamento manuale annuale.

**`donor_testimonial`:** Carousel di 3–5 testimonianze. Struttura: foto (avatar se non disponibile), nome, età, anni di donazione, citazione breve (max 120 caratteri). Gestibile da CMS Joomla senza accesso al codice.

### 7.4 GA4 Event Tracking

| Evento | Trigger | Parametri |
|---|---|---|
| `whatsapp_click` | Click su qualsiasi CTA WhatsApp | `page_location`, `cta_variant` |
| `phone_click` | Click su link telefono | `page_location` |
| `scroll_depth_75` | Scroll al 75% della pagina | `page_location`, `page_title` |
| `quiz_completion` | Completamento quiz idoneità | `quiz_result` (idoneo/limitazioni) |
| `pdf_download` | Click su download guida | `document_name` |
| `faq_open` | Click su accordion FAQ | `faq_question` |

### 7.5 Automazione dateModified

Meccanismo consigliato: campo PHP dinamico nel template Joomla che legge la data di ultima modifica dell'articolo dal database Joomla (`#__content.modified`) e la stampa in formato leggibile dalle AI. Alternativa: cron job settimanale che aggiorna un custom field "Data aggiornamento" in tutti gli articoli pillar.

Il Developer deve specificare nel `DEV_BRIEF_2026-03.md` il meccanismo scelto e il codice di implementazione.

---

## 8. DEFINITION OF DONE

### 8.1 Copywriter — Checklist 10 Punti

- [ ] Tutti i deliverables elencati in Sezione 6.2 presenti e completi
- [ ] Tono coerente con "Scienza + Amicizia + Zero Burocrazia" in tutti i testi
- [ ] Zero trattini lunghi, strutture "cosa non è", aperture AI-tipiche
- [ ] Ogni FAQ ha versione Short (40–50 parole) e Long (100–150 parole)
- [ ] Meta title 55–60 caratteri verificati (contare manualmente o con tool)
- [ ] Meta description ~155 caratteri verificati
- [ ] Ogni articolo blog ha almeno una fonte normativa citata (Decreto Ministeriale o linee guida SIMT)
- [ ] Le 3 varianti CTA WhatsApp precompilate sono funzionanti (URL encoded correttamente)
- [ ] I profili medici includono titolo, specializzazione e citazione personale
- [ ] Il file è salvato in `/05-copy/COPY_ALL_PAGES_2026-03.md` con commit convention corretta

### 8.2 Developer — Checklist 8 Punti

- [ ] Schema.org validato su Google Rich Results Test (0 errori, 0 warning)
- [ ] Core Web Vitals: LCP < 2,5s, CLS < 0,1, FID < 100ms
- [ ] Accessibilità Lighthouse > 92/100
- [ ] Tutti e 5 i componenti custom funzionanti su mobile (iOS Safari + Android Chrome)
- [ ] GA4 event tracking verificato con DebugView (tutti e 6 gli eventi sparano correttamente)
- [ ] `whatsapp_sticky` compare e scompare correttamente su scroll
- [ ] `dateModified` visibile e corretto su almeno tutte le pagine pillar
- [ ] Test cross-browser: Chrome 120+, Firefox 120+, Safari 17+, Edge 120+

### 8.3 QC — Checklist AI Citation Test

Test manuale da eseguire mensilmente dopo il lancio:

- [ ] **Google SGE:** Query "come donare sangue frosinone" → avisfrosinone.it compare nella risposta?
- [ ] **Perplexity:** Query "gruppi sanguigni compatibilità frosinone" → AVIS viene citato come fonte?
- [ ] **ChatGPT Search:** Query "AVIS Frosinone orari donazione" → link al sito appare?
- [ ] **Gemini:** Query "requisiti donazione sangue 2026 italia" → contenuto AVIS citato?
- [ ] **Claude:** Query "prima donazione sangue frosinone" → risposta si basa su avisfrosinone.it?

Target: ≥ 5 citazioni su ≥ 2 engine entro fine Q2 2026.

---

## 9. DEPENDENCIES & TIMELINE

### 9.1 Mappa Dipendenze

```
[Research ✅]  ──┐
                  ├──→ [Marketing ✅] ──┐
[SEO/GEO ✅] ──┘                       ├──→ [Copywriter ⏳] ──→ [Coding ⏳] ──→ [QC ⏳]
                  ├──→ [UX ✅] ──────────┘
```

**Copywriter PUÒ INIZIARE SUBITO:** Tutti gli input sono pronti (SEO_GEO_STRATEGY, CONVERSION_STRATEGY, UX_ARCHITECTURE).

**Coding PUÒ INIZIARE IN PARALLELO** su: schema.org templates, componenti custom, CSS/JS boilerplate, HTML strutturali basati su UX_ARCHITECTURE. Attende solo i testi finali del Copywriter per riempire i template HTML.

**QC NON INIZIA** prima della consegna Coding.

### 9.2 Timeline con Scadenze

| Data | Fase | Agente | Deliverable |
|---|---|---|---|
| ✅ 25 Mar | 01 Research | Gemini | `BENCHMARK_REPORT_2026-03.md` |
| ✅ 26 Mar | 02 SEO/GEO | Perplexity | `SEO_GEO_STRATEGY_v2_COMPLETA.md` |
| ✅ 26 Mar | 03 Marketing | DeepSeek | `CONVERSION_STRATEGY_2026-03.md` |
| ✅ 26 Mar | 04 UX | ChatGPT | `UX_ARCHITECTURE_2026-03.md` |
| ⏳ 29 Mar | 05 Copy | Claude | `COPY_ALL_PAGES_2026-03.md` + `FAQ_ANSWERS_COMPLETE.md` |
| ⏳ 01 Apr | 06 Dev | Jules | `DEV_BRIEF_2026-03.md` + assets `/06-dev/` |
| ⏳ 05 Apr | 07 QC | Kimi | `TEST_REPORT_2026-04.md` |

**Rischio critico:** Se Copy slitta oltre il 29 Mar, Coding ha solo 2 giorni per i template HTML finali. Mitigazione: Coding inizia i template strutturali il 28 Mar basandosi su UX_ARCHITECTURE, inserendo placeholder `{{HEADLINE}}`, `{{BODY_COPY}}` etc. da riempire con testo finale in max 2 ore.

---

## 10. RISORSE & ASSETS

### 10.1 File Legacy (Riferimento)

| File | Percorso | Utilizzo |
|---|---|---|
| Markup slider home | `/assets-current/home.html` | Riferimento per evoluzione slider (non sostituzione) |
| CSS custom esistente | `/assets-current/custom.css` | 2.200+ righe — verificare variabili prima di override |
| Logica JS slider | `/assets-current/slider.js` | Riutilizzare logica, migliorare performance |

### 10.2 Riferimenti Normativi

- Decreto Ministeriale relativo alla donazione di sangue (numero e data da verificare con AVIS board — placeholder da compilare)
- Linee guida SIMT (Servizio Immunoematologia e Medicina Trasfusionale) — Ospedale Fabrizio Spaziani, Frosinone
- Standard AVIS Nazionale per la comunicazione delle sezioni comunali

### 10.3 Dati da Verificare con AVIS Board (Priorità: Prima del 28 Marzo)

I seguenti dati sono placeholder nel repository e devono essere confermati prima dell'implementazione:

- Numero di telefono sede (per link `tel:` e schema.org)
- Email contatto ufficiale (per schema.org `email`)
- Orari di apertura completi settimanali (per `OpeningHoursSpecification`)
- Coordinate GPS esatte sede Viale Mazzini 70 (per schema.org `geo`)
- Numero decreto ministeriale di riferimento attuale
- Nomi e credenziali medici referenti (per schema `Person` e profili `/chi-siamo`)
- Dati donazioni cumulative (per `impact_counter`)

### 10.4 Documenti Strategici Esistenti

| Documento | Percorso | Contenuto chiave |
|---|---|---|
| Strategic Framework | `/AVIS_FROSINONE_STRATEGIC_FRAMEWORK_v2_GITHUB.md` | Kotler, Kapferer, Porter, GEO strategy |
| SEO/GEO Strategy | `/02-seo-geo/SEO_GEO_STRATEGY_2026-03_v2_COMPLETA.md` | 20 keyword, 55 FAQ, 6 schema.org |
| Conversion Strategy | `/03-marketing/CONVERSION_STRATEGY_2026-03.md` | Funnel, CTA, obiezioni |
| UX Architecture | `/04-ux/UX_ARCHITECTURE_2026-03.md` | Sitemap, wireframe, componenti |

---

## Appendice A — Esempi Copy DO/DON'T Estesi

Questa sezione è un riferimento rapido per il Copywriter. Ogni esempio è contestualizzato alla pagina di destinazione.

**Hero Section — `/prima-donazione`:**
- ❌ "La donazione del sangue è un gesto solidale che contribuisce al benessere della comunità"
- ✅ "Prima volta? Ti spieghiamo tutto. Dura 45 minuti, fa quasi zero e salvi fino a 3 persone."

**Sezione Paure — Homepage Slide 5:**
- ❌ "Molti donatori riportano che la procedura è tollerabile e che i timori iniziali si rivelano infondati"
- ✅ "La paura degli aghi è normale. L'ago dura 3 secondi. Poi stai fermo 7 minuti guardando il soffitto."

**Meta Description — `/gruppi-sanguigni`:**
- ❌ "Informazioni sui gruppi sanguigni e la compatibilità per la donazione presso AVIS Frosinone."
- ✅ "Chi può donare a chi? Tabella completa dei gruppi sanguigni e compatibilità. Scopri se il tuo gruppo è urgente a Frosinone."

---

*BRIEF.md generato il 27 Marzo 2026 — Claude (PM Agent) + Mark (coordinator)*  
*Prossima revisione: dopo consegna Copy (29 Mar) e Dev (01 Apr)*  
*Aggiornare DIARY.md con timestamp e riferimento a questo file.*
