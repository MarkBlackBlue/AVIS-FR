/04-ux/UX_ARCHITECTURE_2026-03.md
________________________________________
1. SITEMAP COMPLETO (17+ pagine)
L1 (Primary Navigation)
URL	Pagina	Priorità
/	Home	5
/dona	Come donare	5
/faq	FAQ	4
/chi-siamo	Chi siamo	4
/dove-siamo	Dove siamo	5
/blog/	Blog	4
/eventi	Eventi	3
/contatti	Contatti	5
________________________________________
L2 (Conversion & Support Pages)
URL	Pagina	Parent	Priorità
/prima-donazione	Prima donazione	/dona	5
/diventa-donatore	Diventa donatore	/dona	4
/posso-donare	Posso donare?	/dona	5
/gruppi-sanguigni	Gruppi sanguigni	/faq	4
/plasma	Donazione plasma	/dona	3
/volontariato	Volontariato	/chi-siamo	3
/albo-benemeriti	Albo donatori	/chi-siamo	2
________________________________________
Blog (L2 sotto /blog)
URL	Articolo	Priorità
/blog/paura-aghi-donazione	Paura aghi	5
/blog/fa-male-donare-sangue	Fa male?	5
/blog/tatuaggi-donazione	Tatuaggi	5
/blog/dieta-pre-donazione	Dieta	4
/blog/requisiti-donatori-2026	Requisiti 2026	5
________________________________________
2. WIREFRAME HOME — 10 SLIDE
________________________________________
Slide 1 — Hero
•	Headline: "Doni sangue. Qui a Frosinone."
•	Subheadline: "45 minuti. Prenoti su WhatsApp. Risposta veloce."
•	CTA: WhatsApp — "Scrivici ora"
•	Componenti: whatsapp_sticky
•	Mobile: full viewport, CTA centrale, menu hamburger
________________________________________
Slide 2 — Perché donare
•	Headline: "1 donazione, fino a 3 vite"
•	Subheadline: "Il tuo sangue serve qui, nella tua città"
•	Elementi: 3 blocchi dati (vite, tempo, frequenza)
•	CTA: Interno — "Verifica se puoi donare"
•	Componenti: —
•	Mobile: stack verticale 1 colonna
________________________________________
Slide 3 — Blood Stock
•	Headline: "Oggi servono questi gruppi"
•	Subheadline: "Situazione aggiornata in tempo reale"
•	CTA: WhatsApp — "Prenota subito"
•	Componenti: blood_stock_bar
•	Mobile: banner full-width, colori evidenti
________________________________________
Slide 4 — Come funziona
•	Headline: "Arrivi. Doni. Torni a casa."
•	Subheadline: "Ti guidiamo passo passo"
•	Elementi: 4 step visivi
•	CTA: Interno — "Prima donazione"
•	Componenti: —
•	Mobile: swipe orizzontale step
________________________________________
Slide 5 — Paure
•	Headline: "Hai dubbi? Normale."
•	Subheadline: "Ti rispondiamo senza giri di parole"
•	Elementi: 3 obiezioni rapide
•	CTA: Interno — "Leggi tutte le FAQ"
•	Componenti: —
•	Mobile: accordion semplificato
________________________________________
Slide 6 — Impatto
•	Headline: "Ogni numero è una persona"
•	Subheadline: "Questo è quello che abbiamo fatto insieme"
•	Elementi: contatori
•	CTA: Interno — "Unisciti"
•	Componenti: impact_counter
•	Mobile: animazione al scroll
________________________________________
Slide 7 — Testimonial
•	Headline: "Chi dona torna"
•	Subheadline: "Persone normali, come te"
•	Elementi: 3 testimonianze
•	CTA: Interno — "Scopri le storie"
•	Componenti: donor_testimonial
•	Mobile: carousel swipe
________________________________________
Slide 8 — Medici
•	Headline: "Qui sei seguito da medici veri"
•	Subheadline: "Professionisti del territorio"
•	CTA: Interno — "Chi siamo"
•	Componenti: —
•	Mobile: card scroll verticale
________________________________________
Slide 9 — Eventi
•	Headline: "Non solo donazione"
•	Subheadline: "Corsi e giornate speciali"
•	CTA: Interno — "Vedi eventi"
•	Componenti: —
•	Mobile: lista verticale
________________________________________
Slide 10 — CTA finale
•	Headline: "Vuoi iniziare?"
•	Subheadline: "Scrivici ora. Ti rispondiamo subito."
•	CTA 1: WhatsApp — "Prenota ora"
•	CTA 2: Telefono — "Chiama"
•	Componenti: whatsapp_sticky
•	Mobile: doppio bottone sticky bottom
________________________________________
3. WIREFRAME PAGINE PILLAR
________________________________________
/prima-donazione
1.	Hero
o	Headline diretta
o	CTA WhatsApp immediata
2.	Obiezioni inline
o	10 accordion
o	apertura singola
3.	Timeline
o	4 step visivi
4.	Trust Bar
o	AVIS + ospedale
5.	CTA sticky mobile
________________________________________
/posso-donare
1.	Quiz interattivo
2.	Risultato immediato
3.	Requisiti base (lista)
4.	Sezione "E se ho..."
5.	CTA WhatsApp
________________________________________
/dona
1.	Blood stock bar
2.	4 step processo
3.	Orari + mappa
4.	CTA doppia
________________________________________
/diventa-donatore
1.	Value proposition
2.	3 step iscrizione
3.	Benefits
4.	Form ridotto
5.	CTA
________________________________________
4. COMPONENTI UI
________________________________________
1. whatsapp_sticky
•	Posizione: fixed bottom-right
•	Trigger: scroll >300px
•	Testo: "Scrivici su WhatsApp"
•	Mobile: sempre visibile dopo trigger
•	Desktop: inline
________________________________________
2. blood_stock_bar
•	Posizione: top section
•	Comportamento: statico aggiornabile CMS
•	Colori:
o	Rosso = urgente
o	Giallo = medio
o	Verde = ok
•	Mobile: full width
________________________________________
3. eligibility_quiz
•	Posizione: sopra fold /posso-donare
•	Domande: 5 step
•	Output:
o	Idoneo → CTA diretta
o	Dubbio → contatto
•	No backend
________________________________________
4. impact_counter
•	Posizione: homepage slide 6
•	Animazione: count-up
•	Trigger: scroll in viewport
•	Mobile: attivazione lazy
________________________________________
5. donor_testimonial
•	Posizione: homepage slide 7
•	Tipo: carousel
•	Contenuto:
o	nome
o	età
o	citazione
•	Mobile: swipe
________________________________________
5. NAVIGAZIONE
Menu mobile (max 5 voci)
•	Dona
•	Posso donare
•	Prima donazione
•	Dove siamo
•	Contatti
________________________________________
Footer
•	Indirizzo
•	Orari
•	Social
•	Link utili
________________________________________
Breadcrumb
Formato:
•	Home > Dona > Prima Donazione
Solo L2
________________________________________
Internal Linking
•	/prima-donazione → /posso-donare
•	/posso-donare → /dona
•	/dona → /contatti
•	blog → sempre verso CTA WhatsApp
________________________________________
6. MOBILE-FIRST
Breakpoint
•	320px: base
•	768px: tablet
•	1024px: desktop
________________________________________
Regole
•	Font min: 16px
•	Touch target: 48x48px
•	CTA sempre visibile
•	Immagini lazy load
•	No hover dependency
________________________________________
7. ACCESSIBILITÀ
•	Contrasto ≥ 4.5:1
•	Aria-label su:
o	bottoni
o	quiz
o	accordion
•	Navigazione tastiera:
o	FAQ
o	quiz
•	Focus states visibili
________________________________________
CONCLUSIONE OPERATIVA
Questa architettura è costruita per:
•	ridurre attrito decisionale
•	portare l’utente al WhatsApp nel minor tempo possibile
•	rispondere alle domande prima che vengano fatte
•	essere leggibile sia da persone sia da AI
Il Copywriter deve riempire ogni blocco mantenendo questa struttura.
Il Developer deve implementare senza modificarne la logica.

