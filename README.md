# Lectures notebooks

(Work in progress)

Note, esercizi e notebooks realizzati con Wolfram Mathematica. 


## Introduzione a Wolfram

### Licenza

Recentemente gli studenti dell'Università di Bologna hanno la possibilità di disporre di una licenza campus gratuita, come spiegato a [questa pagina](https://www.unibo.it/it/studiare/vivere-luniversita-e-la-citta/agevolazioni-per-computer-tablet-e-software/mathematica-licenza-campus).

Disponibile con licenza libera per tutti è anche il [Wolfram Engine](https://www.wolfram.com/engine/index.php.en), utilizzabile però solo da linea di comando.


### Note storiche

Già dalla fine degli anni '70 il fisico teorico Stephen Wolfram cominciò a sviluppare un linguaggio di programmazione in grado di automatizzare i calcoli matematici, specialmente quelli molto complicati della teoria quantistica dei campi (QFT). 

La sua idea fondamentale è stata di porre a fondamento del linguaggio non tipi di dati e calcoli numerici su di essi, ma espressioni generiche e regole di manipolazione simbolica su di esse. L'analogia è esattamente quella dell'algebra in cui, per esempio, si può considerare 'x' come qualsiasi cosa, invece che come un numero o un testo particolari.

Dopo un primo tentativo parzialmente fallito con la creazione del linguaggio SMP (Symbolic Manipulation Program), nel 1986 Stephen fonda la azienda Wolfram Research, che nel 1988 finalmente lancia la prima versione di Mathematica.

Mathematica è un nome storico, suggerito a Stephen Wolfram da Steve Jobs, secondo il principio: "Take the generic name for a thing and then romanticize it". Tuttavia, nei molti decenni questo software è diventato qualcosa di molto più generale della sola matematica. 

Così Stephen spesso definice il "Wolfram Language" come un "linguaggio computazionale", che costituisce una "notazione", che permette ai suoi user di "pensare computazionalmente", in analogia a come l'invenzione della notazione matematica, lontano dall'essere un fatto banale, ha facilitato il pensare e gli sviluppi scientifici. 

Infatti il linguaggio Wolfram ad oggi include oltre 6000 funzioni built-in, e spesso basta conoscerne l'esistenza per semplicemente applicarle a dati input e fare senza sforzo grandi cose.

(Oltre a queste 6500 funzioni circa sviluppate internamente da Wolfram Research con "painstaking" cura, si possono integrare ulteriori oltre 3000 "resource functions" contribuite  - anche dal sottoscritto, come mostrato in un altro [repository](https://github.com/Daniele-Gregori/ResourceFunctions) - e sempre revisionate e migliorate dalla casa madre, in analogia col processo di "peer review" per ogni pubblicazione scientifica.)

### Come imparare Wolfram

Oggigiorno la maniera migliore di imparare il linguaggio Wolfram è probabilmente con la [Wolfram U](https://www.wolfram.com/wolfram-u/), la sezione di Wolfram Research che fornisce molti corsi e certificazioni gratuite. 

In particolare è disponibile questa veloce introduzione per studenti di matematica:

- [Fast Introducion for Math Students](https://www.wolfram.com/language/fast-introduction-for-math-students/en/)

Più in dettaglio per i calcoli matematici sono disponibili ad esempio questi corsi interattivi:

- [Algebra lineare](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-linear-algebra/)
- [Analisi I](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-calculus/)
- [Analisi II](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-multivariable-calculus/)
- [Analisi complessa](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-complex-analysis/)
- [Equazioni differenziali](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-differential-equations/)
- [Funzioni speciali](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-special-functions/)
- [Trasformate di Laplace](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-laplace-transforms/)
- [Matematica discreta](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-discrete-mathematics/)
- [Matematica finita](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-finite-mathematics/)
- [Probabilità](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-probability/)
- [Statistica](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-statistics/)
- [Teoria dei giochi](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-decision-process-theory/)
- [Criptografia](https://www.wolfram.com/wolfram-u/courses/mathematics/introduction-to-cryptography/)


Efficace per la matematica è anche questo study group:

- [Mathematica and Wolfram Language for Mathematical Research and Study](https://www.wolfram.com/wolfram-u/courses/wolfram-language/dgs40-mathematica-wolfram-language-for-mathematics-research-study/)


Per avere un introduzione più generale al potente linguaggio Wolfram, breve e efficace è il libro di Stephen Wolfram:

- [An Elementary Introduction to the Wolfram Language](https://www.wolfram.com/language/elementary-introduction/3rd-ed/?source=nav)


Un interessante corso sugli aspetti più avanzati è questo:

- [A guide to Programming with Wolfram Language](https://www.wolfram.com/wolfram-u/courses/programming-applications/guide-to-programming/)

Infine la fonte più ampia a cui attingere è la documentazione del linguaggio Wolfram, molto approfondita e curata, contando qualcosa come 100 000 pagine: 

- [Wolfram Language Documentation](https://reference.wolfram.com/language/?source=nav)

La "punchline" è che Wolfram Research è riuscita a sostenere una filosofia di sviluppo software opposta a quella mainstream dei linguaggi opensource. Siccome per definizione lo sviluppo di questi non viene pagato, rimangono necessariamente o molto limitati (ad esempio Python conta circa 1% delle funzioni built-in di Wolfram) o lasciati allo sviluppo comunitario e volontario senza revisione di esperti. I programmatori usuali quindi devono spendere molto tempo e fatica a imparare tutto questo mondo open source disordinato e incompleto, o peggio affidarsi solo a chatbot che rischiano di commettere gravi errori e non insegnano nulla. Invece per esperienza posso garantire che la curva di apprendimento di Wolfram è molto più veloce e piacevole, perché è senza dubbio il "linguaggio computazionale" più curato e esteso.