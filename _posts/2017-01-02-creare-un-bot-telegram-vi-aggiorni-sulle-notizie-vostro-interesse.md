---
title: Come creare un bot Telegram che vi aggiorni sulle notizie di vostro interesse?
date: 2017-01-02
layout: post
permalink: /creare-un-bot-telegram-vi-aggiorni-sulle-notizie-vostro-interesse/
spacious_page_layout:
  - default_layout
categories:
  - Informatics
tags:
  - Bot
  - DigitalRende
  - Rende
  - Telegram
---
<!--:it-->

<p style="text-align: center;">
  <a href="https://telegram.org/" target="_blank">Telegram</a> è un&#8217;applicazione di messaggistica istantanea utilizzabile via <a href="https://telegram.org/" target="_blank">Web </a>oppure scaricandola sul proprio smartphone.
</p>

![Telegram logo](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/telegram.jpg)

<p style="text-align: center;">
  Telegram permette la creazione di bot, semplici programmi che offrono le loro funzionalità agli utenti via chat.
</p>

<p style="text-align: center;">
  Uno dei più elementari bot realizzabili in autonomia con Telegram è una raccolta di notizie di vostro interesse.
</p>

<p style="text-align: center;">
  Vediamo ad esempio i passi tramite cui ho realizzato il bot <span style="color: #ff0000;"><a style="color: #ff0000;" href="http://telegram.me/DigitalRendebot" target="_blank">@DigitalRendebot</a></span>, una raccolta di notizie sull&#8217;ecosistema IT della città Calabrese di <a href="https://it.wikipedia.org/wiki/Rende" target="_blank">Rende</a>, sede dell&#8217;<a href="http://www.unical.it/" target="_blank">Università della Calabria</a>.
</p>

<p style="text-align: center;">
  Per prima cosa accedete a Telegram e cercate l&#8217;utente <span style="color: #0000ff;">@BotFather</span>.
</p>

![Bot father](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/botfather.jpg)

<p style="text-align: center;">
  Iniziate a chattare con BotFather inviando il comando <span style="color: #800080;">/newbot.</span>
</p>

<p style="text-align: center;">
  BotFather vi chiederà prima il nome che volete dare al vostro bot, nel nostro caso &#8216;<span style="color: #800080;">DigitalRende</span>&#8216;.
</p>

<p style="text-align: center;">
  Poi BotFather vi chiederà il nome utente che volete dare al vostro bot.
</p>

<p style="text-align: center;">
  Il nome utente deve dempre concludersi con la parola bot, quindi scegliamo &#8216;<span style="color: #800080;">DigitalRendebot</span>&#8216;.
</p>

<p style="text-align: center;">
  A questo punto BotFather restituirà la password con la quale è possibile controllare il bot.
</p>

![Bot father](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/botfatheruno.jpg)


<p style="text-align: center;">
  Continuiamo a chattare con BotFather, digitiamo il comando <span style="color: #800080;">/setuserpic</span> per dare un&#8217;immagine del profilo al nostro bot.
</p>

<p style="text-align: center;">
  BotFather chiederà semplicemente di inviare un&#8217;immagine da usare come foto del profilo.
</p>

![Bot father due](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/botfatherdue.jpg)


<p style="text-align: center;">
  Adesso sempre su Telegram, cercate l&#8217;utente <span style="color: #0000ff;">@Manybot</span>.
</p>

<p style="text-align: center;">
  Manybot è un semplicissimo strumento che vi permetterà di implementare delle funzionalità di base del vostro bot, come nel nostro caso leggere il <a href="https://it.wikipedia.org/wiki/RSS" target="_blank">feed RSS</a> di un sito web oppure l&#8217;account Twitter ed avvisarvi con una notifica push sulla pubblicazione di contenuti di vostro interesse.
</p>

![Many bot](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/manybot.jpg)


<p style="text-align: center;">
  Una volta aperta la chat con <span style="color: #0000ff;">@Manybot</span> clicchiamo sul pulsante &#8216;<span style="color: #800080;">Crea un nuovo Bot</span>&#8216;.
</p>

![Many bot](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/manybotuno.jpg)


<p style="text-align: center;">
  Poi clicchiamo sul bottone &#8216;<span style="color: #800080;">Ho copiato la chiave API&#8217;</span>.
</p>

![Many bot](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/manybotdue.jpg)


<p style="text-align: center;">
  Adesso incolliamo la chiave API, si tratta della password che ci aveva fornito <span style="color: #0000ff;">@BotFather</span> quando abbiamo creato il bot.
</p>

<p style="text-align: center;">
  Se non la ricordate, potete semplicemente ritornare alla chat con <span style="color: #0000ff;">@BotFather</span> e copiarla da li.
</p>

<p style="text-align: center;">
  Come ultimo passo @Manybot ci chiederà di inserire una breve descrizione di cosa fa il nostro bot.
</p>

<p style="text-align: center;">
  Scriviamo la descrizione &#8216;<span style="color: #800080;">News ed eventi all&#8217;ecosistema digitale di Rende</span>&#8216; e premiamo invio.
</p>

![Chat bot](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/chatbot.jpg)


<p style="text-align: center;">
  A questo punto apriamo il nostro bot.
</p>

![Chat bot](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/chatbotuno.jpg)


<p style="text-align: center;">
  Dal menù principale clicchiamo su &#8216;<span style="color: #666699;">impostazioni</span>&#8216;.
</p>

![Chat bot](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/chatbotdue.jpg)


<p style="text-align: center;">
  Poi clicchiamo su &#8216;<span style="color: #666699;">Autoposting</span>&#8216;.
</p>

![Chat bot](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/chatbottre.jpg)


<p style="text-align: center;">
  Successivamente clicchiamo su &#8216;<span style="color: #666699;">+ RSS feed</span>&#8216;.
</p>

![Chat bot](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/chatbotquattro.jpg)


<p style="text-align: center;">
  Adesso troviamo il feed RSS di un sito che pubblica notizie rilevanti per noi, il feed potrebbe essere rappresentato dall&#8217;icona dell&#8217;RSS.
</p>

![Logo rss](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/rss.jpg)


<p style="text-align: center;">
  Oppure potrebbe essere nascosto dentro la pagina web.
</p>

<p style="text-align: center;">
  Nel caso sia nascosto clicchiamo col tasto destro del mouse sul sito web e selezioniamo &#8216;<span style="color: #666699;">Visualizza sorgente pagina</span>&#8216;.
</p>

![Hacklab Home](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/hacklabhome.jpg)


<p style="text-align: center;">
  Digitiamo &#8216;<span style="color: #666699;">ctrl + F</span>&#8216; per aprire la casella di ricerca e cerchiamo la parola &#8216;<span style="color: #666699;">rss</span>&#8216;.
</p>

<p style="text-align: center;">
  Abbiamo trovato la url del feed RSS, che in questo caso è <a href="https://hlcs.it/feed/" target="_blank">https://hlcs.it/feed/ </a>
</p>

![Hacklab sorgente](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/hacklabsorgente.jpg)


<p style="text-align: center;">
  Torniamo a chattare col nostro bot per <span style="color: #666699;">incollare la ulr</span> del feed RSS.
</p>

<p style="text-align: center;">
  Abbiamo finito la configurazione del bot, che ci aggiornerà in automnatico ogni volta che il sito da noi scelto pubblica una notizia.
</p>

![Chat bot](https://raw.githubusercontent.com/marcofromsicily/blog/master/images/chatbotcinque.jpg)
