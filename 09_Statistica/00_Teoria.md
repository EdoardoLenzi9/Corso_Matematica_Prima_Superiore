# 🎓 Lezione: Statistica

> 💡 Idea: la `statistica` nasce dalla necessità di **raccogliere**, **organizzare**, **rappresentare** e **interpretare** grandi quantità di dati

> 🎯 Obiettivo: comprendere come si raccolgono i dati statistici, come si organizzano attraverso le `frequenze`, come si rappresentano graficamente e come si calcolano i principali `indici di posizione e di variabilità`.

![](assets/011.svg)

# 📌 Statistica

> 🤏 Definizione: la `statistica` è la disciplina che si occupa di **raccogliere**, **organizzare**, **rappresentare**, **analizzare** e **interpretare** dei `dati`

I dati possono descrivere fenomeni molto diversi:

* altezza degli studenti di una classe
* numero di figli per famiglia
* colore degli occhi
* temperatura durante una giornata
* numero di libri letti in un mese
* voto ottenuto in una verifica

> 💡 Idea: un insieme di dati, preso singolarmente, spesso dice poco. La statistica permette di trasformare una grande quantità di dati in `informazioni` facilmente leggibili.

# 📌 Popolazione e campione

> 🤏 Definizione: la `popolazione statistica` è l'insieme di tutti gli elementi che vogliamo studiare

> 🤏 Definizione: un `campione` è un sottoinsieme della popolazione scelto per effettuare lo studio

## 🚀 Esempio

Vogliamo conoscere l'altezza media degli studenti di una scuola con 800 studenti.

* `Popolazione`: tutti gli 800 studenti della scuola
* `Campione`: 50 studenti scelti per effettuare la misurazione

> 🤔 Domanda: sarebbe possibile misurare tutti gli 800 studenti invece di utilizzare un campione?

# 📌 Carattere statistico

> 🤏 Definizione: il `carattere statistico` è la proprietà o caratteristica che viene osservata su ogni elemento della popolazione

## 🚀 Esempio

Consideriamo gli studenti di una classe e osserviamo:

* altezza
* età
* colore degli occhi
* numero di fratelli

In questo caso i `caratteri statistici` sono rispettivamente:

* `altezza`
* `età`
* `colore degli occhi`
* `numero di fratelli`

I valori assunti dal carattere si chiamano `modalità`.

Per esempio, se il carattere è `colore degli occhi`, alcune modalità possono essere:

\(\{\text{marroni},\text{azzurri},\text{verdi},\text{neri}\}\)

# 📌 Tipi di carattere

I caratteri statistici possono essere principalmente `qualitativi` oppure `quantitativi`.

## 📚 Carattere qualitativo

> 🤏 Definizione: un carattere è `qualitativo` quando le sue modalità descrivono una `qualità` e non sono espresse da numeri

## 🚀 Esempio

Il carattere `colore degli occhi` può assumere le modalità:

\(\{\text{marroni},\text{azzurri},\text{verdi}\}\)

## 📚 Carattere quantitativo

> 🤏 Definizione: un carattere è `quantitativo` quando le sue modalità sono espresse attraverso `numeri`

## 🚀 Esempio

Il carattere `numero di fratelli` può assumere le modalità:

\(\{0,1,2,3,\dots\}\)

Un carattere quantitativo può essere:

* `discreto`, quando assume valori separati, tipicamente interi
* `continuo`, quando può assumere qualsiasi valore all'interno di un intervallo

## 🚀 Esempio

Il `numero di fratelli` è un carattere quantitativo `discreto`:

\(0,\ 1,\ 2,\ 3,\dots\)

L'`altezza` è invece un carattere quantitativo `continuo`, perché può assumere valori come:

\(170\text{ cm},\ 170.5\text{ cm},\ 170.53\text{ cm},\dots\)

# 📌 Rilevazione dei dati statistici

> 🤏 Definizione: la `rilevazione statistica` è il processo attraverso il quale vengono raccolti i dati necessari per uno studio

Possiamo immaginare il processo statistico in questo modo:

$$
\text{rilevazione}
\rightarrow
\text{organizzazione}
\rightarrow
\text{rappresentazione}
\rightarrow
\text{analisi}
\rightarrow
\text{interpretazione}
$$

## 📚 Rilevazione

I dati possono essere raccolti attraverso:

* `osservazione`
* `misurazione`
* `intervista`
* `questionario`
* `esperimento`

## 🚀 Esempio

Vogliamo sapere quale sia lo sport preferito dagli studenti di una classe.

Possiamo chiedere ad ogni studente:

> 🤔 Domanda: qual è il tuo sport preferito?

Supponiamo di ottenere:

$$
\text{calcio},\text{nuoto},\text{calcio},\text{tennis},\text{calcio},\text{nuoto},\text{tennis},\text{calcio}
$$

Abbiamo quindi raccolto i `dati grezzi`.

> 💡 Idea: i dati grezzi sono spesso difficili da leggere. Per questo motivo dobbiamo `organizzarli`.

# 📌 Frequenza

> 🤏 Definizione: la `frequenza` indica quante volte una determinata modalità compare nella raccolta dei dati

Esistono diversi tipi di frequenza:

* `frequenza assoluta`
* `frequenza relativa`
* `frequenza percentuale`
* `frequenza cumulata`

# 📌 Frequenza assoluta

> 🤏 Definizione: la `frequenza assoluta` di una modalità è il numero di volte in cui quella modalità compare nei dati

Si indica generalmente con:

\(f_i\)

## 🚀 Esempio

Consideriamo i voti ottenuti da 10 studenti:

$$
6,\ 7,\ 8,\ 6,\ 9,\ 7,\ 6,\ 8,\ 7,\ 10
$$

Costruiamo una tabella:

| Voto | Frequenza assoluta |
| ---: | -----------------: |
|    6 |                  3 |
|    7 |                  3 |
|    8 |                  2 |
|    9 |                  1 |
|   10 |                  1 |

La somma delle frequenze assolute deve essere uguale al numero totale dei dati:

$$
3+3+2+1+1=10
$$

Quindi:

$$
\sum_i f_i = n
$$

dove `n` è il numero totale delle osservazioni.

> 🤔 Domanda: quale voto compare più frequentemente?

# 📌 Frequenza relativa

> 🤏 Definizione: la `frequenza relativa` è il rapporto tra la frequenza assoluta di una modalità e il numero totale dei dati

Si indica generalmente con:

$$
h_i=\frac{f_i}{n}
$$

## 🚀 Esempio

Nel caso precedente il voto `6` compare 3 volte su 10.

Quindi:

$$
h_6=\frac{3}{10}=0.3
$$

La frequenza relativa del voto `6` è quindi `0.3`.

Vale sempre:

$$
\sum_i h_i=1
$$

# 📌 Frequenza percentuale

> 🤏 Definizione: la `frequenza percentuale` esprime la frequenza relativa sotto forma di percentuale

Si calcola:

$$
p_i=h_i\times100
$$

oppure:

$$
p_i=\frac{f_i}{n}\times100
$$

## 🚀 Esempio

Per il voto `6`:

$$
p_6=\frac{3}{10}\times100=30\%
$$

Quindi il `30%` degli studenti ha ottenuto voto `6`.

Vale sempre:

$$
\sum_i p_i=100\%
$$

## 🚀 Esempio

Completiamo la tabella:

|     Voto | Frequenza assoluta | Frequenza relativa | Frequenza percentuale |
| -------: | -----------------: | -----------------: | --------------------: |
|        6 |                  3 |                0.3 |                   30% |
|        7 |                  3 |                0.3 |                   30% |
|        8 |                  2 |                0.2 |                   20% |
|        9 |                  1 |                0.1 |                   10% |
|       10 |                  1 |                0.1 |                   10% |
| `Totale` |               `10` |                `1` |                `100%` |

> 💡 Idea: frequenza assoluta, relativa e percentuale descrivono la stessa informazione utilizzando `unità di misura` diverse.

# 📌 Frequenza cumulata

> 🤏 Definizione: la `frequenza cumulata` di una modalità è la somma delle frequenze assolute della modalità stessa e di tutte le modalità precedenti

La frequenza cumulata ha senso quando le modalità possono essere `ordinate`.

Si indica generalmente con:

$$
F_i
$$

## 🚀 Esempio

Consideriamo ancora i voti:

| Voto | Frequenza assoluta | Frequenza cumulata |
| ---: | -----------------: | -----------------: |
|    6 |                  3 |                  3 |
|    7 |                  3 |                  6 |
|    8 |                  2 |                  8 |
|    9 |                  1 |                  9 |
|   10 |                  1 |                 10 |

Per esempio, la frequenza cumulata del voto `8` vale:

$$
F_8=3+3+2=8
$$

Questo significa che `8` studenti hanno ottenuto un voto `minore o uguale a 8`.

L'ultima frequenza cumulata deve coincidere con il numero totale dei dati:

$$
F_k=n
$$

> 🤔 Domanda: quanti studenti hanno ottenuto un voto minore o uguale a 9?

# 📌 Tabella delle frequenze

Possiamo raccogliere tutte le informazioni in un'unica tabella:

|     Voto | Frequenza assoluta | Frequenza relativa | Frequenza percentuale | Frequenza cumulata |
| -------: | -----------------: | -----------------: | --------------------: | -----------------: |
|        6 |                  3 |                0.3 |                   30% |                  3 |
|        7 |                  3 |                0.3 |                   30% |                  6 |
|        8 |                  2 |                0.2 |                   20% |                  8 |
|        9 |                  1 |                0.1 |                   10% |                  9 |
|       10 |                  1 |                0.1 |                   10% |                 10 |
| `Totale` |               `10` |                `1` |                `100%` |               `10` |

> 💡 Idea: una tabella delle frequenze permette di passare rapidamente dai `dati grezzi` ad una rappresentazione organizzata del fenomeno.

# 📌 Rappresentazioni grafiche

> 🤏 Definizione: una `rappresentazione grafica` permette di visualizzare i dati attraverso elementi geometrici come barre, settori o punti

Le principali rappresentazioni sono:

* `diagramma a barre`
* `istogramma`
* `diagramma circolare`
* `diagramma cartesiano`
* `grafico lineare`

La scelta del grafico dipende dal tipo di dati che vogliamo rappresentare.

# 📌 Diagramma a barre

Il `diagramma a barre` rappresenta le diverse modalità attraverso barre separate.

## 🚀 Esempio

Consideriamo il numero di libri letti da alcuni studenti:

| Libri | Frequenza |
| ----: | --------: |
|     0 |         2 |
|     1 |         5 |
|     2 |         4 |
|     3 |         3 |

Possiamo rappresentare questi dati con un diagramma a barre:

![](assets/012.svg)

> 💡 Idea: l'altezza di ogni barra rappresenta la `frequenza` della modalità.

# 📌 Istogramma

> 🤏 Definizione: l'`istogramma` è una rappresentazione grafica utilizzata principalmente per caratteri quantitativi continui o per dati raggruppati in intervalli

A differenza del diagramma a barre, nell'istogramma le barre sono generalmente `adiacenti`.

## 🚀 Esempio

Consideriamo le altezze di un gruppo di studenti:

| Altezza        | Frequenza |
| -------------- | --------: |
| $150\le x<160$ |         3 |
| $160\le x<170$ |         8 |
| $170\le x<180$ |         6 |
| $180\le x<190$ |         3 |

![](assets/013.svg)

# 📌 Diagramma circolare

> 🤏 Definizione: il `diagramma circolare` rappresenta i dati attraverso settori di un cerchio, la cui ampiezza è proporzionale alla frequenza

Un cerchio completo misura:

\(360^\circ\)

Se una modalità rappresenta una frequenza relativa $h_i$, l'angolo del relativo settore vale:

$$
\alpha_i=h_i\times360^\circ
$$

## 🚀 Esempio

Se il `25%` degli studenti preferisce il calcio:

$$
\alpha=0.25\times360^\circ=90^\circ
$$

Il settore relativo al calcio avrà quindi un'ampiezza di:

\(90^\circ\)

![](assets/014.svg)

# 📌 Grafico cartesiano

Un `grafico cartesiano` permette di rappresentare una relazione tra due grandezze.

Per esempio possiamo rappresentare la temperatura misurata durante una giornata:

| Ora | Temperatura |
| --: | ----------: |
|   8 | $12^\circ$C |
|  10 | $15^\circ$C |
|  12 | $19^\circ$C |
|  14 | $22^\circ$C |
|  16 | $20^\circ$C |
|  18 | $17^\circ$C |

![](assets/015.svg)

> 💡 Idea: un grafico rende immediatamente visibili `andamenti`, `aumenti`, `diminuzioni` e `confronti` che sarebbero meno evidenti osservando solamente una tabella.

# 📌 Indici di posizione

> 💡 Idea: dopo aver raccolto e rappresentato i dati, possiamo cercare un valore che ci permetta di descrivere la loro `posizione` in modo sintetico.

I principali `indici di posizione` sono:

* `moda`
* `media aritmetica`
* `mediana`

# 📌 Moda

> 🤏 Definizione: la `moda` è la modalità che presenta la frequenza più alta

## 🚀 Esempio

Consideriamo:

$$
2,\ 3,\ 3,\ 4,\ 5,\ 3,\ 6
$$

Il numero `3` compare più volte di tutti gli altri.

Quindi:

$$
\text{Moda}=3
$$

> 🤔 Domanda: può esistere più di una moda?

> 💡 Idea: sì. Se due o più modalità hanno la stessa frequenza massima, la distribuzione può avere più mode.

# 📌 Media aritmetica

> 🤏 Definizione: la `media aritmetica` è il rapporto tra la somma di tutti i dati e il numero totale dei dati

Per `n` dati $x_1,x_2,\dots,x_n$:

$$
\bar{x}=\frac{x_1+x_2+\dots+x_n}{n}
$$

oppure:

$$
\bar{x}=\frac{1}{n}\sum_{i=1}^{n}x_i
$$

## 🚀 Esempio

Consideriamo:

$$
4,\ 6,\ 7,\ 8,\ 10
$$

La media vale:

$$
\bar{x}=\frac{4+6+7+8+10}{5}
$$

$$
\bar{x}=\frac{35}{5}=7
$$

Quindi:

$$
\boxed{\bar{x}=7}
$$

# 📌 Media con le frequenze

Quando abbiamo una tabella delle frequenze, possiamo calcolare la media utilizzando le frequenze assolute:

$$
\bar{x}=
\frac{x_1f_1+x_2f_2+\dots+x_kf_k}{n}
$$

## 🚀 Esempio

Consideriamo:

| Voto | Frequenza |
| ---: | --------: |
|    6 |         3 |
|    7 |         3 |
|    8 |         2 |
|    9 |         1 |
|   10 |         1 |

La media vale:

$$
\bar{x}=
\frac{6\cdot3+7\cdot3+8\cdot2+9\cdot1+10\cdot1}{10}
$$

$$
\bar{x}=
\frac{18+21+16+9+10}{10}
$$

$$
\bar{x}=\frac{74}{10}=7.4
$$

# 📌 Mediana

> 🤏 Definizione: la `mediana` è il valore che, una volta ordinati i dati, divide la distribuzione in due parti contenenti lo stesso numero di osservazioni, con le consuete modalità di gestione del caso pari

## 🚀 Esempio

Consideriamo:

$$
2,\ 4,\ 5,\ 7,\ 9
$$

I dati sono già ordinati e quello centrale è `5`.

Quindi:

$$
\text{Mediana}=5
$$

Se il numero dei dati è `pari`, prendiamo la media dei due valori centrali.

## 🚀 Esempio

Consideriamo:

$$
2,\ 4,\ 5,\ 7,\ 9,\ 10
$$

I due valori centrali sono `5` e `7`.

Quindi:

$$
\text{Mediana}=\frac{5+7}{2}=6
$$

> 💡 Idea: la `media` utilizza tutti i valori, mentre la `mediana` dipende soprattutto dalla loro posizione nell'ordinamento.

# 📌 Confronto tra media, mediana e moda

Consideriamo i dati:

$$
2,\ 3,\ 3,\ 4,\ 8
$$

La `moda` vale:

$$
\text{Moda}=3
$$

La `mediana` vale:

$$
\text{Mediana}=3
$$

La `media` vale:

$$
\bar{x}=\frac{2+3+3+4+8}{5}=4
$$

Abbiamo quindi:

$$
\text{Moda}=3
$$

$$
\text{Mediana}=3
$$

$$
\text{Media}=4
$$

> 💡 Idea: media, mediana e moda possono assumere valori differenti perché descrivono il fenomeno da punti di vista diversi.

# 📌 Indici di variabilità

> 💡 Idea: conoscere un valore centrale non è sufficiente. Due distribuzioni possono avere la stessa media ma essere molto diverse nella loro `dispersione`.

I principali `indici di variabilità` sono:

* `campo di variazione`
* `varianza`
* `deviazione standard`

# 📌 Campo di variazione

> 🤏 Definizione: il `campo di variazione` è la differenza tra il valore massimo e il valore minimo dei dati

Si indica generalmente con:

$$
R=x_{\max}-x_{\min}
$$

## 🚀 Esempio

Consideriamo:

$$
3,\ 5,\ 6,\ 8,\ 10
$$

Il massimo è `10`, il minimo è `3`.

Quindi:

$$
R=10-3=7
$$

# 📌 Varianza

> 🤏 Definizione: la `varianza` misura quanto i dati si discostano mediamente dalla loro media, considerando i quadrati degli scarti

Per una popolazione di `n` dati:

$$
\sigma^2=
\frac{1}{n}
\sum_{i=1}^{n}(x_i-\bar{x})^2
$$

dove:

* $x_i$ è un dato
* $\bar{x}$ è la media
* $x_i-\bar{x}$ è lo `scarto dalla media`
* $(x_i-\bar{x})^2$ è lo `scarto quadratico`

## 🚀 Esempio

Consideriamo:

$$
2,\ 4,\ 6
$$

La media vale:

$$
\bar{x}=\frac{2+4+6}{3}=4
$$

Gli scarti dalla media sono:

$$
2-4=-2
$$

$$
4-4=0
$$

$$
6-4=2
$$

I quadrati degli scarti sono:

$$
(-2)^2=4
$$

$$
0^2=0
$$

$$
2^2=4
$$

Quindi la varianza vale:

$$
\sigma^2=\frac{4+0+4}{3}
$$

$$
\sigma^2=\frac83
$$

# 📌 Deviazione standard

> 🤏 Definizione: la `deviazione standard` è la radice quadrata della varianza

Si indica generalmente con:

$$
\sigma
$$

e vale:

$$
\sigma=\sqrt{\sigma^2}
$$

Nell'esempio precedente:

$$
\sigma=\sqrt{\frac83}\approx1.63
$$

> 💡 Idea: la deviazione standard è espressa nella `stessa unità di misura` dei dati, mentre la varianza è espressa nell'unità di misura `al quadrato`.

# 📌 Interpretare la variabilità

Consideriamo due gruppi:

$$
A=\{4,5,5,6,5\}
$$

$$
B=\{1,3,5,7,9\}
$$

Entrambi hanno media:

$$
\bar{x}=5
$$

Ma i dati del gruppo `B` sono molto più lontani dalla media rispetto a quelli del gruppo `A`.

> 🤔 Domanda: quale dei due gruppi presenta maggiore variabilità?

> 💡 Idea: una `media` simile non significa necessariamente che i dati siano distribuiti nello stesso modo.

# 📌 Esercizi

1. Considera i dati:
   \(2,\ 4,\ 4,\ 5,\ 7,\ 4,\ 8\)

   Trova la `moda`.

2. Considera i dati:
   \(3,\ 5,\ 7,\ 8,\ 12\)

   Calcola la `media`.

3. Considera i dati:
   \(2,\ 4,\ 5,\ 8,\ 10\)

   Trova la `mediana`.

4. Considera i dati:
   \(3,\ 5,\ 7,\ 10,\ 12\)

   Calcola il `campo di variazione`.

5. In una classe vengono rilevati i seguenti numeri di libri letti durante un mese:

   \(0,\ 1,\ 2,\ 1,\ 3,\ 2,\ 1,\ 4,\ 2,\ 1\)

   Costruisci la tabella delle `frequenze assolute`.

6. Completa per gli stessi dati la `frequenza relativa`.

7. Trasforma le frequenze relative in `frequenze percentuali`.

8. Calcola la `frequenza cumulata`.

9. Rappresenta i dati attraverso un `diagramma a barre`.

10. Calcola `media`, `mediana` e `moda`.

# 📌 Esercizio completo

Consideriamo i voti ottenuti da 20 studenti:

$$
6,\ 7,\ 8,\ 6,\ 9,\ 7,\ 6,\ 8,\ 7,\ 10,
$$

$$
8,\ 6,\ 9,\ 7,\ 8,\ 6,\ 10,\ 7,\ 9,\ 8
$$

> 🤔 Domanda: come possiamo trasformare questi dati grezzi in informazioni utili?

## 📚 Passo 1: tabella delle frequenze

|     Voto | Frequenza assoluta |
| -------: | -----------------: |
|        6 |                  5 |
|        7 |                  5 |
|        8 |                  5 |
|        9 |                  3 |
|       10 |                  2 |
| `Totale` |               `20` |

## 📚 Passo 2: frequenze relative

$$
h_i=\frac{f_i}{20}
$$

| Voto | Frequenza assoluta | Frequenza relativa |
| ---: | -----------------: | -----------------: |
|    6 |                  5 |               0.25 |
|    7 |                  5 |               0.25 |
|    8 |                  5 |               0.25 |
|    9 |                  3 |               0.15 |
|   10 |                  2 |               0.10 |

## 📚 Passo 3: frequenze percentuali

$$
p_i=h_i\times100
$$

| Voto | Frequenza percentuale |
| ---: | --------------------: |
|    6 |                   25% |
|    7 |                   25% |
|    8 |                   25% |
|    9 |                   15% |
|   10 |                   10% |

## 📚 Passo 4: frequenze cumulate

| Voto | Frequenza assoluta | Frequenza cumulata |
| ---: | -----------------: | -----------------: |
|    6 |                  5 |                  5 |
|    7 |                  5 |                 10 |
|    8 |                  5 |                 15 |
|    9 |                  3 |                 18 |
|   10 |                  2 |                 20 |

## 📚 Passo 5: media

$$
\bar{x}=
\frac{6\cdot5+7\cdot5+8\cdot5+9\cdot3+10\cdot2}{20}
$$

$$
\bar{x}=
\frac{30+35+40+27+20}{20}
$$

$$
\bar{x}=\frac{152}{20}=7.6
$$

Quindi:

$$
\boxed{\bar{x}=7.6}
$$

## 📚 Passo 6: moda

Le frequenze massime sono:

$$
f=5
$$

e corrispondono ai voti:

$$
6,\ 7,\ 8
$$

Quindi la distribuzione è `trimodale`:

$$
\boxed{\text{Moda}=\{6,7,8\}}
$$

## 📚 Passo 7: mediana

Abbiamo `20` dati.

Essendo il numero di dati pari, prendiamo la media tra il `10^\circ` e l'`11^\circ` valore ordinato.

La sequenza ordinata contiene:

$$
6,6,6,6,6,
7,7,7,7,7,
8,8,8,8,8,
9,9,9,
10,10
$$

Il `10^\circ` valore è `7` e l'`11^\circ` valore è `8`.

Quindi:

$$
\text{Mediana}=\frac{7+8}{2}=7.5
$$

# 📌 Riepilogo

Abbiamo imparato che:

* la `statistica` permette di raccogliere, organizzare, rappresentare, analizzare e interpretare i dati
* la `popolazione statistica` è l'insieme completo degli elementi che vogliamo studiare
* un `campione` è un sottoinsieme della popolazione utilizzato per effettuare uno studio
* il `carattere statistico` è la proprietà che viene osservata sugli elementi della popolazione
* le `modalità` sono i valori o le categorie che il carattere può assumere
* un carattere può essere `qualitativo` oppure `quantitativo`
* un carattere quantitativo può essere `discreto` oppure `continuo`
* la `rilevazione statistica` permette di raccogliere i dati necessari allo studio
* i dati raccolti inizialmente possono essere chiamati `dati grezzi`
* la `frequenza assoluta` indica quante volte compare una determinata modalità:
  \(f_i\)
* la somma delle frequenze assolute è uguale al numero totale dei dati:
  \(\sum_i f_i=n\)
* la `frequenza relativa` è il rapporto tra frequenza assoluta e numero totale dei dati:
  \(h_i=\frac{f_i}{n}\)
* la somma delle frequenze relative vale:
  \(\sum_i h_i=1\)
* la `frequenza percentuale` si ottiene moltiplicando la frequenza relativa per 100:
  \(p_i=h_i\times100\)
* la somma delle frequenze percentuali vale:
  \(\sum_i p_i=100\%\)
* la `frequenza cumulata` somma progressivamente le frequenze assolute delle modalità ordinate:
  \(F_i=f_1+f_2+\dots+f_i\)
* l'ultima frequenza cumulata coincide con il numero totale dei dati:
  \(F_k=n\)
* le principali `rappresentazioni grafiche` sono diagramma a barre, istogramma, diagramma circolare e grafico cartesiano
* il `diagramma a barre` rappresenta le modalità attraverso barre separate
* l'`istogramma` viene utilizzato principalmente per dati quantitativi continui o raggruppati in intervalli
* il `diagramma circolare` rappresenta le frequenze attraverso settori di un cerchio
* l'angolo di un settore circolare si può calcolare con:
  \(\alpha_i=h_i\times360^\circ\)
* la `moda` è la modalità con frequenza massima
* la `media aritmetica` è il rapporto tra la somma dei dati e il loro numero:
  \(\bar{x}=\frac{x_1+x_2+\dots+x_n}{n}\)
* utilizzando le frequenze, la media può essere calcolata come:
  \(\bar{x}=\frac{\sum_i x_if_i}{n}\)
* la `mediana` è il valore centrale dei dati ordinati, oppure la media dei due valori centrali quando il numero dei dati è pari
* gli `indici di variabilità` permettono di descrivere quanto i dati sono dispersi
* il `campo di variazione` è la differenza tra valore massimo e valore minimo:
  \(R=x_{\max}-x_{\min}\)
* la `varianza` misura la dispersione dei dati rispetto alla media:
  \(\sigma^2=\frac{1}{n}\sum_{i=1}^{n}(x_i-\bar{x})^2\)
* la `deviazione standard` è la radice quadrata della varianza:
  \(\sigma=\sqrt{\sigma^2}\)
* una distribuzione con maggiore `deviazione standard` presenta generalmente una maggiore dispersione dei dati rispetto alla propria media

> 💡 Idea: la statistica ci permette di passare dai **dati** alle **informazioni**, trasformando una raccolta di numeri o categorie in qualcosa che possiamo leggere, confrontare e interpretare.

$$
\boxed{
\text{Dati}
\rightarrow
\text{Frequenze}
\rightarrow
\text{Grafici}
\rightarrow
\text{Indici}
\rightarrow
\text{Informazioni}
}
$$

Ogni fase risponde a una nuova esigenza:

$$
\text{Rilevare}
\xrightarrow{\text{organizzare}}
\text{Frequenze}
\xrightarrow{\text{rappresentare}}
\text{Grafici}
\xrightarrow{\text{sintetizzare}}
\text{Indici}
$$
