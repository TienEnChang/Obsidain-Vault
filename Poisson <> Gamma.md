
Formula:
- $P_{N_t}(\{x\geq k\})=P_{T_k}(\{y\leq t\})$  { 超過 = 提前達標 }
- $F_{N_t}(k-1)=1-F_{T_k}(t)$

---

- $N_t\sim{\rm Poisson}(\lambda=\overline{\lambda} t)$
	- $N_t$:  At the $t$-th moment,     $\,$"$k=$ <u>num of occurrences</u>" were realized
- $T_k\sim {\rm gamma}(\alpha=k,\,\lambda=\overline{\lambda})$
	- $T_k$:  At the $k$-th occurrence, $\,$"$t=$ <u>waiting time</u>" was taken

---

- Poisson ←→ Gamma
	- $F_{N_{t}}(k-1)=1-F_{T_k}(t)$   { incomplete }
		- $F_{N_{t}}(k-1)=\sum\limits_{i=1}^{k}p_{N_{t}}(i-1)$
		- $=\sum\limits_{i=1}^{k}\dfrac{1}{\lambda}f_{T_{i}}(t)=\sum\limits_{i=1}^{k}[F_{T_{i-1}}(t)-F_{T_i}(t)]=F_{T_{0}}(t)-F_{T_k}(t)$

- Poisson ←→ Exp
	- $F_{N_t}(0)=1-F_{T_1}(t)$   { ok }
		- Pf:  $F_{N_t}(0)=\sum\limits_{i=0}^{0}\dfrac{(\lambda t)^{i}e^{-(\lambda t)}}{i!}=e^{-\lambda t}=1-F_{T_1}(t)$

- Poisson ←→ Gamma / Exp
	- $p_{N_{t}}(k-1)=\dfrac{1}{\lambda}f_{T_{k}}(t)$   { ok }
		- Pf:  $p_{N_{t}}(k-1)=\dfrac{(\lambda t)^{(k-1)}e^{-(\lambda t)}}{(k-1)!}=\dfrac{\gamma'(k,\,\lambda t)}{\Gamma(k)}=\dfrac{1}{\lambda}f_{T_{k}}(t)dt$
	- $\dfrac{1}{\lambda}f_{T_{k}}(t)=F_{T_{k-1}}(t)-F_{T_k}(t)$   { incomplete }
		- $\forall\,i$: $(T_{1})_{i}\sim \text{exp}(\lambda)$ $\iff$ $\exists\,k$: $[\sum\limits_{i=1}^k{(T_1)_i}]\sim\text{gamma}(k,\,\lambda)$
