# Viaggio in Vietnam — dashboard

Dashboard del viaggio (17–28 marzo 2027), pubblicata con GitHub Pages.

- `index.html` — la dashboard (pagina unica, funziona anche offline)
- `viaggio.xlsx` — i dati del viaggio: si modifica qui
- `.nojekyll` — dice a GitHub Pages di servire i file così come sono

Quando apri il sito, la dashboard legge da sola `viaggio.xlsx` dalla stessa cartella.

## Aggiornare il viaggio

1. Modifica `viaggio.xlsx` in Excel e salvalo (da Numbers: *File › Esporta › Excel*, con lo stesso nome).
2. Su GitHub apri il repository › **Add file › Upload files** › trascina `viaggio.xlsx` › **Commit changes**.
3. Dopo circa un minuto il sito è aggiornato. Sul telefono premi **Aggiorna** nella dashboard.

## Prima pubblicazione (una volta sola)

1. Su github.com: **+ › New repository**. Scegli un nome, ad esempio `vietnam-2027`.
2. **Add file › Upload files** › carica `index.html`, `viaggio.xlsx`, `README.md` e `.nojekyll` › **Commit changes**.
   (Su Mac, per vedere `.nojekyll` nel Finder premi `Cmd + Shift + .`)
3. **Settings › Pages** › *Build and deployment* › Source: **Deploy from a branch** › Branch: **main**, cartella **/ (root)** › **Save**.
4. Dopo 1–2 minuti, in alto in **Settings › Pages** compare il link, ad esempio
   `https://TUO-UTENTE.github.io/vietnam-2027/`. È questo il link da condividere.

## Sul telefono come un'app

Apri il link in Safari › **Condividi › Aggiungi alla schermata Home**.

## Privacy

Un sito GitHub Pages è **pubblico**: chiunque abbia il link può vederlo. Con un account GitHub gratuito anche il repository deve essere pubblico (con GitHub Pro può essere privato, ma il sito resta visibile a chi ha il link).
Non inserire nel file codici di prenotazione, numeri di passaporto o altri dati personali che non vuoi esporre.
