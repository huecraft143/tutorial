# GIT ISTRUZIONI PER L'USO

1. ## **Serie di comandi BASH per inizializzare un repo git in locale e pushare** (DA ***<u>GIT BASH</u>***, nella ***<u>cartella del REPO GIT </u>***)

* **CREO IL REPO** -> git init

* **AGGIUNGO I MIEI FILE NELLA STAGING AREA** (*Il punto sta per "tutti i file"*) -> git add .

* **FACCIO IL COMMIT** -> git commit -m "**MESSAGGIO DI COMMIT**"

* **CREO IL BRANCH *MAIN* E MI CI SPOSTO DENTRO**  -> git branch -M main

* **SETTO L'ORIGIN**  -> git remote set-url origin ***linkdelrepo***

* **IMPOSTO GIT IN MODO CHE SALVI LE MIE CREDENZIALI** -> git config credential.helper store

2. ## Generare un access token su **github**

* Aprire **[questo](https://github.com/settings/personal-access-tokens/new)** link

* Selezionare **Expiration** -> **Custom** e mettete il valore massimo possibile (*Non vi       chiederà il token per un anno dalla sua creazione*)

* Copiarlo 

3. ## Push sull'origin

Se hai fatto tutto bene fino ad ora...

* **FACCIO IL PUSH** -> git push origin main

* **INSERISCO LE CREDENZIALI**

*  username -> username di git

* password -> **Il token recuperato al punto 2**



# Recuperare repository remoti di altri utenti
* **_SCARICO IL REPOSITORY DA GITHUB_** -> git clone ***linkdelrepo***
* **_AGGIORNO IL MIO REPO LOCALE CON L'ULTIMA "VERSIONE" (ULTIMO COMMIT) DEL REPO REMOTO_** -> git pull
