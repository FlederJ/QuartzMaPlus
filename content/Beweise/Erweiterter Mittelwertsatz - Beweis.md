![[Erweiterter Mittelwertsatz]]

## Beweis:

### Fallunterscheidung $g(a)=g(b)$
Nach dem [[Lemma von Rolle]] existiert ein $\xi \in ]a,b[$, sodass gilt: $g'(\xi)=0$. 
Dann gilt 
$$
\begin{align*}
f'(\xi)\cdot(g(b)-g(a))&=g'(\xi)\cdot(f(b)-f(a) \\
f'(\xi)\cdot 0 &= 0 \cdot (f(b)-f(a)) \\
0 = 0 \quad  \text{w.A.}
\end{align*}
$$

### Fallunterscheidung: $g(a)\neq g(b)$

Hilfsfunktion: $h(x)=f(x)-\left( \frac{f(b)-f(a)}{g(b)-g(a)} \right)\cdot(g(x)-g(a))$

$h$ ist [[Stetigkeit|stetig]] auf $[a,b]$ und [[Differenzierbarkeit|differenzierbar]] in $]a,b[$, weil es für $f$ und $g$ auch zutrifft.

$$
\begin{align*}
h(a)&=f(a)-\left( \frac{f(b)-f(a)}{g(b)-g(a)} \right)\cdot(g(a)-g(a))   \\
h(a)&=f(a)-\left( \frac{f(b)-f(a)}{g(b)-g(a)} \right)\cdot 0 \\
h(a)&=f(a)
\end{align*}
$$


$$
\begin{align*}
h(b)&=f(b)-\left( \frac{f(b)-f(a)}{g(b)-g(a)} \right)\cdot(g(b)-g(a)) \\
h(b)&=f(b)-(f(b)-f(a)) \\
h(b)&=f(a)
\end{align*}
$$
Nach dem [[Lemma von Rolle]] existiert also ein $\xi \in ]a,b[$ mit $h'(\xi)=0$.
Da $$
h'(x)=f'(x)-\left( \frac{f(b)-f(a)}{g(b)-g(a)} \right) \cdot g'(x)
$$gilt, gilt für $x=\xi$:
$$
\begin{align*}
h'(\xi)&=f'(\xi)-\left( \frac{f(b)-f(a)}{g(b)-g(a)} \right) \cdot g'(\xi) \\
0 &= f'(\xi)-\left( \frac{f(b)-f(a)}{g(b)-g(a)} \right) \cdot g'(\xi) \\
f'(\xi)&=\left( \frac{f(b)-f(a)}{g(b)-g(a)} \right) \cdot g'(\xi) \\
\frac{f'(\xi)}{g'(\xi)}&=\frac{f(b)-f(a)}{g(b)-g(a)}
\end{align*}
$$
Demnach erfüllt das gefundene $\xi$ die zu zeigende Aussage. $\ \square$
 
