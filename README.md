# Generatore Badge Aziendali — Gruppo EcorNaturaSì

Applicazione web single-file (CR80 86x54mm fronte/retro pieghevole su foglio A4) con QR Code vCard e ritaglio foto interattivo.

## Struttura della Repository GitHub
Carica nella root di questa repository (accanto a `index.html`) i seguenti file grafici e font:

```text
/
├── index.html                  # Applicazione principale (già inclusa)
├── .nojekyll                   # Abilita il caricamento diretto dei font su GitHub Pages
├── README.md                   # Questa guida
├── Logo-bianco.png             # Logo NaturaSì bianco per intestazione
├── lemniscata.png              # Lemniscata verde decorativa di sfondo
├── futura-md-bt-medium.ttf     # Font Futura BT Medium
└── futura-bold-bt.ttf          # Font Futura BT Bold
```

> **Nota sui nomi file:** Assicurati che i nomi dei file caricati su GitHub rispettino esattamente maiuscole e minuscole (`Logo-bianco.png`, `lemniscata.png`, `futura-md-bt-medium.ttf`, `futura-bold-bt.ttf`), poiché i server GitHub Pages sono *case-sensitive*.

## Pubblicazione su GitHub Pages
1. Crea una nuova repository su GitHub e carica tutti i file elencati sopra.
2. Vai su **Settings** > **Pages**.
3. Sotto **Build and deployment > Branch**, seleziona `main` e cartella `/ (root)`, poi clicca **Save**.
4. Dopo circa 1 minuto il generatore sarà attivo online con loghi e font ufficiali.