# Crosslisting Assist Mobile

Prototipo PWA statico per iPhone. Include archivio locale, schede articolo, foto compresse, backup JSON, calcolo indicativo del netto/margine e preparazione testi per Vinted, Facebook Marketplace, Wallapop, Subito, eBay, Depop e Vestiaire Collective.

## Pubblicazione con GitHub Pages
1. In **Settings → Pages**, imposta **Build and deployment → Source: GitHub Actions**.
2. Il workflow `.github/workflows/pages.yml` pubblica automaticamente il contenuto del repository.
3. Apri il link Pages in Safari e scegli **Condividi → Aggiungi alla schermata Home**.

## Limiti
- Prototipo: non sincronizza automaticamente i dati con PC o altri dispositivi.
- Non effettua login, non legge dati dalle app marketplace e non pubblica automaticamente.
- I dati sono conservati nel browser locale. Esporta periodicamente il backup JSON.
- Le immagini e i dati degli annunci restano sul dispositivo, salvo il backup che l'utente decide di esportare/condividere.
