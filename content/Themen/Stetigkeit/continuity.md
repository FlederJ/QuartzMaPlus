---
title: Stetigkeit
---
## Definition


Eine Funktion $f:A\to\mathbb{R}$ heißt stetig an der Stelle $c\in A$, wenn eine der folgenden äquivalenten Bedingungen gilt:
1. $\forall\epsilon>0:\exists\delta>0:\forall x \in A:|x-c|<\delta: |f(x)-f(c)| < \epsilon$ (metrische Stetigkeit)
2. Der Grenzwert $\lim_{x \to c} f(x) = f(c)$ existiert
3. Für alle Folgen $(x_n)\subseteq A$ mit $x_n \to c$ gilt:
   $\lim_{n \to \infty} f(x_n) = f(c)$ (Folgenstetigkeit)

---

## Propositionen

> [!info]  Proposition
> Eine Funktion $f: A \to \mathbb{R}$ ist stetig, wenn $f$ an jeder Stelle $c \in A$ stetig ist.


> [!info] Proposition
> $f:A\to\mathbb{R}$ ist genau dann stetig an der Stelle $c\in A$, wenn gilt: $\lim_{x\nearrow c }f(x)=\lim_{x\searrow c}f(x)=f(c)$.
  

>[!info] Proposition
> Seien $f, g: A \to \mathbb{R}$ stetig in $c \in A$. Dann sind auch folgende Funktionen stetig in $c$:
  >1. $k\cdot f(x)$ für $k\in\mathbb{R}$
  >2. $f(x)+g(x)$
  >3. $f(x)\cdot g(x)$
  >4. $\frac{f(x)}{g(x)}$, vorausgesetzt $g(c)\neq0$

>[!info] Proposition
>Seien $A,B\subseteq \mathbb{R}$ und $g:A\to B$ und $f:B\to \mathbb{R}$. Wenn $g$ stetug in $c\in A$ ist und $f$ stetig in $g(c)\in B$ ist, dann ist $f\circ g$ stetig in $c$.