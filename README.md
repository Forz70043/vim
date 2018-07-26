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

⋅⋅⋅---> La mmucca saltòò finnoo allaa lunnnaa.

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


















