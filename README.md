# Primo Progetto Visualizzazione delle informazionii

## Consegna:

Crea un file json con dei dati multivariati: ci sono 10 data-cases e ogni data-case ha sei variabili quantitative i cui valori sono tutti positivi. 
In base a questi dati disegna 10 aeroplanini (è sufficiente la silhouette) distribuiti nell'area di disegno come se volassero in formazione. 
Ogni aeroplanino corrisponde ad un data-case e utilizza la variabile 1 e 2 del rispettivo data-case per le coordinate x e y. 
Lo sfondo è azzurro e nell'area di disegno ci sono anche 10 nuvolette bianche.
 Quando l'utente clicca su un aeroplanino con il pulsante sinistro del mouse e il tasto "x" premuto tutti gli aeroplani si muovono verso una nuova configurazione passando dietro alle nuvolette. 
Le coordinate della nuova configurazione sono ricavate dalle variabili 3 e 4 del rispettivo data-case. 
Alla prossima pressione del tasto sinistro del mouse con il tasto "x" premuto gli aeroplanini usano le variabili 5 e 6 per le coordinate e alla prossima ancora tornano alla configurazione iniziale. 
Se invece si tiene premuto il tasto "y", gli aeroplanini si muovono nella configurazione precedente. 
Fai in modo che i cambi di posizione degli aeroplanini avvengano con un'animazione fluida. Usa le scale D3.js 
per mappare l'intervallo dei valori delle variabili (che è arbitrario) sull'intervallo dei valori delle coordinate, che dipende dalla tua interfaccia.

## Per il funzionamento, dopo aver scaricato il repository da github, dalla cartella scaricata avviare il terminale e avviare il server python realizzato tramite il file 'simple-cors-http-server.py' eseguendo il seguente comando:

python simple-cors-http-server.py

(qualora si voglia constatare che, a server pyhton spento, lo script non riesca a recuperare il json dal server, si consiglia, per gli utilizzi successivi al primo, di cancellare la cache del browser)
