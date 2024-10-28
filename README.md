Il file elencostrutture presentava diverse problematiche nell'ordinamento dei dati come email e sito web invertiti, alcuni di questi dati erano presenti nella colonna Località.
Ho svolto una pulizia relativamente approfondita della colonna Località cercando di correggere errori ortografici o eliminando parti del testo come frazione o località avendo notato che erano superflue, in altri casi era inmvece presente l'indirizzo.
Laddove una cella della colonna Località risultava nulla, ho fatto in modo che risultasse la città corrispettiva.
Il punto 2 e 3 erano secondo me necessari per avere dei risultati più precisi possibile.
Ho aggiunto la colonna Nome_univoco in modo da ridurre al minimo la sovrapposizione dei dati nel foglio Ricerca e, laddove c'era comunque un risultato multiplo, ho aggiunto una funzione filtro che mostrasse i vari distinti risultati
Ho aggiunto una colonna indice a prezzimedi ed ho associato i risultati nel file elencostrutture così da associare in Power Pivot l'indice numerico corrispondente alla città.
Ho creato il file aggiuntivo modello_dati_grafico per avere una visuale grafica del risultato della relazione tra prezzimedi ed elecostrutture.
