
p.m.f
- (1)  $p_X(k)\begin{cases}\geq 0&\text{if}\;k \in\mathcal{X}\\0&\text{o.w.}\end{cases}$
- (2) $\,\,\sum\limits_{k\in\mathcal{X}}p_X(k)=1$ 

p.d.f
- (1)  $f_{X}(x)\geq 0$  $\forall\,x \in \mathbb{R}$
- (2)  ${\displaystyle\int}_{\mathbb{R}}f_{X}(x)dx=1$

c.d.f.
- (1) non-decreasing
		
- (2) continuous from the right
	- $F_X(x^+)\coloneqq\lim\limits_{t\to x+}F_X(t)=F_X(x)$
	- $F_X(x^-)\coloneqq\lim\limits_{t\to x^-}F_X(t)\not\equiv F_X(x)$
	
- (3) $\begin{cases}\lim\limits_{t\to-\infty}F_X(t)=0\\\lim\limits_{t\to\infty}F_X(t)=1\end{cases}$
	- $\implies$
		- $\forall\,x\in\mathbb{R}$:  $0\leq F_X(x)\leq 1$   { By 1 & 3 }

joint p.m.f
- (1) $p_{\textbf{X}}(\vec{x})\begin{cases}\geq 0&\text{if}\;\vec{x} \in\mathcal{X}\\0&\text{o.w.}\end{cases}$
- (2) $\sum\limits_{\vec{x} \in\mathcal{X}}p_{\textbf{X}}(\vec{x})=1$

joint p.d.f.
- (1)  $f_{\textbf{X}}(\vec{x})\geq 0$  $\forall\,\vec{x} \in \mathbb{R}^{n}$
- (2)  ${\displaystyle\int}_{\mathbb{R}^{n}}f_{\textbf{X}}(\vec{x})d\vec{x}=1$

joint c.d.f.
- (1) non-decreasing:
	- $F_\textbf{X}(x'_1,\,\cdots,\,x'_n)\geq F_\textbf{X}(x_1,\,\cdots,\,x_n)$  for  $(x'_1,\,\cdots,\,x'_n)\geq (x_1,\,\cdots,\,x_n)$
	
- (2) continuous from the right:
	- $\lim\limits_{(t_1,\,\cdots,\,t_n)\,\to\,(x_1,\,\cdots,\,x_n)^+}F_\textbf{X}(t_1,\,\cdots,\,t_n)=F_\textbf{X}(x_1,\,\cdots,\,x_n)$

- (3) $\begin{cases} \lim\limits_{t_i\to-\infty}F_\textbf{X}(t_1,\,\cdots,\,t_n)=0 &{\rm for\;any}\;i \\ \lim\limits_{t_1,\,\cdots,\,t_n\to\infty}F_\textbf{X}(t_1,\,\cdots,\,t_n)=1 \end{cases}$
	- $\implies$
		- $\forall\,x_1,\,\cdots,\,x_n\in\mathbb{R}$:  $0\leq F_X(x_1,\,\cdots,\,x_n)\leq 1$