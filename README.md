# Cookiezappa

Init ambiente per aws-lambda utilizzando Zappa.

## The `zuppa.sh` way

`zuppa.sh` è un wrapper attorno ai comandi di `zappa` per poter far la build della lambda attraverso Docker.

Utilizzando Docker si ha la certezza che gli eventuali packages che richiedono compilazione siano su una distribuzione linux.

## ATTENZIONE

L'esclusione dei pacchetti in `zappa_settings.json` è molto restrittiva, valutare sempre bene se è il caso di utilizzare
un layer oppure andare a rifinire le esclusioni.
