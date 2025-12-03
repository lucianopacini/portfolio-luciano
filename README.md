<!-- FILE: README.md -->
# Portfolio di Luciano Pacini


Struttura del progetto:
- index.html
- cv.html
- contact.html
- /css/styles.css (compilato da styles.scss)
- /assets/ (foto, favicon, CV PDF, og-image)


Istruzioni rapide:
1. Compila `css/styles.scss` con `sass --watch css/styles.scss:css/styles.css` oppure usa un compilatore.
2. Aggiungi i tuoi asset in `/assets/` (me.jpg, favicon.ico, CV PDF, og-image.png).
3. Crea un repo su GitHub e abilita GitHub Pages dalla branch `main` (o `gh-pages`).
4. Controlla che le URL in `og:url` e i link siano aggiornati al tuo username.


EmailJS (opzionale): sostituisci `YOUR_USER_ID`, `SERVICE_ID` e `TEMPLATE_ID` nello script di `contact.html`.


Consegna:
- Nome file progetto: "Progetto HTML e CSS di Luciano Pacini"
- Pubblica con GitHub Pages e invia il link in piattaforma.


 HTML & CSS: tutti i file .html e .css presenti.
Verifica: apri index.html e la pagina CV (cv.html o come l'hai chiamata).

 Almeno 2 pagine: (es. index.html, cv.html, contatti.html).

 Pagina CV in HTML: deve essere file .html (non PDF embedded).

 Pagina contattami con form: <form> presente e validato HTML.

 Front-end framework (Bootstrap/Materialize/altro): obbligatorio secondo i requisiti che hai copiato.
Verifica: cerca in <head> un link a bootstrap.min.css o materialize.css o presence di classi tipiche (container, row, col-*, btn, navbar, ecc.).

Se lo trovi → ok.

Se non lo trovi → aggiungilo facilmente via CDN (vedi sotto).

 Favicon: file .ico/.png e <link rel="icon" href="...">.

 Menu sticky (almeno mobile): header con position: sticky o fixed.

 Layout con Flexbox o Grid: almeno una pagina deve usare display:flex o display:grid.

 Sass o Less: hai file .scss o .sass o .less nel repo?

Se lavori solo con CSS, compila o aggiungi la versione compilata; ma è richiesto usarli nel workflow (puoi avere sorgenti .scss e il .css compilato incluso).

 100% responsive: test con DevTools (mobile sizes).

 Pubblicato su GitHub Pages.