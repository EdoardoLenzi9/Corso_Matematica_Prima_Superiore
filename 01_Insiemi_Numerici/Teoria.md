# Insiemi Numerici

> 💡 Idea: ogni nuovo concetto nasce dalla necessità di **estendere** il precedente

> 🎯 Obiettivo: comprendere come i matematici classificano i numeri attraverso gli **insiemi numerici**.

![](assets/001.svg)

# 1. Insieme

> 🤏 Definizione: **Insieme** $\triangleq$ collezione di **elementi** con **proprieta'** comuni

## 2. Insiemi numerici

I principali insiemi numerici sono:

| Simbolo | Nome |
|---|---|
| $$\mathbb N$$ | Naturali |
| $$\mathbb Z$$ | Interi |
| $$\mathbb Q$$ | Razionali |
| $$\mathbb R$$ | Reali |

$$
\mathbb{N}\subset\mathbb{Z}\subset\mathbb{Q}\subset\mathbb{R}
$$



## Idea fondamentale

Ogni insieme nasce perché quello precedente **non è sufficiente**.

- I naturali non permettono sempre la sottrazione.
- Gli interi non permettono sempre la divisione.
- I razionali non rappresentano tutte le lunghezze.
- I reali completano la retta numerica.

---

# 2. Numeri naturali

## Motivazione

Servono per contare oggetti.

## Definizione

$$
\mathbb N=\{0,1,2,3,\dots\}
$$

## Proprietà

Le operazioni chiuse sono:

- addizione
- moltiplicazione

Non sempre è possibile sottrarre:

$$
3-5\notin\mathbb N
$$

## Rappresentazione

<svg viewBox="0 0 520 70" xmlns="http://www.w3.org/2000/svg">
  <line x1="30" y1="35" x2="490" y2="35" stroke="#111827" stroke-width="2"/>
  <defs>
    <marker id="arrow" markerWidth="8" markerHeight="8" refX="7" refY="4" orient="auto">
      <path d="M0,0 L8,4 L0,8 Z" fill="#111827"/>
    </marker>
  </defs>
  <line x1="470" y1="35" x2="490" y2="35" stroke="#111827" stroke-width="2" marker-end="url(#arrow)"/>
  <g font-family="Arial" font-size="11" text-anchor="middle">
    <g><line x1="40" y1="28" x2="40" y2="42" stroke="#111827"/><text x="40" y="58">0</text></g>
    <g><line x1="110" y1="28" x2="110" y2="42" stroke="#111827"/><text x="110" y="58">1</text></g>
    <g><line x1="180" y1="28" x2="180" y2="42" stroke="#111827"/><text x="180" y="58">2</text></g>
    <g><line x1="250" y1="28" x2="250" y2="42" stroke="#111827"/><text x="250" y="58">3</text></g>
    <g><line x1="320" y1="28" x2="320" y2="42" stroke="#111827"/><text x="320" y="58">4</text></g>
    <g><line x1="390" y1="28" x2="390" y2="42" stroke="#111827"/><text x="390" y="58">5</text></g>
    <g><line x1="460" y1="28" x2="460" y2="42" stroke="#111827"/><text x="460" y="58">6</text></g>
  </g>
</svg>

## Esempi

$$
7+4=11
$$

$$
5\times3=15
$$

## Esercizi

1. Calcola $$18+27$$ *(capire l'addizione)*
2. Calcola $$9\times12$$ *(automatizzare la moltiplicazione)*
3. Spiega perché $$4-9$$ non appartiene ai naturali.

**Transizione:** nasce l'esigenza dei numeri negativi.

---

# 3. Numeri interi

## Motivazione

Come rappresentare debiti, temperature sotto zero e differenze negative?

## Definizione

$$
\mathbb Z=\{\dots,-3,-2,-1,0,1,2,3,\dots\}
$$

## Retta numerica

<svg viewBox="0 0 520 80" xmlns="http://www.w3.org/2000/svg">
  <line x1="30" y1="40" x2="490" y2="40" stroke="#111827" stroke-width="2"/>
  <defs>
    <marker id="arrow2" markerWidth="8" markerHeight="8" refX="7" refY="4" orient="auto">
      <path d="M0,0 L8,4 L0,8 Z" fill="#111827"/>
    </marker>
  </defs>
  <line x1="470" y1="40" x2="490" y2="40" stroke="#111827" stroke-width="2" marker-end="url(#arrow2)"/>
  <g font-family="Arial" font-size="10" text-anchor="middle">
    <g><line x1="40" y1="32" x2="40" y2="48" stroke="#111827"/><text x="40" y="64">-3</text></g>
    <g><line x1="110" y1="32" x2="110" y2="48" stroke="#111827"/><text x="110" y="64">-2</text></g>
    <g><line x1="180" y1="32" x2="180" y2="48" stroke="#111827"/><text x="180" y="64">-1</text></g>
    <g><line x1="250" y1="28" x2="250" y2="52" stroke="#047857" stroke-width="2"/><text x="250" y="64" fill="#047857">0</text></g>
    <g><line x1="320" y1="32" x2="320" y2="48" stroke="#111827"/><text x="320" y="64">1</text></g>
    <g><line x1="390" y1="32" x2="390" y2="48" stroke="#111827"/><text x="390" y="64">2</text></g>
    <g><line x1="460" y1="32" x2="460" y2="48" stroke="#111827"/><text x="460" y="64">3</text></g>
  </g>
</svg>

## Opposto

Due numeri sono opposti se la loro somma è zero.

$$
(+5)+(-5)=0
$$

## Esempi

$$
3-8=-5
$$

$$
-4+7=3
$$

## Esercizi

1. Ordina: $$-2,\;4,\;-7,\;1$$
2. Calcola $$-6+9$$
3. Trova l'opposto di $$13$$

**Transizione:** ora possiamo parlare della distanza da zero.

---

# 4. Valore assoluto

## Definizione

Il valore assoluto è la distanza di un numero dall'origine.

$$
|x|=
\begin{cases}
x & x\ge0\\
-x & x<0
\end{cases}
$$

## Visualizzazione

<svg viewBox="0 0 520 90" xmlns="http://www.w3.org/2000/svg">
  <line x1="30" y1="45" x2="490" y2="45" stroke="#111827" stroke-width="2"/>
  <g font-family="Arial" font-size="10" text-anchor="middle">
    <g><line x1="40" y1="38" x2="40" y2="52" stroke="#111827"/><text x="40" y="66">-3</text></g>
    <g><line x1="110" y1="38" x2="110" y2="52" stroke="#111827"/><text x="110" y="66">-2</text></g>
    <g><line x1="180" y1="38" x2="180" y2="52" stroke="#111827"/><text x="180" y="66">-1</text></g>
    <g><line x1="250" y1="34" x2="250" y2="56" stroke="#047857" stroke-width="2"/><text x="250" y="66" fill="#047857">0</text></g>
    <g><line x1="320" y1="38" x2="320" y2="52" stroke="#111827"/><text x="320" y="66">1</text></g>
    <g><line x1="390" y1="38" x2="390" y2="52" stroke="#111827"/><text x="390" y="66">2</text></g>
    <g><line x1="460" y1="38" x2="460" y2="52" stroke="#111827"/><text x="460" y="66">3</text></g>
  </g>
  <circle cx="110" cy="45" r="5" fill="#2563EB"/>
  <circle cx="390" cy="45" r="5" fill="#2563EB"/>
  <path d="M110 22 Q250 2 390 22" fill="none" stroke="#2563EB" stroke-width="1.5" stroke-dasharray="4 3"/>
  <text x="250" y="14" font-size="10" text-anchor="middle" font-family="Arial" fill="#1D4ED8">stessa distanza = 2</text>
</svg>

## Esempi

$$
|-8|=8
$$

$$
|5|=5
$$

## Proprietà

$$
|x|\ge0
$$

$$
|a-b|=\text{distanza tra }a\text{ e }b
$$

## Esercizi

1. Calcola $$|-15|$$
2. Calcola $$|7-11|$$
3. Risolvi $$|x|=4$$

**Intento:** comprendere la distanza e la simmetria.

---

# 5. Numeri razionali

## Motivazione

Come rappresentare metà pizza o tre quarti di litro?

## Definizione

Un numero razionale è un rapporto tra due interi.

$$
\frac{a}{b},\qquad b\neq0
$$

## Frazioni equivalenti

$$
\frac12=\frac24=\frac36
$$

## Proprietà

Due frazioni sono equivalenti se

$$
ad=bc
$$

## Esempi

$$
\frac34+\frac14=1
$$

$$
\frac25\times\frac53=\frac23
$$

## Esercizi

1. Semplifica $$\frac{18}{24}$$
2. Confronta $$\frac35$$ e $$\frac47$$
3. Verifica l'equivalenza tra $$\frac23$$ e $$\frac46$$

---

# 6. Numeri decimali

## Definizione

Ogni razionale possiede uno sviluppo decimale finito oppure periodico.

## Classificazione

| Tipo | Esempio |
|---|---|
| Finito | $$0.25$$ |
| Periodico semplice | $$0.\overline3$$ |
| Periodico misto | $$1.2\overline7$$ |

## Conversione

$$
\frac18=0.125
$$

$$
0.75=\frac34
$$

## Esercizi

1. Trasforma $$0.4$$ in frazione.
2. Scrivi in decimale $$\frac58$$.
3. Riconosci il tipo di $$2.13\overline5$$.

---

# 7. Numeri irrazionali

## Motivazione

Esistono lunghezze che nessuna frazione può rappresentare.

## Esempio fondamentale

Quadrato di lato 1.

<svg viewBox="0 0 220 180" xmlns="http://www.w3.org/2000/svg">
  <rect x="40" y="30" width="120" height="120" fill="#EEF2FF" stroke="#1D4ED8" stroke-width="2"/>
  <line x1="40" y1="150" x2="160" y2="30" stroke="#DC2626" stroke-width="2"/>
  <text x="100" y="20" font-size="12" text-anchor="middle" font-family="Arial">lato = 1</text>
  <text x="176" y="92" font-size="12" font-family="Arial" fill="#B91C1C">√2</text>
</svg>

Per Pitagora:

$$
d^2=1^2+1^2
$$

quindi

$$
d=\sqrt2
$$

Il suo sviluppo decimale è

$$
1.414213562\dots
$$

infinito e non periodico.

## Esercizi

1. Spiega perché $$\sqrt2$$ non è razionale.
2. Classifica $$\pi$$.
3. Classifica $$0.1010010001\dots$$

---

# 8. Numeri reali

## Definizione

L'insieme dei reali contiene tutti i razionali e tutti gli irrazionali.

$$
\mathbb R=\mathbb Q\cup I
$$

## Diagramma

<svg viewBox="0 0 340 200" xmlns="http://www.w3.org/2000/svg">
  <rect x="10" y="10" width="320" height="180" rx="12" fill="#F8FAFC" stroke="#334155"/>
  <rect x="30" y="30" width="280" height="140" rx="10" fill="#DBEAFE" stroke="#2563EB"/>
  <rect x="55" y="55" width="150" height="90" rx="8" fill="#D1FAE5" stroke="#059669"/>
  <text x="170" y="22" text-anchor="middle" font-family="Arial" font-size="13">ℝ</text>
  <text x="130" y="48" text-anchor="middle" font-family="Arial" font-size="12">ℚ</text>
  <text x="250" y="100" text-anchor="middle" font-family="Arial" font-size="12">Irrazionali</text>
  <text x="130" y="92" text-anchor="middle" font-family="Arial" font-size="11">½</text>
  <text x="130" y="110" text-anchor="middle" font-family="Arial" font-size="11">−3</text>
  <text x="130" y="128" text-anchor="middle" font-family="Arial" font-size="11">0.75</text>
  <text x="250" y="120" text-anchor="middle" font-family="Arial" font-size="11">√2</text>
  <text x="250" y="138" text-anchor="middle" font-family="Arial" font-size="11">π</text>
</svg>

## Idea chiave

La retta reale è continua: ogni punto corrisponde a un numero reale.

---

# 9. Le quattro operazioni

## Proprietà fondamentali

### Commutativa

$$
a+b=b+a
$$

$$
ab=ba
$$

### Associativa

$$
(a+b)+c=a+(b+c)
$$

### Distributiva

$$
a(b+c)=ab+ac
$$

## Priorità

1. Parentesi
2. Potenze
3. Moltiplicazioni e divisioni
4. Addizioni e sottrazioni

## Esercizio

Calcola

$$
3+4\times(5-2)^2
$$

**Intento:** applicare correttamente le priorità.

---

# 10. Potenze

## Definizione

$$
a^n=\underbrace{a\cdot a\cdot\dots\cdot a}_{n\ volte}
$$

## Elementi

- Base
- Esponente

## Proprietà

### Prodotto

$$
a^m\cdot a^n=a^{m+n}
$$

### Quoziente

$$
\frac{a^m}{a^n}=a^{m-n}
$$

### Potenza di potenza

$$
(a^m)^n=a^{mn}
$$

### Potenza del prodotto

$$
(ab)^n=a^nb^n
$$

## Schema

<svg viewBox="0 0 340 170" xmlns="http://www.w3.org/2000/svg">
  <rect x="110" y="10" width="120" height="36" rx="8" fill="#DBEAFE" stroke="#2563EB"/>
  <text x="170" y="28" text-anchor="middle" font-family="Arial" font-size="14">aᵐ</text>
  <line x1="170" y1="46" x2="90" y2="72" stroke="#64748B"/>
  <line x1="170" y1="46" x2="250" y2="72" stroke="#64748B"/>
  <rect x="20" y="72" width="140" height="40" rx="8" fill="#F3E8FF" stroke="#7C3AED"/>
  <text x="90" y="88" text-anchor="middle" font-family="Arial" font-size="11">× aⁿ</text>
  <text x="90" y="100" text-anchor="middle" font-family="Arial" font-size="11">aᵐ⁺ⁿ</text>
  <rect x="180" y="72" width="140" height="40" rx="8" fill="#FCE7F3" stroke="#DB2777"/>
  <text x="250" y="88" text-anchor="middle" font-family="Arial" font-size="11">( )ⁿ</text>
  <text x="250" y="100" text-anchor="middle" font-family="Arial" font-size="11">aᵐⁿ</text>
  <line x1="170" y1="112" x2="170" y2="132" stroke="#64748B"/>
  <rect x="100" y="132" width="140" height="28" rx="8" fill="#D1FAE5" stroke="#059669"/>
  <text x="170" y="146" text-anchor="middle" font-family="Arial" font-size="11">(ab)ⁿ = aⁿbⁿ</text>
</svg>

## Esercizi

1. $$2^5$$
2. $$3^2\cdot3^4$$
3. $$(2^3)^2$$

---

# 11. Multipli, divisori e numeri primi

## Divisibilità

Un numero $$a$$ è divisibile per $$b$$ se esiste un intero $$k$$ tale che

$$
a=bk
$$

## Numeri primi

Un numero primo possiede esattamente due divisori positivi.

Primi fino a 30:

$$
2,3,5,7,11,13,17,19,23,29
$$

## Criteri essenziali

| Numero | Criterio |
|---|---|
| 2 | ultima cifra pari |
| 3 | somma cifre multipla di 3 |
| 5 | termina con 0 o 5 |
| 9 | somma cifre multipla di 9 |

## Esercizi

1. È 147 divisibile per 3?
2. È 250 divisibile per 5?
3. 37 è primo?

---

# 12. Scomposizione in fattori primi

## Teorema fondamentale

Ogni intero maggiore di 1 si scompone in modo unico come prodotto di numeri primi.

## Albero dei fattori

<svg viewBox="0 0 240 170" xmlns="http://www.w3.org/2000/svg">
  <g font-family="Arial" text-anchor="middle" font-size="12">
    <circle cx="120" cy="20" r="16" fill="#DBEAFE" stroke="#2563EB"/>
    <text x="120" y="24">60</text>
    <line x1="120" y1="36" x2="70" y2="60" stroke="#64748B"/>
    <line x1="120" y1="36" x2="170" y2="60" stroke="#64748B"/>
    <circle cx="70" cy="76" r="14" fill="#D1FAE5" stroke="#059669"/>
    <text x="70" y="80">6</text>
    <circle cx="170" cy="76" r="14" fill="#FCE7F3" stroke="#DB2777"/>
    <text x="170" y="80">10</text>
    <line x1="70" y1="90" x2="45" y2="118" stroke="#64748B"/>
    <line x1="70" y1="90" x2="95" y2="118" stroke="#64748B"/>
    <line x1="170" y1="90" x2="145" y2="118" stroke="#64748B"/>
    <line x1="170" y1="90" x2="195" y2="118" stroke="#64748B"/>
    <circle cx="45" cy="134" r="12" fill="#FEF3C7" stroke="#D97706"/>
    <text x="45" y="138">2</text>
    <circle cx="95" cy="134" r="12" fill="#FEF3C7" stroke="#D97706"/>
    <text x="95" y="138">3</text>
    <circle cx="145" cy="134" r="12" fill="#FEF3C7" stroke="#D97706"/>
    <text x="145" y="138">2</text>
    <circle cx="195" cy="134" r="12" fill="#FEF3C7" stroke="#D97706"/>
    <text x="195" y="138">5</text>
  </g>
</svg>

Quindi

$$
60=2^2\cdot3\cdot5
$$

## Esercizi

1. Scomponi 36.
2. Scomponi 84.
3. Scrivi 180 in forma canonica.

---

# 13. Massimo Comune Divisore

## Definizione

È il più grande divisore comune tra due numeri.

## Metodo

Scomponiamo:

$$
24=2^3\cdot3
$$

$$
36=2^2\cdot3^2
$$

Prendiamo gli esponenti minimi.

$$
MCD=2^2\cdot3=12
$$

## Schema

<svg viewBox="0 0 340 140" xmlns="http://www.w3.org/2000/svg">
  <style>
    .b{fill:#fff;stroke:#334155}
    .t{font:12px Arial;text-anchor:middle}
  </style>
  <rect class="b" x="18" y="18" width="130" height="104" rx="8"/>
  <rect class="b" x="192" y="18" width="130" height="104" rx="8"/>
  <text class="t" x="83" y="36">24</text>
  <text class="t" x="83" y="54">2³ · 3</text>
  <text class="t" x="257" y="36">36</text>
  <text class="t" x="257" y="54">2² · 3²</text>
  <line x1="148" y1="70" x2="192" y2="70" stroke="#64748B" stroke-dasharray="4 4"/>
  <text class="t" x="170" y="82" font-size="10">min</text>
  <rect x="122" y="94" width="96" height="20" rx="6" fill="#D1FAE5" stroke="#059669"/>
  <text class="t" x="170" y="108" font-size="11">MCD = 12</text>
</svg>

## Esercizi

1. MCD(18,30)
2. MCD(42,56)
3. MCD(45,75)

**Intento:** individuare i fattori comuni.

---

# 14. Minimo Comune Multiplo

## Definizione

È il più piccolo multiplo comune.

Usando le stesse scomposizioni:

$$
24=2^3\cdot3
$$

$$
36=2^2\cdot3^2
$$

Prendiamo gli esponenti maggiori.

$$
mcm=2^3\cdot3^2=72
$$

## Visualizzazione

<svg viewBox="0 0 340 150" xmlns="http://www.w3.org/2000/svg">
  <style>
    .axis{stroke:#111827;stroke-width:1.5}
    .tick{stroke:#64748B}
    .lbl{font:9px Arial;fill:#374151;text-anchor:middle}
    .m24{fill:#2563EB}
    .m36{fill:#DC2626}
    .both{fill:#059669}
  </style>
  <line class="axis" x1="20" y1="50" x2="320" y2="50"/>
  <line class="axis" x1="20" y1="105" x2="320" y2="105"/>
  <text x="8" y="53" font-size="9" font-family="Arial">24</text>
  <text x="8" y="108" font-size="9" font-family="Arial">36</text>
  <g>
    <line class="tick" x1="20" y1="44" x2="20" y2="56"/>
    <line class="tick" x1="120" y1="44" x2="120" y2="56"/>
    <line class="tick" x1="220" y1="44" x2="220" y2="56"/>
    <line class="tick" x1="320" y1="44" x2="320" y2="56"/>
    <text class="lbl" x="20" y="68">0</text>
    <text class="lbl" x="120" y="68">24</text>
    <text class="lbl" x="220" y="68">48</text>
    <text class="lbl" x="320" y="68">72</text>
  </g>
  <g>
    <line class="tick" x1="20" y1="99" x2="20" y2="111"/>
    <line class="tick" x1="170" y1="99" x2="170" y2="111"/>
    <line class="tick" x1="320" y1="99" x2="320" y2="111"/>
    <text class="lbl" x="20" y="123">0</text>
    <text class="lbl" x="170" y="123">36</text>
    <text class="lbl" x="320" y="123">72</text>
  </g>
  <circle class="m24" cx="120" cy="50" r="4"/>
  <circle class="m24" cx="220" cy="50" r="4"/>
  <circle class="both" cx="320" cy="50" r="5"/>
  <circle class="m36" cx="170" cy="105" r="4"/>
  <circle class="both" cx="320" cy="105" r="5"/>
  <line x1="320" y1="55" x2="320" y2="100" stroke="#059669" stroke-dasharray="3 3"/>
  <text x="320" y="16" font-size="10" text-anchor="middle" font-family="Arial" fill="#047857">primo comune</text>
</svg>

## Esercizi

1. mcm(8,12)
2. mcm(15,20)
3. mcm(18,30)

---

# 15. Rapporti, proporzioni e percentuali

## Rapporto

È il quoziente tra due grandezze.

$$
a:b=\frac ab
$$

## Proporzione

Una proporzione è un'uguaglianza tra rapporti.

$$
a:b=c:d
$$

Proprietà fondamentale:

$$
ad=bc
$$

## Esempio

$$
2:5=8:20
$$

infatti

$$
2\cdot20=5\cdot8
$$

## Percentuale

Una percentuale rappresenta una frazione su 100.

$$
p\%=\frac p{100}
$$

### Formula generale

$$
\text{Parte}=\frac p{100}\times\text{Totale}
$$

### Esempio

Il 20% di 80:

$$
\frac{20}{100}\times80=16
$$

## Esercizi

1. Trova il 15% di 200.
2. Risolvi la proporzione $$3:4=x:20$$.
3. Calcola lo sconto del 25% su 60 €.

**Intento:** modellizzare situazioni reali.

---

# Conclusione del modulo

<svg viewBox="0 0 700 120" xmlns="http://www.w3.org/2000/svg">
  <style>
    .b{fill:#F8FAFC;stroke:#334155;stroke-width:1.2}
    .t{font:12px Arial;text-anchor:middle}
    .a{stroke:#64748B;stroke-width:1.2;marker-end:url(#m)}
  </style>
  <defs>
    <marker id="m" markerWidth="8" markerHeight="8" refX="7" refY="4" orient="auto">
      <path d="M0,0 L8,4 L0,8 Z" fill="#64748B"/>
    </marker>
  </defs>
  <rect class="b" x="20" y="35" width="90" height="40" rx="8"/>
  <text class="t" x="65" y="55">Naturali</text>
  <rect class="b" x="130" y="35" width="70" height="40" rx="8"/>
  <text class="t" x="165" y="55">Interi</text>
  <rect class="b" x="220" y="35" width="90" height="40" rx="8"/>
  <text class="t" x="265" y="55">Razionali</text>
  <rect class="b" x="330" y="35" width="100" height="40" rx="8"/>
  <text class="t" x="380" y="55">Irrazionali</text>
  <rect class="b" x="450" y="35" width="70" height="40" rx="8"/>
  <text class="t" x="485" y="55">Reali</text>
  <rect class="b" x="540" y="35" width="140" height="40" rx="8"/>
  <text class="t" x="610" y="49">Calcolo</text>
  <text class="t" x="610" y="63" font-size="10">MCD • mcm • %</text>
  <line class="a" x1="110" y1="55" x2="130" y2="55"/>
  <line class="a" x1="200" y1="55" x2="220" y2="55"/>
  <line class="a" x1="310" y1="55" x2="330" y2="55"/>
  <line class="a" x1="430" y1="55" x2="450" y2="55"/>
  <line class="a" x1="520" y1="55" x2="540" y2="55"/>
</svg>

## Competenze acquisite

- Comprendere la struttura degli insiemi numerici.
- Rappresentare i numeri sulla retta reale.
- Eseguire operazioni con interi e razionali.
- Utilizzare correttamente potenze e loro proprietà.
- Scomporre numeri in fattori primi.
- Calcolare MCD e mcm con metodo rigoroso.
- Risolvere problemi con rapporti, proporzioni e percentuali.

> Questo costituisce un primo modulo completo di aritmetica per il primo anno del Liceo Scientifico, progettato per introdurre tutti i concetti fondamentali senza salti logici.