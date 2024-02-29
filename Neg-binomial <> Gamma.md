
- $Y_r\sim\text{negative-binomial}(r,\,p)$
	- $Y_r$:$\;$  At the $r$-th occurrence, "$k=$ <u>num of trials</u>" were taken
- $T_k\sim {\rm gamma}(\alpha=k,\,\lambda=\overline{\lambda})$
	- $T_k$:  At the $k$-th occurrence, $\,$"$t=$ <u>waiting time</u>" was taken

---

- Geo:  { $e^{-\lambda}=1-p$ }
	- $p_{Y_1}(k)=p(1-p)^{(k-1)}$
	- $F_{Y_{1}}(k)=\sum\limits_{i=r}^{k}p_{Y_1}(i)=1-(1-p)^{k}$
		- $\sum\limits_{i=r}^{k}p_{Y_1}(i)=1-\sum\limits_{i=k}^{\infty}p(1-p)^{i}=1-p(1-p)^{k}\sum\limits_{i=0}^{\infty}(1-p)^{i}=1-(1-p)^{k}$
- Exp:  { $p=1-e^{-\lambda}$ }
	- $F_{T_{1}}(t)=1-e^{-\lambda t}$
	- $p_{T_{1}}(t)=F_{T_{1}}(t)-F_{T_{1}}(t-1)=(1-e^{-\lambda})(e^{-\lambda}){}^{(t-1)}$