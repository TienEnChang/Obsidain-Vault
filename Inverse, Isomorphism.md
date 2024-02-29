
Let
- $V$, $W$ be vector spaces over field $F$

Def.
- $f:X\to Y$ is invertible
- $\iff$ $\exists\,f^{-1}:Y\to X$  where  $\begin{cases}f^{-1}(f(x))=x\\ f(f^{-1}(x))=x\end{cases}$  $\forall\, x\in X$

Def.
- $A\in M_{n}(F)$ is invertible
- $\iff$ $\exists\,A^{-1}\in M_{n}(F)$  where  $A^{-1}A=AA^{-1}=I_n$

Prop.
- $f^{-1}$ is unique ,  $(f_1\circ f_2)^{-1}=f_2^{-1}\circ f_1^{-1}$
- $A^{-1}$ is unique ,  $(AB)^{-1}=B^{-1}A^{-1}$

Thm.
- $f$ invertible $\iff$ $f$ bijective

---

Def. $T$ is isomorphism:  $T$ is linear & invertible

Def. $V$, $W$ are isomorphic:  $\exists$ isomorphism $T:V\to W$

Thm.
- isomorphic ${\overset{\rm iso}\sim}$ is
  an equivalence relation on $\{\,$ all vector space over same field $\}$
	- i.e. 
- $V\;{\overset{\rm iso}\sim}\;V$  by identity trans. $I_V$ ( is iso )
- $V\;{\overset{\rm iso}\sim}\;W$  by iso $f$ $\implies$ $f^{-1}$ is iso,  $W\;{\overset{\rm iso}\sim}\;V$
- $V\;{\overset{\rm iso}\sim}\;W$  by iso $f_1$,  $V\;{\overset{\rm iso}\sim}\;Z$  by iso $f_2$
  $\implies$ $f_2\circ f_1$ is iso,  $V\;{\overset{\rm iso}\sim}\;Z$ 

Thm.
- $T$ is isomorphism $\implies$ $T^{-1}$ isomorphism
- $T$ is isomorphism $\iff$ $[T]_\beta^\gamma$ is invertible

Thm.
- $V$, $W$ isomorphic $\iff$ $\dim(V)=\dim(W)$

---

Let
- $V$, $W$  with  ${\rm dim}(V)=n$, ${\rm dim}(W)=m$, $<\infty$
- $\beta$, $\gamma$ be order bases of $V$, $W$
	- with  $\beta\coloneqq\{\,\beta_1,\,...,\,\beta_n\}$, $\gamma\coloneqq\{\,\gamma_1,\,...,\,\gamma_m\}$

Thm.
- $f:\mathcal{L}(V,\,W)\to M_{m\times n}(F)$  where  $T\mapsto[T]_\beta^\gamma$  $\forall\,T\in\mathcal{L}(V,\,W)$
- $\implies$
	- $f$ is isomorphism

Def. standard representation of $V$ with respect to $\beta$
- $\phi_\beta:V\to F^n$ 
- where  $x\mapsto[x]_\beta$  $\forall\,x\in V$
- $\implies$
	- $\phi_\beta$ is isomorphism

Thm. commutative diagram
- $\phi_\gamma\circ T:V(\to W)\to F^m$,  $L_{[T]_\beta^\gamma}\circ \phi_\beta:V(\to F^n)\to F^m$
- $\implies$
	- $\phi_\gamma\circ T=L_{[T]_\beta^\gamma}\circ \phi_\beta$

Thm. Isomorphism Thm.
- $T:V\to W$ is linear $\implies$ $\bar T:V/N(T)\to T(V)$ is isomorphism
                            { $v+N(T)\mapsto T(v)$ }

Cor.
- $\dim(V/N(T))=\dim(V)-\dim(N(T))=\dim(T(V))$  {Dimension Thm.}


Pf. 1-1
![[Screenshot 2023-11-07 at 12.33.44 AM.png]]![[Screenshot 2023-11-07 at 12.34.00 AM.png]]![[Screenshot 2023-11-07 at 12.34.15 AM.png]]![[Screenshot 2023-11-07 at 12.34.49 AM.png]]![[Screenshot 2023-11-07 at 12.35.10 AM.png]]