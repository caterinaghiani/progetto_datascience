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


## Nota sull'uso di strumenti AI:
- Claude è stato utilizzato come supporto per la scrittura formale in LaTeX del report (sintassi, formattazione di tabelle, inserimento figure e bibliografia)
- Google Gemini è stato utilizzato per assistere la formulazione linguistica e stilistica del testo.
L'analisi dei dati, le scelte metodologiche, l'interpretazione dei risultati e le conclusioni sono opera dell'autrice.




