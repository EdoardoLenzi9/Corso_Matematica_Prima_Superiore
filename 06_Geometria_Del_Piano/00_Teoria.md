# 🎓 Lezione: Geometria del piano

> 💡 Idea: la `geometria` nasce dalla necessità di descrivere e misurare lo `spazio` 
> attraverso punti, rette, figure e relazioni fra esse.

> 🎯 Obiettivo: comprendere i concetti fondamentali della `geometria del piano`, 
> imparando a riconoscere gli enti geometrici, le principali figure piane e le loro proprietà.

![](assets/011.svg)

# 📌 Enti primitivi

> 💡 Idea: per costruire una teoria geometrica abbiamo bisogno di alcuni `concetti fondamentali` 
> che non vengono definiti attraverso altri concetti più semplici.

Gli `enti primitivi` della geometria euclidea sono:

* `punto`
* `retta`
* `piano`

Essi vengono assunti come concetti di base e vengono descritti attraverso le loro proprietà.

## 📚 Punto

Il `punto` rappresenta una posizione nello spazio e non possiede dimensioni.

Si indica generalmente con una `lettera maiuscola`:

$$A,\ B,\ C,\dots$$

## 📚 Retta

La `retta` è un insieme infinito di punti allineati e si estende infinitamente 
in entrambe le direzioni.

Si indica generalmente con una `lettera minuscola`:

$$r,\ s,\ t,\dots$$

Oppure attraverso due suoi punti:

$$r=AB$$

## 📚 Piano

Il `piano` è una superficie geometrica bidimensionale che si estende infinitamente 
in tutte le direzioni.

Si indica generalmente con una `lettera greca`:

$$\alpha,\ \beta,\ \gamma,\dots$$

> 🤔 Domanda: quante dimensioni possiede un punto? E una retta? E un piano?

# 📌 Postulati e assiomi

> 🤏 Definizione: un `assioma` è una proposizione considerata vera senza bisogno 
> di essere dimostrata.

> 🤏 Definizione: un `postulato` è un'affermazione assunta come vera all'interno 
> di una particolare teoria matematica.

Nella geometria euclidea alcuni risultati fondamentali vengono assunti come punti di partenza.

## 📚 Postulato della retta

> 💡 Idea: per `due punti distinti` passa una e una sola retta.

$$
A\not=B\Rightarrow\exists!\ r\mid A,B\in r
$$

## 📚 Teoremi

> 🤏 Definizione: un `teorema` è una proposizione che viene dimostrata 
> a partire da definizioni, assiomi, postulati e risultati precedenti.

Un teorema possiede generalmente:

* `ipotesi`: ciò che viene assunto come vero
* `tesi`: ciò che deve essere dimostrato

> 🚀 Esempio: se due rette sono parallele ad una stessa retta, allora sono parallele tra loro.

> 🤔 Domanda: qual'e' la differenza fra un `assioma` e un `teorema`?

# 📌 Geometria euclidea

La `geometria euclidea` è la geometria sviluppata a partire dagli elementi e dai postulati 
di `Euclide`.

Una delle sue caratteristiche fondamentali è il `quinto postulato`, legato alle rette parallele.

> 💡 Idea: per molto tempo i matematici hanno cercato di dimostrare il quinto postulato 
> a partire dagli altri, ma si è scoperto che è possibile costruire geometrie coerenti 
> nelle quali esso non vale.

# 📌 Geometrie non euclidee

> 💡 Idea: modificando alcuni postulati della geometria euclidea possiamo ottenere 
> `geometrie non euclidee`.

Le principali sono:

* `geometria ellittica`: non esistono rette parallele
* `geometria iperbolica`: per un punto esterno ad una retta passano più rette parallele alla retta data

Nella geometria euclidea invece:

$$
\text{per un punto esterno ad una retta passa una e una sola parallela}
$$

> 🤔 Domanda: cosa succederebbe sulla superficie di una sfera?

# 📌 Semiretta

Consideriamo una retta $r$ e un punto $A$ appartenente ad essa.

Il punto $A$ divide la retta in due `semirette`.

Una `semiretta` è quindi una parte di retta che possiede:

* un `punto di origine`
* una direzione
* una lunghezza infinita

Si indica con due punti, mettendo per primo l'origine:

$$\overrightarrow{AB}$$

> 🤔 Domanda: le semirette $\overrightarrow{AB}$ e $\overrightarrow{BA}$ sono la stessa semiretta?

# 📌 Segmento

Consideriamo due punti distinti $A$ e $B$.

Il `segmento` $\overline{AB}$ è la parte di retta compresa fra i due punti.

I punti $A$ e $B$ si chiamano `estremi` del segmento.

![](assets/012.svg)

La `lunghezza` del segmento si indica:

$$
AB
$$

> 💡 Idea: a differenza della retta e della semiretta, un segmento ha una `lunghezza finita`.

## 🚀 Esempio

Se:

$$
AB=5\ cm
$$

allora la distanza fra i punti $A$ e $B$ è di `5 cm`.

# 📌 Poligonale

Una `poligonale` è una figura formata da una successione di segmenti consecutivi.

![](assets/013.svg)

I segmenti consecutivi hanno un estremo in comune.

Una poligonale può essere:

* `aperta`, se il primo e l'ultimo estremo sono distinti
* `chiusa`, se il primo e l'ultimo estremo coincidono

> 🤔 Domanda: una poligonale chiusa può essere considerata un poligono?

# 📌 Figure convesse e concave

Consideriamo una figura piana.

> 🤏 Definizione: una figura si dice `convessa` se, presi due punti qualsiasi 
> appartenenti alla figura, il segmento che li unisce è completamente contenuto nella figura.

![](assets/014.svg)

> 🤏 Definizione: una figura si dice `concava` se esistono almeno due punti della figura 
> tali che il segmento che li unisce non è completamente contenuto nella figura.

![](assets/015.svg)

> 💡 Idea: una figura convessa non presenta `rientranze`, mentre una figura concava 
> presenta almeno una `rientranza`.

## 🚀 Esempio

Un triangolo è sempre `convesso`.

Un poligono con una rientranza può essere `concavo`.

> 🤔 Domanda: un quadrato è concavo o convesso?

# 📌 Congruenza tra figure

> 🤏 Definizione: due figure si dicono `congruenti` se hanno la stessa forma e la stessa dimensione, 
> cioè se una può essere sovrapposta perfettamente all'altra tramite un movimento rigido.

Il simbolo di congruenza è:

$$
\cong
$$

Quindi, se due segmenti hanno la stessa lunghezza:

$$
\overline{AB}\cong\overline{CD}
$$

> 💡 Idea: figure congruenti possono essere `traslate`, `ruotate` o `ribaltate` senza modificarne 
> forma e dimensioni.

> 🤔 Domanda: due figure con la stessa area sono necessariamente congruenti?

# 📌 Cerchio e circonferenza

Consideriamo un punto $O$ e una distanza $r$.

## 📚 Circonferenza

> 🤏 Definizione: la `circonferenza` è l'insieme dei punti del piano che hanno 
> la stessa distanza $r$ da un punto fisso $O$, detto `centro`.

$$
C=\{P\mid OP=r\}
$$

![](assets/016.svg)

La distanza $r$ si chiama `raggio`.

## 📚 Cerchio

> 🤏 Definizione: il `cerchio` è la parte di piano delimitata dalla circonferenza.

Quindi:

* `circonferenza` = solo il bordo
* `cerchio` = bordo + parte interna

> 🤔 Domanda: un punto appartenente alla circonferenza è sempre alla stessa distanza 
> dal centro?

## 📚 Raggio

Il `raggio` è il segmento che collega il centro della circonferenza 
con un qualsiasi punto della circonferenza.

$$
OP=r
$$

## 📚 Diametro

Il `diametro` è una corda che passa per il centro.

$$
d=2r
$$

## 📚 Corda

Una `corda` è un segmento che unisce due punti della circonferenza.

Il diametro è la `corda di lunghezza massima`.

# 📌 Angoli

> 🤏 Definizione: un `angolo` è la parte di piano compresa fra due semirette 
> aventi la stessa origine.

Le due semirette si chiamano `lati` dell'angolo.

Il punto comune si chiama `vertice`.

![](assets/017.svg)

L'angolo si può indicare con tre lettere:

$$
\widehat{AOB}
$$

dove $O$ è il vertice.

Oppure con una sola lettera se non c'è ambiguità:

$$
\widehat O
$$

## 📚 Misura degli angoli

L'unità di misura più utilizzata è il `grado`.

Un angolo giro misura:

$$
360^\circ
$$

Un angolo piatto misura:

$$
180^\circ
$$

Un angolo retto misura:

$$
90^\circ
$$

Un angolo nullo misura:

$$
0^\circ
$$

# 📌 Classificazione degli angoli

Gli angoli possono essere classificati in base alla loro ampiezza.

| Tipo | Misura |
|---|---|
| `Nullo` | $$0^\circ$$ |
| `Acuto` | $$0^\circ<\alpha<90^\circ$$ |
| `Retto` | $$\alpha=90^\circ$$ |
| `Ottuso` | $$90^\circ<\alpha<180^\circ$$ |
| `Piatto` | $$\alpha=180^\circ$$ |
| `Concavo` | $$180^\circ<\alpha<360^\circ$$ |
| `Giro` | $$\alpha=360^\circ$$ |

![](assets/018.svg)

# 📌 Angoli complementari

> 🤏 Definizione: due angoli sono `complementari` se la loro somma è un angolo retto.

$$
\alpha+\beta=90^\circ
$$

## 🚀 Esempio

Se:

$$
\alpha=35^\circ
$$

allora il suo complementare vale:

$$
\beta=90^\circ-35^\circ=55^\circ
$$

## 🚀 Esercizi

* Trova il complementare di $20^\circ$
* Trova il complementare di $63^\circ$
* Due angoli complementari misurano $x$ e $2x$. Trova $x$

# 📌 Angoli supplementari

> 🤏 Definizione: due angoli sono `supplementari` se la loro somma è un angolo piatto.

$$
\alpha+\beta=180^\circ
$$

## 🚀 Esempio

Se:

$$
\alpha=120^\circ
$$

allora il suo supplementare vale:

$$
\beta=180^\circ-120^\circ=60^\circ
$$

## 🚀 Esercizi

* Trova il supplementare di $45^\circ$
* Trova il supplementare di $135^\circ$
* Due angoli supplementari misurano $x$ e $3x$. Trova $x$

# 📌 Angoli esplementari

> 🤏 Definizione: due angoli sono `esplementari` se la loro somma è un angolo giro.

$$
\alpha+\beta=360^\circ
$$

## 🚀 Esempio

Se:

$$
\alpha=250^\circ
$$

allora il suo esplementare vale:

$$
\beta=360^\circ-250^\circ=110^\circ
$$

> 🤔 Domanda: un angolo acuto può avere un esplementare?

# 📌 Angoli opposti al vertice

Consideriamo due rette incidenti.

Esse formano quattro angoli.

![](assets/019.svg)

Gli angoli che si trovano uno di fronte all'altro sono detti `opposti al vertice`.

> 🤏 Teorema: gli `angoli opposti al vertice` sono congruenti.

Quindi:

$$
\alpha=\gamma
$$

e:

$$
\beta=\delta
$$

> 💡 Idea: quando due rette si intersecano, basta conoscere la misura di un angolo 
> per determinare anche quella del suo opposto e dei due angoli adiacenti.

## 🚀 Esempio

Se:

$$
\alpha=70^\circ
$$

allora:

$$
\gamma=70^\circ
$$

e gli angoli adiacenti valgono:

$$
180^\circ-70^\circ=110^\circ
$$

# 📌 Poligoni

> 🤏 Definizione: un `poligono` è una parte di piano delimitata da una `poligonale chiusa` 
> formata da segmenti che si incontrano solo nei loro estremi consecutivi.

![](assets/020.svg)

Gli elementi principali di un poligono sono:

* `lati`
* `vertici`
* `angoli interni`
* `diagonali`

> 💡 Idea: il nome del poligono dipende dal `numero dei suoi lati`.

# 📌 Classificazione dei poligoni

| Numero di lati | Nome |
|---|---|
| 3 | Triangolo |
| 4 | Quadrilatero |
| 5 | Pentagono |
| 6 | Esagono |
| 7 | Ettagono |
| 8 | Ottagono |
| 9 | Ennagono |
| 10 | Decagono |

## 🚀 Esempi

Un poligono con 3 lati è un `triangolo`.

Un poligono con 4 lati è un `quadrilatero`.

Un poligono con 8 lati è un `ottagono`.

> 🤔 Domanda: come si chiama un poligono con 12 lati?

# 📌 Poligoni regolari

> 🤏 Definizione: un `poligono regolare` è un poligono che possiede tutti i lati 
> e tutti gli angoli congruenti.

Esempi:

* `triangolo equilatero`
* `quadrato`
* `pentagono regolare`
* `esagono regolare`

> 💡 Idea: un poligono può essere regolare solamente se possiede contemporaneamente 
> `lati congruenti` e `angoli congruenti`.

# 📌 Diagonali

> 🤏 Definizione: una `diagonale` è un segmento che unisce due vertici non consecutivi 
> di un poligono.

![](assets/021.svg)

Per trovare il numero delle diagonali di un poligono con $n$ lati utilizziamo:

$$
D=\frac{n(n-3)}{2}
$$

## 📚 Perché funziona?

Da ogni vertice possiamo tracciare diagonali verso:

$$
n-3
$$

vertici, perché non possiamo collegarlo:

* a se stesso
* ai due vertici consecutivi

Quindi apparentemente avremmo:

$$
n(n-3)
$$

segmenti.

Ma ogni diagonale viene contata `due volte`, una volta per ciascuno dei suoi estremi.

Per questo dividiamo per 2:

$$
\boxed{D=\frac{n(n-3)}{2}}
$$

## 🚀 Esempio

Consideriamo un pentagono:

$$
n=5
$$

Quindi:

$$
D=\frac{5(5-3)}{2}
$$

$$
D=\frac{5\cdot2}{2}=5
$$

Un pentagono possiede quindi `5 diagonali`.

## 🚀 Esempio

Consideriamo un esagono:

$$
n=6
$$

$$
D=\frac{6(6-3)}{2}
$$

$$
D=\frac{6\cdot3}{2}=9
$$

Un esagono possiede quindi `9 diagonali`.

## 🚀 Esercizi

1. Quante diagonali possiede un quadrilatero?
2. Quante diagonali possiede un ettagono?
3. Quante diagonali possiede un decagono?
4. Quante diagonali possiede un poligono di 20 lati?

# 📌 Riepilogo

Abbiamo imparato che:

* gli `enti primitivi` della geometria sono `punto`, `retta` e `piano`
* gli enti primitivi vengono assunti come concetti fondamentali della teoria geometrica
* un `assioma` è una proposizione assunta come vera senza dimostrazione
* un `postulato` è un'affermazione assunta come vera all'interno di una teoria geometrica
* un `teorema` è una proposizione che viene dimostrata a partire da definizioni, assiomi, postulati e risultati precedenti
* per due `punti distinti` passa una e una sola retta
* la `geometria euclidea` si basa sui postulati di Euclide
* modificando alcuni postulati si possono costruire `geometrie non euclidee`
* nella geometria `ellittica` non esistono rette parallele
* nella geometria `iperbolica` per un punto esterno ad una retta passano più rette parallele alla retta data
* una `semiretta` è una parte di retta con un punto di origine e lunghezza infinita in una direzione
* un `segmento` è la parte di retta compresa fra due estremi e possiede lunghezza finita
* una `poligonale` è una successione di segmenti consecutivi
* una poligonale può essere `aperta` oppure `chiusa`
* una figura `convessa` contiene completamente il segmento che unisce due suoi punti qualsiasi
* una figura `concava` possiede almeno una coppia di punti il cui segmento non è completamente contenuto nella figura
* due figure sono `congruenti` se hanno stessa forma e stessa dimensione e possono essere sovrapposte tramite un movimento rigido
* la `circonferenza` è l'insieme dei punti che hanno la stessa distanza dal centro:
  $$C=\{P\mid OP=r\}$$
* il `cerchio` è la parte di piano delimitata dalla circonferenza
* il `raggio` è il segmento che unisce il centro con un punto della circonferenza
* il `diametro` è una corda che passa per il centro:
  $$d=2r$$
* una `corda` è un segmento che unisce due punti della circonferenza
* un `angolo` è la parte di piano compresa fra due semirette aventi la stessa origine
* il punto comune delle semirette è il `vertice`
* le semirette che formano un angolo sono i suoi `lati`
* un angolo `retto` misura $90^\circ$
* un angolo `piatto` misura $180^\circ$
* un angolo `giro` misura $360^\circ$
* due angoli sono `complementari` se la loro somma è $90^\circ$:
  $$\alpha+\beta=90^\circ$$
* due angoli sono `supplementari` se la loro somma è $180^\circ$:
  $$\alpha+\beta=180^\circ$$
* due angoli sono `esplementari` se la loro somma è $360^\circ$:
  $$\alpha+\beta=360^\circ$$
* gli `angoli opposti al vertice` sono congruenti
* un `poligono` è una parte di piano delimitata da una poligonale chiusa
* gli elementi principali di un poligono sono `lati`, `vertici`, `angoli interni` e `diagonali`
* i poligoni vengono classificati in base al `numero di lati`
* un `poligono regolare` possiede tutti i lati e tutti gli angoli congruenti
* una `diagonale` unisce due vertici non consecutivi di un poligono
* il numero delle diagonali di un poligono di $n$ lati è:
  $$D=\frac{n(n-3)}{2}$$

> 💡 Idea: la geometria del piano ci permette di descrivere le `figure`, 
> le loro `relazioni` e le loro `proprieta'` attraverso pochi concetti fondamentali.

Dai `punti` possiamo costruire `rette` e `segmenti`, dai segmenti possiamo costruire 
`poligonali` e `poligoni`, mentre le relazioni fra rette e segmenti permettono di definire 
angoli, congruenze, circonferenze e molte altre figure.

$$
\boxed{
\text{punto}
\rightarrow
\text{retta}
\rightarrow
\text{segmento}
\rightarrow
\text{poligonale}
\rightarrow
\text{poligono}
}
$$

E possiamo classificare gli angoli attraverso le loro misure:

$$
0^\circ
<
\text{acuto}
<
90^\circ
<
\text{ottuso}
<
180^\circ
<
\text{concavo}
<
360^\circ
$$