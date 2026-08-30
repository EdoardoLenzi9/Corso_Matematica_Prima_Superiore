# 🎓 Lezione: Insiemi

> 💡 Idea: un insieme permette di **raggruppare** oggetti che ci interessano e di stabilire in modo preciso quali oggetti **appartengono** al gruppo

> 🎯 Obiettivo: comprendere come si definiscono e si rappresentano gli **insiemi**, come si riconoscono i **sottoinsiemi** e come si eseguono le principali **operazioni tra insiemi**.

![](assets/001.svg)

# 📌 Insieme

> 🤏 Definizione intuitiva: un `insieme` $\triangleq$ collezione di **elementi** accomunati da una determinata **proprieta'**

Gli elementi di un insieme possono essere numeri, lettere, persone, oggetti o persino altri insiemi.

## 🚀 Esempio

Consideriamo l'insieme `colori_primari`

$$
A=\{rosso,\ giallo,\ blu\}
$$

* Nome: `colori_primari`
* Simbolo: $A$
* Definizione: { colori primari }
* Proprieta' comune: essere un `colore primario`
* Elementi: ${rosso,\ giallo,\ blu}$

> 🤔 Domanda: il colore `verde` appartiene all'insieme $A$?

## 🚀 Esempio

Consideriamo l'insieme `numeri_pari`

$$
B=\{0,2,4,6,8,\dots\}
$$

> 💡 Idea: non e' necessario elencare tutti gli elementi di un insieme: se l'insieme e' molto grande o infinito possiamo descriverlo attraverso una `proprieta'`.

> 🤔 Domanda: il numero `14` appartiene a $B$?

> 🤔 Domanda: il numero `15` appartiene a $B$?

# 📌 Insieme vuoto

A volte una proprieta' non e' soddisfatta da nessun elemento.

> 🤏 Definizione: l'`insieme vuoto` e' l'insieme che non contiene alcun elemento

Si indica con:

$$
\emptyset
$$

oppure:

$$
\{\}
$$

Per esempio, consideriamo l'insieme dei numeri naturali minori di $0$:

$$
A=\{x\in\mathbb N\mid x<0\}
$$

Non esiste alcun numero naturale minore di $0$, quindi:

$$
A=\emptyset
$$

> 🤔 Domanda: l'insieme ${0}$ e' uguale all'insieme vuoto?

> 💡 Idea: attenzione: $\emptyset$ non contiene elementi, mentre ${0}$ contiene un elemento, cioe' il numero $0$.

# 📌 Appartenenza a un insieme ($\in$)

Dato l'insieme:

$$
A=\{1,2,3,4,5\}
$$

Possiamo chiederci se un determinato elemento appartiene oppure no ad $A$.

> 🤔 Domanda: il numero $3$ appartiene all'insieme $A$?

$$
3\in A
$$

> 🤔 Domanda: il numero $7$ appartiene all'insieme $A$?

$$
7\not\in A
$$

* $3\in A$ significa: "3 appartiene all'insieme $A$"
* $7\not\in A$ significa: "7 non appartiene all'insieme $A$"

> 💡 Idea: il simbolo $\in$ esprime una relazione tra un `elemento` e un `insieme`.

# 📌 Cardinalita' di un insieme

> 🤏 Definizione: la `cardinalita'` di un insieme e' il numero di elementi che esso contiene

Si indica con:

$$
|A|
$$

Consideriamo:

$$
A=\{2,4,6,8\}
$$

Gli elementi sono `4`, quindi:

$$
|A|=4
$$

Per l'insieme vuoto:

$$
|\emptyset|=0
$$

## 🚀 Esempio

$$
B=\{a,b,c,d,e\}
$$

Quindi:

$$
|B|=5
$$

> 🤔 Domanda: quanto vale la cardinalita' dell'insieme ${1,1,2,2,3}$?

> 💡 Idea: gli elementi di un insieme sono `distinti`: ripetere un elemento non aumenta la cardinalita'.

Infatti:

$$
\{1,1,2,2,3\}=\{1,2,3\}
$$

e quindi:

$$
|\{1,1,2,2,3\}|=3
$$

# 📌 Rappresentazione per caratteristica

> 🤏 Definizione: un insieme puo' essere definito indicando una `proprieta'` che caratterizza tutti e soli i suoi elementi

Si scrive:

$$
A=\{x\mid P(x)\}
$$

e si legge:

"l'insieme degli elementi $x$ tali che vale la proprieta' $P(x)$"

## 🚀 Esempio

L'insieme dei numeri naturali pari puo' essere scritto:

$$
A=\{x\in\mathbb N\mid x\text{ e' pari}\}
$$

oppure:

$$
A=\{x\in\mathbb N\mid x=2k,\ k\in\mathbb N\}
$$

> 💡 Idea: la rappresentazione per `caratteristica` e' particolarmente utile quando l'insieme contiene molti elementi o e' infinito.

## 🚀 Esempio

Consideriamo:

$$
A=\{x\in\mathbb N\mid x<5\}
$$

Possiamo trasformare questa rappresentazione in una rappresentazione per elencazione:

$$
A=\{0,1,2,3,4\}
$$

# 📌 Rappresentazione per elencazione

> 🤏 Definizione: un insieme puo' essere rappresentato `elencando` esplicitamente i suoi elementi fra parentesi graffe

Per esempio:

$$
A=\{1,2,3,4,5\}
$$

> 💡 Idea: nella rappresentazione per elencazione l'ordine degli elementi non e' importante.

Infatti:

$$
\{1,2,3\}=\{3,1,2\}
$$

> 🤔 Domanda: gli insiemi ${a,b,c}$ e ${c,a,b}$ sono uguali?

# 📌 Rappresentazione di Eulero-Venn

Un insieme puo' anche essere rappresentato graficamente attraverso una `rappresentazione di Eulero-Venn`.

![](assets/002.svg)

> 💡 Idea: ogni insieme viene rappresentato attraverso una `regione chiusa` e gli elementi contenuti nella regione appartengono all'insieme.

Consideriamo:

$$
A=\{1,2,3,4\}
$$

Gli elementi `1`, `2`, `3` e `4` si trovano all'interno della regione che rappresenta $A$.

Un elemento che si trova all'esterno non appartiene all'insieme.

> 🤔 Domanda: dove si troverebbe il numero $7$?

# 📌 Sottoinsiemi

Consideriamo:

$$
A=\{1,2,3,4,5\}
$$

e:

$$
B=\{2,4\}
$$

Tutti gli elementi di $B$ appartengono anche ad $A$.

> 🤏 Definizione: un insieme $B$ e' `sottoinsieme` di $A$ se ogni elemento di $B$ appartiene anche ad $A$.

Si indica:

$$
B\subseteq A
$$

e formalmente:

$$
B\subseteq A\iff\forall x,\ x\in B\Rightarrow x\in A
$$

Quindi:

$$
\{2,4\}\subseteq\{1,2,3,4,5\}
$$

> 💡 Idea: ogni insieme e' sottoinsieme di se stesso:

$$
A\subseteq A
$$

Anche l'insieme vuoto e' sottoinsieme di ogni insieme:

$$
\emptyset\subseteq A
$$

## 📚 Sottoinsieme proprio

Se $B$ e' sottoinsieme di $A$, ma $B\not=A$, possiamo dire che $B$ e' un `sottoinsieme proprio` di $A$.

Si puo' indicare:

$$
B\subset A
$$

Per esempio:

$$
\{1,2\}\subset\{1,2,3\}
$$

mentre:

$$
\{1,2,3\}\subseteq\{1,2,3\}
$$

ma non e' un sottoinsieme proprio.

> 🤔 Domanda: ${1,3}\subseteq{1,2,3}$?

> 🤔 Domanda: ${1,4}\subseteq{1,2,3}$?

# 📌 Insieme delle parti

Dato un insieme possiamo costruire un nuovo insieme contenente `tutti i suoi sottoinsiemi`.

> 🤏 Definizione: l'`insieme delle parti` di $A$ e' l'insieme formato da tutti i sottoinsiemi di $A$.

Si indica con:

$$
\mathcal P(A)
$$

Consideriamo:

$$
A=\{1,2\}
$$

I suoi sottoinsiemi sono:

$$
\emptyset,\ \{1\},\ \{2\},\ \{1,2\}
$$

Quindi:

$$
\mathcal P(A)=\{\emptyset,\{1\},\{2\},\{1,2\}\}
$$

e:

$$
|\mathcal P(A)|=4
$$

> 💡 Idea: se un insieme ha cardinalita' $n$, il suo insieme delle parti ha cardinalita':

$$
|\mathcal P(A)|=2^n
$$

## 🚀 Esercizio

Considera:

$$
A=\{a,b,c\}
$$

> 🤔 Domanda: quanti sottoinsiemi possiede $A$?

> 🤔 Domanda: riesci ad elencarli tutti?

# 📌 Operazioni con gli insiemi

> 💡 Idea: come possiamo combinare due o piu' insiemi per ottenere un nuovo insieme?

Le principali operazioni sono:

* `unione`
* `intersezione`
* `differenza`
* `complementare`
* `prodotto cartesiano`

# 📌 Unione ($\cup$)

Consideriamo:

$$
A=\{1,2,3\}
$$

$$
B=\{3,4,5\}
$$

> 🤏 Definizione: l'`unione` di due insiemi $A$ e $B$ e' l'insieme formato da tutti gli elementi che appartengono ad $A$ oppure a $B$.

Si indica:

$$
A\cup B
$$

Formalmente:

$$
A\cup B=\{x\mid x\in A\ \text{oppure}\ x\in B\}
$$

Nel nostro esempio:

$$
A\cup B=\{1,2,3,4,5\}
$$

> 💡 Idea: gli elementi comuni vengono scritti `una sola volta`.

## 🚀 Esempio

$$
A=\{1,2,3\}
$$

$$
B=\{3,4,5\}
$$

$$
A\cup B=\{1,2,3,4,5\}
$$

> 🤔 Domanda: quanto vale $A\cup B$ se $A$ e $B$ non hanno elementi in comune?

# 📌 Intersezione ($\cap$)

Consideriamo nuovamente:

$$
A=\{1,2,3\}
$$

$$
B=\{3,4,5\}
$$

> 🤏 Definizione: l'`intersezione` di due insiemi $A$ e $B$ e' l'insieme formato dagli elementi che appartengono `sia ad A che a B`.

Si indica:

$$
A\cap B
$$

Formalmente:

$$
A\cap B=\{x\mid x\in A\ \text{e}\ x\in B\}
$$

Nel nostro esempio:

$$
A\cap B=\{3\}
$$

> 💡 Idea: l'intersezione contiene solamente gli elementi `comuni` ai due insiemi.

## 🚀 Esempio

$$
A=\{1,2,3\}
$$

$$
B=\{4,5,6\}
$$

Non ci sono elementi comuni, quindi:

$$
A\cap B=\emptyset
$$

> 🤏 Definizione: due insiemi si dicono `disgiunti` se la loro intersezione e' vuota.

$$
A\cap B=\emptyset
$$

# 📌 Differenza tra insiemi ($\setminus$)

Consideriamo:

$$
A=\{1,2,3,4\}
$$

$$
B=\{3,4,5,6\}
$$

> 🤏 Definizione: la `differenza` $A\setminus B$ e' l'insieme degli elementi che appartengono ad $A$ ma `non` appartengono a $B$.

Formalmente:

$$
A\setminus B=\{x\mid x\in A\ \text{e}\ x\not\in B\}
$$

Quindi:

$$
A\setminus B=\{1,2\}
$$

Attenzione:

$$
B\setminus A=\{5,6\}
$$

> 💡 Idea: la differenza `non e' commutativa`:

$$
A\setminus B\not=B\setminus A
$$

> 🤔 Domanda: quanto vale $A\setminus B$ se $A$ e $B$ sono disgiunti?

# 📌 Complementare

Per definire il `complementare` dobbiamo prima stabilire un insieme di riferimento.

> 🤏 Definizione: dato un `insieme universo` $U$, il complementare di $A$ rispetto a $U$ e' formato dagli elementi di $U$ che `non appartengono ad A`.

Si indica, ad esempio, con:

$$
A^c
$$

e vale:

$$
A^c=U\setminus A
$$

## 🚀 Esempio

Consideriamo:

$$
U=\{1,2,3,4,5,6\}
$$

e:

$$
A=\{2,4,6\}
$$

Il complementare di $A$ rispetto a $U$ e':

$$
A^c=\{1,3,5\}
$$

> 💡 Idea: il complementare dipende sempre dall'`insieme universo` scelto.

Infatti, se cambiassimo $U$, potrebbe cambiare anche $A^c$.

## 📚 Proprieta'

Vale:

$$
A\cup A^c=U
$$

e:

$$
A\cap A^c=\emptyset
$$

Inoltre:

$$
(A^c)^c=A
$$

# 📌 Diagrammi di Eulero-Venn e operazioni

Le operazioni sugli insiemi possono essere visualizzate attraverso i diagrammi di `Eulero-Venn`.

## 🚀 Unione

![](assets/003.svg)

La zona rappresentata da $A\cup B$ comprende `entrambi` gli insiemi.

## 🚀 Intersezione

![](assets/004.svg)

La zona rappresentata da $A\cap B$ comprende solamente la parte `comune`.

## 🚀 Differenza

![](assets/005.svg)

La zona rappresentata da $A\setminus B$ comprende la parte di $A$ che si trova `fuori da B`.

> 💡 Idea: i diagrammi permettono di trasformare una definizione astratta in una rappresentazione visiva.

# 📌 Proprieta' delle operazioni tra insiemi

Le operazioni tra insiemi rispettano diverse proprieta'.

## 📚 Commutativa

L'unione e l'intersezione sono commutative:

$$
A\cup B=B\cup A
$$

$$
A\cap B=B\cap A
$$

La differenza invece non e' commutativa:

$$
A\setminus B\not=B\setminus A
$$

## 📚 Associativa

L'unione e l'intersezione sono associative:

$$
(A\cup B)\cup C=A\cup(B\cup C)
$$

$$
(A\cap B)\cap C=A\cap(B\cap C)
$$

## 📚 Distributiva

L'intersezione e' distributiva rispetto all'unione:

$$
A\cap(B\cup C)=(A\cap B)\cup(A\cap C)
$$

L'unione e' distributiva rispetto all'intersezione:

$$
A\cup(B\cap C)=(A\cup B)\cap(A\cup C)
$$

# 📌 Leggi di De Morgan

> 💡 Idea: il complementare di un'unione corrisponde all'intersezione dei complementari.

$$
(A\cup B)^c=A^c\cap B^c
$$

Analogamente:

$$
(A\cap B)^c=A^c\cup B^c
$$

## 🚀 Esempio

Consideriamo un insieme universo $U$ e due insiemi $A$ e $B$.

La prima legge dice:

$$
(A\cup B)^c=A^c\cap B^c
$$

Quindi un elemento `non appartiene ad A oppure a B` solo quando `non appartiene ne' ad A ne' a B`.

> 🤔 Domanda: prova a verificare graficamente questa proprieta' usando un diagramma di Eulero-Venn.

# 📌 Partizione di un insieme

> 🤏 Definizione: una `partizione` di un insieme $A$ e' una suddivisione di $A$ in sottoinsiemi `non vuoti`, `a due a due disgiunti`, la cui unione e' tutto $A$.

Consideriamo:

$$
A=\{1,2,3,4,5,6\}
$$

Possiamo costruire:

$$
A_1=\{1,2\}
$$

$$
A_2=\{3,4\}
$$

$$
A_3=\{5,6\}
$$

Questi tre insiemi formano una partizione di $A$ perche':

$$
A_1\cap A_2=\emptyset
$$

$$
A_1\cap A_3=\emptyset
$$

$$
A_2\cap A_3=\emptyset
$$

e:

$$
A_1\cup A_2\cup A_3=A
$$

> 💡 Idea: una partizione divide un insieme in `blocchi separati`, senza sovrapposizioni e senza lasciare elementi fuori.

> 🤔 Domanda: gli insiemi ${1,2}$, ${2,3}$ e ${4,5}$ possono formare una partizione di ${1,2,3,4,5}$?

# 📌 Prodotto cartesiano

Consideriamo:

$$
A=\{1,2\}
$$

e:

$$
B=\{a,b,c\}
$$

> 🤏 Definizione: il `prodotto cartesiano` $A\times B$ e' l'insieme di tutte le `coppie ordinate` $(a,b)$ in cui il primo elemento appartiene ad $A$ e il secondo appartiene a $B$.

Si definisce:

$$
A\times B=\{(x,y)\mid x\in A,\ y\in B\}
$$

Nel nostro esempio:

$$
A\times B=
\{
(1,a),(1,b),(1,c),
(2,a),(2,b),(2,c)
\}
$$

> 💡 Idea: nel prodotto cartesiano `l'ordine conta`.

Infatti:

$$
(1,a)\not=(a,1)
$$

e generalmente:

$$
A\times B\not=B\times A
$$

## 📚 Cardinalita'

Se:

$$
|A|=m
$$

e:

$$
|B|=n
$$

allora:

$$
|A\times B|=m\cdot n
$$

Nel nostro esempio:

$$
|A|=2
$$

$$
|B|=3
$$

quindi:

$$
|A\times B|=2\cdot3=6
$$

> 🤔 Domanda: quante coppie ordinate contiene $A\times B$ se $|A|=4$ e $|B|=5$?

# 📌 Prodotto cartesiano e piano cartesiano

Il prodotto cartesiano dei numeri reali con se stessi:

$$
\mathbb R\times\mathbb R
$$

e' formato da tutte le coppie ordinate:

$$
(x,y)
$$

con:

$$
x\in\mathbb R,\ y\in\mathbb R
$$

Queste coppie possono essere rappresentate geometricamente come `punti del piano cartesiano`.

![](assets/006.svg)

> 💡 Idea: ogni punto del piano cartesiano puo' essere identificato attraverso una `coppia ordinata` di coordinate $(x,y)$.

# 📌 Problemi con gli insiemi

> 💡 Idea: gli insiemi sono particolarmente utili per rappresentare situazioni in cui alcuni elementi condividono determinate caratteristiche.

## 🚀 Esempio

In una classe di `30` studenti:

* `18` praticano calcio
* `12` praticano pallavolo
* `5` praticano entrambi gli sport

Chiamiamo:

$$
A=\{\text{studenti che praticano calcio}\}
$$

$$
B=\{\text{studenti che praticano pallavolo}\}
$$

Sappiamo che:

$$
|A|=18
$$

$$
|B|=12
$$

$$
|A\cap B|=5
$$

La cardinalita' dell'unione si calcola con:

$$
|A\cup B|=|A|+|B|-|A\cap B|
$$

Quindi:

$$
|A\cup B|=18+12-5=25
$$

> 💡 Idea: sottraiamo $5$ perche' gli studenti che praticano entrambi gli sport erano stati contati `due volte`.

Gli studenti che non praticano nessuno dei due sport sono:

$$
30-25=5
$$

# 📌 Formula della cardinalita' dell'unione

Per due insiemi finiti:

$$
|A\cup B|=|A|+|B|-|A\cap B|
$$

Se invece gli insiemi sono disgiunti:

$$
A\cap B=\emptyset
$$

quindi:

$$
|A\cup B|=|A|+|B|
$$

> 💡 Idea: la formula dell'unione permette di risolvere molti problemi in cui gli elementi possono appartenere contemporaneamente a piu' gruppi.

## 🚀 Esempio

In una classe ci sono `25` studenti.

* `15` studiano inglese
* `10` studiano francese
* `6` studiano entrambe le lingue

Quanti studenti studiano almeno una delle due lingue?

$$
|A\cup B|=15+10-6
$$

$$
|A\cup B|=19
$$

Quindi `19` studenti studiano almeno una delle due lingue.

Quanti non studiano nessuna delle due?

$$
25-19=6
$$

# 🚀 Esercizi

1. Scrivi per elencazione l'insieme dei numeri naturali minori di $8$.
2. Scrivi per caratteristica l'insieme dei numeri naturali pari.
3. Determina la cardinalita' di ${a,b,c,d,e}$.
4. Determina la cardinalita' di ${1,1,2,2,2,3}$.
5. Scrivi tutti i sottoinsiemi di ${1,2}$.
6. Determina $\mathcal P({a,b,c})$.
7. Calcola:
   \(\{1,2,3\}\cup\{3,4,5\}\)
8. Calcola:
   \(\{1,2,3\}\cap\{3,4,5\}\)
9. Calcola:
   \(\{1,2,3,4\}\setminus\{2,4\}\)
10. Considera $U={1,2,3,4,5,6}$ e $A={2,4,6}$. Trova $A^c$.
11. Verifica se ${1,3}\subseteq{1,2,3,4}$.
12. Verifica se ${1,5}\subseteq{1,2,3,4}$.
13. Determina se ${1,2}$ e ${2,3}$ sono disgiunti.
14. Determina:
    \(\{1,2\}\times\{a,b\}\)
15. Se $|A|=3$ e $|B|=4$, quanto vale $|A\times B|$?
16. In una classe di `28` studenti, `17` praticano calcio, `13` praticano basket e `7` praticano entrambi. Quanti praticano almeno uno dei due sport?
17. Nello stesso problema, quanti studenti non praticano ne' calcio ne' basket?
18. Rappresenta con un diagramma di Eulero-Venn due insiemi $A$ e $B$ con intersezione non vuota.
19. Rappresenta graficamente $A\cup B$, $A\cap B$ e $A\setminus B$.
20. Costruisci una partizione dell'insieme:
    \(A=\{1,2,3,4,5,6\}\)

# 📌 Riepilogo

Abbiamo imparato che:

* un `insieme` e' una collezione di elementi caratterizzati da determinate proprieta'
* un insieme puo' contenere numeri, lettere, oggetti o altri insiemi
* l'`insieme vuoto` e' l'insieme che non contiene alcun elemento:
  \(\emptyset\)
* un elemento puo' `appartenere` oppure `non appartenere` a un insieme:
  \(x\in A\)
  \(x\not\in A\)
* la `cardinalita'` di un insieme indica il numero dei suoi elementi:
  \(|A|\)
* ripetere un elemento non aumenta la cardinalita' di un insieme
* un insieme puo' essere rappresentato `per elencazione`, indicando esplicitamente i suoi elementi
* un insieme puo' essere rappresentato `per caratteristica`, indicando la proprieta' comune dei suoi elementi
* i diagrammi di `Eulero-Venn` permettono di rappresentare graficamente gli insiemi
* un insieme $B$ e' `sottoinsieme` di $A$ se ogni elemento di $B$ appartiene anche ad $A$:
  \(B\subseteq A\)
* ogni insieme e' sottoinsieme di se stesso:
  \(A\subseteq A\)
* l'insieme vuoto e' sottoinsieme di ogni insieme:
  \(\emptyset\subseteq A\)
* l'`insieme delle parti` $\mathcal P(A)$ contiene tutti i sottoinsiemi di $A$
* se $|A|=n$, allora:
  \(|\mathcal P(A)|=2^n\)
* l'`unione` $A\cup B$ contiene tutti gli elementi che appartengono ad $A$ oppure a $B$:
  \(A\cup B=\{x\mid x\in A\ \text{oppure}\ x\in B\}\)
* l'`intersezione` $A\cap B$ contiene gli elementi comuni ad $A$ e $B$:
  \(A\cap B=\{x\mid x\in A\ \text{e}\ x\in B\}\)
* due insiemi sono `disgiunti` se:
  \(A\cap B=\emptyset\)
* la `differenza` $A\setminus B$ contiene gli elementi di $A$ che non appartengono a $B$:
  \(A\setminus B=\{x\mid x\in A\ \text{e}\ x\not\in B\}\)
* la differenza tra insiemi non e' commutativa:
  \(A\setminus B\not=B\setminus A\)
* il `complementare` di $A$ rispetto all'insieme universo $U$ e':
  \(A^c=U\setminus A\)
* valgono le proprieta':
  \(A\cup A^c=U\)
  \(A\cap A^c=\emptyset\)
* le principali operazioni tra insiemi rispettano proprieta' `commutative`, `associative` e `distributive`
* le `leggi di De Morgan` stabiliscono:
  \((A\cup B)^c=A^c\cap B^c\)
  \((A\cap B)^c=A^c\cup B^c\)
* una `partizione` divide un insieme in sottoinsiemi non vuoti, a due a due disgiunti, la cui unione coincide con l'insieme di partenza
* il `prodotto cartesiano` $A\times B$ contiene tutte le coppie ordinate $(x,y)$ con:
  \(x\in A,\ y\in B\)
* nel prodotto cartesiano l'ordine degli elementi e' importante:
  \((x,y)\not=(y,x)\)
* se $|A|=m$ e $|B|=n$, allora:
  \(|A\times B|=m\cdot n\)
* il prodotto cartesiano $\mathbb R\times\mathbb R$ permette di rappresentare i punti del `piano cartesiano`
* nei problemi con gli insiemi e' spesso utile rappresentare graficamente le situazioni con i `diagrammi di Eulero-Venn`
* per due insiemi finiti vale la formula:
  \(|A\cup B|=|A|+|B|-|A\cap B|\)

> 💡 Idea: gli insiemi permettono di **classificare**, **confrontare** e **combinare** oggetti attraverso regole precise.

Le principali operazioni possono essere riassunte:

$$
\boxed{
\begin{aligned}
A\cup B &\rightarrow \text{elementi di A oppure di B}\\
A\cap B &\rightarrow \text{elementi di A e di B}\\
A\setminus B &\rightarrow \text{elementi di A ma non di B}\\
A^c &\rightarrow \text{elementi dell'universo che non sono in A}\\
A\times B &\rightarrow \text{coppie ordinate di elementi di A e B}
\end{aligned}
}
$$

E possiamo visualizzare il concetto generale:

$$
\text{insiemi}
\xrightarrow{\text{rappresentazione}}
\text{Eulero-Venn}
\xrightarrow{\text{operazioni}}
\text{nuovi insiemi}
$$

> 💡 Idea: una volta imparato a lavorare con gli insiemi, possiamo usarli come strumento per rappresentare e risolvere problemi sempre piu' complessi.
