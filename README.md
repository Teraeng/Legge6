
                                                  #Bluetentacles Irrigation System

` `**Retrofit di Impianti di Automazione per l’Irrigazione con l’Integrazione di Dati Climatici e Ambientali per la Schedulazione Efficiente dell’Irrigazione**

Il sistema di irrigazione “BLUETENTACLES IRRIGATION SYSTEM” nasce da un progetto di ricerca sviluppato dalla società Tera Engineering srl, in partenariato con il Dipartimento Civile ed Ambientale dell’Università di Trento (DICAM) e la Fondazione Edmund Mach di San Michele All’Adige di Trento, con l’obiettivo risolvere due principali tipologie di problematiche

\1) problematica della scarsità della risorsa idrica in agricoltura derivante dai cambiamenti climatici, fenomeno globale che interessa anche il territorio del Trentino; 

\2) esigenza espressa dai Consorzi di Miglioramento Fondiario (CMF) di ottimizzare la gestione degli impianti irrigui a goccia esistenti senza prevedere la sostituzione integrale dell’impianto, ma intervenendo sulla configurazione della schedulazione irrigua. 

Ad oggi, infatti, è prevista una turnazione irrigua oraria che avviene grazie a sistemi di automazione che permettono l’apertura in automatico di idrovalvole di settore senza bisogno di intervento manuale da parte dell’operatore. La turnazione irrigua, decisa dal CMF ad inizio della stagione irrigua, viene però attuata sempre in maniera automatica senza considerare le condizioni meteo-climatiche e la reale necessità di irrigare.

Lo sviluppo della soluzione tecnologica “SmartWat”, acronimo di “Smart Water irrigation system”, ha consentito di mettere a punto un prodotto hardware/software in grado di rispondere a queste necessità. Lo strumento consente infatti di:

- calcolare un consiglio irriguo per le colture di melo e vite (Scenario 1 del Trentino) che tenga conto delle condizioni meteo/climatiche, sia quelle rilevate tramite sensoristica ambientale (stazioni meteorologiche e sensori di umidità del terreno) sia quelle previsionali (modelli meteorologici);
- interfacciarsi con gli impianti irrigui esistenti permettendo all’utente finale di attuare il consiglio irriguo ricevuto dal DSS (Decision Support System).

Il progetto è stato sviluppato nel comune di Terlago di Trento e, in parte, in provincia di Ferrara.

In estrema sintesi il progetto si è posto i seguenti obiettivi realizzativi:

***Sviluppo di modelli meteorologici previsionali quantitativi per l’ottimizzazione del risparmio idrico ed economico attraverso l’integrazione di dati satellitari di umidità del terreno.***

Gli obiettivi raggiunti dai gruppi di ricerca dell’Università di Trento in collaborazione con il personale di Tera engineering sono:

1. ![](Aspose.Words.e05cab09-5564-4b11-b0e4-c6a1651e8c8d.002.png)Il sistema quantitativo di previsione meteorologica focalizzato sul territorio della Provincia di Trento è operativo (meteo.unitn.it) e fornisce due volte al giorno, al mattino e alla sera, previsioni per le 72 ore successive dei parametri utili per l’ottimizzazione delle risorse irrigue per le colture.	
1. ![](Aspose.Words.e05cab09-5564-4b11-b0e4-c6a1651e8c8d.003.png)È stata condotta un’analisi sul potenziale risparmio idrico ottenibile grazie alla pianificazione dell’irrigazione agricola basata sulle condizioni meteorologiche pregresse e attuali. Lo studio è stato realizzato prendendo in considerazione il territorio del Consorzio di Miglioramento Fondiario di Terlago. 
1. È stata condotta un’analisi preliminare sulle metodologie di elaborazione dei dati satellitari utili per la stima delle variabili di interesse per l’ottimizzazione dell’irrigazione.






***Realizzazione della tecnologia e sperimentazione***

1. Adattamento di software esistente e sviluppo di nuove soluzioni software;
1. Adattamento e sviluppo della tecnologia hardware;
1. Individuazione delle aree pilota e installazione di sensori al suolo;
1. Sperimentazione della tecnologia.

Gli obiettivi raggiunti sono:

1. ![](Aspose.Words.e05cab09-5564-4b11-b0e4-c6a1651e8c8d.004.png)Adattamento software per il passaggio da una architettura basata su server locale, da installare e configurare in loco per ogni cliente, ad una architettura con server unico su cloud in grado di comunicare con i dispositivi LoRaWAN in campo e accessibile da remoto in modo sicuro e privato dai diversi clienti attraverso l’interfaccia grafica (Web app “SmartWat”);
1. Adattamento della tecnologia hardware necessaria al controllo e gestione degli impianti irrigui con metodologie di “smart irrigation” (soluzione tecnologica “SmartWat”);
1. Individuazione particelle pilota, campionatura del suolo (caratterizzazione pedologica) e allestimento sperimentale (stazioni meteo, sensori di umidità del suolo, dispositivi hardware del sistema di comunicazione) presso le particelle pilota dello scenario Base di sviluppo del DSS (Trentino);
1. Confronto prestazionale tra tipologie differenti di sensori di umidità del suolo;
1. Redazione di un protocollo prove per la prima e per la seconda campagna sperimentale;
1. Sperimentazione del DSS in uno scenario aggiuntivo durante la seconda campagna sperimentale; lo scenario, caratterizzato da un contesto territoriale differente (pianura), è risultato funzionale per la scalabilità della soluzione tecnologica.


**Realizzazione di un Sistema di Supporto alle Decisioni (DSS) per la schedulazione dell’irrigazione**

Creazione del DSS denominato “SmartWat”, acronimo per *Smart Water Irrigation System*, un sistema di supporto alle decisioni (DSS) finalizzato al calcolo di un consiglio irriguo per la realizzazione di un’irrigazione intelligente ed ottimizzata che tiene conto della variabilità spaziale e temporale delle precipitazioni, dei suoli e dell’umidità del terreno. Il DSS è stato sviluppato utilizzando i risultati ottenuti nei vari obiettivi realizzativi, la formula dell’equazione del bilancio idrico riportata nel Paper 56 della FAO e i parametri agronomici di fabbisogno irriguo delle colture derivanti da bibliografia e da campionamenti del suolo condotti durante la prima campagna di sperimentazione.

All’interno del repository è possibile scaricare i dati relativi a:

- Previsioni meteorologiche ad alta risoluzione sulle aree oggetto di indagine
- Elaborazioni delle immagini satellitari (NDVI e NDWI)
- Raccolta dei dati delle stazioni meteorologiche utilizzate nella sperimentazione

