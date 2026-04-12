# AuleBook — Istruzioni di installazione

## Cos'è questa app
AuleBook è una PWA (Progressive Web App) installabile su qualsiasi dispositivo
senza passare da App Store o Google Play.

---

## Come pubblicarla online (GRATIS) — Netlify Drop

1. Vai su: https://app.netlify.com/drop
2. Trascina la CARTELLA `aulebook/` nella pagina
3. Netlify ti darà un link tipo: https://nome-casuale.netlify.app
4. Condividi il link con tutti gli utenti

---

## Come installarla sui dispositivi

### Android (Chrome)
1. Apri il link con Chrome
2. Tocca il menu ⋮ in alto a destra
3. Seleziona "Aggiungi alla schermata Home"
4. L'app appare come icona, si apre come app nativa

### iPhone / iPad (Safari)
1. Apri il link con Safari
2. Tocca l'icona Condividi (□↑)
3. Seleziona "Aggiungi alla schermata Home"
4. L'app si installa come app nativa

### Windows (Chrome/Edge)
1. Apri il link con Chrome o Edge
2. Clicca l'icona 🖥 nella barra indirizzi (o menu → "Installa app")
3. L'app si apre come finestra dedicata

### Mac (Chrome/Safari)
1. Su Chrome: icona installa nella barra indirizzi
2. Su Safari: Archivio → Aggiungi al Dock

---

## Account predefiniti

| Ruolo   | Email               | Password   |
|---------|---------------------|------------|
| Admin   | admin@aule.it       | admin123   |
| Gestore | gestore@aule.it     | gestore123 |
| Utente  | (si registra)       | (sceglie)  |

---

## Flusso di utilizzo

1. L'utente si **registra** → riceve messaggio "in attesa approvazione"
2. L'**Admin** approva l'account dalla sezione Utenti
3. L'utente accede e fa una **prenotazione** (aula A o B, VTC/Webex/Corsi ecc.)
4. Il **Gestore** riceve la richiesta e la approva o rifiuta
5. Se approvata, la prenotazione appare nel **Calendario** per tutti

---

## I dati dove vengono salvati?
Tutti i dati sono salvati nel browser (localStorage) del dispositivo.
Per un database centralizzato condiviso tra tutti gli utenti,
è necessario aggiungere un backend (Firebase, Supabase ecc.) — richiedilo se necessario.
