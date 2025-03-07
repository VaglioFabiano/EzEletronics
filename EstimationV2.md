# Project Estimation - CURRENT
Date: 05/05/2024

Version: V2


# Estimation approach
Consider the EZElectronics  project in FUTURE version (as proposed by your team in requirements V2), assume that you are going to develop the project INDEPENDENT of the deadlines of the course, and from scratch (not from V1)

# Estimate by size
### 
|             | Estimate                        |             
| ----------- | ------------------------------- |  
| NC =  Estimated number of classes to be developed   |              7               |             
|  A = Estimated average size per class, in LOC       |        600                   | 
| S = Estimated size of project, in LOC (= NC * A)    | 4200                         |
| E = Estimated effort, in person hours (here use productivity 10 LOC per person hour)  |  420h                        |   
| C = Estimated cost, in euro (here use 1 person hour cost = 30 euro) | 12600 | 
| Estimated calendar time, in calendar weeks (Assume team of 4 people, 8 hours per day, 5 days per week) |      2.63 week  |               

# Estimate by product decomposition
### 
|         component name    | Estimated effort (person hours)   |             
| ----------- | ------------------------------- | 
| Requirement Document    | 60 | 
| GUI prototype | 38 | 
| Design document | 12 | 
| Code | 270 | 
| Unit tests | 20 | 
| Api tests | 38 |
| Management documents  | 12 |
| ---    | --- |
| Totale | 450 | 



# Estimate by activity decomposition
### 
| Activity name                               | Estimated effort (person hours) |
|----------------------------------------|----------------------------------|
| Intervistare i vari Stakeholders | 4 |
| Definire un documento di gestione | 22 |
| Ricerca dei requisiti | 28 |
| Revisione dei progetti esistenti | 4 |
| Analisi dei requisiti per le interfacce| 4 |
| Compilare un documento requisiti | 4 |
| Incontro di sincronizzazione | 4 |
| Definire le interfacce dell'utente | 4 |
| Progettare le interfacce | 28 |
| Analisi dei requisiti per il codice | 4 |
| Scrivere il codice | 210 |
| Revisione del codice sviluppato| 26 |
| Identificare i test per il codice | 14 |
| Scrivere i test | 26 |
| Eseguire i test | 3 |
| Risoluzione dei problemi generati dai test | 26 |
| Identificare i test per le API | 10 |
| Scrivere i test API | 14 |
| Eseguire i test API | 4 |
| Risuluzione problemi generati dai test API | 14 |
| Revisione del documento di gestione | 4 |
| ---    | --- |
| Totale | 457 |


### Gantt Diagram
File pdf: [Gantt Diagram V2](diagrammi/v2/gantt_diagram_v2.pdf)

File xlsx: [Gantt Diagram V2](diagrammi/v2/gantt_diagram_v2.xlsx)

![Gantt Diagram V2](diagrammi/v2/gantt_diagram_v2.png)

# Summary

Report here the results of the three estimation approaches. The  estimates may differ. Discuss here the possible reasons for the difference

|             | Estimated effort                        |   Estimated duration |          
| ----------- | ------------------------------- | ---------------|
| estimate by size | 420 | 2.63 settimane|
| estimate by product decomposition | 450 | 2.81 settimane |
| estimate by activity decomposition | 457 | 2.85 settimane|

Le tre stime si differenziano nel numero di ore, per via dell'approccio che viene impiegato durante la stima. 

Il primo metodo, riguardante solamente la dimensione del codice, è il più approssimativo perché non scompone le varie fasi di programmazione. Infatti immaginando 600 righe per classe, quindi 4200 totali, si stima un numero di ore pari a 420.

Il secondo approccio scompone il monte ore più nel dettaglio, offrendo una visione più specifica della suddivisione oraria in base alla difficoltà dei task. Con questo tipo di stima si è arrivati ad immaginare 175 person hour.

L'ultimo approccio è il più dettagliato in quanto scompone per attività, questo ci permette di dividere nelle varie fasi dello sviluppo. In questo modo si giunge ad una somma di ore maggiore (457 person hour) derivata dalla maggiore specificità della descrizione dei compiti. 

Si sottolinea che le ore tengono conto di un margine temporale ragionevole all'oscillare dell'efficienza umana. Scendendo maggiormente nel dettaglio il monte ore di conseguenza aumenta.


