# Benvenuto nella   Guida   all'editor VIM - Versione 1.7

Sito Ufficiale: [vim](https://www.vim.org)
 
Vim è un Editor molto potente ed ha parecchi comandi, troppi per
spiegarli tutti in una guida come questa. Questa guida serve a 
descrivere quei comandi che ti permettono di usare facilmente
Vim come Editor di uso generale.

Il tempo necessario per completare la guida è circa 25-30 minuti,
a seconda di quanto tempo dedichi alla sperimentazione.

**ATTENZIONE!** 
I comandi nelle lezioni modificano questo testo. Fai una copia di questo 
file per esercitarti (se hai usato `vimtutor`, stai già usando una copia).

E' importante non scordare che questa guida vuole insegnare tramite
l'uso. Questo vuol dire che devi eseguire i comandi per impararli
davvero. Se leggi il testo e basta, dimenticherai presto i comandi!

Adesso, assicurati che il tasto BLOCCA-MAIUSCOLO non sia schiacciato
e premi il tasto ` j ` tanto da muovere il cursore fino a che 
la Lezione 1.1 riempia completamente lo schermo.


## Lezione 1.1 MOVIMENTI DEL CURSORE 

**NOTA:** 	Il tasto ` h ` è a sinistra e muove a sinistra.
		Il tasto ` l ` è a destra e muove a destra.
		Il tasto ` j ` ricorda una freccia in giù.
 
1. Muovi il cursore sullo schermo finchè non ti senti a tuo agio.
2. Tieni schiacciato il tasto "giù" (`j`) finchè non si ripete il movimento.
3. Usando il tasto "giù" spostati alla Lezione 1.2 .

**NOTA:** Quando non sei sicuro del tasto che hai premuto, premi `ESC` per andare in Modalità Normale [Normal Mode]. Poi ri-immetti il comando che volevi.

**NOTA:** I tasti con le frecce fanno lo stsso servizio. Ma usando `hjkl` riesci a muoverti molto più rapidamente, dopo che ci si abitua. Davvero!


## Lezione 1.2 USCIRE DA VIM

**NOTA:** Prima di eseguire quanto richiesto, leggi la Lezione per intero!!

1. Premi il tasto ` ESC ` (per assicurarti di essere in Modalità Normale).
2. Batti: `:q!` `INVIO`. Così esci dall' Editor **scartando** qualsiasi modifica fatta.
3. Quando vedi il PROMPT della Shell, batti il comando con cui sei arrivato qui. Sarebbe: `vimtutor` `INVIO`.
4. Se hai memorizzato questi comandi e ti senti pronto, esegui i passi da 1 a 3 per uscire e rientrare nell'Editor.

**NOTA:** `:q!` `INVIO` SCARTA qualsiasi modifica fatta. In una delle prossime lezioni imparerai come salvare un file che hai modificato.

5. Muovi in giù il cursore per passare alla Lezione 1.3 .


## Lezione 1.3 MODIFICA DI TESTI - CANCELLAZIONE

**Premere** `x` **per cancellare il carattere sotto al cursore**

1. Muovi il cursore alla linea più sotto, indicata da --->
2. Per correggere errori, muovi il cursore fino a posizionarlo sopra il carattere da cancellare.
3. Premi il tasto `x` per cancellare il carattere sbagliato.
4. Ripeti i passi 2 a 4 finchè la frase è corretta.

	---> La mmucca saltòò finnoo allaa lunnnaa.

5. Ora che la linea è corretta, vai alla Lezione 1.4

**NOTA:** Mentre segui questa guida, non cercare di imparare a memoria, ma impara facendo pratica.


## Lezione 1.4: MODIFICA DI TESTI - INSERIMENTO

**Premere** `i` **per inserire del testo**


1. Muovi il cursore alla prima linea qui sotto, indicata da --->.
2. Per rendere la prima linea uguale alla seconda, muovi il cursore sopra il primo carattere DOPO la posizione in cui il testo va inserito.
3. Premi `i` e batti le aggiunte opportune.
4. Quando un errore e' corretto, premi `ESC` per tornare in Modalita' Normale. Ripeti i passi da 2 a 4 fino a completare la correzione della frase.

---> C'era del tsto mncnt questa .<br/>
---> C'era del testo mancante in questa linea.

5. Quando sei a tuo agio nell'inserimento di testo vai alla Lezione 1.5.


## Lezione 1.5: MODIFICA TESTI - AGGIUNTA

**Premere** `A` **per aggiungere testo a fine linea.**


1. Muovi il cursore alla prima linea qui sotto, indicata da --->.
2. Batti `A` ed inserisci le necessarie aggiunte.
3. Alla fine dell'aggiunta premi `ESC` per tornare in Modalità Normale.
4. Muovi il cursore alla seconda linea indicata da ---> e ripeti i passa 2 e 3 per correggere questa frase.

--->C'e' del testo che manca in qu		<br/>
    C'e' del testo che manca in questa linea. 	<br/>
--->C'e' anche del testo che ma			<br/>
    C'e' anche del testo che manca qui.		<br/>

5. Quando sei a tuo agio nell'aggiunta del testo vai alla lezione 1.6.


## Lezione 1.6: MODIFICARE UN FILE

**Usare** `:wq` **per salvare un file ed uscire**

**NOTA:** Prima di eseguire quanto richiesto, leggi la Lezione per intero!!

1. Esci da Vim come hai fatto nella Lezione 1.2: `:q!`
2. Quando vedi il PROMPT della Shell, batti il comando: `vim tutor` `INVIO`,
'vim' e' il comando per richiamare Vim, 'tutor' è il nome del file che desideri modificare. Usa un file che possa essere modificato.
3. Inserisci e cancella del testo come hai imparato nelle Lezioni precedenti.
4. Salva il file ed esci da Vim: `:wq` `INVIO`.
5. Rientra in vimtutor e scendi al sommario che segue.
6. Dopo aver letto i passi qui sopra ed averli compresi: eseguili.


## Lezione 1 SOMMARIO

1. Il cursore si muove usando i tasti con le frece o i tasti `hjkl`.
	`h` sinistra,`j` giu',`k` su,`l` destra
2. Per eseguire Vim dal PROMPT della Shell batti: `vim NOMEFILE` `INVIO`
3. Per uscire da Vim batti: `ESC` `:q!` `INVIO` per uscire senza salvare
			    `ESC` `:wq` `INVIO` per uscire e salvare le modifiche.

**NOTA:** premendo `ESC` ritornerai in Modalita' Normale o annullerai un comando errato che puoi aver inserito in parte.

Ora continua con la Lezione 2.


## Lezione 2.1: COMANDI DI CANCELLAZIONE

**Batti** `dw` **per cancellare una parola.**

1. Premi `ESC` per accertarti di essere in Modalità Normale.
2. Muovi il cursore fino alla linea qui sotto, indicata da --->.
3. Muovi il cursore all'inizio di una parola che vuoi cancellare.
4. Batti `dw` per cancellare la parola.

**NOTA:** La lettera `d` sarà visibile sull'ultima linea dello schermo mentre la batti. Vim attende che tu batta `w`. Se vedi una lettera diversa da `d` hai battuto qualcosa di sbagliato; premi `ESC` e ricomincia.

---> Ci sono le alcune parole gioia che non c'entrano carta in questa frase.

5. Ripeti i passi 3 e 4 finchè la frase è corretta, poi vai alla Leione 2.2.


## Lezione 2.2: ALTRI COMANDI DI CANCELLAZIONE


**Batti** `d$` **per cancellare fino a fine linea.**

1. Premi `ESC` per accertarti di essere in Modalità Normale.
2. Muovi il cursore fino alla linea qui sotto, indicata da --->.
3. Muovi il cursore alla fine della linea corretta (DOPO il primo .).
4. Batti `d$` per cancellare fino a fine linea.

---> Qualcuno ha battuto la fine di questa linea due volte. linea due volte.

5. Vai alla Lezione 2.3 per capire il funzionamento di questo comando.


## Lezione 2.3: OPERATORI E MOVIMENTI


Molti comandi di modifica testi consistono in un operatore e un movimento.
Il formato del comando di cancellazione con l'operatore `d` è il seguente:
`d` movimento

Dove:
* `d` è l'operatore di cancellazione
* `movimento` indica dove l'operatore va applicato (lista qui sotto).

Breve lista di movimenti:
* `w` fino a inizio della parola seguente, ESCLUSO il suo primo carattere.
* `e` alla fine della parola corrente, COMPRESO il suo ultimo carattere.
* `$` dal cursore fino a fine linea, COMPRESO l'ultimo carattere della linea.

Quindi se batti `de` cancelli dal cursore fino a fine parola.

**NOTA:** Se batti solo il movimento mentre sei in Modalità Normale, sena nessun operatore, il cursore si muoverà come specificato.


## Lezione 2.4: USO DI UN CONTATORE PER UN MOVIMENTO 

**Se batti un numero prima di un movimento, lo ripeti altrettante volte.**

1. Muovi il cursore fino all'inizio della linea qui sotto, indicata da --->
2. Batti `2w` per spostare il cursore due parole più avanti.
3. Batti `3e` per spostare il cursore alla fine della terza parola seguente.
4. Batti `0` (zero) per posizionarti all'inizio della linea.
5. Ripeti i passi 2 e 3 usando numeri differenti.

---> Questa è solo una linea con parole all'interno della quale puoi muoverti.

6. Vai alla Lezione 2.5.


## Lezione 2.5: USO DI UN CONTATORE PER CANCELLARE DI PIU'

**Se batti un numero prima di un movimento, lo ripeti altrettante volte.**

Nella combinazione dell'operatore cancella e di un movimento, descritto prima, inserite un contatore prima del movimento per cancellare di più:

1. Muovi il cursore alla prima parola MAIUSCOLA nella riga indicata da --->.
2. Batti `d2w` per cancellare le due parole MAIUSCOLE
3. Ripeti i passi 1 e 2 con un contatore diverso per cancellare le parole MAIUSCOLE consecutive con un solo comando

---> questa ABC DE linea FGHI JK OP di parole è Q RS TUV ora ripulita.



## Lezione 2.6: LAVORARE SU LINEE INTERE

**Batti** `dd` **per cancellare un'intera linea.**

Per la frequenza con cui capita di cancellare linee intere, chi ha disegnato Vi ha deciso che sarebbe stato più semplice battere due d consecutive per cancellare una linea.

1. Muovi il cursore alla linea 2) nella frase qui sotto.
2. Batti `dd` per cancellare la linea.
3. Ora spostati alla linea 4).
4. Batti `2dd` per cancellare due linee.

---> 1) Le rose sono rosse,  
---> 2) Il fango è divertente,  
---> 3) Le viole sono blu,  
---> 4) Io ho un'automobile,  
---> 5) Gli orologi segnano il tempo,  
---> 6) Lo zucchero è dolce,  
---> 7) E così sei anche tu.  



## Lezione 2.7: IL COMANDO UNDO [ANNULLA]

**Premi** `u` **per annullare gli ultimi comandi eseguiti.**  
**Premi** `U` **per annullare le modifiche all'ultima linea.**  

1. Muovi il cursore fino alla linea qui sotto, indicat da --->
2. Batti `x` per cancellre il primo carattere sbagliato.
3. Adesso batti `u` per annullare l'ultimo comando eseguito.
4. Ora invece, correggi tutti gli errori sulla linea usando il comando `x`.
5. Adesso batti una `U` Maiuscola per riportare la linea al suo stato originale.
6. Adesso batti `u` più volte per annullare la `U` e i comandi precedenti.
7. Adesso batti più volte `CTRL` `r` (tenere premuto CTRL metre si preme r) per rieseguire i comandi (annullare l'annullamento).

--->Correeggi gli errori ssu quuesta linea e riimpiazzali con "undo".  

8. Questi comandi sono molto utili. Ora spostati al Sommario della Lezione 2.



## Lezione 2 SOMMARIO

1. Per cancellare dal cursore fino alla parola seguente batti: `dw`.
2. Per cancellare dal cursore fino alla fine della linea batti: `d$`. 
3. Per cancellare un'intera linea batti: `dd`.
4. Per eseguire più volte un movimento, mettici davanti un numero: `2w`
5. Il formato per un comando di modifica è:  

  operatore [numero] movimento  

  dove:
* operatore: indica il da farsi, ad es. `d` per [delete] cancellare  
* [numero]:  contatore facoltativo di ripetizione del movimento
* movimento: spostamento nel testo su cui operare, ad es.  
  `w` [word] parola, `$` (fino a fine linea), etc
6. Per andare a inizio linea usate uno zero: 	`0` 
7. Per annullare i comandi precedenti, batti:	`u` (minuscola)
    Per annullare tutte le modiche a una linea batti: `U` (Maiuscola)
    Per annullare l'annullamento ["redo"] batti: `CTRL` `r`


## Lezione 3.1: IL COMANDO PUT [METTI, PONI]

**Batti** `p` **per porre [put] testo (cancellato prima) dopo il cursore.**

1. Muovi il cursore alla prima linea indicata da ---> qui in basso.
2. Batti `dd` per cancellare la linea e depositarla in un registro di Vim.
3. Muovi il cursore fino alla linea c) SOPRA quella dove andrebbe messa la linea appena cancellata.
4. Batti `p` per mettere la linea sotto il cursore.
5. Ripeti i passi da 2 a 4 per mettere tutte le linee nel giusto ordine.

---> d) Puoi impararla tu?  
---> b) Le viole sono blu,
---> c) La saggezza si impara,
---> a) Le rose sono rosse,


## Lezione 3.2: IL COMANDO REPLACE [RIMPIAZZARE]

**Batti** `rx` **per rimpiazzare il carattere sotto al cursore con x .**

1. Muovi il cursore alla prima linea qui sotto, indicata da --->.
2. Muovi il cursore fino a posizionarlo sopra il primo errore.
3. Batti r e poi il carattere che dovrebbe stare qui 
4. Ripeti i passi 2 e 3 finche' la prima linea e' uguale alle seconda.

---> Ammattendo quetta lince, qualcuno ha predato alcuni tosti sballiati!  
---> Immettendo questa linea, qualcuno ha premuto alcuni tasti sbagliati!  

5. Ora passa alla Lezione 3.2.

**NOTA:** Ricordati che dovresti imparare con la pratica, non solo leggendo.


## Lezione 3.3: L'OPERATORE CHANGE [CAMBIA]

**Per cambiare fino alla fine di una parola, batti** `ce`.

1. Muovi il cursore alla prima linea qui sotto, indicata da --->
2. Posiziona il cursore alla `u` in lubw
3. Batti `ce` e la parola corretta (in questo caso, batti inea ). 
4. Premi `ESC` e vai sul prossimo carattere da modificare.
5. Ripeti i passi 3 e 4 finche' la prima frase e' uguale alla seconda.

---> Questa lubw ha alcune pptfd da asdert usgfk l'operatore CHANGE.  
---> Questa linea ha alcune parole da cambiare usando l'operatore CHANGE.

**Nota che** `ce` **cancella la parola e ti mette anche in Modalita' Inserimento [Insert Mode]**


## Lezione 3.4: ALTRI CAMBIAMENTI USANDO c

**L'operatore** `c` **[CHANGE] agisce sugli stessi movimenti di** `d` **[DELETE]**

1. L'operatore CHANGE si comporta come DELETE. Il formato e':
	`c` [numero] movimento
2. I movimenti sono gli stessi: `w` (word,parola), `$` (fine linea), etc.
3. Muovi il cursore alla prima linea qui sotto, indicata da --->.
4. Posiziona il cursore al primo errore.
5. Batti `c$` e inserisci resto della linea utilizzando come modello la linea seguente e quando hai finito premi `ESC`

---> La fine di questa linea deve essere aiutata a divenire come la seguente.  
---> La fine di questa linea deve essere corretta usando il comando `c$`.    

**NOTA:** Puoi usare il tasto Backspace se devi correggere errori di battitura.

## Lezione 3 SOMMARIO

1. Per iniziare del testo appena cancellato, batti `p` .Questo inserisce [pone] il testo cancellato DOPO il cursore (se era stata tolta una linea intera, questa verra' messa nella linea SOTTO il cursore)
2. Per rimpiazzare il carattere sotto il cursore, batti `r` e poi il carattere che vuoi sostituire.
3. L'operatore change ti permette di cambiare dal cursore fino a dove arriva il movimento. Ad es. Batti `ce` per cambiare dal cursore fino alla fine della parola, `c$` per cambiare finoi alla linea.
4. Il formato di `change` e':
	`c` [numero] `movimento`

Ora vai alla prossima Lezione.


##Lezione 4.1: POSIZIONAMENTO E SITUAZIONE FILE

**Batti** `CTRL` `G` **per vedere a che punto sei nel file e la situazione del file.**  
**Batti** `G` **per raggiungere una linea nel file.**

**NOTA:** Leggi l'intera Lezione prima di eseguire un qualsiasi passo!!

1. Tieni premuto il tasto `CTRL` e batti `g`. Ossia batti `CTRL` `G`.  Un messaggio apparira' in fondo alla pagina con il NOME FILE e la posizione nel file.  
Ricordati il numero della linea per il passo 3.  

**NOTA:** La posizione del cursore si vede nell'angolo in basso a destra dello schermo, se e' impostata l'opzione `ruler` (righello, vedi `:help ruler`).  
2. Premi `G` [G Maiuscolo] per posizionarti in fondo al file.  Batti `gg` per posizionarti in cima al file.
3. Batti il numero della linea in cui ti trovavi e poi `G`.  Questo ti riportera' fino alla fine in cui ti trovavi quando avevi premuto `CTRL` `g`.
4. Se ti senti sicuro nel farlo, esegui passi da 1 a 3.


## Lezione 4.2: IL COMANDO SEARCH [RICERCA]

**Batti** `/` **seguito da una frase per ricercare quella frase**  

1. In Modalita' Normale batti il carattere `/`.  Nota che la "/" e il cursore sono visibili in fondo dello schermo come quando si usa il comando `:` .  
2. Adesso batti `errroore` `INVIO`.  Questa e' la parola che vuoi ricercare.
3. Per ricercare ancora la stessa frase, batti `n`.  Per ricercare la stessa frase in direzione opposta, batti `N`.  
4. Per ricercare una frase nella direzione opposta, usa `?` al posto di `/`.  
5. Per tornare dove eri prima nel file premi `CTL` `O` (tieni premuto `CTRL` mentre premi la lettera O).  Ripeti `CTRL` `O` per andare ancora indietro.  Puoi usare `CTRL` `I` per tornare in avanti.  

---> "errroore" non e' il modo giusto di digitare errore;  errrore e' un errore.  
**NOTA:** Quando la ricerca arriva a fine file, ricomincia dall'inizio del file, a me che l'opzione 'wrapscan' sia stata disattivata.  


## Lezione 4.3: RICERCA DI PARENTESI CORRISPONDENTI

**Batti** `%` **per trovare una ),] o } corrispondente.**

1. Posiziona il cursore su una (,[ o { nella linea otto, indicata da --->
2. Adesso batti il carattere `%`
3. Il cursore si spostera' sulla parentesi corrispondente 
4. Batti `%` per muovere il cursore all'altra parentesi corrispondente.  

---> Questa ( e' una linea di test con (, [ ] e { } al suo interno ))  

**NOTA:**  Qusto e' molto utile nel "debug" di un programma con parentesi errate!


## Lezione 4.4: L'OPERATORE SOSTITUZIONE (SUBSTITUTE)

**Batti** `s:/vecchio/nuovo/g` **per sostituire 'nuovo' a 'vecchio'**  

1. Muovi il cursore fino alla linea qui sotto, indicata da --->. 
2. Batti `s:/lla/la/g` .  Aggiungendo il flag g si chiede di sostituire "globalmente" sulla linea, ossia tutte le occorenze di "lla" sulla linea.  

--->  lla stagione migliore per lla fioritura e' lla primavera.

4. Per cambiare ogni ricorrenza di una stirnga di caratteri tra due linee, batti `#,#s/vecchio/nuovo/g` dove  
  #,# sono i numeri che delimitano il gruppo di linee in cui si vuole sostituire.  
  Batti `:%s/vecchio/nuovo/g` per cambiare ogni occorenza nell'intero file.  
  Batti `%s/vecchio/nuovo/gc`  per trovare ogni occorenza nell'intero file ricevendo per ognuna una richiesta se effettuare o meno la sostituzione.  


## Lezione 4 SOMMARIO

1. `CTRL-G` visualizza a che punto sei nel file e la situazione del file.  `G` [G Maiuscolo] ti porta all'ultima linea del file.  
`numero G` ti porta alla linea con quel numero.  
`gg` ti porta alla prima linea del file.  
2. Battendo `/` seguito da una frase ricerca IN AVANTI quella frase.  
Battendo `?` seguito da una frase ricerca ALL'INDIETRO quella frase.  
DOPO una ricerca batti `n` per trovare la prossima occorenza nella stessa direzione, oppure `N` per cercare in direzione opposta.  
`CTRL-O` ti porta alla posizione precedente, `CTRL-I` a quella piu' nuova.  
3. Battendo `%` mentre il cursore si trova su (,),[,],{, oppure } ti posizioni sulla corrispondente parentesi.  
4. Per sostituire "nuovo" al primo "vecchio" in 1 linea batti `:s/vecchio/nuovo`  
  Per sostituire "nuovo" ad ogni "vecchio" in 1 linea batti `s:/vecchio/nuovo/g`  
  Per sostituire frasi tra due numeri di linea [#] batti `#,#s/vecchio/nuovo/g`  
  Per sostituire tutte le occorenze nel file batti `:%s/vecchio/nuovo/g`  
  Per chiedere conferma ogni volta aggiungi 'c' `:%s/vecchio/nuovo/gc`  


## Lezione 5.1: COME ESEGUIRE UN COMANDO ESTERNO 

**Batti** `:!` **seguito da un comando esterno per eseguire quel comando**

1. Batti il comando `:` per posizionare il cursore in fondo allo schermo.  Cio' ti permette di immettere un comando alla linea comandi.  
2. Adesso batti il carattere `!` (punto esclamativo).  Cio' ti permette di eseguire qualsiasi comando esterno si possa eseguire nella "shell".  
3. Ad esempio batti `ls` dopo il `!` e poi premi `INVIO`.  Questo visualizza una lista della tua directoru, proprio come se fossi in una "shell".  Usa `:!dir` se `ls` non funziona.[Unix: ls MS-DOS: dir]  

**Nota:** E' possibile in questo modo eseguire un comando a piacere, specificando anche dei parametri per i comandi stessi.  
**Nota:** Tutti i comandi `:` devono essere terminati premendo `INVIO`.  Da qui in avanti non li ripeteremo ogni volta.  



## Lezione 5.2: ANCORA SULLA SCRITTURA DEI FILE

**Batti** `:!` **seguito da un comando esterno per eseguire quel comando**

1. Batti il comando `:` per posizionare il cursore in fondo allo schermo.  Cio' ti permette di mmettere un comando dalla linea comandi.  
2. Adesso batti il carattere `!` (punto esclamativo).  Cio' ti permette di eseguire qualsiasi comando esterno si possa eseguire nella "shell".  
3. Ad esempio batti `ls` dopo il `!` e poi premi `INVIO`.  Questo visualizza una lista della tua directory, proprio come se fossi in una "shell".  Usa `:!dir` se `ls` non funziona [Unix: ls MS-DOS: dir]

**Nota:** Se esci da Vim e riesegui Vim battendo `vim TEST`, il file aperto sara' una copia esatta di 'tutor.it' al momento del salvataggio 
5. Ora cancella il file battendo (MS-DOS): `:!del TEST` o (Unix): `:!rm TEST` .  


## Lezione 5.3: SELEZIONARE IL TESTO DA SCRIVERE  

**Per salvare una porzione di file, batti** `v movimento :w NOMEFILE` .  

1. Muovi il cursore su questa linea.  
2. Premi `v` e muovi il cursore fino alla linea numerata 5, qui sotto .  Nota che il testo viene evidenziato.  
3. Batti il carattere `:`, in fondo allo schermo apparira' `:'<,'>` .  
4. Batti `w TEST`, dove `TEST` e' il nome di un file non ancora esistente .  Verifica che si veda `:'<,'>W TEST` prima di dare `INVIO`.  
5. Vim scrivera' nel file TEST le linee che hai selezionato.  Usa `:!dir` o `:!ls` per controllare che esiste.  Non cancellarlo ora! Ti servira' nella prossima lezione.  

**Nota:** Battere `v` inizia una selezione visuale.  Puoi muore il cursore come vuoi e rendere la selezione piu' piccola o piu' grande .  Poi puoi usare un operatore per agire sul testo selezionato. Ad es: `d` cancella il testo.  


## Lezione 5 SOMMARIO 

1. `:!comando` esegue un comando esterno.  Alcuni esempi utili sono [in MSDOS]:  `:!dir` visualizza lista directory  `:!del NOMEFILE` cancella file NOMEFILE.
2. `:w NOMEFILE` scrive su disco il file che stai editando con NOMEFILE.  
3. `v movimento :w NOMEFILE` da disco e lo inserisce nel file che stai modificando, dopo la linea in cui e' posizionato il cursore.  
4. `:r NOMEFILE` legge il file NOMEFILE da disco e lo inserisce nel file che stai modificando, dopo la lina in cui e' posizionato il cursore.  
5. `:r !dir` legge l'output del ocmando dir e lo inserisce dopo la linea in cui e' posizionato il cursore.  


## Lezione 6.1: IL COMANDO OPEN [APRIRE]

**Batti** `o` **per aprire una linea sotto il cursore e passare in Modalita' Inserimento.**

1. Muovi il cursore fino alla linea qui sotto, indicata da --->.
2. Batti la lettera minuscola `o` per aprire una linea sotto il cursore e passare in Modalita' Inserimento .
3. Poi inserisci del testo e premi `ESC` per uscire dalla Modalita' Inserimento.  

---> Dopo battuto `o` il cursore e' sulla linea aperta (in Modalita' Inserimento).  

4. Per aprire una linea SOPRA il cursore, batti una `O` maiuscola, invece che una `o` minuscola.  Prova sulla linea qui sotto.  

---> Apri una linea SOPRA questa battendo `O` mentre il cursore e' su questa linea.   


## Lezione 6.2: IL COMANDO APPEND [AGGIUNGERE]

**Batti** `a` **per inserire testo DOPO il cursore .**  

1. Muovi il cursore all'inizio della liunea qui sotto, indicata da --->
2. Batti `e` finche' il cursore arriva alla fine di  li.  
3. batti una `a` (minuscola) per aggiungere testo DOPO il cursore.  
4. Completa la parola come mostrato nella linea successiva.  Premi `ESC` per uscire dalla Modalita' Inserimento.  
5. Usa `e` per passare alla successiva parola incompleta e ripeti i passi 3 e 4.  

---> Questa li yti permettera' di esercit ad aggiungere testo a una linea.  
---> Questa linea ti permettera' di esercitarti ad aggiungere testo a una linea.  

**NOTA:** `a`,`i` ed `A` entrano sempre in Modalita' Iserimento, la sola differenza e' dove verranno inseriti i caratteri .  


## Lezione 6.3: UN ALTRO MODO DI RIMPIAZZARE [REPLACE]

**Bati una** `R` **maiuscola per rimpiazzare piu' di un carattere**

1. Muovi il cursore alla prima linea qui sotto, indicata da --->.  Muovi il cursore all'inizio del primo xxx.  
2. Ora batti `R` e batti il numero che vedi nella linea seguente, in modo che rimpiazzi l' xxx.  
3. Premi `ESC` per uscire dalla Modalita' Replace.  Nota che il resto della linea resta invariato.  
4. Ripeti i passi in mododa rimpiazzare l'altro xxx.  

---> Aggiungendo 123 a xxx si ottiene xxx.  
---> Aggoiungendo 123 a 456 si ottiene 579.  

**NOTA:** Puoi usare `y` come operatore; `yw` copia una parola [word].  


## Lezione 6.4: COPIA E INCOLLA DEL TESTO 

**usa l'operatore** `y` **per copiare del testo e** `p` **per incollarlo**

1. Vai alla linea indicata da ---> qui sotto, e metti il cursore dopo "a)".  
2. Entra in Modalita' Visuale con `v` e metti il cursore davanti a "primo".  
3. Batti `y` per copiare [yank] il testo evidenziato.  
4. Muovi il curosre alla fine della linea successiva: `j$` .  
5. Batti `p` per incollare [paste] il testo.  Poi batti: `a` secondo `ESC`.  
6. Usa la Modalita' Visuale per selezionare " elemento.", copialo con `y`.  Vai alla fine della linea successiva con `j$` e incolla il testo con `p`.  

---> a) questo e' il primo elemento.  b)  

**NOTA:** Puoi usare `y` come operatore; `yw` copia una parola [word]. 


## Lezione 6.5: SET [IMPOSTA] UN'OPZIONE 

**Imposta un'opzione per ignorare maiuscole/minuscole durante la ricerca/sostituzione**  

1. Ricerca 'nota' battendo: `/nota ENTER` .  Ripeti la ricerca piu' volte usando il tasto `n`.  
2. Imposta l'opzione `ic` (Ignore Case, [Ignora maiuscolo/minuscolo])  battendo `:set ic`.  
3. Ora ricerca ancora 'nota' premendo il tasto `n` .  Troverai adesso anche Nota e NOTA.  
4. Imposta le opzionei `hlserach` e `incsearch` `:set hls is`.  
5. Ora bati ancora il comando di ricerca, e guarda cosa succede: `/nota`.  
6. Per disabilitare il riconoscimento di maiuscole/minuscole batti: `:set noic`.  

**NOTA:** Per non evidenziare le occorenze trovate batti: `:nohlsearch` .  
**NOTA:** Per ignorare maiuscole/minuscole solo per una ricerca, usa `\c` nel comando di ricerca: `/nota\c INVIO`


## Lezione 6 SOMMARIO

1. Batti `o` per aggiungere una linea SOTTO il cursore ed entrare in Modalita Inserimento.  Batti `O` per aggiungere una linea SOPRA il cursore.  
2. Batti `a` per inserire testo DOPO il cursore.  Batti `A` per inserire testo alla fine della linea.  
3. Il comando `e` sposta il cursore alla fine di una parola.  
4. L'operatore `y` copia del testo, `p` incolla del testo.  
5. Batti `R` per entrare in Modalita' Replace, e ne esci premendo `ESC`.  
6. Batti `:set xxx` per impostare l'opzione "xxx". Alcune opzioni sono:  
	`ic` `ignorecase` ignorare maiuscole/minuscole nella ricerca  
	`is` `incsearch` mostra occorenze parziali durante una ricerca  
	`hls` `hlsearch` evidenzia tutte le occorenze di una ricerca.  Puooi usare sia il nome di un'opzione che quello abbreviato.
7. Usa il prefisso "no" per annullare un'opzione: `:set noic`.  


## Lezione 7.1: OTTENERE AIUTO

**Usa il sistema aiuto on-line**

Vim ha un esauriente sistema di aiuto on-line.  Per cominciare, prova una di queste alternative:  
	premi il tasto `AIUTO`(se ce n'e' uno).  
	premi il tasto `F1` (se ce n'e' uno).  
	batti `:help INVIO` OPPURE `:h INVIO`

Leggi il testo nella finestra di aiuto per vedere come funziona l'aiuto.  
Batti `CTRL-W CTRL-W` per passare da una finestra all'altra.  Batti `:q INVIO` per chiudere la finestra di aiuto.  

Puoi trovare aiuto su quasi tutto, dando un argomento al comando `:help`.  Prova questi (non dimenticare di premere `INVIO`):  
	`:help w`  
	`:help c_CTRL-D`  
	`:help insert-index`  
	`:help user-manual`  

 
## Lezione 7.2: PREPARARE UNO SCRIPT INIZIALE

**Attiva le opzioni Vim**

1. Comincia a editare il file "vimrc". Questo dipende dal tuo sistema:  
	`:e ~/`vimrc` per Unix  
	`:e $VIM/_vimrc` per MS-Windows  
2. Ora leggi i contenuti del file "vimrc" distribuito come esempio:  
	`:r $VIMRUNTIME/vimrc_example.vim`  
3. Scrivi il file con:  `:w`  

La prossima volta che apri Vim, sara' abilitata la colorazione sintattica.  Puoi aggoiungere a questo file "vimrc" tutte le tue impostazioni preferite.  Per maggiorni informazioni bati: `:help vimrc-intro`.  


## Lezione 7.3: COMPLETAMENTO  

**Completamento linea comandi con** `CtRL-D` **e** `TAB`  

1. IMposta Vim in modalita' compatibile: `:set nocp`  
2. Guarda i file esistenti nella directory: `:!ls` o `:!dir`  
3. Batti l'inizio di un comando: `:e`  
4. Premi `CTRL-D` e Vim ti mostra una lista di comandi che iniziano per "e".  
5. Premi `TAB` e Vim completa per te il nome del comando come `:edit`.  
6. Ora batti uno spazio e l'inizio del nome di un file esistente: `:edit FIL`.  
7. Premi `TAB`. Vim completera' il nome del file (se e' il solo possibile).  

**NOTA:** Il completamento e' disponibile per molti comandi.  Prova a battere `CTRL-D` e `TAB`.  Particolarmente utile per `:help`.  


## Lezione 7 SOMMARIO  

1. Batti `:help` o premi `F1` o `Help` per aprire una finestra di aiuto.  
2. Bati `:help comando` per avere aiuto su comando.  
3. Batti `CTRL-W` per saltare alla prossima finestra.  
4. Batti `:q` per chiudere la finestra di aiuto.  
5. Crea uno script iniziale vimrc contenente le tue impostazioni preferite.  
6. Mentre bati un comando :, premi `CTRL-D` per vedere i possibili completamenti.  Premi `TAB` per usare il completamento desiderato.  



Qui finisce la Guida a Vim.  Il suo intento è di fornire una breve panoramica dell'Editor Vim, che ti consenta di usare l'Editor abbastanza facilmente.  
Questa guida è largamente incompleta poiché Vim ha moltissimi altri comandi.  Puoi anche leggere il manuale utente (anche in italiano): ":help user-manual".

Per ulteriore lettura e studio, raccomandiamo:  
        Vim - Vi Improved - di Steve Oualline     Editore: New Riders  
  Il primo libro completamente dedicato a Vim. Utile specie per principianti.  
  Contiene molti esempi e figure.  
  Vedi http://iccf-holland.org/click5.html  

  Quest'altro libro è più su Vi che su Vim, ma è pure consigliato:  
        Learning the Vi Editor - di Linda Lamb e Arnold Robbins  
        Editore: O'Reilly & Associates Inc.  
  E' un buon libro per imparare quasi tutto ciò che puoi voler fare con Vi.  
  Ne esiste una traduzione italiana, basata su una vecchia edizione.  

  Questa guida è stata scritta da Michael C. Pierce e Robert K. Ware,  
  Colorado School of Mines, usando idee fornite da Charles Smith,  
  Colorado State University - E-mail: bware@mines.colorado.edu  
  Modificato per Vim da Bram Moolenaar.  
  Segnalare refusi ad Antonio Colombo - E-mail: azc100@gmail.com  
  Vedi http://iccf-holland.org/click5.html


