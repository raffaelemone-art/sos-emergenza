# Pubblicare SOS Emergenza su GitHub Pages (15 minuti, gratis)

Alla fine avrai un indirizzo web tuo, tipo `https://TUOUSER.github.io/sos-emergenza/`, da aprire su qualsiasi telefono e installare come app.

## Cosa ti serve
- Un indirizzo email
- Il computer (la procedura è più comoda da PC)
- I 7 file della cartella: `index.html`, `manifest.json`, `sw.js`, `icon.svg`, `icon-192.png`, `icon-512.png`, `icon-512-maskable.png`

## Passo 1 · Crea l'account GitHub
1. Vai su https://github.com e premi **Sign up**.
2. Scegli un nome utente semplice (comparirà nell'indirizzo del sito) e conferma l'email.

## Passo 2 · Crea il "repository" (la cartella online)
1. In alto a destra premi **+** e poi **New repository**.
2. Nome: `sos-emergenza`
3. Scegli **Public** (serve per la pubblicazione gratuita).
4. Spunta **Add a README file** e premi **Create repository**.

## Passo 3 · Carica i 7 file
1. Nella pagina del repository premi **Add file** e poi **Upload files**.
2. Trascina dentro tutti e 7 i file (decomprimi prima lo ZIP).
3. In fondo premi **Commit changes**.
4. Controlla che i file siano nell'elenco, non dentro una sottocartella.

## Passo 4 · Attiva GitHub Pages
1. Premi **Settings** (ingranaggio in alto).
2. Nel menu a sinistra scegli **Pages**.
3. Sotto **Build and deployment**, in **Source** scegli **Deploy from a branch**.
4. In **Branch** scegli `main` e la cartella `/ (root)`, poi **Save**.
5. Aspetta 1-2 minuti e ricarica la pagina: in alto compare l'indirizzo del sito.

L'indirizzo sarà: `https://TUOUSER.github.io/sos-emergenza/`

## Passo 5 · Installa l'app sul telefono
**Android (Chrome):** apri l'indirizzo, menu ⋮, poi **Installa app** (o **Aggiungi a schermata Home**).
**iPhone (Safari):** apri l'indirizzo, tocca **Condividi**, poi **Aggiungi a Home**. Deve essere Safari.

Alla prima apertura parte la guida: segui i 3 passaggi.

## Passo 6 · Prova prima di fidarti
1. Spunta **Modalità prova** e premi SOS: devono comparire il conto alla rovescia, la sirena e la posizione.
2. Togli la spunta, inserisci come contatto **un tuo numero** e premi SOS davvero: controlla che si apra l'SMS già scritto e che parta la chiamata.
3. Fai la prova su almeno un telefono Android e uno iPhone.
4. Con EmailJS configurato, usa **Invia email di prova** e controlla che l'email arrivi (guarda anche nello spam).

## Aggiornare l'app in futuro
Nel repository apri il file da cambiare (es. `index.html`), premi la matita per modificarlo oppure **Add file → Upload files** per sostituirlo, poi **Commit changes**. Dopo 1-2 minuti il sito è aggiornato. Chiudi e riapri l'app sul telefono per vedere le novità.

## Cose da sapere
- Il repository pubblico mostra il **codice** dell'app, non i dati degli utenti: nome, codice fiscale e contatti restano nel telefono di ciascuno.
- Non scrivere mai le chiavi EmailJS nei file: si inseriscono dentro l'app, nella sezione "Invio email automatico (avanzato)".
- Su EmailJS puoi limitare l'uso della chiave al tuo sito (sezione **Security**, indirizzo `TUOUSER.github.io`), così nessun altro può usarla.
- Se il sito non si apre, controlla in **Settings → Pages** che lo stato sia verde e che i file siano nella radice del repository.
- Un nome di dominio personalizzato (es. `sosemergenza.it`) si può collegare dopo, sempre da **Settings → Pages**.

## Per il Play Store (più avanti)
1. Vai su https://www.pwabuilder.com e incolla l'indirizzo del sito.
2. Scarica il pacchetto Android generato.
3. Carica il pacchetto su Google Play Console (costo una tantum di 25 $).
Prima di pubblicare sugli store servono una pagina di informativa privacy e una descrizione chiara dei dati trattati (nome, codice fiscale, posizione).
