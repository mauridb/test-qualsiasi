# Docs:
INTRO: git è quello strumento che ci permette di tenere traccia di tutto il nostro codice che noi sviluppiamo durante 
il ciclo di vita del nostro progetto, ci serve in particolar modo per avere uno storico di esso.
HOTKEYWORDS: [repository, branch, master, 'always git status', commit, merge]

## Basic commands:
```
$ git status
``` 
è il comando che andrete a lanciare ogni volta, non c'è un motivo, lanciatelo sempre. 
Vi mostra tutte le informazioni.

```
$ git add 
``` 
a questo punto i file vengo tracciati ci serve per preparare i nostri file ad essere 'committati'. Segue poi il file
o i files che vogliamo tracciare.

```
$ git commit
``` 
Come mette un timbro, un etichetta di quello che è il codice che avete committato. DIFATTI assegnerà un codice
univoco alla situazione in cui si trova il vostro progetto.

```
$ git push
``` 
Boom! OK! State pubblicando il vostro codice su GITHUB.
```
$ git checkout
``` 
La sua funzione principale è quella di spostarsi e muoversi, si può creare un nuovo branch, oppure 
si può scartare tutte le modifiche non ancora tracciate oppure ancora muoversi all'interno della storia del nostro 
codice del progetto.


GIUSTO un esempio Quick and Dirty questo è quello che andrò a fare tra un minuto dopo aver già inizializzato e preparato
la mia repository su GITHUB!!

```git
git status
git add .
git status
git commit -m "Always amazing learning Versioning!"
git status
git push -u origin master
```
Aggiorna su GitHub e divertiti!