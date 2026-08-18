# Chimica Generale — Appunti

Riscrittura in LaTeX degli appunti del corso di **Chimica Generale**, a cura di Roberto Riccucci.

Il PDF compilato si trova in `build/Chimica.pdf`.

## Scopo del progetto

Questi appunti nascono con un obiettivo preciso: **avere un testo ordinato e completo con cui prepararsi all'esame**. L'idea è raccogliere in un unico documento la teoria necessaria, riscritta in modo leggibile e coerente, invece di dover saltare tra fogli sparsi e appunti presi di fretta.

Non sono quindi un manuale universitario né un sostituto del libro di testo: sono appunti d'esame.

## Cosa NON trovi qui: gli esercizi

Il documento contiene **solo teoria**. Non ci sono esercizi svolti né raccolte di problemi.

Non è una dimenticanza, è una scelta: per la parte pratica il modo migliore di prepararsi è **esercitarsi sugli esami passati**, che rispecchiano il livello, lo stile e il tipo di domande che si trovano davvero alla prova. Consiglio quindi di usare questi appunti per la teoria e le prove d'esame precedenti per l'allenamento sugli esercizi.

## Fonti e limiti (leggere prima di usarli)

Questi appunti si basano su **appunti scritti a mano da ex studenti del corso**, che ho riorganizzato, riscritto e formattato in LaTeX.

Va detto chiaramente: **io non ho frequentato le lezioni**. Non ho quindi ascoltato direttamente il docente, e tutto ciò che è qui dentro passa attraverso il filtro degli appunti altrui e della mia rielaborazione. Questo comporta alcuni rischi concreti:

- possono esserci **imprecisioni o errori** ereditati dagli appunti originali o introdotti da me nella riscrittura;
- alcuni passaggi potrebbero essere **interpretati male**, perché mancava il contesto della spiegazione a lezione;
- l'ordine degli argomenti e l'importanza data a ciascuno **potrebbero non coincidere** con quelli del corso;

## Struttura

```
Chimica.tex            documento principale
chapters/
  template.tex         preambolo, pacchetti e stile
  capitolo_1.tex       Teoria atomica
  capitolo_2.tex       Proprietà degli elementi
  capitolo_3.tex       Legami
  capitolo_4.tex       Rappresentazione delle molecole
  capitolo_5.tex       (in lavorazione)
foto/                  immagini e figure
build/                 output della compilazione (PDF)
```

## Compilazione

Il progetto si compila con `latexmk` e `pdflatex`:

```bash
latexmk -pdf -outdir=build Chimica.tex
```

Il PDF risultante è `build/Chimica.pdf`.

## Stato

Lavoro in corso — versione **v0.1**. I capitoli vengono aggiunti e rivisti man mano.

## Contatti

robertoriccucci1304@gmail.com
