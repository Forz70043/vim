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

**NOTA:** Mentre segui questa guida, non cercare di imparare  memoria, ma impara facendo pratica.


## Lezione 1.4: MODIFICA DI TESTI - INSERIMENTO

**Premere** `i` **per inserire del testo**


1. Muovi il cursore alla prima linea qui sotto, indicata da --->.
2. Per rendere la prima linea uguale alla seconda, muovi il cursore sopra il primo carattere DOPO la posizione in cui il testo va inserito.
3. Premi `i` e batti le aggiunte opportune.
4. Quando un errore e' corretto, premi `ESC` per tornare in Modalita' Normale. Ripeti i passi da 2 a 4 fino a completare la correzione della frase.

---> C'era del tsto mncnt questa .
---> C'era del testo mancante in questa linea.

5. Quando sei a tuo agio nell'inserimento di testo vai alla Lezione 1.5.



## Lezione 1.5: MODIFICA TESTI - AGGIUNTA

**Premere** `A` **per aggiungere testo a fine linea.**


1. Muovi il cursore alla prima linea qui sotto, indicata da --->.
2. Batti `A` e inserisci le necessarie aggiunte.
3. Alla fine dell'aggiunta premi `ESC` per tornare in Modalita' Normale.
4. Muovi il cursore alla seconda linea indicata da ---> e ripeti i passa 2 e 3 per correggere questa frase.

--->C'e' del testo che manca da qu
    C'e' del testo che manca in questa linea.
--->C'e' anche del testo che ma
    C'e' anche del testo che manca qui.

5. Quando sei a tuo agio nell'aggiunta del testo vai alla lezione 1.6.


## Lezione 1.6: MODIFICARE UN FILE

**Usare** `:wq` **per salvare un file ed uscire**

**NOTA:** Prima di eseguire quanto richiesto, leggi la Lezione per intero!!

1. Esci da Vim come hai fatto nella Lezione 1.2: `:q!`
2. Quando vedi il PROMPT della Shell, batti il comando: `vim tutor` `INVIO`,
'vim' e' il comando per richiamare Vim, 'tutor' e' il nome del file che desideri modificare. Usa un file che possa essere modificato.
3. Inserisci e cancella del testo come hia imparato nelle Lezioni precedenti.
4. Salva il file ed esci da Vim: `:wq` `INVIO`.
5. Rientra in vimtutor e scendi al sommario che segue.
6. Dopo aver letto i passi qui sopra ed averli compresi: eseguili.

#Lezione 1 SOMMARIO

1. Il cursore si muove usando i tasti con le frece o i tasti `hjkl`.
	`h` sinistra,`j` giu',`k` su,`l` destra
2. Per eseguire Vim dal PROMPT della Shell batti: `vim NOMEFILE` `INVIO`
3. Per uscire da Vim batti: `ESC` `:q!` `INVIO` per uscire senza salvare
			    `ESC` `:wq` `INVIO` per uscire e salvare le modifiche.

**NOTA:** premendo `ESC` ritornerai in Modalita' Normale o annullerai un comando errato che puoi aver inserito in parte.

Ora continua con la Lezione 2.

