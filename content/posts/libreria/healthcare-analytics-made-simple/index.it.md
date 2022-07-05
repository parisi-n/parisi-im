---
title: "Healthcare Analytics Made Simple - di Vikas Kumar"
date: 2022-07-04
description: Libro che si colloca a pieno titolo nel percorso formativo del modello della figura ibrida medico-data analitica.
image: cover_book.png
menu:
  sidebar:
    name: Healthcare Analytics Made Simple di Vikas Kumar
    identifier: healthcare-analytics-made-simple
    parent: libreria
    weight: 1
tags: [ "Libri", "Python", "ML" ]
---

{{< alert type="info" >}}
Questo post fa parte di un ciclo di post in cui parlo di un libro a mio avviso interessante nella formazione data analitica.

Trovi gli altri post [qui](/posts/libreria/).{{< /alert >}}

&nbsp;

La letteratura offerta ad oggi sul _machine learning_ è sconfinata ed offre differenti punti di vista e spunti d'apprendimento in base al linguaggio che al lettore sta più congeniale o - semplicemente - in base al linguaggio che l'utente pensa di poter o voler padroneggiare.
Il target di questi libri, reperibili facilmente in libreria, è per un pubblico _naive_ - di estrazione settoriale differente dall'IT - che studia e approfondisce i temi in libri più completi e tecnici.

Il difficile fino ad oggi è stato trovare qualcosa che - pur parlando di _ML e _AI_ - offrisse spunti di innovazione o _hint_ nel campo medico. Qualcosa che ispiri la _medical informatics_ che ci piace tanto: un nuovo progetto o l'_empowering_ di un progetto già in essere - aggiungendo feature fino a quel momento non ancora prese in considerazione.

È per questo che in questo post parlo in modo entusiasta di _Healthcare analytics made simple_ - scritto da Vikas Kumar.

## L'autore

Per comprenderne il _mindset_ ed il taglio ancor prima di leggere il libro è sufficiente uno sguardo al [profilo LinkedIn](https://www.linkedin.com/in/vikas-kumar-md-1a1a2525/) dell'autore.

Laureato in **Medicina** presso la _Pittsburgh University_ prosegue la sua formazione con un _master degree_ in **Scienze informatiche** presso il _Georgia Institute of Technology_.

Sul suo profilo si descrive rapidamente: "_Sr Data Scientist at OMNY Health | Teaching Assistant, Data & Visual Analytics at Georgia Tech | Author | Course Content Creator_".

## Il libro

### Per chi nasce?

Un libro scritto da un medico _per medici_ e _per data scientists_ che vorrebbero addentrarsi nel tema medico nel modo più diretto possibile ma con _step_.

Come detto più volte non sempre i due gruppi di professionisti sono interoperabili - e ciò rende le comunicazioni complesse e talvolta inefficaci; questo lo scopo del libro: fornire _ai medici le basi per metter su in modo rudimentale algoritmici di predizione_ e _ai data scientists di approcciarsi alla terminologia medica_.

Vengono spiegati nelle prime pagine *i rudimenti del linguaggio python*, come importare un **dataset con Numpy o Pandas** e quale dovrebbe essere l'approccio a step nel momento in cui si decide di analizzare un dataset (l'autore non lo dice esplicitamente, ma ricordiamo che nei dati vige la legge non scritta del **garbage in, garbage out**).

### Dettagliato

L'autore parte con un'_excursus_ su Numpy e Pandas - spiegando le principali possibilità e capacità delle due librerie nel momento in cui ci si approccia alla pulizia del database e alla sua riorganizzazione.

Non mancano le base statistiche teoriche che vengono rinfrescate durante tutta l'opera - per rendere la lettura più agevole.
Dopo una spazzolata su _sensitivity, sensibility, negative/positive predictive value, false-positive rate_ si passa poi a metter su un vero e proprio database di esempio basato su *SQLIte* e ne vengono analizzate le principali caratteristiche.

Di pari passo con i dati - si fa qualche riferimento anche alla libreria _matplotlib_ e di come possa essere inserita nella pipeline per produrre grafici che spesso aiutano a visualizzare meglio la distribuzione dei dati.

* * *

Un intero capitolo viene dedicato ai **database**: _SQL vs noSQL_, **perché scegliere SQL** ed introduce pian piano nella costruzione di una serie di tabelle destinate al salvataggio di **dati medici**.

Per chi è alle prime armi - questo potrebbe essere estremamente illuminante.

Si fanno cenni anche alle istruzioni **CURD**, con esempi base per comprenderne l'utilizzo: _Create_, _Update_, _Read_, _Delete_.

* * *

Una volta gettate le basi, viene spiegato **dove e come usarle**: si viene guidati nell'uso di un **Jupyter Notebook** per mettere in pratica le nozioni apprese e creare su alcuni modelli predittivi di reale utilità, selezionati secondo alcune _esigenze sanitarie degli Stati Uniti_.

* * *

L'ultimo capitolo viene dedicato ad una rapida panoramica del _deep learning_ ed ai problemi etici e morali che è necessario affrontare nel momento in cui si affida una parte delle scelte cliniche, seppur sotto supervisione, ad un algoritmo.

### Pratico

Circa metà del libro è dedicata alla realizzazione di progetti **pratici** e di uso reale: si tenta di sviluppare un modello per la **riduzione della riammissione in Pronto Soccorso del paziente** (misurando indirettamente la qualità delle cure) e un modello che **quantifica la qualità sanitaria fornita ai pazienti con ESRD** (End Stage Renal Disease);

## Considerazioni

Un libro assolutamente da consigliare ad **un medico** che decida di intraprendere, per ragioni di ricerca o di miglioramento delle performance del dipartimento, la strada dell'analisi dei dati o che cerchi un valido sostegno nella creazione di modelli predittivi _data-based_.

Anche i medici più navigati potrebbero giovare dalla lettura di questo libro. Se è vero che _repetita juvant_ - è anche vero che le competenze settoriali informatiche acquisite saranno comunque costantemente segmentarie ed orientata alla risoluzione di un problema piuttosto che alla creazione di una valida base culturale per approcciare multipli problemi di varia natura; proprio per questo motivo la trovo una lettura che, anche non aggiungendo nulla a competenze avanzate, fornisce un valido punto di vista **prettamente medico** alla realizzazione di modelli o infrastrutture informatiche di reale utilità.

Il mio parere: **consigliato assolutamente per chi inizia**.