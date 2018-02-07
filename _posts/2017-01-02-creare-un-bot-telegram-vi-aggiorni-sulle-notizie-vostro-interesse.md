---
id: 3374
title: Come creare un bot Telegram che vi aggiorni sulle notizie di vostro interesse?
date: 2017-01-02T18:12:45+00:00
author: businessinformatics
layout: post
guid: http://www.businessinformatics.it/wordpress/?p=3374
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

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2016/01/Telegram_logo.svg_.png"><img class="alignnone size-full wp-image-3126" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2016/01/Telegram_logo.svg_.png" alt="" width="512" height="512" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2016/01/Telegram_logo.svg_.png 512w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2016/01/Telegram_logo.svg_-150x150.png 150w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2016/01/Telegram_logo.svg_-300x300.png 300w" sizes="(max-width: 512px) 100vw, 512px" /></a>
</p>

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

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-15.55.01.png"><img class="alignnone size-full wp-image-3375" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-15.55.01.png" alt="" width="312" height="148" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-15.55.01.png 312w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-15.55.01-300x142.png 300w" sizes="(max-width: 312px) 100vw, 312px" /></a>
</p>

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

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-15.57.51.png"><img class="alignnone size-full wp-image-3376" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-15.57.51.png" alt="" width="802" height="427" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-15.57.51.png 802w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-15.57.51-300x160.png 300w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-15.57.51-768x409.png 768w" sizes="(max-width: 802px) 100vw, 802px" /></a>
</p>

<p style="text-align: center;">
  Continuiamo a chattare con BotFather, digitiamo il comando <span style="color: #800080;">/setuserpic</span> per dare un&#8217;immagine del profilo al nostro bot.
</p>

<p style="text-align: center;">
  BotFather chiederà semplicemente di inviare un&#8217;immagine da usare come foto del profilo.
</p>

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.00.19.png"><img class="alignnone size-full wp-image-3377" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.00.19.png" alt="" width="806" height="578" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.00.19.png 806w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.00.19-300x215.png 300w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.00.19-768x551.png 768w" sizes="(max-width: 806px) 100vw, 806px" /></a>
</p>

<p style="text-align: center;">
  Adesso sempre su Telegram, cercate l&#8217;utente <span style="color: #0000ff;">@Manybot</span>.
</p>

<p style="text-align: center;">
  Manybot è un semplicissimo strumento che vi permetterà di implementare delle funzionalità di base del vostro bot, come nel nostro caso leggere il <a href="https://it.wikipedia.org/wiki/RSS" target="_blank">feed RSS</a> di un sito web oppure l&#8217;account Twitter ed avvisarvi con una notifica push sulla pubblicazione di contenuti di vostro interesse.
</p>

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.19.46.png"><img class="alignnone size-full wp-image-3378" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.19.46.png" alt="" width="523" height="286" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.19.46.png 523w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.19.46-300x164.png 300w" sizes="(max-width: 523px) 100vw, 523px" /></a>
</p>

<p style="text-align: center;">
  Una volta aperta la chat con <span style="color: #0000ff;">@Manybot</span> clicchiamo sul pulsante &#8216;<span style="color: #800080;">Crea un nuovo Bot</span>&#8216;.
</p>

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.08.14.png"><img class="alignnone size-full wp-image-3379" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.08.14.png" alt="" width="811" height="105" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.08.14.png 811w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.08.14-300x39.png 300w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.08.14-768x99.png 768w" sizes="(max-width: 811px) 100vw, 811px" /></a>
</p>

<p style="text-align: center;">
  Poi clicchiamo sul bottone &#8216;<span style="color: #800080;">Ho copiato la chiave API&#8217;</span>.
</p>

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.08.25.png"><img class="alignnone size-full wp-image-3380" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.08.25.png" alt="" width="812" height="289" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.08.25.png 812w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.08.25-300x107.png 300w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.08.25-768x273.png 768w" sizes="(max-width: 812px) 100vw, 812px" /></a>
</p>

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

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.09.23.png"><img class="alignnone size-full wp-image-3381" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.09.23.png" alt="" width="804" height="381" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.09.23.png 804w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.09.23-300x142.png 300w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2016-12-30-alle-16.09.23-768x364.png 768w" sizes="(max-width: 804px) 100vw, 804px" /></a>
</p>

<p style="text-align: center;">
  A questo punto apriamo il nostro bot.
</p>

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.54.43.png"><img class="alignnone size-full wp-image-3383" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.54.43.png" alt="" width="542" height="259" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.54.43.png 542w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.54.43-300x143.png 300w" sizes="(max-width: 542px) 100vw, 542px" /></a>
</p>

<p style="text-align: center;">
  Dal menù principale clicchiamo su &#8216;<span style="color: #666699;">impostazioni</span>&#8216;.
</p>

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.31.png"><img class="alignnone size-full wp-image-3385" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.31.png" alt="" width="814" height="313" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.31.png 814w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.31-300x115.png 300w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.31-768x295.png 768w" sizes="(max-width: 814px) 100vw, 814px" /></a>
</p>

<p style="text-align: center;">
  Poi clicchiamo su &#8216;<span style="color: #666699;">Autoposting</span>&#8216;.
</p>

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.47.png"><img class="alignnone size-full wp-image-3386" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.47.png" alt="" width="818" height="307" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.47.png 818w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.47-300x113.png 300w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.47-768x288.png 768w" sizes="(max-width: 818px) 100vw, 818px" /></a>
</p>

<p style="text-align: center;">
  Successivamente clicchiamo su &#8216;<span style="color: #666699;">+ RSS feed</span>&#8216;.
</p>

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.58.png"><img class="alignnone size-full wp-image-3387" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.58.png" alt="" width="807" height="203" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.58.png 807w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.58-300x75.png 300w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-17.53.58-768x193.png 768w" sizes="(max-width: 807px) 100vw, 807px" /></a>
</p>

<p style="text-align: center;">
  Adesso troviamo il feed RSS di un sito che pubblica notizie rilevanti per noi, il feed potrebbe essere rappresentato dall&#8217;icona dell&#8217;RSS.
</p>

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/rss_512.png"><img class="alignnone size-full wp-image-3388" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/rss_512.png" alt="" width="512" height="512" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/rss_512.png 512w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/rss_512-150x150.png 150w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/rss_512-300x300.png 300w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/rss_512-270x270.png 270w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/rss_512-230x230.png 230w" sizes="(max-width: 512px) 100vw, 512px" /></a>
</p>

<p style="text-align: center;">
  Oppure potrebbe essere nascosto dentro la pagina web.
</p>

<p style="text-align: center;">
  Nel caso sia nascosto clicchiamo col tasto destro del mouse sul sito web e selezioniamo &#8216;<span style="color: #666699;">Visualizza sorgente pagina</span>&#8216;.
</p>

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.03.41.png"><img class="alignnone size-full wp-image-3389" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.03.41.png" alt="" width="1238" height="617" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.03.41.png 1238w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.03.41-300x150.png 300w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.03.41-768x383.png 768w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.03.41-1024x510.png 1024w" sizes="(max-width: 1238px) 100vw, 1238px" /></a>
</p>

<p style="text-align: center;">
  Digitiamo &#8216;<span style="color: #666699;">ctrl + F</span>&#8216; per aprire la casella di ricerca e cerchiamo la parola &#8216;<span style="color: #666699;">rss</span>&#8216;.
</p>

<p style="text-align: center;">
  Abbiamo trovato la url del feed RSS, che in questo caso è <a href="https://hlcs.it/feed/" target="_blank">https://hlcs.it/feed/ </a>
</p>

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.04.19.png"><img class="alignnone size-full wp-image-3390" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.04.19.png" alt="" width="1352" height="393" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.04.19.png 1352w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.04.19-300x87.png 300w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.04.19-768x223.png 768w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.04.19-1024x298.png 1024w" sizes="(max-width: 1352px) 100vw, 1352px" /></a>
</p>

<p style="text-align: center;">
  Torniamo a chattare col nostro bot per <span style="color: #666699;">incollare la ulr</span> del feed RSS.
</p>

<p style="text-align: center;">
  Abbiamo finito la configurazione del bot, che ci aggiornerà in automnatico ogni volta che il sito da noi scelto pubblica una notizia.
</p>

<p style="text-align: center;">
  <a href="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.10.28.png"><img class="alignnone size-full wp-image-3391" src="http://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.10.28.png" alt="" width="807" height="368" srcset="https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.10.28.png 807w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.10.28-300x137.png 300w, https://www.businessinformatics.it/wordpress/wp-content/uploads/2017/01/Schermata-2017-01-02-alle-18.10.28-768x350.png 768w" sizes="(max-width: 807px) 100vw, 807px" /></a>
</p>

<!--:-->