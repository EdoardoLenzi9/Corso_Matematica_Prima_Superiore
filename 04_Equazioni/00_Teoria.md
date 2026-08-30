# 🎓 Lezione: Le equazioni

> 💡 Idea: dopo aver imparato a costruire e manipolare espressioni algebriche, possiamo usare le lettere per **rappresentare quantità incognite** e trovare i valori che rendono vere determinate uguaglianze

> 🎯 Obiettivo: comprendere la differenza tra **identità** ed **equazione**, imparare a trasformare e risolvere le equazioni attraverso i **principi di equivalenza**, riconoscere equazioni **determinate, indeterminate e impossibili** e utilizzare le **formule inverse**.

![](assets/011.svg)

# 📌 Uguaglianza e identità

Prima di introdurre le equazioni, ricordiamo il significato di `uguaglianza`.

Un'uguaglianza mette in relazione due espressioni attraverso il simbolo:

$$=$$

Per esempio:

$$3+2=5$$

oppure:

$$2x+1=7$$

Ma queste due uguaglianze hanno una differenza importante.

Nel primo caso l'uguaglianza è vera **sempre**.

Nel secondo caso l'uguaglianza è vera solo per alcuni valori di $x$.

# 📌 Identità matematica

> 🤏 Definizione: una `identità` è un'uguaglianza che risulta vera **per ogni valore ammesso delle variabili** presenti nelle espressioni.

## 🚀 Esempio

Consideriamo:

$$2(x+3)=2x+6$$

Sviluppiamo il primo membro:

$$2x+6=2x+6$$

L'uguaglianza è vera qualunque sia il valore di $x$.

Quindi:

$$\boxed{2(x+3)=2x+6}$$

è un'identità.

## 🚀 Esempio

Consideriamo:

$$x+x=2x$$

Questa uguaglianza è vera per ogni $x$.

Quindi è un'identità.

> 🤔 Domanda: l'uguaglianza

$$3(x+2)=3x+5$$

è un'identità?

# 📌 Equazione

> 🤏 Definizione: una `equazione` è un'uguaglianza tra due espressioni contenenti una o più `incognite`, che risulta vera solo per determinati valori delle incognite.

Consideriamo:

$$2x+3=9$$

In questo caso dobbiamo trovare il valore di $x$ che rende vera l'uguaglianza.

Proviamo:

$$x=3$$

$$2\cdot3+3=9$$

$$6+3=9$$

L'uguaglianza è vera.

Quindi $x=3$ è una `soluzione` dell'equazione.

## 📚 Membri

In un'equazione distinguiamo:

* `primo membro`: l'espressione a sinistra del simbolo $=$
* `secondo membro`: l'espressione a destra del simbolo $=$

Per esempio:

$$2x+3=9$$

ha:

* primo membro: $2x+3$
* secondo membro: $9$

> 🤏 Definizione: la `soluzione` di un'equazione è un valore dell'incognita che rende vera l'uguaglianza.

## 🚀 Esercizi

Stabilisci se le seguenti uguaglianze sono `identità` oppure `equazioni`:

1. $$2(x+1)=2x+2$$
2. $$3x+1=10$$
3. $$(x+2)^2=x^2+4x+4$$
4. $$5x-2=5x+1$$
5. $$4(x-1)=4x-4$$

# 📌 Verifica di una soluzione

Una volta trovata una possibile soluzione, possiamo sempre `verificarla` sostituendo il valore nell'equazione.

Consideriamo:

$$3x-2=10$$

Supponiamo che:

$$x=4$$

Sostituiamo:

$$3\cdot4-2=10$$

$$12-2=10$$

$$10=10$$

L'uguaglianza è vera.

Quindi:

$$\boxed{x=4}$$

è soluzione dell'equazione.

> 💡 Idea: risolvere un'equazione significa trovare **tutti e soli** i valori che la rendono vera.

# 📌 Principi di equivalenza

> 💡 Idea: quando risolviamo un'equazione possiamo trasformarla in un'altra equazione più semplice, purché le due equazioni abbiano **le stesse soluzioni**.

> 🤏 Definizione: due equazioni sono `equivalenti` se hanno esattamente lo stesso insieme delle soluzioni.

## 📚 Primo principio di equivalenza

> 🤏 Regola: aggiungendo o sottraendo la **stessa quantità** a entrambi i membri di un'equazione, otteniamo un'equazione equivalente.

Consideriamo:

$$x+3=8$$

Sottraiamo $3$ da entrambi i membri:

$$x+3-3=8-3$$

$$x=5$$

Le due equazioni hanno la stessa soluzione.

Quindi:

$$x+3=8\iff x=5$$

## 🚀 Esempio

$$x-7=4$$

Aggiungiamo $7$ a entrambi i membri:

$$x-7+7=4+7$$

$$x=11$$

Quindi:

$$\boxed{x=11}$$

## 📚 Secondo principio di equivalenza

> 🤏 Regola: moltiplicando o dividendo entrambi i membri di un'equazione per una **quantità diversa da zero**, otteniamo un'equazione equivalente.

Consideriamo:

$$3x=12$$

Dividiamo entrambi i membri per $3$:

$$\frac{3x}{3}=\frac{12}{3}$$

$$x=4$$

Quindi:

$$3x=12\iff x=4$$

> ⚠️ Attenzione: non possiamo dividere per zero.

## 🚀 Esempio

$$\frac{x}{5}=3$$

Moltiplichiamo entrambi i membri per $5$:

$$5\cdot\frac{x}{5}=5\cdot3$$

$$x=15$$

# 📌 Trasporto dei termini

> 💡 Idea: il primo principio di equivalenza permette di "trasportare" un termine da un membro all'altro **cambiandone il segno**.

Consideriamo:

$$x+5=12$$

Sottraiamo $5$ da entrambi i membri:

$$x+5-5=12-5$$

$$x=12-5$$

$$x=7$$

Per questo motivo possiamo scrivere direttamente:

$$x+5=12$$

$$x=12-5$$

> 🤏 Regola: quando un termine passa da un membro all'altro, cambia il proprio `segno`.

## 🚀 Esempi

$$x-4=9$$

$$x=9+4$$

$$x=13$$

---

$$x+7=2$$

$$x=2-7$$

$$x=-5$$

---

$$3x-8=10$$

$$3x=10+8$$

$$3x=18$$

$$x=6$$

# 📌 Equazioni lineari

> 🤏 Definizione: un'equazione `lineare` o `di primo grado` è un'equazione nella quale l'incognita compare con esponente massimo uguale a `1`.

La forma generale di un'equazione lineare è:

$$ax+b=0$$

dove:

$$a,b\in\mathbb R$$

e, nel caso di un'equazione di primo grado:

$$a\not=0$$

## 🚀 Esempio

Consideriamo:

$$5x-15=0$$

Trasportiamo il termine noto:

$$5x=15$$

Dividiamo per $5$:

$$x=3$$

Quindi:

$$\boxed{x=3}$$

## 🚀 Esempio

$$7x+14=0$$

$$7x=-14$$

$$x=-2$$

Quindi:

$$\boxed{x=-2}$$

# 📌 Equazioni lineari con parentesi

> 💡 Idea: prima di risolvere un'equazione possiamo semplificare le espressioni utilizzando la `proprietà distributiva`.

Consideriamo:

$$3(x+2)=15$$

Applichiamo la proprietà distributiva:

$$3x+6=15$$

Trasportiamo $6$:

$$3x=9$$

Dividiamo per $3$:

$$x=3$$

Quindi:

$$\boxed{x=3}$$

## 🚀 Esempio

$$2(x-4)+3=11$$

Sviluppiamo la parentesi:

$$2x-8+3=11$$

Riduciamo i termini simili:

$$2x-5=11$$

$$2x=16$$

$$x=8$$

Quindi:

$$\boxed{x=8}$$

## 🚀 Esercizi

Risolvi:

1. $$x+8=13$$
2. $$x-6=10$$
3. $$4x=28$$
4. $$3x+5=20$$
5. $$2(x+3)=18$$

# 📌 Equazioni con l'incognita nei due membri

Consideriamo:

$$5x+2=2x+14$$

Portiamo tutti i termini con $x$ a sinistra e i termini noti a destra:

$$5x-2x=14-2$$

$$3x=12$$

$$x=4$$

Quindi:

$$\boxed{x=4}$$

## 🚀 Esempio

$$7x-3=4x+12$$

$$7x-4x=12+3$$

$$3x=15$$

$$x=5$$

Quindi:

$$\boxed{x=5}$$

> 💡 Idea: possiamo scegliere liberamente quale membro utilizzare per raccogliere i termini con l'incognita. L'importante è applicare correttamente i principi di equivalenza.

# 📌 Equazioni riducibili a forma normale

Un'equazione può contenere molti termini, parentesi e termini simili.

L'obiettivo è trasformarla nella forma:

$$ax+b=0$$

oppure:

$$ax=b$$

per poi isolare l'incognita.

## 🚀 Esempio

$$3(x+2)-2x=14$$

Sviluppiamo:

$$3x+6-2x=14$$

Riduciamo i termini simili:

$$x+6=14$$

$$x=8$$

Quindi:

$$\boxed{x=8}$$

## 🚀 Esempio

$$4(x-2)+3x=2x+9$$

Sviluppiamo:

$$4x-8+3x=2x+9$$

Riduciamo:

$$7x-8=2x+9$$

Portiamo le $x$ a sinistra:

$$7x-2x=9+8$$

$$5x=17$$

$$x=\frac{17}{5}$$

Quindi:

$$\boxed{x=\frac{17}{5}}$$

# 📌 Equazioni determinate

> 🤏 Definizione: un'equazione `determinata` è un'equazione che possiede **una sola soluzione**.

Consideriamo:

$$2x+4=10$$

$$2x=6$$

$$x=3$$

L'insieme delle soluzioni è:

$$S=\{3\}$$

Quindi l'equazione è `determinata`.

# 📌 Equazioni indeterminate

> 🤏 Definizione: un'equazione `indeterminata` è un'equazione che possiede **infinite soluzioni**.

Consideriamo:

$$2(x+3)=2x+6$$

Sviluppiamo:

$$2x+6=2x+6$$

L'uguaglianza è vera per ogni valore di $x$.

Quindi:

$$S=\mathbb R$$

e l'equazione è `indeterminata`.

> 💡 Idea: un'equazione indeterminata non ci chiede di trovare un unico valore, perché **ogni valore ammesso dell'incognita è soluzione**.

# 📌 Equazioni impossibili

> 🤏 Definizione: un'equazione `impossibile` è un'equazione che non possiede alcuna soluzione.

Consideriamo:

$$2x+3=2x+7$$

Sottraiamo $2x$ da entrambi i membri:

$$3=7$$

Questa uguaglianza è falsa.

Quindi:

$$S=\emptyset$$

e l'equazione è `impossibile`.

> 💡 Idea: quando tutte le incognite scompaiono e rimane un'uguaglianza falsa, l'equazione è impossibile.

## 🚀 Esempio

$$5(x-1)=5x+2$$

Sviluppiamo:

$$5x-5=5x+2$$

Sottraiamo $5x$:

$$-5=2$$

Assurdo.

Quindi:

$$\boxed{S=\emptyset}$$

# 📌 Classificazione delle equazioni

Quando riduciamo un'equazione lineare alla forma:

$$ax=b$$

possiamo distinguere tre casi.

### Caso 1: $a\not=0$

$$ax=b$$

Possiamo dividere per $a$:

$$x=\frac ba$$

L'equazione è `determinata`.

### Caso 2: $a=0$ e $b=0$

Otteniamo:

$$0x=0$$

che è vera per ogni $x$.

L'equazione è `indeterminata`.

### Caso 3: $a=0$ e $b\not=0$

Otteniamo:

$$0x=b$$

con $b\not=0$.

L'uguaglianza è impossibile.

L'equazione è `impossibile`.

| Caso | Risultato | Tipo |
|---|---|---|
| $a\not=0$ | $x=\frac ba$ | Determinata |
| $a=0,\ b=0$ | $0=0$ | Indeterminata |
| $a=0,\ b\not=0$ | $0=b$ | Impossibile |

# 📌 Problemi con le equazioni

> 💡 Idea: un'equazione permette di trasformare un problema scritto con le parole in un problema matematico.

## 🚀 Esempio

Un numero aumentato di $7$ è uguale a $19$.

Indichiamo il numero incognito con $x$.

La frase diventa:

$$x+7=19$$

Risolviamo:

$$x=19-7$$

$$x=12$$

Quindi il numero cercato è:

$$\boxed{12}$$

## 🚀 Esempio

Il triplo di un numero diminuito di $4$ è uguale a $17$.

Indichiamo il numero con $x$:

$$3x-4=17$$

$$3x=21$$

$$x=7$$

Quindi:

$$\boxed{x=7}$$

> 🤔 Domanda: un numero sommato al suo doppio è uguale a $24$. Qual è il numero?

# 📌 Formule inverse

> 💡 Idea: una formula può essere vista come un'equazione nella quale una grandezza deve essere ricavata in funzione delle altre.

Consideriamo:

$$A=b\cdot h$$

Questa formula permette di calcolare l'area di un rettangolo.

Possiamo però voler ricavare una delle altre grandezze.

## 📚 Ricavare la base

Partiamo da:

$$A=b\cdot h$$

Dividiamo entrambi i membri per $h$, con $h\not=0$:

$$\frac Ah=\frac{b\cdot h}{h}$$

$$b=\frac Ah$$

Quindi:

$$\boxed{b=\frac Ah}$$

## 📚 Ricavare l'altezza

Partiamo sempre da:

$$A=b\cdot h$$

Dividiamo per $b$, con $b\not=0$:

$$h=\frac Ab$$

Quindi:

$$\boxed{h=\frac Ab}$$

> 💡 Idea: una `formula inversa` si ottiene risolvendo la formula originale rispetto alla grandezza che vogliamo isolare.

# 📌 Esempio: velocità, spazio e tempo

Consideriamo la formula:

$$v=\frac st$$

dove:

* $v$ = velocità
* $s$ = spazio
* $t$ = tempo

Possiamo ricavare lo spazio:

$$v=\frac st$$

Moltiplichiamo per $t$:

$$vt=s$$

Quindi:

$$\boxed{s=vt}$$

Possiamo ricavare il tempo:

$$v=\frac st$$

Moltiplichiamo per $t$:

$$vt=s$$

Dividiamo per $v$, con $v\not=0$:

$$t=\frac sv$$

Quindi:

$$\boxed{t=\frac sv}$$

## 🚀 Esercizi

Ricava la formula inversa richiesta:

1. Da $$P=2(a+b)$$ ricava $b$
2. Da $$A=\frac{bh}{2}$$ ricava $h$
3. Da $$v=\frac st$$ ricava $s$
4. Da $$I=\frac VR$$ ricava $R$
5. Da $$d=vt$$ ricava $t$

# 📌 Equazioni parametriche

> 💡 Idea: un `parametro` è una quantità che consideriamo fissata, ma il cui valore può cambiare da un caso all'altro.

Consideriamo:

$$ax=6$$

dove $a$ è un parametro.

La soluzione dipende dal valore di $a$.

### Caso $a\not=0$

Possiamo dividere per $a$:

$$x=\frac6a$$

Quindi l'equazione è determinata.

### Caso $a=0$

Otteniamo:

$$0x=6$$

cioè:

$$0=6$$

che è impossibile.

Quindi:

* se $a\not=0$, $$x=\frac6a$$
* se $a=0$, $$S=\emptyset$$

## 🚀 Esempio

Consideriamo:

$$(a-2)x=4$$

Se:

$$a-2\not=0$$

cioè:

$$a\not=2$$

possiamo dividere per $a-2$:

$$x=\frac4{a-2}$$

Se invece:

$$a=2$$

otteniamo:

$$0x=4$$

che è impossibile.

Quindi:

$$
\boxed{
\begin{cases}
x=\frac4{a-2} & a\not=2\\
S=\emptyset & a=2
\end{cases}}
$$

# 📌 Equazioni parametriche con casi

Consideriamo:

$$ax=0$$

Se:

$$a\not=0$$

allora:

$$x=0$$

Se invece:

$$a=0$$

otteniamo:

$$0=0$$

che è vera per ogni $x$.

Quindi:

$$
\boxed{
\begin{cases}
x=0 & a\not=0\\
S=\mathbb R & a=0
\end{cases}}
$$

> 💡 Idea: nelle equazioni parametriche dobbiamo sempre controllare i valori del parametro che rendono **nullo il coefficiente dell'incognita**.

# 📌 Errori comuni

> ⚠️ Attenzione: ci sono alcuni errori molto frequenti nella risoluzione delle equazioni.

### 1. Cambiare segno senza motivo

Da:

$$x+3=7$$

non possiamo scrivere:

$$x+3=-7$$

Il termine $3$ cambia segno solo quando viene sottratto da entrambi i membri:

$$x=7-3$$

### 2. Dividere per zero

Da:

$$ax=b$$

possiamo dividere per $a$ solo se:

$$a\not=0$$

### 3. Dimenticare le parentesi

Consideriamo:

$$2(x+3)$$

Non è uguale a:

$$2x+3$$

ma:

$$2(x+3)=2x+6$$

### 4. Non verificare la soluzione

Dopo aver trovato $x$, è sempre utile sostituirlo nell'equazione iniziale.

> 💡 Idea: la verifica permette di individuare rapidamente molti errori di calcolo.

# 📌 Riepilogo

Abbiamo imparato che:

* un'`uguaglianza` confronta due espressioni attraverso il simbolo $=$
* un'`identità` è un'uguaglianza vera per tutti i valori ammessi delle variabili
* un'`equazione` è un'uguaglianza che risulta vera solo per determinati valori delle incognite
* il `primo membro` è l'espressione a sinistra del simbolo $=$
* il `secondo membro` è l'espressione a destra del simbolo $=$
* una `soluzione` è un valore dell'incognita che rende vera l'equazione
* due equazioni sono `equivalenti` se possiedono lo stesso insieme delle soluzioni
* il `primo principio di equivalenza` permette di aggiungere o sottrarre la stessa quantità a entrambi i membri
* il `secondo principio di equivalenza` permette di moltiplicare o dividere entrambi i membri per una quantità diversa da zero
* nel `trasporto dei termini` un termine che passa da un membro all'altro cambia segno
* un'equazione `lineare` ha la forma generale:
  $$ax+b=0$$
* per risolvere un'equazione lineare bisogna semplificare i membri, raccogliere i termini simili e isolare l'incognita
* un'equazione `determinata` possiede una sola soluzione
* un'equazione `indeterminata` possiede infinite soluzioni
* un'equazione `impossibile` non possiede alcuna soluzione:
  $$S=\emptyset$$
* quando un'equazione lineare viene ridotta alla forma $ax=b$:
  * se $a\not=0$, l'equazione è determinata
  * se $a=0$ e $b=0$, l'equazione è indeterminata
  * se $a=0$ e $b\not=0$, l'equazione è impossibile
* un'`equazione parametrica` contiene uno o più parametri e la sua soluzione può dipendere dal valore assunto dal parametro
* una `formula inversa` si ottiene risolvendo una formula rispetto alla grandezza che vogliamo ricavare
* nella risoluzione di un'equazione è importante rispettare le condizioni di esistenza e non dividere mai per zero
* la `verifica` consiste nel sostituire la soluzione trovata nell'equazione iniziale per controllare che l'uguaglianza sia vera

# 🚀 Esercizi finali

1. Stabilisci se è un'identità oppure un'equazione:
   $$3(x+2)=3x+6$$

2. Risolvi:
   $$4x-7=13$$

3. Risolvi:
   $$3(x-2)+5=2x+9$$

4. Classifica l'equazione:
   $$5x+2=5x+2$$

5. Classifica l'equazione:
   $$4x-3=4x+5$$

6. Risolvi e verifica:
   $$7x-4=3x+20$$

7. Risolvi:
   $$2(x+5)-3(x-1)=9$$

8. Un numero aumentato di $12$ è uguale al doppio del numero diminuito di $3$. Trova il numero.

9. Ricava $h$ dalla formula:
   $$A=\frac{bh}{2}$$

10. **Sfida:** considera l'equazione parametrica
    $$ (a-3)x=2a+4 $$
    
    Studia tutti i casi al variare di $a$.