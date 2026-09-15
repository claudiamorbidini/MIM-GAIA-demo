# G.A.I.A.

Demo del marketplace nazionale di soluzioni di Intelligenza Artificiale per le scuole, integrato in UNICA (Linee guida MIM, DM 166/2025).

Proposta per il Ministero dell'Istruzione e del Merito.

## Avvio

Doppio clic su `apri-dashboard.bat` (Windows) oppure apri `index.html` nel browser.

In alternativa, dalla cartella del repository:

```bash
python -m http.server 8000
```

Poi apri http://localhost:8000

Serve internet per la traduzione AI e per la generazione PDF. I dati delle soluzioni sono esemplificativi.

## Modifiche

Tutto il prototipo è in un solo file HTML, con le immagini a parte.

| File | Cosa modificare |
|------|-----------------|
| `index.html` | Testi, stili (blocco `<style>`), logica (blocco `<script>`), viste e profili |
| `assets/` | Emblema, logo UNICA, titolo «tutti», illustrazione della home |

Dopo una modifica, salva e ricarica la pagina nel browser.
