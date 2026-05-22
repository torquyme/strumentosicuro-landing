# StrumentoSicuro landing page

Pacchetto statico pronto per GitHub Pages.

## Cosa modificare prima della pubblicazione

1. In `index.html`, sostituire `https://formspree.io/f/INSERISCI_ID_FORM` con l’endpoint reale del form.
2. Completare `privacy.html` con dati del titolare, servizio form e dettagli privacy reali.
3. Revisionare `termini.html` prima di gestire transazioni reali.
4. Verificare DNS e dominio custom `strumentosicuro.it` in GitHub Pages.

## Asset inclusi

- `assets/logo.svg` — logo completo
- `assets/logo-light.svg` — logo completo per sfondi scuri
- `assets/icon.svg` — icona logo
- `assets/logo-horizontal.png` — logo PNG grande
- `assets/logo-horizontal-light.png` — logo PNG grande per sfondi scuri
- `assets/logo-icon-512.png` — icona PNG 512
- `assets/icons/icon-16.png`, `icon-32.png`, `icon-64.png`, `icon-128.png`, `icon-180.png`, `icon-192.png`, `icon-256.png`, `icon-512.png`
- `assets/og-image.png` — immagine anteprima social


## Formspree

La landing usa Formspree per il modulo contatti.

1. Crea un account su https://formspree.io
2. Crea un nuovo form per `info@strumentosicuro.it`
3. Copia l’endpoint, nel formato `https://formspree.io/f/xxxxxxx`
4. In `index.html`, sostituisci `https://formspree.io/f/INSERISCI_ID_FORM` con il tuo endpoint reale.
5. Pubblica su GitHub Pages e invia un test dal form.

Opzionale: in Formspree puoi impostare redirect, captcha/anti-spam e notifiche email.

## Cookie e Privacy

Sono incluse bozze di `privacy.html` e `cookie.html` aggiornate per l’uso di Formspree. Prima di mandare traffico reale, completale con i dati effettivi del titolare.
