
Def. { finite }
- characteristic polynomial:  { monic = leading coeff. is 1 }
	- $\text{char}_{A}(t)\coloneqq\text{det}(t I_{n}-A)\in P_{n}(F)$
	- $\text{char}_{T}(t)\coloneqq\text{det}(t I_{n}-[T]_{\beta})\in P_{n}(F)$  for any  (ordered) $\beta\,$ of $V$  

Def. { finite }
- multiplicity of $\lambda$:  $m_{\lambda}\coloneqq\max\{m\;|\;(t-\lambda)^{m}$ devides $\text{char}_{A}(t)\}$

---

Prop.
- $v$ is eigenvector of $T$  cor. $\lambda$
- $\iff$ $v \in\text{Null}(\lambda \,\text{id}_{V}-T)-\{\vec{0}\}$   { $E_{\lambda}\coloneqq\text{Null}(\lambda \,\text{id}_{V}-T)$, eigenspace }

Prop. { finite ver. }
- $v$ is eigenvector of $A$  cor. $\lambda$
- $\iff$ $v \in \text{Null}(\lambda I_{n}-A)-\{\vec{ 0}\}$       
	     { find its basis!! }

Thm. { finite }
- $\lambda$ is eigenvalue of $A$
- $\iff$ $\text{Null}(\lambda I_{n}-A)\supsetneq\{\vec{0}\}\!$        { i.e. $\text{dim}(E_{\lambda})\geq 1$ }
- $\iff$ $\lambda \in\text{Sol}(\,\text{det}(tI_{n}-A)=0\,)\,\,$  { i.e. $\det(\lambda I_{n}-A)=0$ }
	     { find its solutions!! }

---

Cor. { finite }
- $A$ has $n$ <u>distinct</u> eigenvalues $\implies$ $A$ diagonalizable

Thm. { finite }
- $\text{char}_{A}(t)$ "not" splits $\implies$ $A$ "not" diagonalizable
  { splits: $\text{char}_{A}(t)=\prod\limits_{i=1}^{n}(t-\lambda_{i})$  for some  $\lambda_{1},\,\cdots,\,\lambda_{n}\in F$ }


Prop. { finite }
- $\forall\,$ eigenvalue $\lambda$ of $A$:  $1\leq \text{dim}(E_{\lambda})\leq m_{\lambda}$

Thm.
- $A$ diagonalizable $\iff$
	- $\text{char}_{A}(t)$ splits  $\land$  $\forall\,\lambda$ of $A$:  $m_{\lambda}=\text{dim}(E_{\lambda})\,$ or $\,n-\text{rank}(\lambda I_{n}-A)$
		- OR
	- $F^{n}=\bigoplus\limits_{\lambda} E_{\lambda}$
		- OR
	- $\forall\,\lambda$ of $A$:  $\beta_{\lambda}$ basis of $E_{\lambda}$ $\implies$ $\bigcup\limits_{\lambda} \beta_{\lambda}$ is eigenbasis of $A$ for $F^{n}$

Rmk. T.A.F.E. of direct sum
- ...
	- ![[Screenshot 2024-03-19 at 5.22.50 PM.png]]![[Screenshot 2024-03-19 at 5.23.06 PM.png]]

