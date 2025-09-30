
# Sito (Netlify-ready) · L’Indomita Compagnia Teatrale

## Deploy su Netlify (gratis)
1. Vai su https://app.netlify.com e crea l’account
2. Clicca **Add new site** → **Deploy manually**
3. Trascina dentro l’intera cartella del sito (quella di questo ZIP)
4. Fine: il sito sarà online su `https://<nome>.netlify.app`

## Modifiche contenuti
- **Spettacoli**: `assets/data/spettacoli.json`
- **Date**: `assets/data/eventi.json` (+ `assets/data/indomita.ics` per il download)
- **Contatti**: il form usa **Netlify Forms** (nessuna configurazione). Le richieste le trovi su Netlify → **Forms**.

## Note tecniche
- `netlify.toml`: header di sicurezza + caching per asset statici
- `404.html`: pagina di errore personalizzata
- `thank-you.html`: pagina di conferma invio form
