1) Creare un file .xml ed inserire un prologo con la dichiarazione XML e un commento con le vostre informazioni. 
<!-- This document contains data on Codifica di Testi. 
Filename: project.xml 
Author: your name 
Date: today's date --> 
Salvare il file su github nel repository del progetto.

File relativi: esercizio_1.xml


2) Aprire il file XML non ben formato presente nel repository github: 
  validarlo con un parser XML 
  correggerlo (commentando gli errori e le modifiche) 
  aggiungere un figlio (child) ad un elemento
  aggiungere un fratello (sibling) ad un elemento.

File relativi: esercizio_2-doc_well.xml


3) Definire i seguenti elementi: 
elemento root: TEI 
elementi figli: 
  header (obbligatorio una occorrenza) 
  facsimile (opzionale una occorrenza) 
  text (obbligatorio almeno una occorrenza) 
Gli elementi header, facsimile e text hanno tutti un content model testuale.

File relativi: codice-DTD.xml, dichiarazione-DTD.dtd


4) root: TEI 
Figli: 
  header (obbligatorio una volta sola) 
  facsimile (opzionale una volta sola - ?) 
  testo (obbligatorio una o più volte - +) 
* testo è un mixed content con possibile elemento 
Attributi: 
  header: type:(fixed, CDATA “intestazione”); lang(opzionale, NMTOKEN) 
  facsimile: source:(obbligatorio); ref(opzionale, IDREFS) 
  testo: id(obbligatorio, ID) type(opzionale contenuto testuale)

File relativi: validazione.xml


5) Includere all’interno di un documento XML la dichiarazione del tipo, definire internamente gli elementi e gli attributi e validare (-v). 
Inserire nel prologo di un documento XML la dichiarazione del tipo di documento e validare. 
Creare un file esterno con estensione .dtd prima di includerlo nel prologo XML. 

File relativi: doctype_incluso.xml, doctype_reindirizzato.xml, doctype_reindirizzato.dtd


6) Marcare un testo plain text di circa 3000 caratteri a piacere.
inserire prologo XML
marcare la struttura usando gli elementi fin qui descritti in particolare marcare tutti i paragrafi usando <p> e la struttura editoriale usando <div>
verificare che sia ben formato con xmllint
salvare il file XML su github

File relativi: testo-marcato.xml


7) Utilizzare puntatori, note, lista, glossario marcare nomi, rs, term.

8) Esercizi documenti di tipo e genere diversi
codificare usando gli opportuni elementi TEI un articolo di rivista
codificare usando gli opportuni elementi TEI una cartolina

9) Trascrivere e codificare un frammento di lettera di Bellini
(Vincenzo Bellini a Carlo Pepoli, in Puteaux, 26 giugno 1834)

File relativi: frammento-lettera-bellini.xml


10)
