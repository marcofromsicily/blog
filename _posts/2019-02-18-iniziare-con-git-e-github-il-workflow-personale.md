---
layout: post
title: "Iniziare con Git e GitHub: il workflow personale"
categories: Open Source
---

![git](/blog/images/git.jpg)

# Git

L’obiettivo di questo post è illustrare un flusso di lavoro personale che si può percorrere per iniziare a lavorare su Git e GitHub.

Innanzitutto, cosa sono Git e GitHub?

Git è un sistema per il controllo di versione.

A tutti sarà capitato di scrivere un file di testo e di nominare e datare il file come la "versione 1.0 del 18/02/2019".

Se il giorno dopo volessimo editare nuovamente il file e salvarlo, allora avremo la "versione 1.1 del 19/02/2019" di quel file.

Per farla breve, Git permette di tener traccia delle varie versioni di un file di testo, e di visualizzare quali cambiamenti sono avvenuti tra una versione e l'altra del file.

I pallini che vedete in alto accanto al logo di Git, non fanno altro che simboleggiare le varie versioni di un file di testo.

![github](/blog/images/git-github.jpg)

# GitHub  

GitHub è un social network, un servizio al pari di Facebook e Twitter.

L'unica differenza tra Facebook e GitHub è che mentre su Facebook gli utenti condividono post personali sulle loro attività, il classico "Buongiornissimo amici, caffè?", su GitHub gli utenti condividono la traccia delle versioni dei loro file di testo.

Come vedete dall'immagine sopra, GitHub non è nient'altro che una esatta copia online delle varie versioni del nostro file di testo che abbiamo editato sul nostro pc personale.

La copia online delle versioni del nostro file di testo può essere accessibile a tutti, oppure solo ai nostri colleghi di lavoro, in base alle impostazioni che utilizziamo per condividere il nostro lavoro.

Un pò come su Facebook si può scegliere di condividere un post solo con gli amici oppure con tutti.

![ATOM](/blog/images/atom.jpg)

# I file di testo

Attenzione: i file di testo di cui si parla in Git sono dei file senza formattazione del testo.

Probabilmente molti di voi sono familiari con editor di testo complessi come Microsoft Word o LibreOffice.

Questi strumenti non vanno bene per la creazione di file di testo per Git perchè aggiungono una formattazione per per la lettura e per la stampa del testo.

I testi elaborati con Word e LibreOffice, ad esempio, possono avere colori diversi, essere grassetti, corsivi, maiuscoli e minuscoli.

Quando si lavora con Git, invece, si utilizza testo puro, senza alcuna formattazione.

Se non sai quale editor di testo utilizzare, ti consiglio di scaricare [ATOM](https://atom.io/) oppure [Visual Studio Code](https://code.visualstudio.com/), entrambi liberi e gratuiti.

![Terminale](/blog/images/terminale.jpg)

# Il Terminale

Il Terminale, tecnicamente noto come [Shell di Bash](https://it.wikipedia.org/wiki/Bash), è la classica modalità di interazione tra utente e computer nei sistemi [Unix](https://it.wikipedia.org/wiki/Unix).

Se avete un bel Mac oppure un pc con Linux: congratulazioni, non dovete installare nulla! 
Troverete il terminale tra i vostri programmi installati, controllate bene tutti i menù.

Se un avete un sistema Windows o un Chromebook, cercate su Google come si installa ed usa un terminale, perchè non verrà descritto in questa guida.

![Nuovo repo](/blog/images/1-nuovo-repo.png)

# Creare un repo su GitHub

Siamo già pronti a sporcarci le mani ed a lavorare!

Entriamo sul nostro profilo [GitHub](https://github.com/) e clicchiamo in alto a destra sul "+" che permette di creare nuovi Repository.

A questo punto basterà inserire questi elementi fondamentali:

* Il nome del repository.
* La descrizione del repository.
* Se il repository è pubblico o privato.
* La spunta per la creazione del primo file di testo del repository, il file README.
* La licenza che vogliamo apporre al nostro lavoro.

![Nuovo repo](/blog/images/2-nuovo-repo.png)

# Il nostro primo repo!

Detto fatto!

Il nostro primo repo è stato creato!

Congratulazioni! Siete attivi su GitHub!

Adesso l'unica cosa che dovete ricordare è la url del vosoro repository, la trovate come sempre in alto, nella barra di navigazione.

![Git Clone](/blog/images/3-git-clone.png)

# git clone

E' arrivato il momento di aprire il terminale e scaricare una copia del repo che abbiamo appena creato online.

Spostiamoci nella cartella dove vorremo scaricare il nostro repo con il comando "cd".

Nel mio caso ho dato il comando "cd Desktop" per spostarmi sul desktop.

Poi ho dato il comando per scaricare il mio repo, la mia cartella di lavoro, digitando "git clone url" (al posto di url, scrivete, ovviamente, la url del vostro repository).

Vi verranno chiesti il vostro nome utente e la vostra password di GitHub, prima che cominci il download.

![Git Desktop](/blog/images/4-git-desktop.png)

# Il repo sul nostro desktop!

A questo punto, sul nostro desktop troveremo la nostra cartella di lavoro.

Aprendola troveremo i seguenti file:

* Il file "README.md", che è il primo file di testo del nostro repository.
* La licenza che vogliamo apporre al nostro lavoro.
* Una cartella nascosta di nome .git, visualizzabile se avete attivato le impostazioni per vedere i file e le cartelle nascoste. 
Se non avete attivato le impostazioni per vedere cartelle e file nascosti, va bene lo stesso. 
Quella cartella .git è il posto in cui git tiene traccia dei cambiamenti di versione del vostro progetto, non va toccata in nessun modo. 

![File Readme](/blog/images/5-readme.png)

# Il file readme

Un bel doppio click sul file "README.md" per aprirlo con l'editor di testo, io uso [Geany](https://www.geany.org/).

Possiamo aggiungere una riga qualunque di prova e salvare il nostro file.

Io ho scritto "Aggiungo questa riga".

![Git Diff](/blog/images/6-git-diff.png)

# git diff

Se adesso torniamo al nostro terminale, digitando il comando "git diff", git ci farà vedere che si è accorto delle modifiche che abbiamo fatto al nostro file di testo.

In particolare, in verde si vede la riga che ho aggiunto al file.

![Git Status](/blog/images/7-git-status.png)

# git status

Digitando in qualsiasi momento il comando "git status", git ci informerà dello stato in cui si trova il nostro progetto.

Nel nostro caso, in rosso, è evidenziato il nome del file che è stato modificato.

![Nuovo File](/blog/images/8-nuovo-file.png)

# Un nuovo file

Tornando adesso all'editor di testo, possiamo creare un nuovo file per il nostro progetto.

Lo chiamiamo ad esempio "primofile.md" e scriviamo dentro una riga a caso, giusto per non lasciarlo vuoto.

![Git Status](/blog/images/9-git-status.png)

# git status

Digitando nuovamente "git status", visualizzeremo che git ha preso atto del fatto che il file "README.md" è stato modificato e che il file "primofile.md" è stato aggiunto al repository.

Li trovate entrambi evidenziati in rosso.

![Git Add](/blog/images/10-git-add.png)

# git add

A questo punto, come suggerito dallo stesso comando "git status", digitiamo un "git add ." per aggiungere tutti i file della nostra cartella di lavoro all'elenco dei file tracciati da git, ovvero l'elenco dei file di cui git fa un controllo di versione.

Digitando nuovamente un "git status" ci accorgeremo che adesso i nomi dei file sono verdi, perchè sono tracciati da git.

![Git Commit](/blog/images/11-git-commit.png)

# git commit

Siamo pronti adesso a salvare una nuova versione del nostro lavoro.

Digitiamo 'git commit -a -m "descrizionedellamodifica" '

Un commit è un salvataggio che diamo al nostro lavoro.

L'opzione -a serve a git per tracciare i file da salvare, come abbiamo già visto in "git add".

L'opzione -m serve a git per accettare il nome che vogliamo dare al salvataggio, descritto tra parentesi.

Nel mio caso ho digitato 'git commit -a -m "aggiunto primofile" ' per descrivere che sto salvando la versione del mio lavoro in cui ho aggiunto il mio primo file. 

![Git Status](/blog/images/12-git-status.png)

# git status

Se adesso digitiamo un "git status" per sapere a che punto è il nostro lavoro, git ci risponderà che la versione della cartella che abbiamo salvato sul nostro pc, ha un salvataggio in più rispetto alla cartella che si trova su GitHub.

![Git Push](/blog/images/13-git-push.png)

# git push

Come suggerito dallo stesso comando "git status", digitiamo adesso un "git push" per far si che il salvataggio presente sul nostro pc personale venga riportato anche sul salvataggio in cloud che abbiamo si GitHub.

Ci verranno richieste nome utente e password per salvare su GitHub.

![Git Log](/blog/images/14-git-log.png)

# git log

Il comando "git log" serve a darci l'elenco di tutte le versioni del nostro lavoro.

Nel nostro caso le versioni del lavoro sono solo due.

* Un "initial commit", il primo salvataggio, che ha un codice numerico 6a80eae7.

* Un "aggiunto primo file" che ha un codice numerico b1da0782

Di entrambi i salvataggi vengono riportati l'autore del lavoro e la data del salvataggio.

![Git Show](/blog/images/15-git-show.png)

# git show

Se adesso voglio vedere nel dettaglio cosa è cambiato all'interno di un salvataggio di versione, posso digitare il comando "git show codicenumerico", indicando quindi il numero del salvataggio.

Nel mio caso digitando "git show b1da0782" 

Come potete leggere in verde, in basso, è riportata la riga che ho aggiunto al file "primofile.md".

![Git Log](/blog/images/16-git-log.png)

# git log

Se adesso voglio vedere lo stesso elenco di tutte le versioni del mio lavoro, mi basta andare su GitHub e cliccare su "commits".

![Git Show](/blog/images/17-git-show.png)

# git show

Cliccando, infine sul commit di un salvataggio, potrò visualizzare le modifiche fatte in quella specifica versione.
