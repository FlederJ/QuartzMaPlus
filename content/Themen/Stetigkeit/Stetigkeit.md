## Definition

Eine Funktion $$ f: A \to \mathbb{R} $$ heißt stetig an der Stelle $$ c \in A $$, wenn eine der folgenden äquivalenten Bedingungen gilt:

1. Für alle $$ \epsilon > 0 $$ existiert ein $$ \delta > 0 $$, sodass für alle $$ x \in A $$ mit $$ |x - c| < \delta $$ gilt: 
   $$ |f(x) - f(c)| < \epsilon $$ 
(metrische Stetigkeit)
1. Der Grenzwert $$ \lim_{x \to c} f(x) = f(c) $$ existiert.

2. Für alle Folgen $$ (x_n) \subseteq A $$ mit $$ x_n \to c $$ gilt:
   $$ \lim_{n \to \infty} f(x_n) = f(c) $$ (Folgenstetigkeit)
## Propositionen

- **Proposition:** Eine Funktion $$ f: A \to \mathbb{R} $$ ist stetig, wenn $$ f $$ an jeder Stelle $$ c \in A $$ stetig ist.

- **Proposition:** $$ f: A \to \mathbb{R} $$ ist genau dann stetig an der Stelle $$c \in A$$, wenn $$\lim_{x\nearrow c}f(x)=\lim_{x\searrow c}f(x)=f(c)$$
- **Proposition:** Seien $$ f, g: A \to \mathbb{R} $$ stetig in $$ c \in A $$. Dann sind auch folgende Funktionen stetig in $$ c $$:
  1. $$ k \cdot f(x) $$ für $$ k \in \mathbb{R} $$
  2. $$ f(x) + g(x) $$
  3. $$ f(x) \cdot g(x) $$
  4. $$ \frac{f(x)}{g(x)} $$, vorausgesetzt $$ g(c) \neq 0 $$

Diese Ergebnisse folgen aus den Grenzwertsätzen und der Folgenstetigkeit.

### Verbundene Sätze
- [[Urbilder offener Mengen unter stetigen Funktionen]]
- [[...]]