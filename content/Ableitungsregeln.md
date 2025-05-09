>[!info] Ableitungsregeln
>Seien $f$ und $g$ [[Differenzierbarkeit|differenzierbar]] in $c$. Dann ist auch:
>1. $f\pm g$ [[Differenzierbarkeit|differenzierbar]] in $c$ mit $(f\pm g)'(c)=f'(c)\pm g'(c)$.
>2. $\lambda\cdot f$ [[Differenzierbarkeit|differenzierbar]] in $c$ mit $(\lambda\cdot f)'(c)=\lambda\cdot f'(c)$.
>3. $f\cdot g$ [[Differenzierbarkeit|differenzierbar]] in $c$ mit $(f\cdot g)'(c)=f'(c)\cdot g(c)+f(c)\cdot g'(c)$.
>4. $\frac{f}{g}$ [[Differenzierbarkeit|differenzierbar]] in $c$ mit $\left(\frac{f}{g} \right)'(c)=\frac{[f'(c)\cdot g(c)-f(c)\cdot g'(c)]}{g(c)^2}$.


Beweis:
(1.),(2.) folgen aus Grenzwertsätzen
(4.) folgt aus (3.)

### Beweis (3.)
$$
\begin{align}
 \frac{f(c+h)\cdot g(c+h)-f(c)\cdot g(c)}{h}&=\frac{[f(c+h)-f(c)]\cdot g(c)}{h} + \frac{f(c)\cdot[g(c+h)-g(c)]}{h} \\
&+\frac{[f(c+h)-f(c)]\cdot[g(c+h)-g(c)]}{h} \\
&=\frac{f(c+h)-f(c)}{h}\cdot g(c) + f(c) \cdot \frac{g(c+h)-g(c)}{h} \\
 &+ \frac{[f(c+h)-f(c)]\cdot[g(c+h)-g(c)]\cdot h}{h^{2}} \\
&\stackrel{x\to c}{\to}f'(c)\cdot g(c)+f(c)\cdot g'(c)
\end{align}
$$
> [!info] Kettenregel
> Sei $f$ [[Differenzierbarkeit|differenzierbar]] in $g(c)$ und $g$ [[Differenzierbarkeit|differenzierbar]] in $c$. Dann ist $f\circ g$ [[Differenzierbarkeit|differenzierbar]] in $c$ mit $(f\circ g)'(c)=f'(g(c))\cdot g'(c)$.
### Beweis Kettenregel
Wir definieren eine Hilfsfunktion:
$$
d(y)=\begin{cases}
\frac{f(y)-f(g(c))}{y-g(c)} & y \neq g(c) \\
f'(g(c)) & y = g(c)
\end{cases}
$$
Dann ist $d$ [[Stetigkeit|stetig]] an der Stelle $g(c)$, denn:
$$
\lim_{ y \to g(c) }d(y)=\lim_{ y \to g(c) } \frac{f(y)-f(g(c))}{y-g(c)}\stackrel{f \text{ differenzierbar an }g(c)}{=}f'(g(c))
$$
Außerdem gilt $\frac{f(g(x))-f(g(c))}{x-c}=d(g(x))\cdot \frac{g(x)-g(c)}{x-c}$, weil:
Für $g(x)=g(c)$ gilt:
$$
\begin{align}
\frac{f(g(x))-f(g(c))}{x-c}&=d(g(x))\cdot \frac{g(x)-g(c)}{x-c} \\
\frac{0}{x-c}&=d(g(x))\cdot\frac{0}{x-c} \\
0 &= 0
\end{align}
$$
Für $g(x)\neq g(c)$ gilt:
$$
\begin{align}
 \frac{f(g(x))-f(g(c))}{x-c}&=d(g(x))\cdot \frac{g(x)-g(c)}{x-c} \\
\frac{f(g(x))-f(g(c))}{x-c}&=\frac{f(g(x))-f(g(c))}{g(x)-g(c)}\cdot \frac{g(x)-g(c)}{x-c} \\
\frac{f(g(x))-f(g(c))}{x-c}&=\frac{f(g(x))-f(g(c))}{x-c} \quad w.A.
\end{align}
$$
Somit gilt:
$$
\begin{align}
 (f\circ g)'(c) & =\lim_{ x \to c } \frac{f(g(x))-f(g(c))}{x-c} \\
&=\lim_{ x \to c } \left[ d(g(x))\cdot \frac{g(x)-g(c)}{x-c}\right] \\ 
&=\lim_{ x \to c } d(g(x)) \cdot \lim_{ x \to c } \frac{g(x)-g(c)}{x-c} \\
&= f'(g(x))\cdot g'(x)
\end{align}
$$
