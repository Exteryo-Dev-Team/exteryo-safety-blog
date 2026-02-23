---
title: "Risolti i problemi di ricerca ed esportazione: la piattaforma ora è ancora più fluida!"
date: 2026-02-23T12:21:59+01:00
draft: false
cover:
    image: assets/images/new_color_logo.png
    imageDark: assets/images/new_white_logo_logo.png
    alt: "Aggiornamento Piattaforma"
    relative: false
---

Oggi abbiamo rilasciato un nuovo aggiornamento per rendere la piattaforma ancora più stabile e intuitiva da usare, specialmente quando si tratta di cercare le informazioni e scaricarle.

Abbiamo individuato e risolto due piccoli "intoppi" che potevano verificarsi durante il normale utilizzo:

### 1. Esportazioni Excel a prova di errore (anche senza risultati)
Prima di oggi, se provavi a esportare un file Excel dopo aver fatto una ricerca che non produceva alcun risultato (nessun dato trovato), il sistema si bloccava mostrando un errore tecnico. Questo accadeva perché il "motore" che crea l'Excel provava testardamente a inserire delle colonne in un foglio che era completamente vuoto.

**Cosa abbiamo fatto:** Ora abbiamo insegnato al sistema a gestire queste situazioni. Se la tua ricerca non produce risultati, il sistema non andrà più in errore, ma ti farà scaricare un file Excel perfettamente formattato contenente solo la riga delle intestazioni, pronto per essere utilizzato.

### 2. Ricerca più intelligente per dati composti (come "Nome e Cognome")
Abbiamo notato che, in alcune schermate, cercando parole chiave specifiche (ad esempio il nome o il cognome di un lavoratore) il sistema restituiva zero risultati, anche quando il lavoratore era effettivamente presente.

**Cosa abbiamo fatto:** Il problema era dovuto a un controllo troppo rigido del nostro motore di ricerca interno, che "ignorava" i campi creati unendo più informazioni (come, appunto, il campo che unisce "Nome" e "Cognome"). Abbiamo rimosso questo limite: ora la ricerca "legge" correttamente anche i dati combinati. In questo modo le tue ricerche saranno sempre precise e non rischierai più di ritrovarti con schermate vuote senza motivo.

---

Continuiamo a lavorare per rendere il vostro lavoro quotidiano sempre più semplice e senza interruzioni. Buon proseguimento sulla piattaforma!
