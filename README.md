# Calculator 2023 by Enrico Cordero
## Progetto realizzato tra Settembre e Ottobre 2023
Lo scopo del progetto **CALCULATOR** è quello di produrre un clone della calcolatrice di Windows, cercando di rimanere il più fedeli possibile all'originale, sia nell'aspetto del programma, sia nel suo funzionamento.

Gli step sono i seguenti:
1. presa di confidenza con GIT e gli altri strumenti di lavoro
1. creazione del progetto Windows Form .NET
1. realizzazione del codice:
    - creazione dinamica dei pulsanti di comando
    - programmazione comune dell'evento click
    - gestione degli operatori comuni e speciali
    - gestione dei pulsanti di Clear, ClearEntry, Delete e Comma
    - creare una label con l'operazione in corso

### Prontuario dei comandi
* Tramite il comando `git status` è possibile visionare lo stato della directory di lavoro e permette di vedere quali modifiche sono state sottoposte a staging, quali no e quali file non vengono tracciati da Git.<br>
* Tramite il comando `git remote show origin` è possibile visionare l'URL del repository remoto.<br>
* Tramite il comando `git clone https://github.com/.../...` è possibile scaricare la directory in locale da remoto, ma bisogna farlo solo la prima volta. Dalla seconda volta in poi si usa `git pull`.<br>
* Tramite i comandi `git add -A`, `git commit -a -m "Commento"` e `git push` è possibile sincronizzare il repository da locale in remoto
