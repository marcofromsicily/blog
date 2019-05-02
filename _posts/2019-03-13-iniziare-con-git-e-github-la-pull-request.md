---
layout: post
title: "Iniziare con Git e GitHub: la Pull Request"
categories: Open Source
---

![git pull request](/blog/images/git-github.jpg)

# La pull request

Dopo aver visto come realizzare [un workflow personale](http://marcolombardo.com/blog/open/source/2019/02/18/iniziare-con-git-e-github-il-workflow-personale.html) ed [i branch](https://marcolombardo.com/blog/open/source/2019/02/19/iniziare-con-git-e-github-i-branch.html), in questo post vedremo la "Pull Request".

La "Pull Request" è una nostra richiesta, fatta all'autore originale di un sofware o di un documento, di includere le nostre personali modifiche al suo progetto.

Iniziamo!

![Branch](/blog/images/github-1p.png)

# Creiamo un branch

Per prima cosa, usiamo il comando "git branch" per creare un nuovo branch nel quale salveremo le nostre personali modifiche.

Quando importiamo i progetti di altre persone, infatti, il ramo principale del progetto, spesso chiamato "master", appartiene all'autore originale del software.

Dobbiamo quindi creare un nostro ramo per lavorare.

Usiamo il comando "git checkout" per spostarci sul nuovo ramo di lavoro appena creato.

![Editare il file](/blog/images/github-2p.png)

# Editiamo il file

Apriamo il file che vogliamo modificare ed appprtiamo i cambiamenti che più ci piacciono.

Salviamo il file dal menù dell'editor di testo, come faremmo con qualsiasi documento.

![Committiamo il file](/blog/images/github-3p.png)

# Committiamo il file

Diciamo a git di tracciare il cambiamento che abbiamo appena fatto, creando un nuovo commit.

Usiamo il comando "git commit -a -m 'nome modifiche' " per salvare la nuova versione del nostro documento. 

![Inviamo le modifiche a GitHub](/blog/images/github-4p.png)

# Inviamo le modifiche a GitHub

Adesso che le modifiche sono correttamente salvate nel nostro computer personale, possiamo creare una copia del nostro nuovo ramo di sviluppo su GitHub.

Usiamo il comando "git push --set-upstream -origin nomeramo" per inviare il nuovo ramo di sviluppo a GitHub.

Nota che si tratta di un comando abbastanza complicato da ricordare a memoria.

Git però viene in nostro aiuto, basterà quindi semplicemente ricordare il comando classico "git push" per ricevere da git un messaggio di errore che contiene l'indicazione sulla sintassi esatta del comando da usare. 

![Apriamo GitHub](/blog/images/github-5p.png)

# Apriamo GitHub

Apriamo GitHub e noteremo la presenza di un nuovo tasto verde dal titolo "Compare & Pull request".

Questo tasto ci permette di mettere a confronto il nostro ramo di sviluppo col ramo di sviluppo "principale o originario" del software o del documento.

![Due branch](/blog/images/github-6p.png)

# Due Branch

Nella casella a sinistra noteremo la possibilità di visualizzare due branch: il ramo di sviluppo "principale" del progetto ed il nostro ramo di sviluppo che contiene le modifiche.

![Pull request](/blog/images/github-7p.png)

![Pull request](/blog/images/github-8p.png)

# Apriamo una pull request

Cliccando su "Compare & Pull request" giungiamo ad una schermata nella quale possiamo descrivere allo sviluppatore originale del progetto i cambiamenti che abbiamo fatto nel nostro ramo di sviluppo.

I cambiamenti sono comunque visibili in basso, dove si possono notare le righe aggiunte e quelle cancellate nei file.

![Accettare la Pull request](/blog/images/github-9p.png)

# Accettare una pull request

A questo punto, lo sviluppatore originario del progetto può rispondere alla nostra pull request, accettando o negando l'unione di due rami di sviluppo e commentando il nostro lavoro.

![Pull request accettata](/blog/images/github-10p.png)

# Pull request accettata

Se una pull request viene accettata, è possibile cancellare il ramo di sviluppo che non ci serve più, quello nel quale avevamo inserito le nostre personali modifiche, e tenere solo il ramo di sviluppo principale, quello nel quale le nostre modifiche sono state integrate.

La cancellazione di un ramo di sviluppo è comunque un'operazione del tutto facoltativa e per nulla obbligatoria.

Se un ramo di sviluppo ci serve, semplicemente possiamo tenerlo.

![Git Pull](/blog/images/github-11p.png)

# Git pull

Una volta uniti su GitHub due rami di sviluppo tramite un merge, possiamo scaricare sul nostro pc personale i cambiamenti che sono avvenuti su GitHub utilizzando il comando "git pull".

![Git log](/blog/images/github-12p.png)

# Git log

Il comando "git log" ci mostrerà come sul ramo di sviluppo principale siano state integrate le modifiche del ramo di sviluppo secondario, tramite un commit che contiene l'indicazione "merge pull request".

![Forkare un repo](/blog/images/github-13p.png)

# Forkare un repo

Hey, aspetatte un attimo, non avete notato nulla di strano fino ad ora?

Nelle immagini precedenti, ho mostrato di aver fatto una pull request, e di averla accettata io stesso.

Questo perchè non volevo disturbare altre persone solo per fare vedere come si fa e come si accetta una pull request.

Normalmente però, l'integrazione di modifiche tramite la pull request si richiede agli sviluppatori di  progetti non "nostri".

Troviamo quindi un altro progetto, come ad esempio il tema bootstrap mostrato nell'immagine.

Clicchiamo sul tasto "Fork" in alto a destra.

![Forkare un repo](/blog/images/github-14p.png)

![Repo Forkato](/blog/images/github-15p.png)

# Repo Forkato

Il tasto fork creerà una copia del progetto sul nostro profilo personale di GitHub.

Di questa copia del progetto non potremo toccare il ramo "master", perchè appartiene agli sviluppatori originari del progetto.

Possiamo però creare un nostro branch per fare le modifiche che più ci piacciono.

![Git clone](/blog/images/github-16p.png)

# Git clone

Scarichiamo il progetto sul nostro computer personale usando il comando "git clone".

![Git Branch](/blog/images/github-17p.png)

# Git branch

Come sopra, usiamo il comando "git branch" per creare un nuovo ramo del progetto, ed il comando "git checkout" per spostarci sul nuovo ramo.

![Editiamo il file](/blog/images/github-18p.png)

# Editiamo il file

Apriamo l'editor di testo ed editiamo il file con le modifiche che ci sembrano più opportune.

Salviamo dal menù dell'editor di testo.

![Git push](/blog/images/github-19p.png)

# Git push

Digitiamo un "git status" per capire a che punto si trova il nostro progetto.

Git risponderà che un file è stato modificato.

Usiamo il comando "git commit -a -m 'nome modifiche' " per salvare la nuova versione del nostro documento. 

Usiamo il comando "git push --set-upstream -origin nomeramo" per inviare il nuovo ramo di sviluppo a GitHub.


![Pull request](/blog/images/github-20p.png)

![Pull request](/blog/images/github-21p.png)

# Pull request

Andiamo su GitHub e clicchiamo il pulsante "Compare & Pull request" per avviare agli sviluppatori originari del progetto una richiesta di integrazione del nostro ramo.

Descriviamo i cambiamenti che abbiamo fatto e inviamo la Pull Request.

Aspettiamo di sapere se la richiesta viene accettata o meno.

# Il prossimo passo

L'ultima parte della guida è dedicata a[importare commit dai progetti open source che abbiamo forkato](https://marcolombardo.com/blog/open/source/2019/05/02/iniziare-con-git-e-github-importare-i-commit.html).


