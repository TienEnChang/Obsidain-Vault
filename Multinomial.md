
$(X_{1},\,\cdots,\,X_{n})\sim \text{multi-nomial}(m,\,n,\,p_{1},\,\cdots,\,p_{n})$ 
- where
- (x) indep.     $\mathcal{X}$ not cross product set { ${{\sum\limits_{i=1}^{n}k_{i}=m}}$ (1) }
- (v) identical
	- $X_{i}\sim \text{binomial}(m,\,p_{i})$  where  { $\sum\limits_{i=1}^{n}p_{i}=1\,$, $p_{n}=1-\sum\limits_{i=1}^{n-1}p_{i}$ (2) } 
	- with  $\mu_{i}=mp_{i}$,  $\sigma_{i}{^{\!2}}=mp_{i}(1-p_{i})$
- where
	- param:  $m\in\{1,\,2,\,\cdots\,\}$,  $\,p_{i}=P_0(E_0{^{\!(i)}})$
	- sample space:  $\Omega=\Omega_{0}{^{\!m}}$
	- count variable:  $X_{i}(\omega)\coloneqq\sum\limits_{j=1}^m1_{E_0{^{(i)}}}(\omega_{j})$

---

$(X_{1},\,\cdots,\,X_{k},\,[m-\sum\limits_{i=1}^{k}X_{i}])\sim \text{multi-nomial}(m,\,k+1,\,p_{1},\,\cdots,\,p_{k},\,[1-\sum\limits_{i=1}^{k}p_{i}])$

$(X,\,m-X)\sim \text{multi-nomial}(m,\,2,\,p,\,1-p)$ $\iff$ $X\sim \text{binomial}(m,\,p)$

---

Thm.
- multi-nomial:  $(x_{1}+\cdots+x_{n})^{m}=\sum\limits_{\begin{array}{}0\leq k_{1},\,\cdots,\,k_{n}\leq n \\k_{1}+\cdots+k_{n}=m\end{array}}{m\choose k_{1},\,\cdots,\,k_{n}}\,x_{1}{^{\!k_{1}}}\cdots x_{n}{^{\!k_{n}}}$
- binomial:  $(x+y)^{n}=\sum\limits_{k=0}^{n}{n\choose k}\,x^{k}\,y^{1-k}$







