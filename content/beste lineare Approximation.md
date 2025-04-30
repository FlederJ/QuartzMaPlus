>[!info] beste lineare Approximation
>Eine Funktion $f:D\to \mathbb{R}$ ist genau dann [[Differenzierbarkeit|differenzierbar]]  in $c\in D$, wenn es eine Konstante $L$ gibt und eine Restfunktion $r:D\to \mathbb{R}$ mit $$
f(x)=f(c)+L(x-c)+r(x) \text{ und } \lim_{ x \to c }\frac{r(x)}{|x-c|}=0
$$ In diesem Fall ist $L=f'(c)$.

### Beweis
$$
\begin{align}
\text{Hinrichtung:}  \\ 
&\exists \lim_{ x \to c } \frac{f(x)-f(c)}{x-c} \\
 &L:=\lim_{ x \to c }\frac{f(x)-f(c)}{x-c} \\
 &r:D\to\mathbb{R}, r:=f(x)-f(c)-L\cdot(x-c) \\
 \mathrm{Z\kern-.3em\raise-0.5ex\hbox{Z}}: &f(x)=f(c)+L\cdot(x-c)+r(x) \\
 &f(x)=f(c)+L\cdot(x-c)+f(x)-f(c)-L\cdot(x-c) \quad |-f(x)\\
 &  0=f(c)+L\cdot(x-c)+f(x)-f(x)-f(c)-L\cdot(x-c)\\
 \\ 
& 0 = 0 \quad \text{w.A.} 
\end{align}
$$
$$
\begin{align}
\text{Rückrichtung: }\mathrm{Z\kern-.3em\raise-0.5ex\hbox{Z}}:  &\lim_{ x \to c } \frac{f(x)-f(c)}{x-c} \text{ existiert}\\
 \\
&\frac{f(x)+f(c)}{x-c} \\
&=\frac{f(c)+L\cdot(x-c)+r(x)-f(c)}{x-c} \\
&=\frac{L\cdot (x-c)}{x-c}+\frac{r(x)}{x-c}\stackrel{x\to c}{\longrightarrow}L+0=L=\lim_{ x \to c } \frac{f(x)-f(c)}{x-c} 
\end{align}
$$
