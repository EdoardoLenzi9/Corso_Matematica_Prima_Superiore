# 🎓 Lezione: I polinomi

> 💡 Idea: dopo aver imparato a lavorare con i **monomi**, possiamo costruire espressioni algebriche più complesse mettendo insieme più monomi attraverso **addizioni e sottrazioni**

> 🎯 Obiettivo: comprendere cosa sono i **polinomi**, riconoscerne le caratteristiche e imparare a eseguire le principali **operazioni tra polinomi**, i **prodotti notevoli** e la **scomposizione in fattori**.

![](assets/011.svg)

# 📌 Polinomio

> 🤏 Definizione intuitiva: un `polinomio` è un'espressione algebrica formata dalla **somma algebrica di uno o più monomi**

Per esempio:

$$3x^2+5x-7$$

è formato dai monomi:

$$3x^2,\qquad 5x,\qquad -7$$

Quindi possiamo pensare al polinomio come a una **somma di monomi**.

## 🚀 Esempi

Sono polinomi:

$$3x+2$$

$$x^2-5x+6$$

$$4a^3-2a^2+a-7$$

$$5x^2y-3xy^2+8$$

$$7$$

Un singolo monomio è quindi anche un polinomio.

> 🤔 Domanda: il monomio $3x^2$ può essere considerato un polinomio?

> 💡 Idea: sì. Un polinomio può essere formato anche da **un solo monomio**.

## 🚀 Esempi

Non sono polinomi:

$$\frac{1}{x}+2$$

$$\sqrt{x}+1$$

$$\frac{x+1}{x}$$

perché le lettere compaiono con esponenti che non sono interi non negativi.

# 📌 Termini di un polinomio

Consideriamo:

$$P(x)=3x^2-5x+7$$

I suoi termini sono:

$$3x^2,\qquad -5x,\qquad 7$$

> 🤏 Definizione: i `termini` di un polinomio sono i **monomi** che lo compongono, considerati con il loro segno.

Il polinomio:

$$3x^2-5x+7$$

può quindi essere scritto come:

$$3x^2+(-5x)+7$$

## 🚀 Esempio

Consideriamo:

$$P(x)=-2x^3+4x^2-x+6$$

I termini sono:

* $-2x^3$
* $4x^2$
* $-x$
* $6$

> 🤔 Domanda: quanti termini ha il polinomio?

$$5x^4-3x^2+7x-1$$

# 📌 Coefficiente e parte letterale

Ogni termine di un polinomio è un monomio.

Per esempio:

$$-7x^3$$

ha:

* coefficiente: $-7$
* parte letterale: $x^3$

Consideriamo quindi:

$$P(x)=4x^3-2x^2+5x-9$$

Ogni termine possiede il proprio coefficiente e la propria parte letterale.

| Termine | Coefficiente | Parte letterale |
|---|---:|---|
| $4x^3$ | $4$ | $x^3$ |
| $-2x^2$ | $-2$ | $x^2$ |
| $5x$ | $5$ | $x$ |
| $-9$ | $-9$ | nessuna |

> 💡 Idea: un polinomio non possiede quindi un unico coefficiente: **ogni suo termine è un monomio** e possiede il proprio coefficiente.

# 📌 Forma normale di un polinomio

Un polinomio può contenere termini simili.

Per esempio:

$$3x^2+5x-2x^2+7$$

I termini:

$$3x^2\qquad -2x^2$$

sono simili.

Possiamo quindi sommarli:

$$3x^2-2x^2=x^2$$

Otteniamo:

$$x^2+5x+7$$

> 🤏 Definizione: un polinomio è in `forma normale` quando è scritto come somma algebrica di **monomi non simili**, generalmente ordinati secondo il grado decrescente.

## 🚀 Esempio

Portiamo in forma normale:

$$3x^2+4x-5+2x^2-7x+3$$

Raggruppiamo i termini simili:

$$3x^2+2x^2+4x-7x-5+3$$

Sommiamo i coefficienti:

$$5x^2-3x-2$$

Quindi:

$$\boxed{5x^2-3x-2}$$

## 🚀 Esercizi

Porta in forma normale:

* $3x+2x^2-5x+7$
* $4a^2-3a+2a^2+5a$
* $5x^3-2x+3x^2-4x^3$
* $7a^2b-3ab^2+2a^2b+5ab^2$

# 📌 Grado di un polinomio

> 🤏 Definizione: il `grado di un polinomio` è il **massimo grado dei suoi monomi non nulli**.

Consideriamo:

$$P(x)=3x^4-2x^2+7x-5$$

I gradi dei termini sono:

$$4,\qquad2,\qquad1,\qquad0$$

Il grado massimo è $4$.

Quindi:

$$\boxed{\deg(P)=4}$$

## 🚀 Esempio

Consideriamo:

$$P(x)=5x^3+2x^5-7x+1$$

Il termine di grado massimo è:

$$2x^5$$

Quindi:

$$\boxed{\deg(P)=5}$$

## 🚀 Esempio

Consideriamo:

$$P(x,y)=3x^2y+5xy^2-7$$

Il grado dei primi due monomi è:

$$2+1=3$$

$$1+2=3$$

Il termine costante ha grado $0$.

Quindi:

$$\boxed{\deg(P)=3}$$

> 🤔 Domanda: qual è il grado del polinomio?

$$P(x)=7x^6-3x^2+5x-8$$

# 📌 Polinomi particolari

Un polinomio può essere classificato in base al numero di termini.

> 🤏 Definizione: un polinomio con un solo termine è un `monomio`.

$$3x^2$$

> 🤏 Definizione: un polinomio con due termini è un `binomio`.

$$x+3$$

> 🤏 Definizione: un polinomio con tre termini è un `trinomio`.

$$x^2+3x+2$$

Un polinomio con quattro termini viene semplicemente indicato come polinomio di quattro termini.

$$x^3+x^2+x+1$$

## 🚀 Esercizi

Classifica i seguenti polinomi:

* $5x^2$
* $x+7$
* $x^2-3x+2$
* $a^3-2a^2+a-1$

# 📌 Zeri di un polinomio

> 💡 Idea: un polinomio può essere visto come una **funzione** che associa un valore al risultato ottenuto sostituendo un numero alla variabile.

Consideriamo:

$$P(x)=x-3$$

Calcoliamo il valore del polinomio per $x=3$:

$$P(3)=3-3=0$$

> 🤏 Definizione: un numero $x_0$ si dice `zero del polinomio` $P(x)$ se:

$$P(x_0)=0$$

Quindi $3$ è uno zero di:

$$P(x)=x-3$$

## 🚀 Esempio

Consideriamo:

$$P(x)=x^2-4$$

Cerchiamo gli zeri imponendo:

$$P(x)=0$$

$$x^2-4=0$$

$$x^2=4$$

$$x=\pm2$$

Quindi gli zeri sono:

$$\boxed{x_1=2,\qquad x_2=-2}$$

## 🚀 Esempio

Consideriamo:

$$P(x)=x^2+1$$

Cerchiamo gli zeri reali:

$$x^2+1=0$$

$$x^2=-1$$

Non esiste alcun numero reale il cui quadrato sia $-1$.

Quindi $P(x)$ non ha zeri reali.

> 🤔 Domanda: qual è lo zero del polinomio?

$$P(x)=2x-6$$

# 📌 Addizione di polinomi

> 💡 Idea: per sommare due polinomi sommiamo tra loro i **monomi simili**.

Consideriamo:

$$P(x)=3x^2+2x-5$$

$$Q(x)=x^2-4x+7$$

Sommiamo:

$$P(x)+Q(x)$$

$$=3x^2+2x-5+x^2-4x+7$$

Raggruppiamo i termini simili:

$$=(3+1)x^2+(2-4)x+(-5+7)$$

$$=4x^2-2x+2$$

Quindi:

$$\boxed{P(x)+Q(x)=4x^2-2x+2}$$

## 🚀 Esempio

$$
(2x^3-3x+4)+(5x^3+7x-1)
$$

$$=(2+5)x^3+(-3+7)x+(4-1)$$

$$=\boxed{7x^3+4x+3}$$

## 🚀 Esercizi

Calcola:

1. $(3x^2+2x)+(5x^2-7x)$
2. $(4a^3-a+2)+(2a^3+5a-6)$
3. $(x^2+3x-4)+(2x^2-x+7)$
4. $(5x^3-2x^2+x)+(x^3+4x^2-3x)$
5. $(2a^2b+3ab^2)+(5a^2b-ab^2)$

# 📌 Sottrazione di polinomi

> 💡 Idea: per sottrarre un polinomio dobbiamo cambiare il segno a **tutti i suoi termini** e poi sommare.

Consideriamo:

$$P(x)=3x^2+5x-2$$

$$Q(x)=x^2-2x+4$$

Calcoliamo:

$$P(x)-Q(x)$$

$$=3x^2+5x-2-(x^2-2x+4)$$

Cambiamo i segni del secondo polinomio:

$$=3x^2+5x-2-x^2+2x-4$$

Raggruppiamo:

$$=(3-1)x^2+(5+2)x+(-2-4)$$

$$=\boxed{2x^2+7x-6}$$

> 🤔 Domanda: perché bisogna cambiare il segno a **tutti** i termini del polinomio sottratto?

## 🚀 Esercizi

Calcola:

1. $(5x^2+3x-1)-(2x^2-x+4)$
2. $(7a^2-2a+5)-(3a^2+4a-1)$
3. $(4x^3-x^2+2)-(x^3+3x^2-5)$
4. $(6ab-2a+3)-(ab+5a-4)$
5. $(x^2+2x+1)-(3x^2-x-2)$

# 📌 Moltiplicazione di un polinomio per un monomio

> 💡 Idea: per moltiplicare un polinomio per un monomio possiamo usare la **proprietà distributiva**.

Consideriamo:

$$2x(3x^2-4x+5)$$

Distribuiamo $2x$ su ogni termine:

$$2x\cdot3x^2-2x\cdot4x+2x\cdot5$$

Calcoliamo:

$$6x^3-8x^2+10x$$

Quindi:

$$\boxed{2x(3x^2-4x+5)=6x^3-8x^2+10x}$$

## 🚀 Esempio

$$-3a(2a^2-5a+4)$$

$$=-6a^3+15a^2-12a$$

## 🚀 Esercizi

Calcola:

1. $3x(2x^2-5x+1)$
2. $-2a(a^2+3a-4)$
3. $5x^2(2x^3-x+7)$
4. $-4ab(2a-b+3)$
5. $3xy(x^2+2xy-y^2)$

# 📌 Moltiplicazione di polinomi

> 💡 Idea: per moltiplicare due polinomi dobbiamo moltiplicare **ogni termine del primo polinomio per ogni termine del secondo**.

Consideriamo:

$$
(x+2)(x+3)
$$

Applichiamo la proprietà distributiva:

$$
x\cdot x+x\cdot3+2\cdot x+2\cdot3
$$

$$
=x^2+3x+2x+6
$$

$$
=\boxed{x^2+5x+6}
$$

## 🚀 Esempio

$$
(2x-3)(x+4)
$$

$$=2x^2+8x-3x-12$$

$$=\boxed{2x^2+5x-12}$$

## 🚀 Esempio

$$
(x^2+2x+1)(x+3)
$$

Moltiplichiamo ogni termine:

$$
x^2\cdot x+x^2\cdot3
+2x\cdot x+2x\cdot3
+1\cdot x+1\cdot3
$$

$$
=x^3+3x^2+2x^2+6x+x+3
$$

$$
=\boxed{x^3+5x^2+7x+3}
$$

## 🚀 Esercizi

Calcola:

1. $(x+2)(x+5)$
2. $(x-3)(x+4)$
3. $(2x+1)(x-5)$
4. $(x^2+x+1)(x+2)$
5. $(2a-3)(a^2+a+1)$

# 📌 Prodotti notevoli

> 💡 Idea: alcune moltiplicazioni tra polinomi ricorrono così spesso che possiamo utilizzare delle **formule immediate**.

I principali prodotti notevoli sono:

* quadrato di un binomio
* somma per differenza
* quadrato di un trinomio
* cubo di un binomio

# 📌 Quadrato di un binomio

Consideriamo:

$$
(a+b)^2
$$

Per definizione:

$$
(a+b)^2=(a+b)(a+b)
$$

Applichiamo la proprietà distributiva:

$$
=a^2+ab+ab+b^2
$$

$$
=\boxed{a^2+2ab+b^2}
$$

> 🤏 Regola: il `quadrato di un binomio` è uguale al **quadrato del primo termine**, più il **doppio prodotto del primo per il secondo**, più il **quadrato del secondo termine**.

$$
\boxed{(a+b)^2=a^2+2ab+b^2}
$$

## 🚀 Esempio

$$
(x+3)^2
$$

$$=x^2+2\cdot x\cdot3+3^2$$

$$=\boxed{x^2+6x+9}$$

## 🚀 Esempio

$$
(2x-5)^2
$$

$$=(2x)^2+2(2x)(-5)+(-5)^2$$

$$=\boxed{4x^2-20x+25}
$$

## 🚀 Esercizi

Sviluppa:

1. $(x+4)^2$
2. $(x-3)^2$
3. $(2x+5)^2$
4. $(3a-2)^2$
5. $(x^2+3)^2$

# 📌 Somma per differenza

Consideriamo:

$$
(a+b)(a-b)
$$

Applichiamo la proprietà distributiva:

$$
a^2-ab+ab-b^2
$$

I termini centrali si annullano:

$$
\boxed{a^2-b^2}
$$

> 🤏 Regola: il prodotto della `somma per la differenza` di due termini è uguale alla **differenza dei loro quadrati**.

$$
\boxed{(a+b)(a-b)=a^2-b^2}
$$

## 🚀 Esempio

$$
(x+5)(x-5)
$$

$$=\boxed{x^2-25}
$$

## 🚀 Esempio

$$
(2x+3)(2x-3)
$$

$$=(2x)^2-3^2$$

$$=\boxed{4x^2-9}
$$

## 🚀 Esercizi

Sviluppa:

1. $(x+7)(x-7)$
2. $(a+4)(a-4)$
3. $(2x+5)(2x-5)$
4. $(3a+2)(3a-2)$
5. $(x^2+3)(x^2-3)$

# 📌 Quadrato di un trinomio

Consideriamo:

$$
(a+b+c)^2
$$

Possiamo riscrivere:

$$
(a+b+c)(a+b+c)
$$

Sviluppando otteniamo:

$$
a^2+b^2+c^2+2ab+2ac+2bc
$$

Quindi:

$$
\boxed{(a+b+c)^2=a^2+b^2+c^2+2ab+2ac+2bc}
$$

> 🤏 Regola: il `quadrato di un trinomio` è uguale alla somma dei **quadrati dei tre termini** più il **doppio prodotto di ogni coppia di termini**.

## 🚀 Esempio

$$
(x+y+2)^2
$$

$$
=x^2+y^2+4+2xy+4x+4y
$$

Quindi:

$$
\boxed{x^2+y^2+4+2xy+4x+4y}
$$

## 🚀 Esercizi

Sviluppa:

1. $(x+y+1)^2$
2. $(a+b+2)^2$
3. $(x+2y+3)^2$
4. $(2a-b+c)^2$
5. $(x^2+x+1)^2$

# 📌 Cubo di un binomio

Consideriamo:

$$
(a+b)^3
$$

Possiamo scrivere:

$$
(a+b)^3=(a+b)^2(a+b)
$$

Usando il quadrato del binomio:

$$
=(a^2+2ab+b^2)(a+b)
$$

Sviluppiamo:

$$
=a^3+a^2b+2a^2b+2ab^2+ab^2+b^3
$$

$$
=\boxed{a^3+3a^2b+3ab^2+b^3}
$$

> 🤏 Regola: il `cubo di un binomio` è uguale al cubo del primo termine, più o meno il triplo prodotto tra il quadrato del primo e il secondo, più il triplo prodotto tra il primo e il quadrato del secondo, più o meno il cubo del secondo.

Per la somma:

$$
\boxed{(a+b)^3=a^3+3a^2b+3ab^2+b^3}
$$

Per la differenza:

$$
\boxed{(a-b)^3=a^3-3a^2b+3ab^2-b^3}
$$

## 🚀 Esempio

$$
(x+2)^3
$$

$$
=x^3+3x^2\cdot2+3x\cdot2^2+2^3
$$

$$
=\boxed{x^3+6x^2+12x+8}
$$

## 🚀 Esempio

$$
(2x-1)^3
$$

$$
=(2x)^3-3(2x)^2\cdot1+3(2x)\cdot1^2-1^3
$$

$$
=\boxed{8x^3-12x^2+6x-1}
$$

## 🚀 Esercizi

Sviluppa:

1. $(x+2)^3$
2. $(x-3)^3$
3. $(2x+1)^3$
4. $(a-2)^3$
5. $(2a+b)^3$

# 📌 Il triangolo di Tartaglia

> 💡 Idea: quando sviluppiamo potenze di binomio compaiono coefficienti numerici particolari.

Per esempio:

$$
(a+b)^2=a^2+2ab+b^2
$$

i coefficienti sono:

$$
1,\ 2,\ 1
$$

Per il cubo:

$$
(a+b)^3=a^3+3a^2b+3ab^2+b^3
$$

i coefficienti sono:

$$
1,\ 3,\ 3,\ 1
$$

Questi coefficienti compaiono nel `triangolo di Tartaglia`:

$$
\begin{array}{ccccccc}
&&&&1&&&&\\
&&&1&&1&&\\
&&1&&2&&1&&\\
&1&&3&&3&&1&
\end{array}
$$

Ogni numero interno è ottenuto sommando i due numeri che si trovano sopra.

## 📚 Potenze di binomio

Per esempio:

$$
(a+b)^4
$$

utilizziamo la riga:

$$
1,\ 4,\ 6,\ 4,\ 1
$$

e otteniamo:

$$
(a+b)^4
=
a^4+4a^3b+6a^2b^2+4ab^3+b^4
$$

> 🤔 Domanda: quali coefficienti utilizzeresti per sviluppare $(a+b)^5$?

## 🚀 Esercizi

Sviluppa usando il triangolo di Tartaglia:

1. $(x+y)^4$
2. $(a+b)^4$
3. $(x+2)^4$
4. $(a-b)^4$
5. $(x+y)^5$

# 📌 Raccoglimento a fattor comune

> 💡 Idea: scomporre un polinomio significa cercare di scriverlo come **prodotto di fattori**.

Consideriamo:

$$
6x^2+9x
$$

I termini hanno in comune:

$$
3x
$$

Raccogliamo $3x$:

$$
6x^2+9x=3x(2x+3)
$$

Quindi:

$$
\boxed{6x^2+9x=3x(2x+3)}
$$

> 🤏 Definizione: il `raccoglimento totale` consiste nel mettere in evidenza il **fattore comune a tutti i termini** del polinomio.

## 🚀 Esempio

$$
8a^3-12a^2
$$

Il fattore comune è:

$$
4a^2
$$

Quindi:

$$
8a^3-12a^2=4a^2(2a-3)
$$

## 🚀 Esercizi

Scomponi mediante raccoglimento totale:

1. $6x^2+12x$
2. $15a^3-10a^2$
3. $8x^3+12x^2-4x$
4. $14ab^2-21a^2b$
5. $18x^4-12x^3+6x^2$

# 📌 Raccoglimento parziale

> 💡 Idea: a volte non esiste un fattore comune a **tutti** i termini, ma possiamo raggruppare i termini in modo da creare fattori comuni.

Consideriamo:

$$
ax+ay+bx+by
$$

Raggruppiamo:

$$
(ax+ay)+(bx+by)
$$

Raccogliamo:

$$
a(x+y)+b(x+y)
$$

Ora compare il fattore comune $(x+y)$:

$$
\boxed{(a+b)(x+y)}
$$

Quindi:

$$
ax+ay+bx+by=(a+b)(x+y)
$$

> 🤏 Definizione: il `raccoglimento parziale` consiste nel raggruppare i termini del polinomio per ottenere fattori comuni e procedere successivamente con un secondo raccoglimento.

## 🚀 Esempio

$$
3x+6+xy+2y
$$

Raggruppiamo:

$$
(3x+6)+(xy+2y)
$$

Raccogliamo:

$$
3(x+2)+y(x+2)
$$

Raccogliamo ancora:

$$
\boxed{(3+y)(x+2)}
$$

## 🚀 Esercizi

Scomponi mediante raccoglimento parziale:

1. $ax+ay+bx+by$
2. $2x+6+xy+3y$
3. $3a+3b+ax+bx$
4. $x^2+2x+3x+6$
5. $2a^2+4a+ab+2b$

# 📌 Scomposizione mediante prodotti notevoli

> 💡 Idea: i prodotti notevoli possono essere utilizzati anche **al contrario**, per scomporre un polinomio.

Consideriamo:

$$
x^2+6x+9
$$

Riconosciamo:

$$
x^2+2\cdot x\cdot3+3^2
$$

Quindi:

$$
\boxed{x^2+6x+9=(x+3)^2}
$$

## 🚀 Esempio

$$
x^2-25
$$

Riconosciamo una differenza di quadrati:

$$
x^2-5^2
$$

Quindi:

$$
\boxed{x^2-25=(x+5)(x-5)}
$$

## 🚀 Esempio

$$
x^2-10x+25
$$

Riconosciamo:

$$
x^2-2\cdot x\cdot5+5^2
$$

Quindi:

$$
\boxed{x^2-10x+25=(x-5)^2}
$$

## 🚀 Esercizi

Scomponi:

1. $x^2+8x+16$
2. $x^2-36$
3. $x^2-12x+36$
4. $4x^2-25$
5. $9a^2+12a+4$

# 📌 Riconoscere il metodo di scomposizione

> 💡 Idea: davanti a un polinomio dobbiamo prima **osservare la sua struttura** e scegliere il metodo più adatto.

Possiamo chiederci:

1. C'è un `fattore comune` a tutti i termini?
2. Posso fare un `raccoglimento parziale`?
3. Riconosco un `prodotto notevole`?
4. Il polinomio può essere ulteriormente scomposto?

## 🚀 Esempio

Consideriamo:

$$
2x^2-18
$$

Prima raccogliamo $2$:

$$
2(x^2-9)
$$

Ora riconosciamo una differenza di quadrati:

$$
x^2-3^2
$$

Quindi:

$$
2(x+3)(x-3)
$$

e dunque:

$$
\boxed{2x^2-18=2(x+3)(x-3)}
$$

> 💡 Idea: una scomposizione non è necessariamente conclusa dopo il primo passaggio. Dobbiamo verificare se i fattori ottenuti sono ancora scomponibili.

# 📌 Verifica della scomposizione

> 💡 Idea: possiamo verificare una scomposizione **moltiplicando nuovamente i fattori**.

Consideriamo:

$$
x^2+5x+6
$$

Abbiamo trovato:

$$
x^2+5x+6=(x+2)(x+3)
$$

Verifichiamo:

$$
(x+2)(x+3)
$$

$$
=x^2+3x+2x+6
$$

$$
=x^2+5x+6
$$

La scomposizione è corretta.

> 🤔 Domanda: come puoi verificare che

$$
x^2-9=(x+3)(x-3)
$$

sia corretta?

# 📌 Riepilogo

Abbiamo imparato che:

* un `polinomio` è una somma algebrica di uno o più monomi
* i `termini` di un polinomio sono i monomi che lo compongono
* ogni termine possiede un proprio `coefficiente` e una propria `parte letterale`
* un polinomio è in `forma normale` quando è scritto come somma di monomi non simili, generalmente ordinati secondo il grado decrescente
* il `grado di un polinomio` è il massimo grado dei suoi monomi non nulli
* un polinomio con un termine è un `monomio`
* un polinomio con due termini è un `binomio`
* un polinomio con tre termini è un `trinomio`
* uno `zero di un polinomio` è un valore della variabile che rende il polinomio uguale a zero:
  $$P(x_0)=0$$
* nell'`addizione` di polinomi si sommano i monomi simili
* nella `sottrazione` di polinomi si cambia il segno a tutti i termini del polinomio sottratto
* nella `moltiplicazione` di un polinomio per un monomio si applica la proprietà distributiva
* nella `moltiplicazione` tra polinomi ogni termine del primo polinomio viene moltiplicato per ogni termine del secondo
* il `quadrato di un binomio` vale:
  $$(a+b)^2=a^2+2ab+b^2$$
* la `somma per differenza` vale:
  $$(a+b)(a-b)=a^2-b^2$$
* il `quadrato di un trinomio` vale:
  $$(a+b+c)^2=a^2+b^2+c^2+2ab+2ac+2bc$$
* il `cubo di un binomio` vale:
  $$(a+b)^3=a^3+3a^2b+3ab^2+b^3$$
  $$(a-b)^3=a^3-3a^2b+3ab^2-b^3$$
* il `triangolo di Tartaglia` permette di ottenere i coefficienti delle potenze di un binomio
* la `scomposizione in fattori` consiste nel trasformare un polinomio in un prodotto di fattori
* il `raccoglimento totale` consiste nel raccogliere un fattore comune a tutti i termini
* il `raccoglimento parziale` consiste nel raggruppare i termini per ottenere fattori comuni
* i `prodotti notevoli` possono essere utilizzati anche al contrario per scomporre un polinomio
* una scomposizione può richiedere `più passaggi` prima di essere completata
* una scomposizione può essere verificata sviluppando nuovamente il prodotto ottenuto

# 🚀 Esercizi finali

1. Porta in forma normale:
   $$3x^2+5x-2x^2+7-3x$$

2. Individua il grado del polinomio:
   $$P(x)=4x^5-3x^2+7x-1$$

3. Trova gli zeri del polinomio:
   $$P(x)=x^2-9$$

4. Calcola:
   $$(3x^2+2x-1)+(5x^2-7x+4)$$

5. Calcola:
   $$(6x^2-3x+2)-(2x^2+x-5)$$

6. Sviluppa:
   $$2x(3x^2-4x+5)$$

7. Sviluppa:
   $$(2x-3)(x+4)$$

8. Sviluppa usando un prodotto notevole:
   $$(x+5)^2$$

9. Sviluppa:
   $$(2x-1)^3$$

10. **Sfida:** scomponi completamente:
    $$2x^2-8x+8$$

> 💡 Idea: i polinomi permettono di passare dai singoli **monomi** a espressioni algebriche più ricche, nelle quali possiamo **calcolare, trasformare, sviluppare e scomporre**.

$$
\boxed{
\text{Monomi}
\longrightarrow
\text{Polinomi}
}
$$

I polinomi ci permettono quindi di costruire gli strumenti necessari per affrontare
equazioni, funzioni e problemi algebrici sempre più complessi.