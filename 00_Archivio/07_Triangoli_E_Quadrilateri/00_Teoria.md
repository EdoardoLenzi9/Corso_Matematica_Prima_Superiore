# 🎓 Lezione: Triangoli e Quadrilateri

> 💡 Idea: dopo aver studiato i numeri e le loro proprietà, possiamo usare la matematica per descrivere e misurare le **figure geometriche**

> 🎯 Obiettivo: comprendere le principali proprietà di **triangoli** e **quadrilateri**, imparare a riconoscerne gli elementi fondamentali e applicare i principali **teoremi geometrici**.

![](assets/011.svg)

# 📌 Triangolo

> 🤏 Definizione: un `triangolo` è una figura piana delimitata da `tre segmenti`, detti `lati`, che si incontrano a due a due in tre punti distinti, detti `vertici`

Un triangolo ha quindi:

* `3` lati
* `3` vertici
* `3` angoli

Indichiamo generalmente un triangolo con tre lettere maiuscole, una per ogni vertice:

\(\triangle ABC\)

I suoi lati sono:

\(AB,\ BC,\ CA\)

I suoi angoli sono:

\(\widehat A,\ \widehat B,\ \widehat C\)

> 🤔 Domanda: quanti lati e quanti vertici possiede un triangolo?

# 📌 Classificazione dei triangoli

I triangoli possono essere classificati in base ai `lati` oppure in base agli `angoli`.

## 📚 Classificazione rispetto ai lati

### 🚀 Triangolo equilatero

Un triangolo si dice `equilatero` se possiede tre lati congruenti.

\(AB=BC=CA\)

In un triangolo equilatero anche i tre angoli sono congruenti:

\(\widehat A=\widehat B=\widehat C=60^\circ\)

### 🚀 Triangolo isoscele

Un triangolo si dice `isoscele` se possiede almeno due lati congruenti.

Per esempio:

\(AB=AC\)

I due lati congruenti sono detti `lati obliqui`, mentre il terzo lato è detto `base`.

Gli angoli opposti ai lati congruenti sono congruenti.

\(\widehat B=\widehat C\)

### 🚀 Triangolo scaleno

Un triangolo si dice `scaleno` se possiede tre lati di lunghezza diversa.

\(AB\not=BC\not=CA\)

Di conseguenza anche i suoi angoli sono generalmente tutti diversi.

## 📚 Classificazione rispetto agli angoli

### 🚀 Triangolo acutangolo

Ha tutti gli angoli `acuti`:

\(\widehat A<90^\circ,\quad \widehat B<90^\circ,\quad \widehat C<90^\circ\)

### 🚀 Triangolo rettangolo

Possiede un angolo `retto`:

\(\widehat C=90^\circ\)

Il lato opposto all'angolo retto si chiama `ipotenusa`.

Gli altri due lati si chiamano `cateti`.

### 🚀 Triangolo ottusangolo

Possiede un angolo `ottuso`:

\(\widehat A>90^\circ\)

Gli altri due angoli sono necessariamente acuti.

> 🤔 Domanda: può un triangolo avere due angoli ottusi?

# 📌 Angoli interni di un triangolo

> 🤏 Teorema: la `somma degli angoli interni` di un triangolo è sempre uguale a $180^\circ$

$$
\widehat A+\widehat B+\widehat C=180^\circ
$$

## 🚀 Esempio

Consideriamo un triangolo con:

\(\widehat A=50^\circ\)
\(\widehat B=60^\circ\)

Il terzo angolo vale:

$$
\widehat C=180^\circ-50^\circ-60^\circ=70^\circ
$$

> 🤔 Domanda: se due angoli di un triangolo misurano $35^\circ$ e $75^\circ$, quanto misura il terzo?

# 📌 Perimetro del triangolo

Il `perimetro` di un triangolo è la somma delle lunghezze dei suoi lati.

$$
P=AB+BC+CA
$$

Per un triangolo con lati $a$, $b$ e $c$:

$$
P=a+b+c
$$

## 🚀 Esempio

Un triangolo ha lati:

\(a=4,\quad b=5,\quad c=7\)

Quindi:

\(P=4+5+7=16\)

# 📌 Mediana

> 🤏 Definizione: la `mediana` relativa ad un lato è il segmento che unisce il vertice opposto con il `punto medio` del lato stesso

Consideriamo il triangolo $\triangle ABC$.

Se $M$ è il punto medio di $BC$:

\(BM=MC\)

allora il segmento $AM$ è la `mediana` relativa al lato $BC$.

Ogni triangolo possiede `3 mediane`.

![](assets/012.svg)

> 🤔 Domanda: quante mediane possiamo tracciare in un triangolo?

# 📌 Altezza

> 🤏 Definizione: l'`altezza` relativa ad un lato è il segmento perpendicolare al lato, o al suo prolungamento, condotto dal vertice opposto

Se $H$ è il piede dell'altezza relativa al lato $BC$:

\(AH\perp BC\)

Il segmento $AH$ è quindi l'`altezza` relativa a $BC$.

Ogni triangolo possiede `3 altezze`.

![](assets/013.svg)

> 💡 Idea: l'altezza permette di misurare la distanza `perpendicolare` di un vertice dal lato opposto.

# 📌 Bisettrice

> 🤏 Definizione: la `bisettrice` di un angolo è la semiretta che divide l'angolo in `due angoli congruenti`

Se $AD$ è la bisettrice dell'angolo $\widehat A$:

$$
\widehat{BAD}=\widehat{DAC}
$$

Ogni triangolo possiede `3 bisettrici interne`.

![](assets/014.svg)

# 📌 Asse di un segmento

> 🤏 Definizione: l'`asse` di un segmento è la retta perpendicolare al segmento che passa per il suo `punto medio`

Se $M$ è il punto medio di $AB$:

\(AM=MB\)

e l'asse di $AB$ è perpendicolare ad $AB$.

\(r\perp AB\)

Ogni punto dell'asse di un segmento è equidistante dagli estremi del segmento.

$$
P\in r\Rightarrow PA=PB
$$

> 🤔 Domanda: se un punto è equidistante da $A$ e $B$, dove si trova?

# 📌 Teorema del triangolo isoscele

Consideriamo un triangolo isoscele:

\(AB=AC\)

> 🤏 Teorema: in un `triangolo isoscele` gli angoli alla base sono congruenti.

$$
\widehat B=\widehat C
$$

Vale anche il contrario:

> 🤏 Teorema inverso: se due angoli di un triangolo sono congruenti, allora i lati opposti sono congruenti.

$$
\widehat B=\widehat C\Rightarrow AB=AC
$$

## 🚀 Esempio

Consideriamo:

\(AB=AC\)

e:

\(\widehat B=40^\circ\)

Allora:

\(\widehat C=40^\circ\)

e quindi:

\(\widehat A=180^\circ-40^\circ-40^\circ=100^\circ\)

# 📌 Congruenza tra figure

> 🤏 Definizione: due figure si dicono `congruenti` se hanno la stessa forma e la stessa dimensione, cioè se una può essere sovrapposta all'altra mediante un movimento rigido

Indichiamo la congruenza con:

\(\cong\)

Per esempio:

\(\triangle ABC\cong\triangle DEF\)

> 💡 Idea: figure congruenti possono essere traslate, ruotate o ribaltate, ma mantengono invariate lunghezze e angoli.

# 📌 Criteri di congruenza dei triangoli

I criteri di congruenza permettono di stabilire che due triangoli sono congruenti senza dover confrontare tutti i loro elementi.

## 📚 Primo criterio: LAL

> 🤏 Definizione: `LAL` significa `Lato-Angolo-Lato`

Due triangoli sono congruenti se hanno rispettivamente:

* due lati congruenti
* l'angolo compreso fra questi due lati congruente

$$
LAL\Rightarrow\triangle ABC\cong\triangle DEF
$$

## 📚 Secondo criterio: ALA

> 🤏 Definizione: `ALA` significa `Angolo-Lato-Angolo`

Due triangoli sono congruenti se hanno rispettivamente:

* due angoli congruenti
* il lato compreso fra i due angoli congruente

$$
ALA\Rightarrow\triangle ABC\cong\triangle DEF
$$

## 📚 Terzo criterio: LLL

> 🤏 Definizione: `LLL` significa `Lato-Lato-Lato`

Due triangoli sono congruenti se hanno i tre lati rispettivamente congruenti.

$$
LLL\Rightarrow\triangle ABC\cong\triangle DEF
$$

> 🤔 Domanda: se conosco solamente i tre lati di un triangolo, posso determinarne la forma?

# 📌 Disuguaglianza triangolare

> 🤏 Teorema: in ogni triangolo la lunghezza di ciascun lato è `minore della somma` degli altri due lati.

Se i lati sono $a$, $b$ e $c$:

$$
a<b+c
$$

$$
b<a+c
$$

$$
c<a+b
$$

Equivalentemente:

$$
|a-b|<c<a+b
$$

> 💡 Idea: non è possibile costruire un triangolo con tre segmenti qualsiasi.

## 🚀 Esempio

Possiamo costruire un triangolo con lati:

\(3,\ 4,\ 5\)

perché:

\(3+4>5\)

e anche:

\(3+5>4\)

\(4+5>3\)

Ma non possiamo costruire un triangolo con lati:

\(2,\ 3,\ 6\)

perché:

\(2+3<6\)

# 🚀 Esercizi

* Classifica il triangolo con angoli $40^\circ$, $60^\circ$, $80^\circ$
* Trova il terzo angolo di un triangolo con angoli $45^\circ$ e $65^\circ$
* Un triangolo ha lati $5$, $5$, $8$: che tipo di triangolo è rispetto ai lati?
* Verifica se $4$, $7$, $12$ possono essere lati di un triangolo
* Verifica se $6$, $8$, $10$ possono essere lati di un triangolo

# 📌 Teorema di Pitagora

Consideriamo un `triangolo rettangolo`.

I due lati che formano l'angolo retto sono i `cateti`:

\(a,\ b\)

Il lato opposto all'angolo retto è l'`ipotenusa`:

\(c\)

> 🤏 Teorema di Pitagora: in ogni triangolo rettangolo, il `quadrato dell'ipotenusa` è uguale alla somma dei `quadrati dei cateti`.

$$
c^2=a^2+b^2
$$

![](assets/015.svg)

## 🚀 Esempio

Consideriamo un triangolo rettangolo con:

\(a=3,\quad b=4\)

Allora:

$$
c^2=3^2+4^2
$$

$$
c^2=9+16=25
$$

$$
c=\sqrt{25}=5
$$

Quindi:

$$
3^2+4^2=5^2
$$

> 💡 Idea: la terna $(3,4,5)$ è una `terna pitagorica`.

## 📚 Teorema inverso di Pitagora

> 🤏 Teorema: se in un triangolo il quadrato del lato maggiore è uguale alla somma dei quadrati degli altri due lati, allora il triangolo è `rettangolo`.

$$
c^2=a^2+b^2\Rightarrow\widehat C=90^\circ
$$

## 🚀 Esercizi

1. Calcola l'ipotenusa di un triangolo rettangolo con cateti $6$ e $8$
2. Calcola un cateto sapendo che $c=13$ e $a=5$
3. Verifica se $7$, $24$, $25$ formano una terna pitagorica
4. Un triangolo ha lati $8$, $15$, $17$: è rettangolo?

# 📌 Quadrilatero

> 🤏 Definizione: un `quadrilatero` è una figura piana delimitata da `quattro segmenti`, detti lati

Un quadrilatero possiede:

* `4` lati
* `4` vertici
* `4` angoli
* `2` diagonali

Indichiamo un quadrilatero con:

\(ABCD\)

I suoi lati sono:

\(AB,\ BC,\ CD,\ DA\)

Le sue diagonali sono:

\(AC,\ BD\)

![](assets/016.svg)

# 📌 Somma degli angoli interni di un quadrilatero

> 🤏 Teorema: la somma degli angoli interni di un quadrilatero è sempre $360^\circ$.

$$
\widehat A+\widehat B+\widehat C+\widehat D=360^\circ
$$

> 💡 Idea: possiamo dividere un quadrilatero con una diagonale in `due triangoli`.

Ogni triangolo ha somma degli angoli interni pari a $180^\circ$, quindi:

$$
180^\circ+180^\circ=360^\circ
$$

> 🤔 Domanda: quanti triangoli posso ottenere tracciando una diagonale di un quadrilatero?

# 📌 Classificazione dei quadrilateri

I principali quadrilateri sono:

* `trapezio`
* `parallelogramma`
* `rettangolo`
* `rombo`
* `quadrato`

# 📌 Trapezio

> 🤏 Definizione: un `trapezio` è un quadrilatero con almeno una coppia di lati opposti paralleli.

I lati paralleli sono detti `basi`.

Gli altri due lati sono detti `lati obliqui`.

Se $AB\parallel CD$:

$$
AB\parallel CD
$$

![](assets/017.svg)

## 📚 Trapezio isoscele

> 🤏 Definizione: un `trapezio isoscele` è un trapezio i cui lati obliqui sono congruenti.

$$
AD=BC
$$

Gli angoli adiacenti a ciascuna base sono congruenti:

$$
\widehat A=\widehat B
$$

$$
\widehat D=\widehat C
$$

Le diagonali sono congruenti:

$$
AC=BD
$$

## 📚 Trapezio rettangolo

> 🤏 Definizione: un `trapezio rettangolo` è un trapezio che possiede due angoli retti.

![](assets/018.svg)

> 🤔 Domanda: quanti angoli retti possiede necessariamente un trapezio rettangolo?

# 📌 Parallelogramma

> 🤏 Definizione: un `parallelogramma` è un quadrilatero con `due coppie di lati opposti paralleli`.

$$
AB\parallel CD
$$

$$
AD\parallel BC
$$

![](assets/019.svg)

## 📚 Proprietà

In un parallelogramma:

* i lati opposti sono congruenti
* gli angoli opposti sono congruenti
* gli angoli consecutivi sono supplementari
* le diagonali si dividono reciprocamente a metà

Quindi:

$$
AB=CD
$$

$$
AD=BC
$$

e:

$$
\widehat A=\widehat C
$$

$$
\widehat B=\widehat D
$$

Inoltre, se le diagonali si incontrano in $O$:

$$
AO=OC
$$

$$
BO=OD
$$

# 📌 Rettangolo

> 🤏 Definizione: un `rettangolo` è un parallelogramma con `quattro angoli retti`.

$$
\widehat A=\widehat B=\widehat C=\widehat D=90^\circ
$$

![](assets/020.svg)

Le proprietà principali sono:

* i lati opposti sono congruenti
* tutti gli angoli sono retti
* le diagonali sono congruenti
* le diagonali si dividono reciprocamente a metà

Se le diagonali sono $AC$ e $BD$:

$$
AC=BD
$$

e se si incontrano in $O$:

$$
AO=OC
$$

$$
BO=OD
$$

# 📌 Rombo

> 🤏 Definizione: un `rombo` è un parallelogramma con `quattro lati congruenti`.

$$
AB=BC=CD=DA
$$

![](assets/021.svg)

Le proprietà principali sono:

* tutti i lati sono congruenti
* i lati opposti sono paralleli
* gli angoli opposti sono congruenti
* le diagonali sono perpendicolari
* le diagonali si dividono reciprocamente a metà
* le diagonali sono bisettrici degli angoli

Se le diagonali si incontrano in $O$:

$$
AC\perp BD
$$

e:

$$
AO=OC
$$

$$
BO=OD
$$

# 📌 Quadrato

> 🤏 Definizione: un `quadrato` è un quadrilatero con `quattro lati congruenti` e `quattro angoli retti`.

$$
AB=BC=CD=DA
$$

$$
\widehat A=\widehat B=\widehat C=\widehat D=90^\circ
$$

![](assets/022.svg)

Il quadrato possiede contemporaneamente le proprietà del:

* `rettangolo`
* `rombo`
* `parallelogramma`

Le sue diagonali sono:

* congruenti
* perpendicolari
* bisettrici degli angoli
* si dividono reciprocamente a metà

> 💡 Idea: il quadrato è quindi un caso particolare sia di `rettangolo` sia di `rombo`.

> 🤔 Domanda: un quadrato è sempre un rettangolo? E un rettangolo è sempre un quadrato?

# 📌 Diagonali dei quadrilateri

Ogni quadrilatero possiede `2 diagonali`.

$$
AC,\ BD
$$

La presenza e le proprietà delle diagonali aiutano a riconoscere i diversi quadrilateri.

| Figura          | Diagonali congruenti | Diagonali perpendicolari | Si dimezzano |
| --------------- | -------------------- | ------------------------ | ------------ |
| Parallelogramma | non sempre           | non sempre               | sì           |
| Rettangolo      | sì                   | non sempre               | sì           |
| Rombo           | non sempre           | sì                       | sì           |
| Quadrato        | sì                   | sì                       | sì           |

# 📌 Perimetro dei quadrilateri

Il perimetro di un quadrilatero è la somma dei quattro lati:

$$
P=a+b+c+d
$$

## 🚀 Esempio

Un quadrilatero ha lati:

$$
4,\ 5,\ 7,\ 10
$$

Quindi:

$$
P=4+5+7+10=26
$$

## 📚 Perimetro del rettangolo

Se i lati misurano $a$ e $b$:

$$
P=2a+2b
$$

oppure:

$$
P=2(a+b)
$$

## 📚 Perimetro del quadrato

Se il lato misura $l$:

$$
P=4l
$$

## 🚀 Esercizi

* Calcola il perimetro di un rettangolo con lati $8$ e $5$
* Calcola il perimetro di un quadrato di lato $7$
* Un rombo ha lato $6$: quanto vale il suo perimetro?
* Un trapezio ha lati $5$, $7$, $8$, $10$: calcola il perimetro

# 📌 Rette parallele e trasversale

Consideriamo due rette $r$ e $s$ intersecate da una terza retta $t$, detta `trasversale`.

![](assets/023.svg)

Se:

$$
r\parallel s
$$

si possono individuare particolari coppie di angoli.

# 📌 Angoli corrispondenti

> 🤏 Definizione: due angoli sono `corrispondenti` quando occupano la stessa posizione rispetto alle due intersezioni della trasversale con le rette.

Se le rette sono parallele, gli angoli corrispondenti sono congruenti.

$$
\widehat\alpha=\widehat\beta
$$

> 🤏 Teorema inverso: se due angoli corrispondenti sono congruenti, allora le due rette sono parallele.

# 📌 Angoli alterni interni

> 🤏 Definizione: due angoli sono `alterni interni` quando si trovano tra le due rette e su lati opposti rispetto alla trasversale.

Se:

$$
r\parallel s
$$

allora gli angoli alterni interni sono congruenti.

$$
\widehat\alpha=\widehat\beta
$$

![](assets/024.svg)

# 📌 Angoli coniugati interni

> 🤏 Definizione: due angoli sono `coniugati interni` quando si trovano tra le due rette e dalla stessa parte rispetto alla trasversale.

Se:

$$
r\parallel s
$$

gli angoli coniugati interni sono `supplementari`.

$$
\widehat\alpha+\widehat\beta=180^\circ
$$

![](assets/025.svg)

> 💡 Idea: rispetto a due rette parallele, gli angoli corrispondenti e alterni interni sono `congruenti`, mentre gli angoli coniugati interni sono `supplementari`.

# 📌 Rette non parallele

Le relazioni precedenti non richiedono solamente la presenza della trasversale: alcune proprietà dipendono proprio dal fatto che le due rette siano `parallele`.

Se $r$ e $s$ non sono parallele, in generale:

$$
\widehat\alpha\not=\widehat\beta
$$

per gli angoli corrispondenti o alterni interni.

Tuttavia, per ogni intersezione di due rette, valgono sempre alcune proprietà degli angoli:

* gli angoli opposti al vertice sono congruenti
* gli angoli adiacenti sono supplementari

# 📌 Teorema di Talete

> 🤏 Idea: il `Teorema di Talete` permette di mettere in relazione segmenti determinati da un fascio di rette parallele.

Consideriamo due rette `trasversali` intersecate da più rette parallele.

![](assets/026.svg)

> 🤏 Teorema: un fascio di `rette parallele` determina su due trasversali `segmenti proporzionali`.

Se:

$$
r_1\parallel r_2\parallel r_3
$$

allora, sulle due trasversali, vale:

$$
\frac{AB}{BC}=\frac{A'B'}{B'C'}
$$

# 📌 Teorema di Talete applicato al triangolo

Il Teorema di Talete è particolarmente utile nei triangoli.

Consideriamo il triangolo $ABC$ e una retta $DE$ parallela al lato $BC$:

$$
DE\parallel BC
$$

con:

$$
D\in AB,\qquad E\in AC
$$

![](assets/027.svg)

Allora i segmenti sui lati del triangolo sono proporzionali:

$$
\frac{AD}{DB}=\frac{AE}{EC}
$$

e inoltre:

$$
\frac{AD}{AB}=\frac{AE}{AC}
$$

> 💡 Idea: una retta parallela ad un lato di un triangolo determina sui due lati rimanenti segmenti `proporzionali`.

## 🚀 Esempio

Consideriamo:

$$
AD=3,\quad DB=2,\quad AE=6
$$

e supponiamo:

$$
DE\parallel BC
$$

Per Talete:

$$
\frac{AD}{DB}=\frac{AE}{EC}
$$

quindi:

$$
\frac32=\frac6{EC}
$$

Da cui:

$$
3EC=12
$$

$$
EC=4
$$

# 📌 Teorema di Talete applicato al trapezio

Consideriamo un trapezio con basi parallele:

$$
AB\parallel CD
$$

Una retta parallela alle basi può determinare segmenti proporzionali sui lati obliqui.

![](assets/028.svg)

Il Teorema di Talete permette quindi di calcolare segmenti mancanti conoscendo rapporti e lunghezze corrispondenti.

> 💡 Idea: il principio fondamentale è sempre lo stesso: `rette parallele` determinano `segmenti proporzionali` sulle trasversali.

# 🚀 Esercizi

1. In un triangolo gli angoli misurano $30^\circ$ e $80^\circ$. Trova il terzo angolo.
2. Un triangolo isoscele ha angolo al vertice di $40^\circ$. Quanto misurano gli angoli alla base?
3. Verifica se i lati $5$, $12$, $13$ formano un triangolo rettangolo.
4. Un triangolo rettangolo ha cateti $9$ e $12$. Calcola l'ipotenusa.
5. Un quadrilatero ha tre angoli di $80^\circ$, $90^\circ$ e $110^\circ$. Calcola il quarto.
6. Classifica un quadrilatero con quattro lati congruenti e quattro angoli retti.
7. In un parallelogramma un angolo misura $70^\circ$. Quanto misurano gli altri tre?
8. Un quadrato ha lato $9$. Calcola il perimetro.
9. Un rettangolo ha lati $12$ e $7$. Calcola il perimetro.
10. Due rette parallele sono intersecate da una trasversale. Se un angolo misura $65^\circ$, quanto misura il suo angolo alterno interno?
11. Due angoli coniugati interni rispetto a due rette parallele misurano $x$ e $120^\circ$. Calcola $x$.
12. Applica il Teorema di Talete sapendo che:
    \(AD=4,\quad DB=6,\quad AE=8\)
    e $DE\parallel BC$. Calcola $EC$.

# 📌 Riepilogo

Abbiamo imparato che:

* un `triangolo` è una figura delimitata da tre segmenti
* un triangolo possiede `3 lati`, `3 vertici` e `3 angoli`
* i triangoli possono essere classificati rispetto ai `lati` in equilateri, isosceli e scaleni
* i triangoli possono essere classificati rispetto agli `angoli` in acutangoli, rettangoli e ottusangoli
* la somma degli angoli interni di un triangolo vale sempre:
  \(180^\circ\)
* il `perimetro` di un triangolo è la somma dei suoi tre lati:
  \(P=a+b+c\)
* la `mediana` unisce un vertice con il punto medio del lato opposto
* l'`altezza` è il segmento perpendicolare al lato, o al suo prolungamento, condotto dal vertice opposto
* la `bisettrice` divide un angolo in due angoli congruenti
* l'`asse` di un segmento è la retta perpendicolare al segmento che passa per il suo punto medio
* in un `triangolo isoscele` gli angoli alla base sono congruenti
* due figure sono `congruenti` se possono essere sovrapposte mediante un movimento rigido
* i principali criteri di congruenza dei triangoli sono `LAL`, `ALA` e `LLL`
* la `disuguaglianza triangolare` stabilisce che ogni lato di un triangolo è minore della somma degli altri due:
  \(a<b+c\)
* nel `triangolo rettangolo` i lati che formano l'angolo retto sono i `cateti`, mentre il lato opposto è l'`ipotenusa`
* il `Teorema di Pitagora` stabilisce:
  \(c^2=a^2+b^2\)
* il `Teorema inverso di Pitagora` permette di riconoscere un triangolo rettangolo attraverso la relazione tra i quadrati dei suoi lati
* un `quadrilatero` è una figura delimitata da quattro segmenti
* un quadrilatero possiede `4 lati`, `4 vertici`, `4 angoli` e `2 diagonali`
* la somma degli angoli interni di un quadrilatero vale:
  \(360^\circ\)
* un `trapezio` è un quadrilatero con almeno una coppia di lati opposti paralleli
* un `trapezio isoscele` possiede i lati obliqui congruenti
* un `trapezio rettangolo` possiede due angoli retti
* un `parallelogramma` possiede due coppie di lati opposti paralleli
* in un parallelogramma i lati opposti e gli angoli opposti sono congruenti
* le diagonali di un parallelogramma si dividono reciprocamente a metà
* un `rettangolo` è un parallelogramma con quattro angoli retti
* le diagonali di un rettangolo sono congruenti e si dividono reciprocamente a metà
* un `rombo` è un parallelogramma con quattro lati congruenti
* le diagonali di un rombo sono perpendicolari e si dividono reciprocamente a metà
* un `quadrato` possiede contemporaneamente le proprietà del rettangolo e del rombo
* le diagonali di un quadrato sono congruenti, perpendicolari e si dividono reciprocamente a metà
* una `trasversale` è una retta che interseca due o più rette
* rispetto a due rette parallele, gli angoli `corrispondenti` sono congruenti
* rispetto a due rette parallele, gli angoli `alterni interni` sono congruenti
* rispetto a due rette parallele, gli angoli `coniugati interni` sono supplementari
* il `Teorema di Talete` stabilisce che un fascio di rette parallele determina segmenti proporzionali su due trasversali
* il Teorema di Talete può essere applicato anche ai `triangoli`
* nel triangolo, una retta parallela ad un lato determina segmenti proporzionali sugli altri due lati
* il Teorema di Talete può essere utilizzato anche per risolvere problemi relativi ai `trapezi`

> 💡 Idea: triangoli e quadrilateri sono costruiti a partire da pochi elementi fondamentali, ma le loro proprietà permettono di descrivere una grande quantità di figure geometriche.

Le idee fondamentali possono essere riassunte:

$$
\boxed{
\text{Triangoli}
\longrightarrow
\text{Congruenza}
\longrightarrow
\text{Pitagora}
}
$$

e:

$$
\boxed{
\text{Quadrilateri}
\longrightarrow
\text{Parallele}
\longrightarrow
\text{Talete}
}
$$

Le proprietà geometriche diventano quindi strumenti per `riconoscere`, `confrontare`, `misurare` e `calcolare` le figure.

> 💡 Idea: conoscere una figura significa non solo saperla riconoscere, ma anche sapere quali proprietà possiamo utilizzare per dedurre nuove informazioni.
