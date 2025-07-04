>[!Note] Satz
> Sei $f: I \to \mathbb{R}$ eine $(n+1)$-mal [[Stetigkeit|stetig]] differenzierbare Funktion und $a \in I$. Dann gibt es für jedes $x \in I$ ein $\xi \in [a,x]$, sodass
> $$
> \begin{align*}
f(x) = \sum_{k=0}^n \frac{f^{(k)}(a)}{k!} \cdot (x-a)^k + \frac{f^{(n+1)}(\xi)}{(n+1)!} \cdot (x-a)^{n+1}
\end{align*}.
$$

### Woher kommt das Lagrange-Restglied?    
$$
f(x)\stackrel{?}{=} f(a) + f'(a) \cdot (x-a) + \dots + \frac{1}{n!}f^{(n)}(a)\cdot(x-a)^n + R_{n+1}(x)
$$
$$p(x) \coloneqq f(a) + f'(a) \cdot (x-a) + \dots + \frac{1}{n!}f^{(n)}(a)\cdot(x-a)^n + k \cdot (x-a)^{n+1}$$, wobei $k\in\mathbb{R}$ so gewählt wird, dass $f(b)=p(b)\quad\quad\quad (f:[a,b]\to\mathbb{R})$ 
Also gelten:
$f(b)=p(b)$
$f(a)=p(a)$
$f'(a)=p'(a)$
$f''(a)=p''(a)$
$\vdots$
$f^{(n)}(a)=p^{(n)}(a)$
bzw. für $h(x)\coloneqq f(x)-p(x)$
$h(b)=0$
$h(a)=0$
$h'(a)=0$
$\vdots$
$h^{(n)}(a)=0$

$h(b)=0 \land h(a)=0 \implies \exists \xi_{1}\in[a,b]:h'(\xi_{1})=0$
$h'(a)=0 \land h'(\xi_{1})=0 \implies \exists \xi_{2}\in[a,\xi_{1}]:h''(\xi_{2})=0$
$\dots$ nach (ca.) $n$-mal [[Lemma von Rolle]]
$\exists \xi \in [a, \xi_{n-1}]: h^{(n+1)}(\xi)=0 \iff f^{(n+1)}(\xi)=p^{(n+1)}(\xi)$
Da $p^{(n+1)}(x)=k \cdot (n+1)!$, gilt
$k = \frac{f^{(n+1)}(\xi)}{(n+1)!}$
Also: $R_{n+1}(x)=k \cdot (x-a)^{n+1} = \frac{f^{(n+1)}(\xi)}{(n+1)!} \cdot (x-a)^{n+1}$
