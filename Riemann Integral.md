
Let
- $f:[a,\,b]\to \mathbb{R}$  { closed interval }
- $S_{[a,\,b]}\coloneqq\big\{\{a=t_{0}<\cdots <t_{n}=b\}\;|\; n \in \mathbb{N}\big\}$,  $P \in S_{[a,\,b]}$

Def.
- upper sum:  $U(f,\,P)\coloneqq \sum\limits_{i=0}^{n-1}[\sup\limits_{x \in[t_{i},\,t_{i+1}]}f(x)](t_{i+1}-t_{i})$ 
- lower sum:  $L(f,\,P)\coloneqq \sum\limits_{i=0}^{n-1}[\inf\limits_{x \in[t_{i},\,t_{i+1}]}f(x)](t_{i+1}-t_{i})$
	
- upper integral:  $\overline{I}(f)\coloneqq \inf\limits_{P \in S_{[a,\,b]}}U(f,\,P)$
- lower integral:  $\underline{I}(f)\coloneqq \sup\limits_{P \in S_{[a,\,b]}}L(f,\,P)$

Def.
- Riemann integrable:  $\overline{I}(f)=\underline{I}(f)$  i.e. ${\displaystyle\int}_{a}^{b}f(x)dx$  exists


Thm. Riemann integrability criterion
- $f$ R-integrable
	- $\iff$
- $f$ bounded  $\land$  $\forall\,\varepsilon>0$  $\exists\,P \in S_{[a,\,b]}$  s.t.  $U(f,\,P)-L(f,\,P) < \varepsilon$  [[Riemann Integral - Pf.#^3fa6dc|{Pf}]]

Prop.
                         [[Riemann Integral - Pf.#^9f65b5|{Pf}]]              [[Riemann Integral - Pf.#^aad623|{Pf}]]
- $f$ uniformly continuous $\implies$ R-integrable $\implies$ bounded 

Rmk.
- $U(f,\,P)\geq \overline{I}(f)\geq\underline{I}(f)\geq L(f,\,P)$  $\forall\, P \in S_{[a,\,b]}$
	
- For refinement $P'\supseteq P$,
	- $U(f,\,P')\leq U(f,\, P)$  $\land$  $L(f,\,P')\geq L(f,\,P)$

===

Rmk. { not taught }
- $f:[a,\,b]\to \mathbb{R}$  is zero except at finitely many points
	- $\implies$ $f$ is Riemann-integratable with integral 0   [{Pf}](https://math.stackexchange.com/questions/2871367/riemann-integration-of-a-function-with-finite-number-of-non-zero-points)

Rmk.j
- For $f:[a,\,b]\to \mathbb{R}$,
	- ${\displaystyle\int}_{a}^{b}f(x)^{2}dx=0$ $\implies$ $f^{2}(x)\equiv0$ $\implies$ $f(x) \equiv0$
