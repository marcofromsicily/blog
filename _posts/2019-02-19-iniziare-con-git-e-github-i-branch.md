---
layout: post
title: "Iniziare con Git e GitHub: i branch"
categories: Open Source
---

![git branch](/blog/images/git-branch.jpg)

# I branch 

Questo post è la continuazione di ["Iniziare con Git e GitHub: il workflow personale"](http://marcolombardo.com/blog/open/source/2019/02/18/iniziare-con-git-e-github-il-workflow-personale.html).

Dopo aver visto qual è il flusso di lavoro personale per editare i file di testo e versionarli, adesso impariamo il concetto di "branch".

Un "branch" non è nient'altro che un "ramo" dove vengono salvati i progressi del nostro lavoro. 

Fino ad adesso per salvare il nostro lavoro abbiamo utilizzato un solo ramo chiamato "master", rappresentato nella figura in alto dai pallini di colore blu.

Ma cosa succede se vogliamo fare delle modifiche "sperimentali" al nostro file di testo o ai file del nostro progetto, per fare delle prove senza rovinare il nostro ramo principale?

In questo caso, creiamo un nuovo ramo di sviluppo del progetto, o branch, rappresentato nella figura in alto dai pallini di colore rosso.

Se le modifiche che abbiamo provato in questo ramo sperimentale ci soddisfano, allora possiamo integrare le modifiche del ramo sperimentale nel ramo principale.

Iniziamo!

![Desktop](/blog/images/m-1-desktop.png)

# La nostra cartella

Anzitutto riepiloghiamo il contenuto che abbiamo attualmente nella nostra cartella:

* Una cartella "nascosta" di file .git, da non toccare per nessun motivo, perchè è li che git salva i nostri progressi di lavoro.

* Un file "LICENSE" che contiene la licenza con cui vogliamo rilasciare il nostro lavoro.

* Un file "README" che è il primo file di testo che si inserisce nel progetto, per descriverlo.

* Un file "primofile" che è un file di testo del nostro progetto.

![git branch](/blog/images/m-2-branch.png)

# git branch

Digitiamo il comando "git branch nomebranch" per creare un nuovo ramo di lavoro.

Nel mio caso ho digitato "git branch ramodiprova" perchè senza nessuna fantasia, ho voluto chiamare il nuovo ramo di lavoro "ramodiprova".

Poi ho digitato un "git branch" per avere un elenco di tutti i rami del mio progetto.

![git checkout](/blog/images/m-3-checkout.png)

# git checkout

Adesso digito un "git checkout ramodiprova" per spostare il mio ambiente di lavoro sul "ramodiprova".

Da adesso in poi, tutti i cambiamenti che faccio, saranno salvati solo e soltanto nel "ramodiprova", che è una copia esatta del ramo "master".

Digito un "git branch" per essere sicuro di essere sul "ramodiprova" prima di fare cambiamenti.

![Secondo file](/blog/images/m-4-secondofile.png)

# Secondo file

Adesso che sono nel mio ambiente di lavoro di prova, posso cambiare qualsiasi cosa senza sporcare il ramo "master".

Creo ad esempio un nuovo file di testo chiamato "secondofile" e lo aggiungo al progetto.

Salvo il file con l'editor di testo nella cartella del mio progetto, e mi sposto sul terminale.

![git status](/blog/images/m-5-git-status.png)

# git status

Sul terminale digito un "git status" per capire cosa fare.

Git mi dice che nella mia cartella c'è un nuovo file non tracciato, mi suggerisce di aggiungerlo ai file tracciati usando un "git add". 

![git add](/blog/images/m-6-git-add.png)

# git add

Come suggerito da git, aggiungo il nuovo file al mio progetto digitando un "git add secondofile.md".

Controllo con un "git status" che il mio file sia stato aggiunto a git.

Si, è diventato verde!

Git allora mi suggerisce di fare un salvataggio di versione usando il comando "git commit".

![git commit](/blog/images/m-7-git-commit.png)

# git commit

Digito un 'git commit -a -m "commento al salvataggio" ' per salvare la versione attuale del mio lavoro.

![git log](/blog/images/m-8-git-log.png)

# git log

Adesso digito un "git log" per vedere la storia del mio progetto.

Il mio progetto sul "ramodiprova" adesso si compone di tre salvataggi distinti di versione.

![git checkout](/blog/images/m-9-git-checkout.png)

# git checkout

Mi sposto adesso sul ramo "master", quello che non è stato intaccato dalla modifica sul "ramodiprova" che ho appena fatto.

Per spostarmi digito un "git checkout master".

Successivamente controllo di essere sul ramo giusto con un "git branch".

![cartella](/blog/images/m-10-cartella.png)

# Cartella

Ta-dan! Se adesso riapro la mia cartella di lavoro, il file "secondofile.md" è sparito!

Questo perchè la modifica che ho fatto l'ho salvata sul "ramodiprova" e non nel mio ambiente di lavoro principale "master".

![git log](/blog/images/m-11-git-log.png)

# git log

Se digito il comando "git log" nel mio ramo "master", scoprirò che i salvataggi di versione presenti sono ancora due, e non tre come invece nel "ramodiprova".

![git merge](/blog/images/m-12-git-merge.png)

# git merge

Immaginiamo che sono soddisfatto dei cambiamenti fatti al mio progetto nel "ramodiprova".

Come faccio a riportare i miei progressi dal "ramodiprova" al "master"?

In questo caso, bisogna unire i due rami di lavoro con un "git merge".

Digito un "git branch" per essere sicuro di essere sul ramo corretto, il ramo dentro il quale vorrei integrare i miei cambiamenti, nel mio caso il ramo "master".

Adesso digito "git merge ramodiprova" per integrare nel "master" i cambiamenti fatti nel "ramodiprova".

![git log](/blog/images/m-13-git-log.png)

# git log

Il comando "git log" mi conferma che ora sul "master" è presente un nuovo salvataggio, riportato dal "ramodiprova", ovvero l'aggiunta del secondo file alla mia cartella di lavoro. 

![git branch](/blog/images/m-14-git-branch.png)

# git branch

Per ultimo, se lo vogliamo, possiamo cancellare il "ramodiprova" che avevamo creato, tanto i cambiamenti ormai sono stati integrati nel "master".

Digitiamo quindi un "git branch -d ramodiprova" per cancellare il "ramodiprova".

Controlliamo l'elenco dei nostri branch con un "git branch".

# Il prossimo passo

Il prossimo passo è [imparare a usare la Pull Request](https://marcolombardo.com/blog/open/source/2019/03/13/iniziare-con-git-e-github-la-pull-request.html).
