UNLIMITED MUSIC — PROTOTIPO ANDROID/PWA CON RICERCA MUSICALE ONLINE

Questa versione mantiene il lettore locale e aggiunge una ricerca nel catalogo Jamendo tramite la API pubblica:
- ricerca online e riproduzione dei risultati disponibili;
- preferiti e playlist salvati localmente;
- link alla pagina della fonte per ogni brano Jamendo;
- lettore audio con avanzamento, precedente e successivo.

IMPORTANTE PRIMA DELLA PUBBLICAZIONE
- L'app usa il Client ID dimostrativo 709fa152 riportato nella documentazione Jamendo esclusivamente per test. Non è una credenziale di produzione e può essere limitato o revocato.
- Registrati al portale sviluppatori Jamendo, crea la tua applicazione e sostituisci JAMENDO_CLIENT_ID in app.js con il tuo Client ID.
- Verifica le condizioni API aggiornate e la licenza di ogni brano. L'API richiede attribuzione degli artisti e un link diretto alla pagina del contenuto. La compatibilità dell'uso previsto deve essere verificata prima di pubblicare.
- Questa build è una PWA/web app, non un APK Android. Per installarla dal browser deve essere servita via HTTPS. Per un APK si può successivamente impacchettare con Capacitor o creare un wrapper Android.
- Il progetto non è affiliato né approvato da Jamendo.

AVVIO
1. Estrai il file ZIP.
2. Per un test rapido, servi la cartella da un server web locale oppure pubblicala su hosting HTTPS.
3. Apri index.html nel browser. Per testare la ricerca online è necessario accesso a Internet.
4. Cerca il nome di un artista o brano nella barra di ricerca.

File principali: index.html, app.js, style.css, manifest.json, sw.js.
