# Mister Lasagna — Stock Check App

App PWA per lo stock check di Mister Lasagna Leicester Square.

## Cosa fa
- **Stock Check**: conta lo stock di lasagne, pasta, toppings, arancini, acqua e S.Pellegrino.
  L'app calcola automaticamente quanti pezzi servono (MIN − stock rimanente).
- **2 pulsanti WhatsApp**:
  - 📱 **Cucine NH/Chelsea** — richiesta interna per lasagne/pasta/topping/arancini
  - 📱 **Drinks** — ordine acqua e S.Pellegrino a Casa Julia/Zaino
- **Tab Fornitori**: Casa Julia (preferenziale), Zaino (backup), Donovan (packaging).
  Ogni fornitore ha la sua vista stock check con pulsante WhatsApp dedicato.

## Funzionalità
- I dati di stock restano salvati (localStorage) finché non premi ↻ Reset
- Drinks core sincronizzati tra Stock Check e tab Casa Julia/Zaino
- Zoom A/A/A per visibilità in cucina
- Guida bilingue IT/EN

## Deploy
File statico, niente backend. Si pubblica direttamente su GitHub Pages:
1. Settings → Pages → Branch: `main` → Save
2. URL: `https://<user>.github.io/MisterLasagna/mister_lasagna.html`

## File
- `mister_lasagna.html` — l'app completa (autosufficiente, no dipendenze esterne)
- `mister_lasagna_logo.svg` — logo brand
