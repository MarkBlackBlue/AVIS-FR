AVIS Frosinone — Restyling Completo 2026
Repository: MarkBlackBlue/avis-frosinone-restyling
Status: Fase 3/5 in corso (Copywriting)
Ultimo aggiornamento: 27 Marzo 2026, 00:50 CET
________________________________________
1. Scopo del Progetto
Trasformazione di avisfrosinone.it da sito brochure statico (informativo istituzionale) a hub di conversione digitale focalizzato su due obiettivi paralleli:
•	Acquisition: Triplicare le prime donazioni mensili (da 8-10 a 20-30/mese) targettizzando Gen Z (18-35 anni) attraverso un funnel WhatsApp-first che elimina attriti burocratici
•	Authority & AI-Citability: Posizionare AVIS Frosinone come fonte primaria citata dalle AI generative (ChatGPT, Gemini, Perplexity, Claude) per query relative alla donazione di sangue nella provincia di Frosinone
Il progetto adotta un approccio GEO-first (Generative Engine Optimization) combinato a SEO locale aggressiva, ridisegnando l'architettura informativa e il tone of voice per abbattere le barriere psicologiche specifiche dei neofiti (paura degli aghi, incertezza sull'idoneità, percezione della burocrazia).
2. Struttura del Repo
avis-frosinone-restyling 
•	README.md           	# Questo file — Overview progetto    
•	BRIEF.md              	# Brief master — Contesto completo e Definition of Done         
•	STATUS.md        	 # Dashboard esecutiva aggiornata (stato fasi)  

avis-frosinone-restyling/01-research/  
•	BENCHMARK_REPORT_2026-03.md    # Analisi 15+ siti AVIS + competitor
•	RESEARCH_METHODOLOGY.md        # Approccio euristico e fonti

avis-frosinone-restyling/02-seo-geo/          
•	SEO_GEO_STRATEGY_2026-03_v2_COMPLETA.md  	# 20 keyword, 55 FAQ, 6 schema.org, AI-opt
•	KEYWORD_RESEARCH.xlsx        				# Volume e difficoltà
•	SCHEMA_MARKUP_TEMPLATES.json   			# JSON-LD pronti per implementazione

avis-frosinone-restyling/03-marketing/                      
•	CONVERSION_STRATEGY_2026-03.md 		# Funnel 4 stadi, CTA architecture, UVP
•	MESSAGING_VARIANTS.md          			# Test A/B headline e copy
•	EDITORIAL_CALENDAR_Q1.xlsx     		# Pianificazione contenuti
avis-frosinone-restyling/03-marketing/      
•	UX_ARCHITECTURE_2026-03.md     		# Sitemap, wireframe, componenti UI         
•	WIREFRAMES_HOME.md            		# 10 slide — specifiche tecniche      
•	WIREFRAMES_FIRST_TIME.md       		# Pagina "Prima Donazione" zero-attrito 
•	COMPONENTS_SPEC.md             		# 5 componenti custom (quiz, sticky CTA, etc.)

avis-frosinone-restyling/05-copy/    
                       
•	COPY_ALL_PAGES_2026-03.md      		# [DA CREARE] Testi pillar + blog + meta
•	FAQ_ANSWERS_COMPLETE.md        	# [DA CREARE] 55 risposte short/long
•	MICROCOPY_ERRORS.md            		# [DA CREARE] Messaggi errore/successo	
avis-frosinone-restyling/06-dev/                            
•	DEV_BRIEF_2026-03.md           	# [DA CREARE] Schema.org + GA4 + componenti
•	HTML_TEMPLATES/                	# [DA CREARE] Template pagine pillar
•	CSS_COMPONENTS.css             	# [DA CREARE] Override Helix Ultimate
•	JS_INTERACTIONS.js             		# [DA CREARE] Accordion, quiz, sticky

avis-frosinone-restyling/ assets-current/                    # Codice legacy di riferimento
•	home.html                      	# Markup attuale slider 10 sezioni
•	custom.css                    	# CSS custom esistente (2.200+ righe)
•	slider.js                     	# Logica JS slider verticale

3. Obiettivo Finale
KPI Primari 
Metrica	Baseline	Target	Strumento
Prime donazioni/mese                	8-10       	20-30 (+200%)	CRM/WhatsApp       
Click WhatsApp CTA                  	30-50/mese	150/mese      	GA4 Event Tracking
Tasso conversione lead→donazione    	~15%       	40%           	CRM
Posizione "donare sangue frosinone"	#12        	#2-3          	Search Console     

KPI Secondari (AI-Citability)
•	ChatGPT/Gemini citation: Almeno 3-5 citazioni mensili entro 8 settimane
•	Featured Snippets: 5+ rich results su query informational (paura aghi, requisiti, tatuaggi)
•	Domain Authority: Da ~15 a 22-25 (Moz)
Trasformazione Qualitativa
•	Da: Sito istituzionale statico, tono burocratico, form complessi
•	A: Hub conversazionale, tono "scienza + amicizia", conversione tramite WhatsApp con risposta <10 min
4. Team Agenti

Agente	Modello AI	Ruolo	Deliverable	Cartella
Project Manager	Claude	Coordinamento, integrazione, review                  	`README.md`, `BRIEF.md`, `STATUS.md`      	root
Researcher	Gemini  	Benchmark competitivo, best practices internazionali	‘BENCHMARK_REPORT_2026-03.md`             	01-research
SEO/AI Strategist	Perplexity	Keyword research, GEO strategy, schema.org           	BENCHMARK_REPORT_2026-03.md`             	01-research
SEO/AI Strategist	Perplexity	Keyword research, GEO strategy, schema.org           	SEO_GEO_STRATEGY_2026-03_v2_COMPLETA.md	02-seo-geo
Marketing Strategist	DeepSeek	Funnel conversione, messaging, CTA architecture      	CONVERSION_STRATEGY_2026-03.md	03-marketing
UX Architect	ChatGPT	Information architecture, wireframe, componenti      	UX_ARCHITECTURE_2026-03.md	04-ux
Copywriter	Claude	Copy SEO/GEO ottimizzato, 55 FAQ, meta tags          	COPY_ALL_PAGES_2026-03.md	05-copy
Coding Agent	Jules	Sviluppo HTML/CSS/JS, implementazione schema         	DEV_BRIEF_2026-03.md` + assets           	06-dev
QC Team	Kimi	Testing funzionale, SEO audit, AI citation test      	TEST_REPORT_2026-04.md	root

5. Come Leggere Questo Repository
Per il Project Manager
•	Leggi sempre prima BRIEF.md (contesto e vincoli non negoziabili)
•	Consulta STATUS.md ogni giorno per lo stato avanzamento
•	Verifica le dipendenze tra agenti prima di approvare passaggi di fase
Per gli Agenti Operativi
•	Leggi BRIEF.md — Contiene il contesto AVIS, i vincoli tecnici (Joomla 6 + Helix Ultimate), il tone of voice e la Definition of Done
•	Accedi alla tua cartella (0X-ruolo/) — Crea i file indicati nella checklist della tua fase
•	Usa gli input delle fasi precedenti:
o	Copywriter: usa /04-ux/UX_ARCHITECTURE_2026-03.md (struttura) + /02-seo-geo/SEO_GEO_STRATEGY_2026-03_v2_COMPLETA.md (Sezione 4-5-6 per FAQ e meta)
o	Coding: usa /04-ux/ (wireframe) + /02-seo-geo/ (Sezione 3 per schema.org)
•	Rispetta le convenzioni (vedi Sezione 7) per commit e nomenclatura file
Per gli Stakeholder AVIS
•	Leggi BRIEF.md (Sezioni 1-2-3) per l'overview strategica
•	Consulta CONVERSION_STRATEGY_2026-03.md per capire il funnel di conversione
•	Monitora STATUS.md per le scadenze e il progresso
6. Workflow Agenti — Come Contribuire
Setup Locale
git clone https://github.com/MarkBlackBlue/avis-frosinone-restyling.git
cd avis-frosinone-restyling
git checkout -b 05-copy-27mar  # Esempio per Copywriter
Ciclo di Lavoro
1.	Input: Leggi i file delle fasi precedenti (dipendenze indicate in BRIEF.md Sezione 10.2)
2.	Lavorazione: Crea/modifica file nella tua cartella assegnata
3.	Validazione: Verifica di aver soddisfatto la Definition of Done (BRIEF.md Sezione 12)
4.	Commit: Segui la Commit Convention (Sezione 7)
5.	Push: git push origin nome-branch
6.	Aggiornamento Stato: Modifica STATUS.md con il nuovo stato (✅ COMPLETATO)
Dipendenze e Flusso
[Researcher] ──┐
               ├──→ [Marketing] ──┐
[SEO/AI] ──────┘                  ├──→ [Copywriter] ──→ [Coding] ──→ [QC]
               ├──→ [UX] ─────────┘
Regole critiche:
•	Copywriter può iniziare in parallelo a UX (input SEO già pronti)
•	Coding inizia schema.org in parallelo a Copy (input UX pronti), attende Copy per i template HTML finali
•	QC non inizia prima che Coding abbia consegnato
7. Commit Convention
Pattern obbligatorio per ogni commit:
[FASE]-[AGENTE]: [File] ([Descrizione breve]) — [Data]
Esempi validi:
•	✅ 01-research: BENCHMARK_REPORT_2026-03.md (Analisi 15 siti AVIS + international) — 25 mar 2026
•	✅ 02-seo-geo: SEO_GEO_STRATEGY_v2_COMPLETA.md (20 keyword, 55 FAQ, 6 schema.org) — 26 mar 2026
•	⏳ 05-copy: COPY_ALL_PAGES_2026-03.md (Home, pillar pages, 55 FAQ, meta tags) — 29 mar 2026
•	⏳ 06-dev: DEV_BRIEF_2026-03.md (Schema.org, GA4, componenti custom) — 01 apr 2026

Note:
•	Usa ✅ per commit completati, ⏳ per work-in-progress
•	Includi sempre la data in formato italiano
•	Descrivi il contenuto, non solo il nome file
________________________________________
8. Documenti Essenziali
1. BRIEF.md (Master)
Leggere assolutamente prima di qualsiasi attività.
Contiene:
•	Contesto cliente e situazione attuale (traffico, conversioni, tecnologia)
•	Target audience dettagliato (Gen Z, barriere psicologiche)
•	Vincoli tecnici non negoziabili (Joomla 6, Helix Ultimate, slider esistente)
•	Architettura home (10 slide verticali)
•	Tono di voce ("Scienza + Amicizia + Zero Burocrazia")
•	KPI di successo e metriche
•	Definition of Done per ogni fase
2. SEO_GEO_STRATEGY_2026-03_v2_COMPLETA.md
Input critico per Copywriter e Coding.
Contiene:
•	Sezione 1: 20 keyword ricercate con volume e difficoltà
•	Sezione 3: 6 template schema.org (JSON-LD) pronti per copia-incolla
•	Sezione 4: 55 FAQ strutturate (short 40-50 parole + long 100-150)
•	Sezione 5: 20 meta title/description ottimizzati
•	Sezione 6: AI-specific optimization (ChatGPT, Gemini, Perplexity, Claude)
•	Sezione 10: KPI tracking e dashboard
3. UX_ARCHITECTURE_2026-03.md
Input per Copywriter (struttura) e Coding (wireframe).
Contiene:
•	Sitemap completa (17+ pagine)
•	Wireframe home slider (8 slide dettagliate con contenuti)
•	Wireframe pagina "Prima Donazione" (zero-attrito)
•	Specifiche 5 componenti UI custom (whatsapp_sticky, blood_stock_bar, eligibility_quiz, impact_counter, donor_testimonial)
•	Mobile-first specifications (breakpoint 320/768/1024)
4. CONVERSION_STRATEGY_2026-03.md
Input per Copywriter (tone e messaging).
Contiene:
•	UVP (Unique Value Proposition) positioning
•	4-stage funnel (Awareness → Consideration → Intent → Action)
•	CTA architecture (primaria WhatsApp, secondaria download, urgenza)
•	10 obiezioni mappate con risposte specifiche
•	Social proof strategy e urgency triggers
________________________________________
9. Checklist Agenti
Copywriter (Claude) — Scadenza: 29 Marzo EOD
Input richiesti:
•	CONVERSION_STRATEGY_2026-03.md (tone, messaging, obiezioni)
•	UX_ARCHITECTURE_2026-03.md (struttura pagine)
•	SEO_GEO_STRATEGY_2026-03_v2_COMPLETA.md (Sezione 4, 5, 6)
Output atteso in /05-copy/COPY_ALL_PAGES_2026-03.md:
•	[ ] Home page completa (hero + 5 sezioni)
•	[ ] 4 pagine pillar: /dona, /prima-donazione, /diventa-donatore, /posso-donare
•	[ ] 55 FAQ complete (short + long version)
•	[ ] 5 articoli blog (paura-aghi, fa-male, tatuaggi, dieta, requisiti-2026)
•	[ ] 20 meta title/description (pronti per implementazione)
•	[ ] 10 obiezioni + risposte inline in /prima-donazione
•	[ ] 3 CTA WhatsApp precompilati (primaria, urgenza, fallback telefono)
•	[ ] Profili medici /chi-siamo con bio e credenziali
Criticità specifiche:
•	Umanizzare 100%: eliminare trattini lunghi, strutture "cosa non è", frasi troppo corte da AI
•	Mantenere tono Gen Z: "Aghi sottilissimi: 3 secondi" non "Procedure mediche minimamente invasive"

Coding Agent (Jules) — Scadenza: 01 Aprile EOD
Input richiesti:
•	UX_ARCHITECTURE_2026-03.md (wireframe, componenti, mobile spec)
•	SEO_GEO_STRATEGY_2026-03_v2_COMPLETA.md (Sezione 3 schema.org)
•	COPY_ALL_PAGES_2026-03.md (una volta consegnato)
Output atteso:
•	[ ] /06-dev/DEV_BRIEF_2026-03.md con:
o	Implementazione 6 schema.org (MedicalWebPage, LocalBusiness, FAQPage, BreadcrumbList, NewsArticle, Person)
o	GA4 Event Tracking (WhatsApp click, phone click, scroll depth)
o	5 componenti custom (whatsapp_sticky, blood_stock_bar, impact_counter, eligibility_quiz, donor_testimonial)
o	HTML templates per home + 4 pagine pillar
o	CSS custom (rispettare variabili Helix Ultimate)
o	JS per accordion FAQ, quiz idoneità, sticky CTA
o	Automation dateModified settimanale
•	[ ] /06-dev/HTML_TEMPLATES/ (home.html, prima-donazione.html, posso-donare.html, faq.html)
•	[ ] /06-dev/CSS_COMPONENTS.css
•	[ ] /06-dev/JS_INTERACTIONS.js
Vincoli tecnici critici:
•	Stack: Joomla 6 + Helix Ultimate (non modificare variabili CSS globali)
•	Slider home: evolvere, non eliminare (asset distintivo)
•	Colori: AVIS Red #e30513, AVIS Blue #004C97
•	Mobile-first: breakpoint 320/768/1024
•	Performance: LCP <2.5s, CLS <0.1, lazy loading sistematico
________________________________________
10. QC Team — Scadenza: 05 Aprile
Input:
•	COPY_ALL_PAGES_2026-03.md (da Copywriter)
•	DEV_BRIEF_2026-03.md + assets (da Coding)
Output atteso in /TEST_REPORT_2026-04.md:
1. Functional Testing
•	[ ] Navigazione end-to-end (home → dona → prima-donazione → contatti)
•	[ ] CTA WhatsApp funzionante con testo precompilato
•	[ ] FAQ accordion (open/close smooth)
•	[ ] Mobile responsive (iOS Safari + Android Chrome)
2. SEO Audit
•	[ ] 20 keyword posizionate in Google Top 20
•	[ ] Schema.org validation (Google Rich Results Test — 0 errori)
•	[ ] Meta tags compliance (title 55-60 char, description ~155 char)
•	[ ] Core Web Vitals: LCP <2.5s, CLS <0.1, FID <100ms
3. Copy Review
•	[ ] Grammatica italiana (zero errori)
•	[ ] Tone consistency Gen Z (no burocratese)
•	[ ] CTA clarity ("Prenota su WhatsApp" non "Contattaci")
•	[ ] Link integrity (nessun 404)
4. AI Citation Test (Manuale)
•	[ ] ChatGPT: Query "donare sangue frosinone" → cita avisfrosinone.it?
•	[ ] Gemini: Schema LocalBusiness riconosciuto in risposta?
•	[ ] Perplexity: Citazione diretta con URL per "requisiti donazione 2026"?
•	[ ] Claude: Contenuto sufficientemente approfondito?
5. Browser Compatibility
•	[ ] Chrome 120+
•	[ ] Firefox 120+
•	[ ] Safari 17+
•	[ ] Edge 120+
6. Accessibility
•	[ ] WCAG 2.1 AA compliance
•	[ ] Screen reader test (NVDA/VoiceOver)
•	[ ] Keyboard navigation completa
•	[ ] Color contrast ratio ≥4.5:1
________________________________________
11. Analisi del Brief — Congruenza e Riproducibilità
Valutazione Complessiva: ALTA ✅
Il BRIEF.md è un documento industriale di alta qualità che soddisfa i criteri di congruenza e riproducibilità.
✅ Congruenza (Coerenza interna)
Punti di forza:
1.	Allineamento obiettivi-strategia: Gli obiettivi primari (3x donazioni) sono coerenti con le leve strategiche (SEO locale + AI citability + WhatsApp-first). Non esiste disallineamento tra cosa si vuole ottenere e come si vuole ottenere.
2.	Coerenza tone of voice: Il target Gen Z (18-35) è perfettamente allineato con il tono "scienza + amicizia" e l'abbattimento del burocratese. Esempio congruente: "Aghi sottilissimi: 3 secondi" vs "Procedure mediche minimamente invasive".
3.	Vincoli tecnici realistici: La scelta di mantenere Joomla 6 + Helix Ultimate è giustificata dal contesto cliente (upgrade recente) e non entra in conflitto con gli obiettivi di conversione (si lavora per evoluzione, non per rivoluzione).
4.	KPI misurabili: Tutti i KPI (dalle prime donazioni al Domain Authority) sono quantificabili e tracciabili con strumenti specifici (CRM, GA4, Search Console, Moz).
Osservazione critica:
•	Il BRIEF richiede un "dateModified automatico (settimanale)" nella Sezione 12.6 ma non specifica il meccanismo tecnico (cron job? trigger Joomla? aggiornamento manuale?). Questo potrebbe generare ambiguità in fase di sviluppo. Raccomandazione: Specificare se si intende un campo dinamico PHP o un aggiornamento manuale calendarizzato.
✅ Riproducibilità (Eseguibilità pratica)

Punti di forza:
1.	Definition of Done dettagliata: Ogni fase (Research, SEO, Marketing, UX, Copy, Coding, QC) ha checklist specifiche e misurabili. Esempio: Copywriter sa esattamente che deve produrre 55 FAQ con short (40-50 parole) e long (100-150 parole) version.
2.	Input/Output chiari: Il BRIEF specifica esplicitamente "Input da" e "Output per" per ogni agente (Sezione 10.1), eliminando ambiguità sulle dipendenze.
3.	Timeline realistica: Le scadenze (25 mar → 29 mar → 01 apr → 05 apr) rispettano le dipendenze logiche e concedono tempo sufficiente per ogni fase senza sovrapposizioni critiche.
4.	Stack tecnico documentato: Vincoli espliciti (Joomla 6, Helix Ultimate, variabili CSS globali, moduli esistenti come iCagenda) permettono al Coding Agent di operare senza ipotesi.
5.	Risorse di riferimento: Inclusione di file legacy in assets-current/ (home.html, custom.css) garantisce continuità e rispetto dell'esistente.
Potenziali criticità riproducibili:
1.	Dipendenza dalla consegna Copy per Coding: Il BRIEF (Sezione 10.2) indica che Coding può iniziare schema.org in parallelo, ma per i template HTML finali attende Copy. Se Copy slitta (scadenza 29 mar), Coding ha solo 3 giorni (30 mar-01 apr) per completare. Mitigazione: Consigliato anticipare lo sviluppo dei template HTML strutturali basandosi su UX_ARCHITECTURE, lasciando solo l'inserimento dei testi finali come task rapido.
2.	Assenza specifiche tecniche API: Per il "contatore donazioni dinamico" e il "banner urgenza sangue aggiornabile" non sono specificate le API o i metodi di aggiornamento (file JSON? CMS Joomla? Google Sheets?). Mitigazione: Il Coding Agent dovrà proporre una soluzione nel DEV_BRIEF basata sulle capacità di Joomla 6.
3.	Contenuti placeholder da compilare: Alcuni elementi in SEO_GEO_STRATEGY (Sezione 3.2 LocalBusiness) richiedono dati non ancora forniti (indirizzo esatto con numero civico, coordinate GPS lat/long). Mitigazione: Richiedere al PM o allo stakeholder AVIS di compilare questi placeholder prima della fase di Coding.
4.	Test AI manuali non automatizzabili: I KPI GEO (citazioni da ChatGPT/Gemini) richiedono test manuali settimanali. Questo è corretto dato lo stato dell'arte, ma va calendarizzato esplicitamente nel piano QC.
Verifica specifica requisiti Copywriter (Sezione 16 BRIEF)
Il BRIEF include una "REGOLA FONDAMENTALE PER IL COPYWRITTER" che richiede l'eliminazione di tracce AI (trattini lunghi, frasi troppo brevi, struttura "cosa non è"). Questo è congruente con l'obiettivo Gen Z (autenticità) ma aumenta la soglia qualitativa richiesta. La riproducibilità dipende dalla capacità del Copywriter Agent di umanizzare effettivamente i contenuti.
Conclusione
Il brief è congruente e riproducibile con le seguenti raccomandazioni immediate:
1.	Oggi (27 mar): Richiedere ad AVIS indirizzo completo + coordinate GPS per LocalBusiness schema
2.	Entro 28 mar: Copywriter fornisce bozze pagine pillar (anche non finali) per anticipo lavoro Coding
3.	Entro 29 mar: Definire meccanismo tecnico esatto per dateModified automatico
4.	Entro 30 mar: Verificare accesso GA4 e Google Search Console per setup event tracking
Stato attuale: 4/7 fasi completate (Research, SEO, Marketing, UX). Il progetto è in linea con la timeline. La prossima milestone critica è la consegna Copy del 29 marzo.
________________________________________
Documento generato da: Kimi (QC Agent)
Data analisi: 27 Marzo 2026, 00:50 CET
Versione README: 3.0 — Revisione completa post-analisi repository





