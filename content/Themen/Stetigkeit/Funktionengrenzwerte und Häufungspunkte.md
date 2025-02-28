## Definitionen
### Häufungspunkt
**Definition**: Ein Punkt c heißt ==Häufungspunkt== einer Menge A, wenn es eine Folge $$ (x_n) \subseteq A\setminus{c} $$ gibt mit $$ \lim_{x \to c} x_n = c $$
### Funktionengrenzwert
**Definition**: Sei $$f:A\to \mathbb{R}$$ und $$c \in A$$ ein Häufungspunkt von A. Wir definieren den ==Funktionengrenzwert==
$$\lim_{x\to c}f(x) = L$$ durch die beiden folgenden äquivalenten Definitionen.
- Für jede Folge $$(x_n) \subseteq A \setminus{c}$$ mit $$\lim_{x\to \infty}x_n = c$$ gilt, dass  $$\lim_{x\to \infty}f(x_n) = L$$
- $$\forall \epsilon > 0 : \exists \delta > 0: \forall x\in \mathbb{R}: 0 < |x - c| < \delta \implies |f(x)-L|<\epsilon$$

