---
layout: post
title: "Open Data Bellissimi"
categories: Open Source
---

# Open Data Bellissimi.

In questo post ho intenzione di raccogliere tutte le cose bellissime che ho visto realizzare agli open datari, in particolare alla comunità di [#opendatasicilia](http://opendatasicilia.it/).

![Open Data](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/opendata.jpg)

## Indice

* [Cultura](#cultura)
* [Amministrazione](#amministrazione)
* [Trasporti](#trasporti)
* [Turismo](#turismo)


### Cultura

La comunità open data, nascendo circa trenta anni dopo la comunità open source, ha una cultura dell'informatica "nativamente" improntata alle architetture informatiche moderne come il cloud computing, il mobile e l'IoT, ecco alcuni esempi:

* Lotta alla "cultura del pdf".

Gli stumenti cloud e mobile oggi a nostra disposizione hanno cambiato il modo in cui possiamo fruire dei dati, il modo in cui possiamo utilizzare l'informatica.

Eppure esiste una pesante "eredità del passato" che spinge ancora le persone ad utilizzare l'informatica come se quello che si vede sullo schermo fosse una semplice trasposizione "uno ad uno" di quello che si fa con la carta.

Il pdf è un formato di file nato per la stampa.

In un passato non troppo lontano l'esigenza di stampare le informazioni era reale, non esistevano dispositivi mobili o connessioni ad internet a tariffa fissa che potessero permettere alle persone di portare sempre con loro i servizi digitali.

Il pdf, garantendo la possibilità di stampare in maniera "universale", con vari sistemi operativi e programmi, è stato per anni un punto di riferimento per la gestione dei documenti, delle mappe, dei biglietti, delle fatture e così via.

Fortunatamente però oggi viviamo in un'era di dispositivi mobili che hanno permesso di fruire ovunque dei servizi digitali.

Queste considerazioni danno senso al post dal titolo ["Gli strumenti digitali e la relativa usabilità - against pdf culture"](https://medium.com/@cirospat/gli-strumenti-digitali-e-la-relativa-usabilit%C3%A0-e7298b325487) che vi invito fortemente a leggere, perchè mostra con un esempio pratico di trasformazione di una [mappa in pdf](http://www.ladomenicafavorita.com/wp-content/uploads/2016/11/Mappa-Fruizione.pdf) in una [mappa interattiva](http://umap.openstreetmap.fr/it/map/la-domenica-favorita-a-palermo-aprile-maggio-2018_134993#14/38.1598/13.3558) il cambio strategico nella fruizione dei servizi digitali necessario oggi.

Il pdf oltre a non essere uno strumento "usabile digitalmente" perchè nasce per la stampa, non permette l'elaborazione dei dati che contiene, come avverrebbe invece se i dati fossero inseriti in un foglio di calcolo o in un database.

Per ovviare a questo problema, l'associazione [Ondata](http://ondata.it/) mette anche a disposizione sul proprio sito web uno [strumento per estrarre dati dai pdf](http://tabula.ondata.it/) per poterli utilizzare nei fogli di calcolo.

* Motore di ricerca di risorse, dati e mappe.

La comunità open data utilizza diffusamente un [motore di ricerca di risorse, dati e mappe](https://github.com/SiciliaHub/nonportaleregionesicilia) che può essere hostato su GitHub.

Il motore di ricerca è stato utilizzato ad esempio per il ["non portale open data"](http://nonportale.opendatasicilia.it/index.html) della Regione Siciliana che ha preceduto la pubblicazione del [portale open data ufficiale](https://dati.regione.sicilia.it/) della regione.

Il motore di ricerca è stato utilizzato anche per [catalogare app, siti web e servizi online](http://petrusino.opendatasicilia.it/) di utilizzo comune, ed un [database di tutorial](http://accussi.opendatasicilia.it/) per imparare vari argomenti legati all'informatica ed all'open data.

Questi motori di ricerca sono la dimostrazione della volontà della comunità open data di portare avanti il lavoro sugli open data anche oltre il supporto che arriva dalle istituzioni, sostituendosi ad esse quando necessario.

* GitHub e "mobile first".

La comunità open data utilizza diffusamente [GitHub come strumento collaborativo](https://github.com/SiciliaHub).

Tutti i siti della comunità sono realizzati secondo il paradigma del "mobile first", ovvero i siti sono disegnati per la fruizione da smartphone e sono visualizzabili anche da desktop, ma la precedenza nel design è data alla fruizione da mobile.

Questo ad esempio è il [sito internet del raduno del 2016 a Messina](https://github.com/SiciliaHub/ods16).


### Amministrazione

Dopo qualche anno di attivismo della comunità, la cultura open data è riuscita ad entrare nelle pubbliche amministrazioni, ecco due esempi:

* Con le [Linee guida open data del Comune di Palermo](http://linee-guida-open-data-comune-palermo.readthedocs.io/it/latest/) si è stabilito il principio per cui i dati sono un servizio pubblico a tutti gli effetti e non una attività che la pubblica amministrazione deve svolgere a caso o in maniera discontinua.
Le linee guida descrivono l'organizzazione interna al Comune che si occupa della pubblicazione degli open data, il processo con cui i cittadini possono richiedere i dati, il formato con il quale i dati devono essere pubblicati.

Le linee guida sono pubblicate sul [Read the docs](http://documenti-comune-palermo.readthedocs.io/it/latest/) del Comune e su [repository GitHub](https://github.com/cirospat/linee-guida-open-data-comune-palermo/blob/master/index.rst), due formati per la visualizzazione interattiva e moderna dei documenti.

* Il [Portale Open Data Comune di Palermo](https://opendata.comune.palermo.it/), realizzato secondo le linee guida nazionali di [design dei siti della pubblica amministrazione](https://designers.italia.it/), permette la segnalazione tramite l'account [GitHub del Comune](https://github.com/ComuneDiPalermo/PortaleOpendata) di eventuali problemi di visualizzazione o di elementi non aderenti agli standard.


### Trasporti

Vediamo adesso due esempi pratici degli effetti della cultura e dell'amministrazione open data nel campo dei trasporti:

* Il Comune rilascia i [dati del trasporto pubblico locale di Palermo](https://opendata.comune.palermo.it/opendata-dataset.php?dataset=1021) in formato [GTFS](https://www.wikiwand.com/it/General_Transit_Feed_Specification).

Il formato GTFS permettendo l'elaborazione dei dati degli orari dei trasporti pubblici e delle relative informazioni geografiche, consente a famose app come [Moovit](https://moovit.com/) e [Google Maps](https://www.google.it/maps) di mostrare agli utenti le informazioni sugli autobus e sui tram di Palermo.

La comunità open data può inoltre realizzare delle [mappe del trasporto pubblico come questa](https://umap.geonue.com/it/map/openamat-trasporti-pubblici-gtfs-palermo-validi-fi_155#12/38.1266/13.3690).

* Il Comune di Palermo realizza un GeoRSS con le [notizie di interesse generale per la città](https://www.comune.palermo.it/feed/rss.xml) ed un GeoRSS con le notizie sulla [mobilità e sul traffico](https://www.comune.palermo.it/feed/rss_pm.xml).

Il [GeoRSS](https://www.wikiwand.com/it/GeoRSS) è un formato di file che permette la rappresentazione di informazioni geografiche tramite un feed RSS, per cui ad esempio è possibile realizzare ed una [mappa in real time degli eventi e delle notizie di Palermo ](https://rawgit.com/aborruso/e40a5ae873d33e690dc9a33f58c557bb/raw/a9b2f9a44f2eb92105ed808cf63f5e4aa2dadae7/georssPA.html) ed una [mappa in real time degli avvisi sulla mobilità della città di Palermo](http://umap.openstreetmap.fr/it/map/avvisi-della-polizia-municipale-sulla-mobilita-a-p_135416#13/38.1518/13.3547).

### Turismo  

Concludo questa panoramica sugli open data bellissimi con due esempi di utilizzo degli open data ai fini turistici:

* Il Comune di Palermo pubblica un [dataset in formato XML dei luoghi d'interesse della città](https://www.comune.palermo.it/xmls/VIS_DATASET_TURISMO03.xml), che include i cenni storici sui monumenti, gli orari di apertura e la loro posizione geografica.

Questo dataset ha permesso la realizzazione di una [mappa dei luoghi di interesse turistico a Palermo](https://umap.geonue.com/it/map/luoghi-di-interesse-turistico-a-palermo_195#13/38.1859/13.3737)

* La Regione Siciliana pubblica un file JSON con i [dati delle strutture alberghiere in Sicilia](https://dati.regione.sicilia.it/dataset/strutture-ricettive).

Questi dati [georeferenziati](https://www.wikiwand.com/it/Georeferenziazione) hanno permesso la realizzazione di un [bot Telegram](https://telegram.me/dovedormireinsicilia_bot) per la ricerca di strutture ricettive suddivise per città.
