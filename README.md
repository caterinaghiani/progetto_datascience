# Analisi del Rischio di Default

## Descrizione del progetto
Analisi del rischio di credito dei clienti di una banca, con l'utilizzo di modelli predittivi per classificare in anticipo i clienti a rischio di insolvenza.

## Descrizione del dataset
Dataset fornito da una banca: 30.000 clienti, 24 feature. 
Variabile target sbilanciata: 78% solvibili e 22% in default. 

## Obiettivo
Prevedere se un cliente andrà in default sul pagamento del mese successivo, analizzando il suo profilo demografico e finanziario.

## Modelli usati
- regressione logistica
- k-Nearest Neighbour (k = 21)
- random forest (200 alberi)
Feature aggiunta: `UTILIZATION_RATIO` utilizzo del credito in %

*Risultato migliore* ottenuto con random forest, per la recall più alta, utile a minimizzare i falsi negativi. 





