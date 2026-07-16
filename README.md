# XBMC4Gamers — Easy Custom View Creator

**by XGekoX**

<img width="1920" height="882" alt="Preview" src="https://github.com/user-attachments/assets/8dd5482e-ca2a-4ca6-8133-489749e37706" />


Editor visuale **drag & drop** per creare le *custom view* dello skin **XBMC4Gamers** sull'Xbox originale, senza scrivere una riga di XML. Costruisci la schermata col mouse, vedi l'anteprima in tempo reale e scarichi il pacchetto pronto da copiare sulla console.

Tutto in **un unico file HTML**: nessuna installazione, nessuna dipendenza, funziona **offline** aprendolo con un qualsiasi browser.

*(English version below — [jump to English](#english))*

---

## Cos'è

XBMC4Gamers supporta fino a 10 custom view (`CustomViewtype_id_80` … `_89`) per personalizzare il modo in cui i giochi appaiono a schermo. Scriverle a mano in XML è laborioso e pieno di dettagli facili da sbagliare. Questo tool ti fa comporre la view visivamente e genera l'XML corretto al posto tuo.

## Caratteristiche

- **Anteprima fedele 1280×720** con l'area realmente visibile dello schermo, e immagini campione per capire subito gli ingombri.
- **32 oggetti pronti**, divisi per categoria:
  - contenitori e sfondi (Game List, Fanart, Image/Panel);
  - 11 artwork del gioco (poster, cd, cd poster, open case, icon, banner, thumb, synopsis, dual3D, fanart thumb, screenshot);
  - 9 icone synopsis (anno, genere, rating, giocatori, volte giocato, ESRB, trainer, trained…);
  - 6 testi synopsis (le stesse informazioni come solo testo);
  - testo generico, label ed items counter.
- **Game List completa**: focus fisso (stile XBMC4Gamers) o navigazione libera, orientamento, dimensioni e spaziatura delle cover, focus position, zoom on‑focus, cover e titoli configurabili separatamente per lo stato normale e on‑focus, immagini on‑focus (es. cornici glossy), navigazione automatica.
- **Titoli scorrevoli** (marquee) attivabili separatamente per normale e on‑focus, visibili anche in anteprima.
- **Sfumature ai bordi della griglia** per lato (sinistra/destra/alto/basso), con spessore, morbidezza e colore regolabili, oppure con una tua immagine.
- **Import di una view esistente** da file `.xml` o da pacchetto `.zip`, immagini esterne comprese, per modificarla.
- **Esporta**: copia l'XML, scarica il `.xml`, l'immagine di anteprima `.jpg`, oppure il **pacchetto ZIP completo** già organizzato come lo attende la console.
- **Salva/carica progetto** in JSON per riprendere il lavoro in un secondo momento.
- **Wiki integrata** con guida passo‑passo a prova di principiante.
- **5 lingue** (Italiano, English, Español, Français, Deutsch) con selezione automatica dalla lingua del sistema.

## Come si usa

1. Apri il file `.html` in un browser (doppio clic, nessuna installazione).
2. Aggiungi gli oggetti dalla palette e posizionali col mouse; regola i dettagli nel pannello a destra.
3. Premi **📦 Pacchetto** per scaricare lo ZIP.
4. Copia il contenuto nella cartella `skins/Profile/xml/custom views/_global/` del tuo skin XBMC4Gamers.

> Suggerimento: apri la **📖 Wiki** dal tool per la spiegazione di ogni singola opzione.

## Compatibilità

Pensato per lo skin **XBMC4Gamers** (Rocky5) su **XBMC4Xbox** / Xbox originale.

## Disclaimer

Progetto non ufficiale, sviluppato per la community. XBMC4Gamers è di Rocky5. "Xbox" è un marchio Microsoft; qui usato solo a scopo descrittivo.

---

<a name="english"></a>

## English

Visual **drag & drop** editor to build **XBMC4Gamers** custom views for the original Xbox — no XML by hand. Compose the screen with your mouse, watch a live preview, and download a package ready to copy onto the console.

Everything is in **one single HTML file**: no install, no dependencies, works **offline** in any browser.

### Highlights

- Faithful **1280×720 preview** with the real visible screen area and sample images for instant sizing.
- **32 ready‑made objects**: containers and backgrounds, 11 game artworks, 9 synopsis icons, 6 synopsis text fields, plus labels and an items counter.
- **Full Game List control**: fixed focus (XBMC4Gamers style) or free navigation, orientation, cover size and spacing, focus position, on‑focus zoom, separate normal / on‑focus titles, on‑focus overlays, automatic navigation.
- **Scrolling (marquee) titles**, toggled separately for normal and on‑focus, visible in the preview.
- **Per‑side grid edge fades** (left/right/top/bottom) with adjustable thickness, softness and colour, or your own image.
- **Import an existing view** from `.xml` or a `.zip` package (external images included) to edit it.
- **Export**: copy the XML, download the `.xml`, the `.jpg` preview, or the **full ZIP package** laid out the way the console expects.
- **Save/load project** as JSON.
- **Built‑in Wiki** with a beginner‑friendly, step‑by‑step guide.
- **5 languages** (IT/EN/ES/FR/DE) with automatic detection from the system language.

### Usage

1. Open the `.html` file in a browser (no install).
2. Add objects from the palette, position them with the mouse, tune the details on the right.
3. Click **📦 Package** to download the ZIP.
4. Copy its contents into your skin's `skins/Profile/xml/custom views/_global/` folder.

### Compatibility

Made for the **XBMC4Gamers** skin (Rocky5) on **XBMC4Xbox** / original Xbox.

### Disclaimer

Unofficial community project. XBMC4Gamers belongs to Rocky5. "Xbox" is a Microsoft trademark, used here for descriptive purposes only.
