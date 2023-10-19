
Def.
- injective, 1-1:  $f(a)=f(b)\implies a=b$  $\forall\,a,\,b\in{\rm Dom}(f)$
- surjective, onto:  $\forall\,y\in{\rm Cod}(f)$ $\exists\,x\in{\rm Dom}(f)$  s.t. $f(x)=y$
- bijective, 1-1 $\land$ onto

Def.
- image:    $f(\{x\})\coloneqq\{f(x)\}$
- preimage: $f^{-1}(\{y\})\coloneqq\{\,x\in{\rm Dom}(f)\;|\;f(x)=y\,\}$

Thm. $\exists\,f^{-1}$ as a function (not preimage) $\iff$ $f$ is 1-1

Def. 
- $|A| = |B|$:  $\exists$ bijective $f:A\to B$
- $|\varnothing|\coloneqq0$

Def.
- $X$ is finite:       $\exists$ bijective $f:\{1,2,...N\in\mathbb{N}\} \to X$
                      $\implies$ $|X|=N$
- $X$ is infinite:     not finite
- $X$ is denumerable:  $\exists$ bijective $f:\mathbb{N} \to X$
					  $\iff$ $|X|=|\mathbb{N}|$

Def.
![[Screenshot 2023-09-22 at 6.05.49 PM.png|280]]|![[Screenshot 2023-09-22 at 6.05.37 PM.png|290]]

---

Prop.  $|\mathbb{N}^2|=|\mathbb{N}|$  [[Cardinality - Pf.#^b41af7|{Pf}]]

Thm.  Well-ordering Principle
- Let $X\subseteq\mathbb{N}$ $\land$ $X\neq\varnothing$ $\implies$ $\exists$ smallest $x\in X$

Thm.
- $\exists$ 1-1 $f:X\to S$  where  $S$ is countable
- $\implies$
	- $X$ is countable  [[Cardinality - Pf.#^296471|{Pf}]]
Cor. 
- $X\subseteq S$ $\land$ $S$ is countable $\implies$ $X$ is countable  [[Cardinality - Pf.#^c8f556|{Pf}]]
- $X\subseteq S$ $\land$ $X$ is infinite $\land$ $S$ is denumerable
	- $\implies$ $X$ is denumerable  [[Cardinality - Pf.#^ae3bbd|{Pf}]]

Thm.
- $X_i$ is countable $\forall\,i\in\mathbb{N}$  $\implies$ $\bigcup\limits_{i\in\mathbb{N}}X_i$ is countable [[Cardinality - Pf.#^65395d|{Pf}]]
Cor.
- $X_i$ is countable $\forall\,i\in I$  $\land$  $I$ is countable $\implies$ $\bigcup\limits_{i\in I}X_i$ is countable [[Cardinality - Pf.#^f28697|{Pf}]]

Thm.
- $A$, $B$ are countable $\implies$ $A\times B$ is countable  [[Cardinality - Pf.#^895a9c|{Pf}]]
- $A$ is countable $\implies$ $A^n$ is countable $\forall\,n\in\mathbb{N}$  [[Cardinality - Pf.#^3ba3c1|{Pf}]]

Prop. 
- $\mathbb{Z}$, $\mathbb{Q}$ are denumerable (i.e. $|\mathbb{N}|=|\mathbb{Z}|=|\mathbb{Q}|$)  [[Cardinality - Pf.#^f300b4|{Pf}]] [[Cardinality - Pf.#^a8d7c6|{Pf2}]]

---

Thm. Cantor's Theorem
- $(0,\,1)$ is uncountable  [[Cardinality - Pf.#^aa29ae|{Pf}]]
Cor.
- $\mathbb{R}$ is uncountable  [[Cardinality - Pf.#^59ef2c|{Pf}]]

Thm.
- $2^{\mathbb{N}}\coloneqq\mathcal{F}(\mathbb{N},\,\{0,\,1\})$ is uncountable  [[Cardinality - Pf.#^1e88b1|{Pf}]]

---

Def.
- $|A|\leq|B|$ $\iff$ $\exists$ 1-1 $f:A\to B$

Thm.  The Schroeder-Bernstein Theorem
- $|A|\leq|B|$ $\land$ $|A|\geq|B|$ $\implies$ $|A|=|B|$  [[Cardinality - Pf.#^74fb5f|{Pf}]]

Cor.
- $|(0,\,1)\times(0,\,1)|=|(0,\,1)|$  [[Cardinality - Pf.#^35cf24|{Pf}]]
- $|\mathbb{R}^n|=|\mathbb{R}|$  $\forall\,n\in\mathbb{N}$  [[Cardinality - Pf.#^1105d6|{Pf}]]
- $|[\,0,\,1)|=|\mathcal{P}(\mathbb{N})|$  [[Cardinality - Pf.#^ed6639|{Pf}]]
- $|\mathbb{R}|=|\mathcal{P}(\mathbb{N})|$

Hypo. the Continuum hypothesis
- $\not\exists\,S$  s.t.  $|\mathbb{N}|<|S|<|\mathbb{R}|$

---

{not taught}

Thm.
- $\exists$ onto $f:A\to B$  $\implies$  $\exists$ 1-1 $g:B\to A$
Pf.
- 