# 🎓 Lezione: Frazioni Algebriche

> 💡 Idea: una `frazione algebrica` estende il concetto di frazione, sostituendo
> ai numeri `lettere` e `espressioni algebriche`

> 🎯 Obiettivo: comprendere come definire, semplificare e operare con le
> **frazioni algebriche**, fino alla risoluzione delle **equazioni fratte**.

# 📌 Frazione algebrica

> 🤏 Definizione: una `frazione algebrica` e' un rapporto tra due
> `espressioni algebriche`, con denominatore diverso da zero

$$
\frac{A}{B}
$$

dove `A` e `B` sono espressioni algebriche e deve valere:

$$B\not=0$$

## 🚀 Esempi

Sono frazioni algebriche:

$$
\frac{x}{2}
$$

$$
\frac{3x+1}{x-2}
$$

$$
\frac{x^2-4}{x+3}
$$

$$
\frac{2x+1}{x^2-9}
$$

> 🤔 Domanda: quali sono numeratore e denominatore nella frazione
> $\frac{x^2-4}{x+3}$?

* `Numeratore`: $x^2-4$
* `Denominatore`: $x+3$

# 📌 Condizioni di esistenza (`C.E.`)

> 💡 Idea: nelle frazioni numeriche non possiamo dividere per `0`.
> Lo stesso vale per le frazioni algebriche: il `denominatore non puo' essere zero`

Consideriamo:

$$
\frac{3}{x-2}
$$

Il denominatore deve essere diverso da zero:

$$
x-2\not=0
$$

quindi:

$$
x\not=2
$$

La `condizione di esistenza` e':

$$
C.E.: x\not=2
$$

## 🚀 Esempio

Consideriamo:

$$
\frac{x+1}{x^2-9}
$$

Troviamo le condizioni di esistenza imponendo il denominatore diverso da zero:

$$
x^2-9\not=0
$$

Scomponiamo:

$$
(x-3)(x+3)\not=0
$$

Quindi:

$$
x\not=3
\qquad
x\not=-3
$$

La `C.E.` e':

$$
C.E.: x\not=\pm3
$$

## 🚀 Esercizi

* Trova la `C.E.` di $\frac{1}{x-5}$
* Trova la `C.E.` di $\frac{2x}{x+4}$
* Trova la `C.E.` di $\frac{x+1}{x^2-16}$
* Trova la `C.E.` di $\frac{3}{x^2-5x}$

# 📌 Frazione algebrica nulla

> 🤏 Definizione: una frazione algebrica vale `0` quando il `numeratore` e'
> uguale a zero e contemporaneamente il denominatore e' diverso da zero

$$
\frac{A}{B}=0
\iff
\begin{cases}
A=0\\
B\not=0
\end{cases}
$$

## 🚀 Esempio

Consideriamo:

$$
\frac{x-3}{x+2}=0
$$

Perche' la frazione sia nulla deve essere:

$$
x-3=0
$$

quindi:

$$
x=3
$$

Controlliamo la `C.E.`:

$$
x+2\not=0
\Rightarrow x\not=-2
$$

Quindi $x=3$ e' una soluzione.

# 📌 Semplificazione

> 💡 Idea: come nelle frazioni numeriche, possiamo `semplificare` una frazione
> algebrica dividendo numeratore e denominatore per uno stesso `fattore diverso da zero`

Consideriamo:

$$
\frac{6x}{9x}
$$

Possiamo raccogliere e semplificare il fattore comune:

$$
\frac{6x}{9x}
=
\frac{2\cancel{x}}{3\cancel{x}}
=
\frac23
$$

Ma attenzione:

$$
x\not=0
$$

Quindi:

$$
\frac{6x}{9x}=\frac23
\qquad
C.E.:x\not=0
$$

> ⚠️ Attenzione: `semplificare` non significa eliminare una condizione di esistenza.
> La condizione $x\not=0$ rimane valida anche dopo la semplificazione.

# 📌 Scomposizione del numeratore e del denominatore

> 💡 Idea: per semplificare una frazione algebrica spesso dobbiamo prima
> `scomporre` numeratore e denominatore in fattori

## 🚀 Esempio

Consideriamo:

$$
\frac{x^2-9}{x^2+3x}
$$

Scomponiamo numeratore e denominatore:

$$
\frac{(x-3)(x+3)}{x(x+3)}
$$

Ora possiamo semplificare il fattore comune $(x+3)$:

$$
\frac{(x-3)\cancel{(x+3)}}{x\cancel{(x+3)}}
=
\frac{x-3}{x}
$$

Ma dobbiamo ricordare la `C.E.` originale:

$$
x^2+3x\not=0
$$

$$
x(x+3)\not=0
$$

quindi:

$$
x\not=0
\qquad
x\not=-3
$$

Pertanto:

$$
\frac{x^2-9}{x^2+3x}
=
\frac{x-3}{x}
\qquad
C.E.:x\not=0,\ x\not=-3
$$

## 🚀 Esercizi

* Semplifica $\frac{4x^2}{8x}$
* Semplifica $\frac{x^2-4}{x+2}$
* Semplifica $\frac{x^2-9}{x^2-3x}$
* Semplifica $\frac{x^2+5x}{x^2+10x+25}$

# 📌 Moltiplicazione

> 🤏 Regola: per moltiplicare due frazioni algebriche si moltiplicano
> `numeratore per numeratore` e `denominatore per denominatore`

$$
\frac{A}{B}\cdot\frac{C}{D}
=
\frac{AC}{BD}
$$

Naturalmente devono essere rispettate le `condizioni di esistenza`:

$$
B\not=0
\qquad
D\not=0
$$

## 🚀 Esempio

$$
\frac{x}{x+1}\cdot\frac{x+1}{x-2}
$$

Possiamo semplificare $(x+1)$:

$$
\frac{x\cancel{(x+1)}}{(x+1)(x-2)}
=
\frac{x}{x-2}
$$

Le condizioni di esistenza vengono dal denominatore originale:

$$
x+1\not=0
\qquad
x-2\not=0
$$

quindi:

$$
C.E.:x\not=-1,\ x\not=2
$$

# 📌 Divisione

> 🤏 Regola: per dividere due frazioni algebriche si moltiplica la prima
> per `l'inversa` della seconda

$$
\frac{A}{B}:\frac{C}{D}
=
\frac{A}{B}\cdot\frac{D}{C}
=
\frac{AD}{BC}
$$

Inoltre la frazione per cui dividiamo deve essere `diversa da zero`:

$$
\frac{C}{D}\not=0
$$

quindi:

$$
C\not=0
$$

## 🚀 Esempio

$$
\frac{x}{x+1}:\frac{x-2}{x+3}
$$

Trasformiamo la divisione in moltiplicazione:

$$
\frac{x}{x+1}\cdot\frac{x+3}{x-2}
$$

Otteniamo:

$$
\frac{x(x+3)}{(x+1)(x-2)}
$$

Le condizioni sono:

$$
x+1\not=0
$$

$$
x-2\not=0
$$

e, poiche' stiamo dividendo per $\frac{x-2}{x+3}$, deve inoltre essere:

$$
x-2\not=0
$$

Quindi:

$$
C.E.:x\not=-1,\ x\not=2,\ x\not=-3
$$

> ⚠️ Attenzione: nella divisione bisogna controllare anche che la
> `frazione divisore` non sia nulla.

# 📌 Addizione e sottrazione

> 💡 Idea: per sommare o sottrarre frazioni algebriche dobbiamo prima
> trovare un `denominatore comune`

## 🚀 Esempio

Consideriamo:

$$
\frac{2}{x}+\frac{3}{x}
$$

Il denominatore e' gia' comune:

$$
\frac{2+3}{x}
=
\frac5x
$$

con:

$$
C.E.:x\not=0
$$

## 🚀 Esempio

Consideriamo:

$$
\frac{1}{x}+\frac{1}{x+1}
$$

Il denominatore comune e':

$$
x(x+1)
$$

Portiamo le due frazioni allo stesso denominatore:

$$
\frac{x+1}{x(x+1)}
+
\frac{x}{x(x+1)}
$$

Sommiamo i numeratori:

$$
\frac{x+1+x}{x(x+1)}
$$

quindi:

$$
\frac{2x+1}{x(x+1)}
$$

Le condizioni di esistenza sono:

$$
x\not=0
\qquad
x\not=-1
$$

# 📌 Minimo Comune Multiplo (`m.c.m.`)

> 💡 Idea: quando i denominatori sono prodotti di fattori, possiamo utilizzare
> la `scomposizione in fattori` per trovare il minimo comune multiplo

## 🚀 Esempio

Consideriamo:

$$
\frac{1}{x^2-4}+\frac{1}{x-2}
$$

Scomponiamo:

$$
x^2-4=(x-2)(x+2)
$$

Quindi:

$$
\frac{1}{(x-2)(x+2)}+\frac{1}{x-2}
$$

Il denominatore comune e':

$$
(x-2)(x+2)
$$

Otteniamo:

$$
\frac{1}{(x-2)(x+2)}
+
\frac{x+2}{(x-2)(x+2)}
$$

Sommiamo:

$$
\frac{1+x+2}{(x-2)(x+2)}
$$

$$
\frac{x+3}{(x-2)(x+2)}
$$

La `C.E.` e':

$$
x\not=2
\qquad
x\not=-2
$$

# 📌 Espressioni con frazioni algebriche

> 💡 Idea: per risolvere un'espressione con frazioni algebriche conviene
> seguire un ordine preciso

1. Troviamo le `condizioni di esistenza`
2. Scomponiamo numeratori e denominatori
3. Semplifichiamo quando possibile
4. Eseguiamo `moltiplicazioni` e `divisioni`
5. Eseguiamo `addizioni` e `sottrazioni`
6. Semplifichiamo il risultato finale

## 🚀 Esempio

Consideriamo:

$$
\frac{x}{x-1}+\frac{1}{x-1}
$$

La `C.E.` e':

$$
x-1\not=0
\Rightarrow x\not=1
$$

Il denominatore e' gia' comune:

$$
\frac{x+1}{x-1}
$$

Quindi:

$$
\boxed{\frac{x+1}{x-1}}
\qquad
C.E.:x\not=1
$$

## 🚀 Esercizi

* Semplifica $\frac{2}{x}+\frac{3}{x}$
* Semplifica $\frac{1}{x}+\frac{1}{x+2}$
* Semplifica $\frac{2}{x-1}-\frac{1}{x+1}$
* Semplifica $\frac{x}{x^2-4}+\frac{1}{x+2}$

# 📌 Equazioni fratte

> 💡 Idea: un'equazione fratta e' un'equazione nella quale l'incognita
> compare almeno in un `denominatore`

## 🚀 Esempio

$$
\frac{2}{x}=1
$$

Prima di tutto troviamo la `C.E.`:

$$
x\not=0
$$

Possiamo moltiplicare entrambi i membri per $x$:

$$
2=x
$$

quindi:

$$
x=2
$$

La soluzione rispetta la C.E., quindi:

$$
S=\{2\}
$$

# 📌 Risoluzione di un'equazione fratta

> 💡 Idea: per eliminare i denominatori possiamo moltiplicare entrambi
> i membri dell'equazione per il `minimo comune multiplo` dei denominatori,
> dopo aver stabilito le `condizioni di esistenza`

Procediamo quindi:

1. Determiniamo la `C.E.`
2. Troviamo il `m.c.m.` dei denominatori
3. Moltiplichiamo entrambi i membri per il `m.c.m.`
4. Risolviamo l'equazione ottenuta
5. Controlliamo che le soluzioni rispettino la `C.E.`

## 🚀 Esempio

Risolviamo:

$$
\frac{1}{x-1}=\frac{2}{x+1}
$$

### 1. Condizioni di esistenza

I denominatori devono essere diversi da zero:

$$
x-1\not=0
\Rightarrow x\not=1
$$

$$
x+1\not=0
\Rightarrow x\not=-1
$$

Quindi:

$$
C.E.:x\not=\pm1
$$

### 2. Minimo comune multiplo

Il m.c.m. dei denominatori e':

$$
(x-1)(x+1)
$$

### 3. Moltiplichiamo

$$
\frac{1}{x-1}=\frac{2}{x+1}
$$

moltiplichiamo entrambi i membri per $(x-1)(x+1)$:

$$
x+1=2(x-1)
$$

### 4. Risolviamo

$$
x+1=2x-2
$$

$$
x=3
$$

### 5. Controlliamo la C.E.

$$
3\not=1
\qquad
3\not=-1
$$

La soluzione e' accettabile:

$$
S=\{3\}
$$

# 📌 Equazione fratta con piu' termini

## 🚀 Esempio

Risolviamo:

$$
\frac{1}{x}+\frac{1}{x+1}=1
$$

### 1. Condizioni di esistenza

$$
x\not=0
$$

$$
x+1\not=0
\Rightarrow x\not=-1
$$

Quindi:

$$
C.E.:x\not=0,\ x\not=-1
$$

### 2. Minimo comune multiplo

$$
m.c.m.=x(x+1)
$$

### 3. Moltiplichiamo tutta l'equazione

$$
x(x+1)
\left(
\frac1x+\frac1{x+1}
\right)
=
x(x+1)
$$

Otteniamo:

$$
x+1+x=x(x+1)
$$

### 4. Risolviamo

$$
2x+1=x^2+x
$$

Portiamo tutto a primo membro:

$$
x^2-x-1=0
$$

Usiamo la formula risolutiva:

$$
x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}
$$

con:

$$
a=1,\quad b=-1,\quad c=-1
$$

Quindi:

$$
x=
\frac{1\pm\sqrt{1+4}}{2}
$$

$$
x=
\frac{1\pm\sqrt5}{2}
$$

Entrambe le soluzioni rispettano la C.E., quindi:

$$
S=
\left\{
\frac{1+\sqrt5}{2},
\frac{1-\sqrt5}{2}
\right\}
$$

# 📌 Attenzione alle soluzioni escluse

> ⚠️ Idea: una soluzione ottenuta durante i calcoli deve sempre essere
> confrontata con le `condizioni di esistenza`

## 🚀 Esempio

Consideriamo:

$$
\frac{x-2}{x-2}=0
$$

La `C.E.` impone:

$$
x-2\not=0
\Rightarrow x\not=2
$$

Ma per avere una frazione uguale a zero dovrebbe essere:

$$
x-2=0
\Rightarrow x=2
$$

Questa soluzione non rispetta la C.E.

Quindi l'equazione e' `impossibile`:

$$
S=\emptyset
$$

> 💡 Idea: una frazione non puo' essere uguale a `0` quando il suo
> denominatore e' anch'esso `0`.

# 📌 Errori comuni

> ⚠️ Non possiamo semplificare `addendi` diversi, ma solo `fattori`

Per esempio e' corretto:

$$
\frac{x(x+2)}{x}
=
x+2
$$

con:

$$
x\not=0
$$

Ma e' sbagliato fare:

$$
\frac{x+2}{x}
\not=
2
$$

perche' $x$ e $x+2$ non sono fattori comuni.

> ⚠️ Non possiamo cancellare termini attraverso una somma:

$$
\frac{x+2}{x}
\not=
\frac22
$$

> 💡 Idea: prima di semplificare bisogna `scomporre` in fattori.

Per esempio:

$$
\frac{x^2-4}{x+2}
=
\frac{(x-2)(x+2)}{x+2}
=
x-2
$$

con:

$$
x\not=-2
$$

# 📌 Riepilogo

Abbiamo imparato che:

* una `frazione algebrica` e' un rapporto tra due espressioni algebriche:
  $$\frac{A}{B}$$
* il `denominatore` di una frazione algebrica deve essere sempre diverso da zero:
  $$B\not=0$$
* le `condizioni di esistenza` si ottengono imponendo che tutti i denominatori siano diversi da zero
* una frazione algebrica e' `nulla` quando il numeratore e' zero e il denominatore e' diverso da zero:
  $$\frac{A}{B}=0\iff A=0,\ B\not=0$$
* per `semplificare` una frazione algebrica bisogna scomporre numeratore e denominatore e semplificare i `fattori comuni`
* quando si semplifica una frazione algebrica bisogna comunque mantenere le `condizioni di esistenza` originali
* nel `prodotto` di frazioni algebriche si moltiplicano numeratori e denominatori:
  $$\frac AB\cdot\frac CD=\frac{AC}{BD}$$
* nella `divisione` si moltiplica per la frazione inversa:
  $$\frac AB:\frac CD=\frac AB\cdot\frac DC$$
* nella divisione bisogna inoltre assicurarsi che la `frazione divisore` sia diversa da zero
* per sommare o sottrarre frazioni algebriche bisogna trovare un `denominatore comune`
* per trovare il denominatore comune e' spesso necessario `scomporre` i denominatori
* un'`equazione fratta` e' un'equazione nella quale l'incognita compare almeno in un denominatore
* per risolvere un'equazione fratta bisogna prima determinare le `condizioni di esistenza`
* per eliminare i denominatori si puo' moltiplicare tutta l'equazione per il `m.c.m. dei denominatori`
* al termine della risoluzione bisogna sempre verificare che le soluzioni rispettino le `condizioni di esistenza`
* una soluzione che annulla un denominatore deve essere `scartata`
* non e' possibile semplificare `addendi`, ma solamente `fattori`
* le condizioni di esistenza devono essere determinate a partire dalla `frazione originale`, prima delle eventuali semplificazioni

> 💡 Idea: le frazioni algebriche permettono di estendere le operazioni con le
> frazioni introducendo espressioni contenenti `incognite`.

Il procedimento fondamentale e':

$$
\boxed{
\text{C.E.}
\rightarrow
\text{scomposizione}
\rightarrow
\text{semplificazione}
\rightarrow
\text{operazioni}
\rightarrow
\text{equazione}
\rightarrow
\text{controllo}
}
$$

Le condizioni di esistenza sono il punto di partenza:

$$
\boxed{
\text{denominatore}\not=0
}
$$

e nelle equazioni fratte la soluzione finale deve sempre appartenere
all'insieme definito dalle condizioni di esistenza.