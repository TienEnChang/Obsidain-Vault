
Let
- $V$, $W$ be vector spaces over field $F$

Def. space of linear transformation
- $\mathcal{L}(V,\,W)\coloneqq\{\,T:V\to W\;|\;T$ is linear$\,\}$
- where
	- "$+$":
		- Let $T,\,U\in\mathcal{L}(V,\,W)$
		- $\implies$ $(T+U)(x)\coloneqq T(x)+_{w}U(x)$  $\forall\,x\in V$
	- "$\,\cdot\,$":
		- Let $a\in F$
		- $\implies$ $(a\cdot T)(x)\coloneqq a\cdot_w T(x)$  $\forall\,x\in V$

Def.
- zero transformation
	- $T_0:V\to W$  where  $T_0(\vec v)\coloneqq\vec 0_w$  $\forall\,\vec v\in V$
- identity transformation
	- $I_V:V\to V$  where  $I_V(\vec v)\coloneqq\vec v$  $\forall\,\vec v\in V$

---

Thm.
- $(\mathcal{L}(V,\,W),\,+,\,\cdot\;)$ is a subspace of $(\mathcal{F}(V,\,W),\,+,\,\cdot\;)$  [[Pf.]]
- i.e.
	- (1) $T_0\in\mathcal{L}(V,\,W)\subseteq\mathcal{F}(V,\,W)$
	- (2) $\forall\,T,\,U\in\mathcal{L}(V,\,W)$, $a\in F$:  $a\cdot T+U\in\mathcal{L}(V,\,W)$
	- $\implies$
		- $[a\cdot T+U\,]_\beta^\gamma=a\cdot[T]_\beta^\gamma+[U]_\beta^\gamma$

---

Let
- $V$, $W$, $Z$, $X$ be vector spaces over field $F$
	- with ordered bases $\beta$, $\gamma$, $\alpha$, $\delta$
	- and ${\rm dim}(V)=n$, ${\rm dim}(W)=m$, $\dim(Z)=p$, $\dim(X)=q$

Thm. Composition Thm.
- $T\in\mathcal{L}(V,\,W)$,  $U\in\mathcal{L}(W,\,Z)$
- $\implies$ $U\circ T\in\mathcal{L}(V,\,Z)$  where  $[U\circ T]_\beta^\alpha=[U]^\alpha_\gamma\cdot[T]^\gamma_\beta$

Thm.
- Let $T\in\mathcal{L}(V,\,W)$,  $U_1,\,U_2\in\mathcal{L}(W,\,Z)$,  $S_1,\,S_2\in\mathcal{L}(X,\,V)$
- $\implies$
- "distributive law":
	- $T\circ(S_1+S_2)=T\circ S_1 + T\circ S_2$
	- $(U_1+U_2)\circ T=U_1\circ T+ U_2\circ T$
- "associative law":
	- $(U_1\circ T)\circ S_1=U_1(\circ T\circ S_1)\,$
	- $(a\,U_1)\circ T=a\,(U_1\circ T)$  $\forall\,a\in F$

Thm.
- Let $A\in M_{m\times n}(F)$,  $C_1,\,C_2\in M_{p\times m}(F)$,  $B_1,\,B_2\in M_{n\times q}(F)$
- $\implies$
- "distributive law":
	- $A(B_1+B_2)=AB_1 + AB_2$
	- $(C_1+C_2)A=C_1A+ C_2A$
- "associative law":
	- $(C_1A)B_1=C_1(AB_1)\,$
	- $(a\,C_1)A=a\,(C_1A)$  $\forall\,a\in F$

---

Let $A\in M_{m\times n}(F)$

Def. left multiplication transformation
- $L_A:F^n\to F^m$  where  $L_A(x)\coloneqq A\cdot x$  $\forall\,x\in F^n$ ^fkqudmsn

Def. right multiplication transformation:
- $R_A:F^m\to F^n$  where  $R_A(x)\coloneqq x\cdot A$  $\forall\,x\in F^m$ ^wngjasmfl

Let
- $\beta,\,\gamma$ be the ordered bases of $F^n,\,F^m$
- $L_A$ be left multi. trans.

Thm.
- $L_A$ is linear
- $[L_A]^\gamma_\beta=A$
	- $L_A=L_B\iff A=B$   $\forall\,A,\,B\in M_{m\times n}(F)$
	- $L_{(c\,\cdot A+B)}=c\cdot L_A+L_B$   $\forall\,A,\,B\in M_{m\times n}(F)$, $\forall\,c\in F$
	- $L_{AB}=L_A\cdot L_B$          $\forall\,A\in M_{m\times n}(F)$, $\,B\in M_{n\times q}(F)$

Thm.
- $\forall\,T\in\mathcal{L}(F^n,\,F^m)$:  $\exists\,!\,A\in M_{m\times n}(F)$  s.t.  $T=L_A$  i.e.  $[T]^\gamma_\beta=A$