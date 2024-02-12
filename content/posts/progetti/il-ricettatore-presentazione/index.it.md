---
title: "Il Ricettatore: un nuovo modo di scrivere le ricette"
date: 2024-02-11
description: Libro che si colloca a pieno titolo nel percorso formativo del modello della figura ibrida medico-data analitica.
image: ilricettatore_header.png
menu:
  sidebar:
    name: Il Ricettatore - Presentazione
    identifier: il-ricettatore-presentazione
    parent: projects
    weight: 1
tags: [ "Progetti", "Python", "Medicina" ]
---

## Background

La carenza dei Medici di Famiglia (Medici di Medicina Generale, MMG) - correlato allo scarso appeal, all’elevatissimo carico di lavoro richiesto, alle spese necessarie per l’ambulatorio, alla mancanza di diritti in termini di ferie e malattia, ma soprattutto al non adeguamento salariale già da svariati anni  -  è un problema sempre più concreto.

Per garantire, nei limiti del possibile, un’assistenza sanitaria anche se basica, sono numerose le Aziende Territoriali che stanno aprendo, nelle ore diurne, degli _ambulatori straordinari di Continuità Assistenziale_ chiamati, in base alla localizzazione regionale, anche _ASCOT_.
Il compito del medico incaricato del servizio è essenzialmente quello di garantire l'approvvigionamento farmaceutico all’utenza rimasta senza Medico di Medicina Generale. Per farlo, il lavoro consiste nella trascrizione dei farmaci nel __Ricettario Regionale__ fornito per l’incarico ed emettere una __ricetta rossa__.
Il lavoro di trascrizione spesso può essere lungo, impegnativo, ricco in errori: esenzioni, note, codici regionali sono solo alcuni degli errori in cui si può incorrere.

__Ma soprattutto faticoso__.

## L'idea

Dalla personale esperienza nel lavoro (ho svolto tale mansione in più regioni ed a più riprese, più per solidarietà e senso del dovere verso i pazienti tutti che per reale ritorno economico, anche perchè spesso la remunerazione non è così vantaggiosa) nasce così una nuova web-app:

__Il Ricettatore__

{{< img src="ilricettatore5.png" title="Il Ricettatore: prescrizione di esami" align="center">}}

## La web-app

Attualmente in versione __beta v0.2__, permette funzioni basiche ma essenziali per la sopravvivenza del medico in questi ambulatori provvisori. L’unico requisito è disporre di un __computer con accesso ad internet__ (in questa direzione il proprio laptop ed uno smartphone in tether possono essere strategici) ed una __stampante__.

{{< img src="ilricettatore1.png" title="Il Ricettatore: interfaccia per la prescrizione di farmaci" align="center" >}}

__Il Ricettatore__, che supporta anche la _lettura delle tessere sanitarie_ tramite lettore di barcode, permette di prescrivere qualunque farmaco possa essere trascritto sul Ricettario Regionale.

L’interfaccia web è essenziale ma potente e racchiude in poco spazio tutti i dati necessari per compilare una ricetta formalmente corretta. Sono di contorno il servizio per redigere (e stampare) _un referto su carta intestata al professionista_.

{{< img src="ilricettatore4.png" title="Il Ricettatore: interfaccia per la compilazione di un diario ed eventuale stampa" align="center" >}}

Non sarà necessario registrare il paziente in quanto verrà salvato automaticamente in caso non esista.
La funzione di Cronologia permette di prescrivere nuovamente tutti i farmaci precedentemente trascritti con pochi click, con un enorme risparmio di tempo, risorse ed energie.

{{< img src="ilricettatore3.png" title="Il Ricettatore: la cronologia" align="center" >}}

Riducendo gli errori di trascrizione, per cui spesso si rende necessario compilare una nuova ricetta, si va indirettamente anche a risparmiare sulle risorse pubbliche (ricordo che ogni Ricetta Rossa del Ricettario Regionale, prodotta dalla Zecca dello Stato e dotata di filigrana antiriproduzione, costa ben 1€!).

In caso al servizio sia concessa la prescrizione di esami laboratoristico-strumentali o consulenze, sarà concessa anche la loro prescrizione con pochi semplici click.

I _Profili per gli Esami del Sangue_ messi a disposizione permettono una più rapida scrittura delle richieste più comuni.

{{< img src="ilricettatore2.png" title="Il Ricettatore: interfaccia per la prescrizione di esami" align="center" >}}

## Funzionalità presenti

Attualmente permette le seguenti funzioni:
*   registrazione automatica del paziente
*   autocompletamento delle prescrizioni basato su Elenco farmaci dell’AIFA
*   suggerimento automatico sulle Note AIFA per i farmaci
*   Possibilità di prescrivere esami strumentali, laboratoristici o richiedere consulenze
*   Cronologia delle prescrizioni
*   Possibilità di esplicitare, in caso lo si ritenga, l’Induttore della prescrizione
*   Diario del Paziente, in caso si desideri scrivere due appunti sulla valutazione eseguita (ed eventualmente stamparla)

## Road map

Road-map previsto per lo sviluppo:
*   possibilità di firma digitale con registrazione blockchain della sessione di lavoro
*   integrazione multi-utente (ideale per medici che lavorano a turni negli stessi ambulatori)

## Video di presentazione
Attualemente è offerto __gratuitamente in versione Beta__ — accessibile al sito [ricettatore.cloud](https://ricettatore.cloud) — la cui registrazione è per il momento __tramite invito__.

{{< youtube id="Dmx54BrfqU4" title="Video presentazione" >}}