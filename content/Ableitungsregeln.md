>[!info] Ableitungsregeln
>Seien $f$ und $g$ [[Differenzierbarkeit|differenzierbar]] in $c$. Dann ist auch:
>1. $f\pm g$ [[Differenzierbarkeit|differenzierbar]] in $c$ mit $(f\pm g)'(c)=f'(c)\pm g'(c)$.
>2. $\lambda\cdot f$ [[Differenzierbarkeit|differenzierbar]] in $c$ mit $(\lambda\cdot f)'(c)=\lambda\cdot f'(c)$.
>3. $f\cdot g$ [[Differenzierbarkeit|differenzierbar]] in $c$ mit $(f\cdot g)'(c)=f'(c)\cdot g(c)+f(c)\cdot g'(c)$.
>4. $\frac{f}{g}$ [[Differenzierbarkeit|differenzierbar]] in $c$ mit

Beweis:
(1.),(2.) folgen aus Grenzwertsätzen
(4.) folgt aus (3.)

### Beweis (3.)
$$
\begin{align}
 \frac{f(c+h)\cdot g(c+h)-f(c)\cdot g(c)}{h}&=\frac{[f(c+h)-f(c)]\cdot g(c)}{h} + \frac{f(c)\cdot[g(c+h)-g(c)]}{h} \\
&+\frac{[f(c+h)-f(c)]\cdot[g(c+h)-g(c)]}{h} \\
&=\frac{f(c+h)-f(c)}{h}\cdot g(c) + f(c) \cdot \frac{g(c+h)-g(c)}{h} \\
 &+ \frac{[f(c+h)-f(c)]\cdot[g(c+h)-g(c)]h}{h^{2}} \\
&\stackrel{x\to c}{\to}f'(c)\cdot g(c)+f(c)\cdot g'(c)
\end{align}
$$
