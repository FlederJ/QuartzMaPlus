>[!info] [[Differenzierbarkeit|differenzierbar]]  $\implies$ stetig
>Wenn $f:D\to\mathbb{R}$ an einer Stelle $c\in D$ [[Differenzierbarkeit|differenzierbar]] ist, dann ist $f$ auch [[Stetigkeit|stetig]] in $c$.

### Beweis
Weil $f$ [[Differenzierbarkeit|differenzierbar]]  ist, gibt es $L, r(x)$ mit 
$$
f(x)=f(c)+L\cdot(x-c)+r(x)
$$
und $$
\frac{r(x)}{x-c}\stackrel{x\to c}{\to}{0}
$$
Daraus folgt $r(x)\stackrel{x\to c}{\to}{0}$.

Dann ist aber $$
\begin{align}
\lim_{ x \to c } f(x)&\stackrel{GWS}{=}\lim_{ x \to c } f(c)+\lim_{ x \to c } L\cdot(x-c)+\lim_{ x \to c }r(x) \\ 
&=f(c)+0+0=f(c)
\end{align}
$$Also existiert der Funktionsgrenzwert an der Stelle $c$. Demnach ist $f$ an der Stelle $c$ stetig.