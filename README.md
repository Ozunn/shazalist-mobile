# Shazalist Mobile

App Android di **Shazalist**: porta le playlist dal PC al telefono via QR (Internet), le ascolti offline con player moderno.

Questa repository e il **canale di distribuzione** (landing + APK). Non contiene documentazione interna di sviluppo.

## Installazione

1. Apri [Releases](https://github.com/Ozunn/shazalist-mobile/releases/latest) oppure scansiona il QR dalla playlist sul PC.
2. Scarica l'APK `shazalist-mobile-*.apk`.
3. Su Android abilita l'installazione da fonti esterne se richiesto.
4. Installa e apri l'app (splash nero + logo).

## Aggiornamenti

In app, in alto vicino al menu, vedi la versione (`vX.Y.Z`).  
Se c'e una release piu recente su GitHub, compare un pulsante azzurro **Aggiorna a v…**:

1. Tocca il pulsante
2. L'APK si scarica e parte l'installer di sistema
3. Conferma l'aggiornamento

**I tuoi brani, playlist e cartelle restano**: Android sostituisce solo l'app, non la libreria locale.

## Funzioni

- **Home** — Play / Libreria
- **Libreria e Playlist** — riproduzione, riordino, rinomina, elimina, selezione multipla
- **Import da QR** — ricetta playlist + download con la rete del telefono (non serve la Wi‑Fi del PC)
- **Normalizzazione** — opzionale post-download (Sound Check-like) e tab dedicata
- **Player** — mini-bar persistente, drag su/giu, timeline in mini, volume nel player pieno, audio in background
- **Navigazione** — swipe laterale tra le sezioni (anche a player aperto)
- **Deep link** — `shazalist://import/…` e `shazalist://playlist/…`

## Landing

GitHub Pages: [https://ozunn.github.io/shazalist-mobile](https://ozunn.github.io/shazalist-mobile)

Il QR del desktop apre questa pagina: prova ad avviare l'app; se manca, propone l'APK piu recente.

## Privacy dati

- Nessuna musica personale viene caricata su GitHub.
- Libreria e file audio restano sul telefono (storage dell'app).
- Aggiornare l'APK non cancella la libreria (stesso `applicationId` e stessa firma).

## Supporto

Problemi di installazione: verifica che il file sia l'APK ufficiale della release e che la versione in-app sia allineata al tag GitHub (`vX.Y.Z`).
