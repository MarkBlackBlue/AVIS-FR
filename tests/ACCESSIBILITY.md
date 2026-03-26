# Checklist Accessibilità WCAG 2.1 AA - AVIS Frosinone

## 1. Contenuto (HTML)
- [ ] Il sito ha una lingua impostata (`<html lang="it">`).
- [ ] Tutti i tag `<img>` hanno un attributo `alt` descrittivo o vuoto (`alt=""`) per immagini decorative.
- [ ] I pulsanti e i link hanno etichette comprensibili (`aria-label` se necessario).
- [ ] Non ci sono interruzioni nell'ordine gerarchico degli header (`<h1>`, `<h2>`, etc.).
- [ ] I form (VisForm) hanno etichette `<label>` associate correttamente.

## 2. Navigazione
- [ ] Il menu è navigabile interamente tramite tastiera (`tabindex`, focus visibile).
- [ ] Sono presenti link di salto ("Salta al contenuto") per utenti con screen reader.
- [ ] Il contrasto del testo è almeno 4.5:1 per testo normale e 3:1 per testo grande.

## 3. Dinamicità
- [ ] Gli slider hanno controlli di stop/pausa.
- [ ] Nessun elemento lampeggia più di 3 volte al secondo.
- [ ] I menu a tendina sono accessibili tramite tastiera.

## 4. Validazione
- [ ] Nessun errore di validazione HTML W3C critico.
- [ ] Pa11y non segnala errori di conformità AA.
