<h3 align="center">Free-BSD Webiste | (school project)</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()

</div>

---

## Introduzione 

Free-BSD è un sistema operativo gratuito basato su BSD(Berkeley Software Distribution), la versione di UNIX sviluppata dall’università di California. È un progetto open source, che viene costantemente aggiornato e mantenuto da tutta la community. Ha compatibilità con diversi tipi di piattaforme, tra le più importanti troviamo ARM 32 bit e ARM 64 bit. 

## Storia 

Nel 1974, il professor Bob Fabry dell'Università della California, ha acquisito una licenza sorgente Unix da AT&T, per poi creare una versione migliorata che chiamò BSD: implementava diverse nuove funzioni. Il progetto BSD è stato fondato nel 1976 da Bill Joy. Ma poiché BSD conteneva codice da AT&T Unix, tutti i destinatari dovevano prima ottenere una licenza da AT&T per poter utilizzare BSD. Venne quindi rilasciata ufficialmente la prima versione nel 1989. Dopo il rilascio, uno sviluppatore ha suggerito di sostituire tutto il codice AT&T con uno liberamente ridistribuibile sotto la licenza BSD originale. Dopo 18 mesi di lavori, gran parte del codice è stato sostituito, e venne rilasciata ufficialmente la prima versione di Free-BSD nel 1991. FreeBSD 2.0, rilasciato nel novembre 1994, è stata la prima versione di FreeBSD senza codice di AT&T. 


## Caratteristiche 

I vari tipi di BSD (3 principali) sono tutti dei sistemi operativi conformi a POSIX (Portable Operating System Interface) derivati da UNIX, tutti i BSD si basano sui concetti di stabilità e prestazioni.

Come abbiamo già accennato prima è molto usato nell’ambito dei server in quanto è molto stabile e facilmente scalabile dal punto di vista del networking, appunto per questo motivo con gli anni si è evoluto (anche NetBSD e ancor di più OpenBSD) per quanto riguarda la sicurezza in rete, infatti presenta sin dalle prime patch della versione 6.0, 3 tipi diversi di firewall (“Pf sense”) 

Dal punto di vista dello storage FreeBSD ed in particolare anche OpenBSD presentano alcune caratteristiche che vanno ad agire sul salvataggio preventivo dei dati (“sort of”) quando il sistema è in overload (in particolare per la CPU) e di conseguenza quando potrebbe andare in crash, inoltre entrambi (soprattutto OpenBSD [molto più complesso e sicuro]) presentano l’encrypting dei dati salvati nel disco. 

## Ports  

Sono un altro metodo per l’installazione di applicazioni compatibili con FreeBSD, sono molto importanti e convenienti per vari motivi: (una volta installati contengono tutti i percorsi per ottenere una copia del codice sorgente dell’applicazione per poi compilarlo [si usa il comando “make install...”]) 

Rispetto ai soliti metodi di installazione in binario come pkg comprendono un catalogo molto più grande e specifico in certi punti di vista 

Si può scaricare il framework dell’intera lista di ports (installando il ports hierarchy) avendo quindi il codice sorgente di centinaia di applicazioni pronte per essere unzippate (non so un termine per unpaked)  e compilare in qualunque momento anche offline 

 

## OpenBSD e NetBSD 

Quasi contemporaneamente allo sviluppo di FreeBSD c’è stato quello di NetBSD ed in seguito partendo da questi due è stato creato OpenBSD per la necessità di avere un sistema più sicuro. 

 

NetBSD, si concentra di più su portabilità e gestione sistemi di rete 

OpenBSD è più focalizzato verso la sicurezza e possiede alcuni caratteri come una crittografia incorporata molto più complessa rispetto a quella standard (e spesso controproducente) di FreeBSD, il dico non è controllato da un'unica chiave crittografica ma è divisa in sezioni e ogni dispositivo ne genera di nuove (avere dei backup delle chiavi è essenziale per un cambiamento hardware) 

 

## Differenze rispetto a Linux 

FreeBSD è in grado di eseguire gran parte dei pacchetti facenti parte di moltissime distribuzioni di Linux (tutte le applicazioni che possono essere eseguite dal sistema operativo di Linux [in sé Linux è solo un kernel] [BSD è l’intero sistema operativo]) Considerando che non tutti questi pacchetti possono essere eseguiti sono presenti alcune espansioni del kernel per risolvere il problema (non tutti alcuni non possono proprio essere eseguiti da BSD)  

FreeBSD è molto più legato (vicino) a UNIX rispetto a Linux, uno dei motivi che ha reso BSD (relativamente) più utile rispetto a Linux è la possibilità andar a modificare il codice sorgente senza l’obbligo di dover pubblicare ciò che si è modificato 

## ⛏️ Built With <a name = "tech_stack"></a>

- [VSCode](https://code.visualstudio.com/) - Text Editor
- [HTML](https://en.wikipedia.org/wiki/HTML) 
- [CSS](https://en.wikipedia.org/wiki/CSS)

## ✍️ Authors <a name = "authors"></a>

- [@diskxo_](https://github.com/diskxo)
- [@Project-Piffa](https://github.com/Project-Piffa)
- [@rickyguala](https://github.com/rickyguala)
