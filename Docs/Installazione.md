Procedura installazione repository e apertura index.html

1.  Aprire Terminale

cd Desktop

2.  Clonare repository

git clone https://github.com/utente/mia-webapp.git

3.  Entrare nella cartella

cd mia-webapp

4.  Visualizzare contenuto

ls

5.  Entrare in src

cd src

6.  Verificare presenza file

ls

Risultato atteso: index.html

7.  Aprire il file HTML

open index.html

Oppure dalla root:

open src/index.html

Aprire con Chrome:

open -a “Google Chrome” src/index.html

Aprire con Safari:

open -a Safari src/index.html

Aprire con Firefox:

open -a Firefox src/index.html

Aprire in VS Code:

code .

Server locale opzionale:

python3 -m http.server 8000

Aprire nel browser:

http://localhost:8000/src/index.html

Procedura veloce:

cd Desktop git clone URL cd nome_repo open src/index.html