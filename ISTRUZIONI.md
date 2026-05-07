# 📲 Guida installazione — Budget Personale

## File inclusi nel pacchetto
- `index.html` — l'app completa
- `manifest.json` — configurazione PWA
- `sw.js` — service worker (funziona offline)
- `icons/icon-192.png` — icona app
- `icons/icon-512.png` — icona app grande

---

## PASSO 1 — Crea un account GitHub
1. Vai su https://github.com
2. Clicca "Sign up" e registrati (è gratis)
3. Conferma l'email

---

## PASSO 2 — Crea un nuovo repository
1. Clicca il **+** in alto a destra → "New repository"
2. Nome: `budget-app` (tutto minuscolo)
3. Seleziona **Public**
4. Clicca **"Create repository"**

---

## PASSO 3 — Carica i file
1. Nel repository appena creato, clicca **"uploading an existing file"**
2. Trascina TUTTI i file e la cartella `icons/` nell'area di upload
3. Scrivi un messaggio es. "Prima versione"
4. Clicca **"Commit changes"**

---

## PASSO 4 — Attiva GitHub Pages
1. Vai su **Settings** (in alto nel repository)
2. Clicca **"Pages"** nel menu a sinistra
3. In "Source" seleziona **"Deploy from a branch"**
4. Branch: **main** / Folder: **/ (root)**
5. Clicca **Save**
6. Aspetta 1-2 minuti

Il tuo sito sarà disponibile a:
**https://TUONOME.github.io/budget-app**

---

## PASSO 5 — Installa sul telefono Android
1. Apri Chrome sul telefono Android
2. Vai all'indirizzo `https://TUONOME.github.io/budget-app`
3. Apparirà un banner in basso: **"Aggiungi alla schermata Home"**
4. Oppure tocca i 3 puntini ⋮ → "Aggiungi alla schermata Home"
5. Conferma → l'icona apparirà come una normale app!

---

## ✅ Funzionalità dell'app
- Traccia entrate e uscite per mese
- Categorie predefinite (spesa, ristorante, trasporti, ecc.)
- Dati salvati localmente sul telefono (localStorage)
- Export CSV per Excel/Google Sheets
- Backup JSON ripristinabile
- Stampa/PDF del riepilogo mensile
- Funziona OFFLINE dopo la prima visita
- Installabile come app nativa Android

---

## ❓ Problemi comuni

**Non vedo il banner di installazione?**
→ Assicurati di usare Chrome (non Firefox o Samsung Browser)
→ Vai sui 3 puntini ⋮ → "Aggiungi alla schermata Home"

**I dati sono persi?**
→ I dati sono nel browser/app. Usa il backup JSON regolarmente.

**Voglio aggiornare l'app?**
→ Modifica `index.html` su GitHub e fai un nuovo commit. L'aggiornamento
  arriva automaticamente sul telefono al prossimo avvio.
