---
layout: post
title:  "Il C per iniziare"
date:   2016-12-22 15:23:21
categories: tutorials
---

Durante le vacanze appena iniziate vorrei dedicare un po' di tempo alla pubblicazione di alcuni post molto semplici, ma altrettanto pratici su come imparare da zero il linguaggio C. Inizieremo proprio dalle basi, da come prepare il nostro spazio di lavoro a come creare un primo progetto. All'inizio il nostro programma sarà molto semplice, ma andando avanti aggiungeremo nuovi blocchi e introdurremo nuovi concetti.

## Per iniziare

Prima di tutto è necessario installare un IDE sul nostro pc Windows, Linux o Mac. Un IDE è un software che mette insieme vari strumenti necessari alla scrittura di un programma, ma anche alla sua compilazione e al debug. Per iniziare useremo *Codeblocks* (su Windows), un IDE molto semplice e leggero, ma che ha tutto quello che ci serve.

Potete scaricarlo al seguente link: [Download Codeblocks](http://www.codeblocks.org/downloads/26).
Se non avete mai usato programmi di questo tipo su vostro PC Windows, quasi sicuramente non disponete di un compilatore, scaricate quindi l'eseguibile che contiene anche "MinGW" (codeblocks-16.01mingw-setup.exe).

In fase di installazione assicuratevi che il compilatore risulti "detected" dall'installer e completate quindi il processo di installazione.

## Nuovo progetto

Una volta installato, potete creare un nuovo progetto tramite l'apposito pulsante, selezionate quindi "Console application" come tipo di progetto e "C" come linguaggio. Scegliete una cartella e un nome significativo da dare al vostro progetto (evitate gli spazi e i caratteri speciali). Nell'ultima schermata, quella relativa al compilatore, premete 'Finish' senza modificare nulla e a questo punto il vostro progetto base sarà nel workspace pronto per essere modificato.

A questo punto nella barra laterale sinistra navigate fino a trovare il file 'main.c'. Clickando due volte su di esso lo aprirete nell'editor e sarete pronti a modificarlo.

## Il main.c

Questo file di testo appena aperto è il file principale di ogni programma e contiene la funzione 'main()' che è la funzione attivata dal 'loader' quando viene lanciato il programma.

Come vediamo Codeblocks evidenzia con colori diversi le varie parti del codice. Possiamo distinguere in particolare due blocchi:

* le direttive al preprocessore (le prime due righe in verde che iniziano per #),
* la funzione 'main', composta dal suo nome e da alcune istruzioni racchiuse all'interno di parentesi graffe.


