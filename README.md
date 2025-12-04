# Galleria Frontend

Interfaccia statica per caricare profili con nome, data e immagine. L'app salva i profili sia sul backend (`https://galleria-profilo.onrender.com`) sia in cache locale per tenerli visibili offline.

## Come provarla subito
1. Assicurati di avere Python 3 installato.
2. Avvia un server statico dalla cartella del progetto:
   ```bash
   python -m http.server 8000
   ```
3. Apri il browser su [http://localhost:8000](http://localhost:8000) per usare l'app.

> Se preferisci un'altra porta, sostituisci `8000` e apri l'URL corrispondente.

## Note
- L'endpoint del backend è configurato dentro `index.html` tramite la costante `BASE_URL`.
- Se il backend non è raggiungibile, le immagini restano comunque visibili grazie alla cache locale.
