# Procedura installazione repository e apertura `index.html`

## Passi principali

1. **Aprire il Terminale**

   ```bash
   cd Desktop
   ```

2. **Clonare il repository**

   ```bash
   git clone https://github.com/utente/mia-webapp.git
   ```

3. **Entrare nella cartella del progetto**

   ```bash
   cd mia-webapp
   ```

4. **Visualizzare il contenuto**

   ```bash
   ls
   ```

5. **Entrare nella cartella `src`**

   ```bash
   cd src
   ```

6. **Verificare la presenza del file**

   ```bash
   ls
   ```

   > Risultato atteso: `index.html`

7. **Aprire il file HTML**

   ```bash
   open index.html
   ```

---

## Aperture alternative

**Dalla root del progetto:**

```bash
open src/index.html
```

**Con Google Chrome:**

```bash
open -a "Google Chrome" src/index.html
```

**Con Safari:**

```bash
open -a Safari src/index.html
```

**Con Firefox:**

```bash
open -a Firefox src/index.html
```

**In Visual Studio Code:**

```bash
code .
```

---

## Server locale (opzionale)

Avviare un server HTTP con Python:

```bash
python3 -m http.server 8000
```

Aprire nel browser:

```
http://localhost:8000/src/index.html
```

---

## Procedura veloce

```bash
cd Desktop
git clone URL
cd nome_repo
open src/index.html
```
