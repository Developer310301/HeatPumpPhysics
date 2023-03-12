# HeatPump Physics
Questa applicazione aiuta a svolgere i calcoli delle **entalpie** e del **COP** (Coefficient Of Performace) delle pompe di calore.
## Utilizzo
### Inserimento dati
L'applicazione, alla sua apertura, presenta una tabella dove è possibile inserire i valori di **temperatura**, **pressione**, **portata massica** e **assorbimento**.  Le colonne invece delle entalpie e del COP non sono editabili manualmente perchè sono colonne che vengono calcolate automaticamente. Una volta definiti i dati nella tabella si può procedere al calcolo delle entalpie e del COP selezionando il fluido desiderato (menu tendina a destra) e successivamente premendo sul pulsante in basso a destra **"Calcola Valori"**.
Alla tabella si possono aggiungere e rimuovere righe premendo, rispettivamente, sui pulsanti **Aggiungi Riga** e **Rimuovi Riga**. Per poter rimuovere le righe, si deve selezionare la riga o le righe (basta selezionare una riga e poi con Shift+Freccia Giù/Su) e poi premere sul corrispettivo pulsante.
### Import/Export dati
L'applicazione presenta inoltre la possibilità di importare ed esportare i dati in formato **CSV**.
#### Formato dei dati
Per poter essere importati correttamente il file CSV deve presentare alcune caratteristiche:

 - Devono esserci almeno 6 colonne (2 per la temperatura, 2 per la pressione, 1 per la portata massica e 1 per l'assorbimento)
 - Nel file può essere presente una e una sola riga di intestazione e una e una sola colonna che identifica la riga (nel caso abbia questa caratteristica vedere in seguito come proseguire l'importazione)
 - I dati importati devono essere dei numeri (in caso contrario apparirà un messaggio d'errore)
 - I separatori CSV supportati (e rilevati automaticamente) sono: **";"** (punto e virgola), **","** (virgola), **"\t"** (tabulazione).

#### Import dei dati
Se il file da importare presenta le caratteristiche descritte precedentemente basterà premere sul pulsante a destra **"Carica dati"** (oppure dal menu **File>Apri File Dati** o la shortcut **Ctrl + O**) e selezionare il file prescelto. Automaticamente l'applicazione caricherà i dati rilevando l'opportuno separatore.
Se il file da importare presenta una riga di intestazione cliccare sulla checkbox **File con intestazione**.
Se invece il file da importare presenta una prima colonna di identificativo di riga (come ad esempio una data o un numero progressivo) cliccare sulla checkbox **Ignora la prima colonna**.
#### Export dei dati
Per poter esportare i dati basterà cliccare sul pulsante **"Salva dati"** (oppure dal menu **File>Salva File Dati** o la shortcut **Ctrl+S**) e verrà chiesto all'utente il nome del file e la cartella dove salvarlo. Il formato di esportazione dei dati è il **CSV**.
### Graficazione dei dati
L'applicazione permette di visualizzare sottoforma di grafico i dati inseriti premendo sul pulsante **"Graficazione dati"** (oppure con la shortcut **Ctrl+G**). Per poter visualizzare i dati che si desiderano, basta cliccare sulla checkbox del corrispettivo dato che si intende visualizzare.
#### Zoom del grafico
Tenendo premuto la rotella centrale del mouse e trascinandola è possibile effettuare uno zoom sulla zona interessata.
#### Pan del grafico
Tenendo premuto il tasto sinistro del mouse è possibile spostarsi nel grafico zoommato.
#### Menu a tendina
Premendo il tasto destro del mouse si può accedere a un menù a tendina che permette di esportare il grafico sottoforma di immagine o di resettare lo zoom del grafico.

## Shortcut
|Shortcut|Azione|
|--|--|
|Ctrl+O|Apre un file CSV per l'import dei dati|
|Ctrl+S|Salva i dati correnti in formato CSV|
|Ctrl+X|Calcola i valori delle entalpie e del COP|
|Ctrl+G|Apre la visualizzazione del grafico|

## Bug Report e Suggerimenti
Per poter riportare bug dell'applicazione o suggerimenti per ulteriori sviluppi aprire un task alla pagina [Github](https://github.com/Developer310301/HeatPumpPhysics/issues)
