---
layout: post
title: "Iniziare con Git e GitHub: importare i commit"
categories: Open Source
---

![git importare i commit](/blog/images/git-github.jpg)

# Importare i commit

Quarto ed ultimo blog post dedicato a Git e GitHub.

Dopo aver visto la [Pull Request](https://marcolombardo.com/blog/open/source/2019/03/13/iniziare-con-git-e-github-la-pull-request.html), vediamo come importare i commit.

Immaginiamo di forkare un repository per creare un ramo di sviluppo su cui applicare le nostre modifiche personali ad un progetto open source.

Se il progetto open source "originale" prosegue il suo sviluppo, potrebbe essere opportuno o necessario di tanto in tanto aggiornare il nostro repository con le modifiche che sono state fatte sul repository originale.

# Controlliamo i remote

Per prima cosa, usiamo il comando 

git remote -v

per vedere quale repository remoto è associato al repository con cui stiamo lavorando in locale sulla nostra macchina client.

![git remote -v](/blog/images/r-git-remote-v.jpg)

Il nome "origin" è associato al nostro repository "personale" remoto, quello che abbiamo forkato su GitHub dal progetto "originale" open source.

Per aggiungere come repository remoto il progetto "originale" open source, dobbiamo usare il comando

git remote add upstream urldelrepository

![git remote add upstream](/blog/images/r-git-remote-add-upstream.jpg)

Il nome "upstream" è associato al repository del progetto open source "originale".

# Importiamo i commit

Digitando il comando 

git log 

vediamo che l'ultimo commit è stato fatto sul master da noi stessi.  

Il commit precedente invece era stato fatto da Mark Otto il 25 Aprile

![git log](/blog/images/r-git-log.jpg)

Digitiamo il comando 

git fetch upstream master

![git fetch](/blog/images/r-git-fetch.jpg)

git ha aggiunto un nuovo branch, evidenziato appunto dalla dicitura "new branch".

Per visualizzare i commit del branch master e del nuovo branch, digitiamo il comando

git log --all

![git log --all](/blog/images/r-git-log--all.jpg)

Come possiamo vedere dal log, l'ultimo commit adesso risulta fatto da XhmikosR e non più da Marco Lombardo.

Il commit precedente a quello fatto da Marco Lombardo risulta fatto da MartijnCuppens il 02 Giugno e non più il 25 Aprile da Mark Otto.

Questo log è la conferma che nel nuovo branch sono stati scaricati nel nostro computer locale i cambiamenti del progetto open source originale "upstream".


# Uniniamo i cambiamenti importati nel master

Digitiamo il comando

git checkout master

per essere sicuri di essere sul ramo master.

Poi digitiamo il comando 

git merge upstream/master

per unire i cambiamenti del nuovo ramo appena scaricato dal repository "upstream" con i commit del nostro master.

![git merge](/blog/images/r-git-merge.jpg)

Si aprirà un edito di testo per dare un nome al commit.

![gnu nano](/blog/images/r-gnu-nano.jpg)

git confermerà che il merge è completato.

![git auto merging](/blog/images/r-git-auto-merging.jpg)

Digitiamo il comando 

git log 

per l'ultima volta per visualizzare la storia del nostro ramo master, che adesso include un merge con dei commit importati dal repository "upstream". 

![git log finale](/blog/images/r-git-log-finale.jpg)

# Fine

Con questo blog post si conclude la mia guida a git e github.

Buon lavoro!
