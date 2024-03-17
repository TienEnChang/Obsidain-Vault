
Thm. interchange of limit and differentiation
- $f_{n}:(a,\,b)\to \mathbb{R}$  diff.  $\forall\,n \in \mathbb{N}$
- $f_{n}\to {\phi}$, $f_{n}'\to \phi_{d}$  uniformly 
- $\implies$ 
	- $\phi$  diff. $\,\land$  $\phi'=\phi_{d}$  [[limit interchange - Pf.#^3d634a|{Pf}]]

Thm. interchange of limit and integral
- $f_{n}:[a,\,b]\to \mathbb{R}$  R-integrable  $\forall\,n \in \mathbb{N}$
- $(f_{n})_{n \in \mathbb{N}}$  converges uniformly  { i.e. under $||\cdot||_{\sup}$ }
- $\implies$ 
	- $\lim\limits_{n\to\infty} f_{n}$  R-integrable
	- ${\displaystyle\int}_{a}^{b}[\lim\limits_{n\to\infty} f_{n}](x)dx=\lim\limits_{n\to\infty}\left( {\displaystyle\int}_{a}^{b}f_{n}(x)dx \right)$  [[limit interchange - Pf.#^51c022|{Pf}]]


Cor. ??
- $f_{n}:(a,\,b)\to \mathbb{R}$  diff.  $\forall\,n \in \mathbb{N}$
- $\sum\limits_{n=1}^{\infty}f_{n}$, $\sum\limits_{n=1}^{\infty}f'_{n}$  converges uniformly 
- $\implies$ 
	- $\sum\limits_{n=1}^{\infty}f_{n}$  diff.  $\land$  $(\sum\limits_{n=1}^{\infty}f_{n})'=\sum\limits_{n=1}^{\infty}(f'_{n})$  [[limit interchange - Pf.#^4c301e|{Pf}]]

Cor.
- $f_{n}:[a,\,b]\to \mathbb{R}$  R-integrable  $\forall\,n \in \mathbb{N}$
- $\sum\limits_{n=1}^{\infty}f_{n}$  converges uniformly  { i.e. under $||\cdot||_{\sup}$ }
- $\implies$ 
	- $\sum\limits_{n=1}^{\infty}f_{n}$  R-integrable  $\land$  ${\displaystyle\int}_{a}^{b}\left[ \sum\limits_{n=1}^{\infty}f_{n} \right](x)dx=\sum\limits_{n=1}^{\infty}\left( {\displaystyle\int}_{a}^{b}f_{n}(x)dx \right)$

---

Rmk.
- For $f:I\subseteq \mathbb{R}\to \mathbb{R}$,
	- $\sup\limits_{x \in I}|f(x)-g(x)|\geq|\sup\limits_{x \in I}f(x)-\sup\limits_{x \in I}g(x)|,\,\,\,|\inf\limits_{x \in I}f(x)-\inf\limits_{x \in I}g(x)|$