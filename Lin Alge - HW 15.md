
1.
(a) F  $\because$  $\det(d_{i}(a))=a$  where  $a \in\mathbb{R}-\{0\}$
(b) T  $\because$  By Thm. 4.7
(c) F  $\because$  For $M$ square matrix, $M$ invertible $\iff$ $\det(M)\neq 0$
(d) T  $\because$  For $M$ square matrix, $M$ not full rank $\iff$ $\det(M)=0$
(e) F  $\because$  $\det(A^{t})=\det(A)$
(f) T  $\because$  $\det(A)=\sum\limits_{i=1}^{n}(-1)^{i+j}A_{ij}\det(\tilde{A}_{ij})$  for  $n>1$
(g) F  $\because$  System $Ax=b$  with $\det(A)=0$ not solvable by Cramer's rule
(h) F  $\because$  replacing $k$th column by $b$ $\neq$ replacing $k$th row by $b^{t}$

13.
(a)
Let $M \in M_{n}(\mathbb{C})$  with  $M_{ij}=a_{ij}+b_{ij}\text{i}$
               where  $a_{ij},\,b_{ij}\in\mathbb{R}$  $\forall\,i,\,j$ ,  $\text{i}=\sqrt{ -1 }$

$\because$  $\overline{M}_{ij}=\overline{M_{ij}}=a_{ij}-b_{ij}\text{i}$  $\forall\,i,\,j$

$\therefore$  For $n=1$,  $\overline{\det(M)}=a_{11}-b_{11}\text{i}=\det(\overline{M})$
	 .
	 For $n>1$,  assume $n-1$ holds.
	 .
	 $\overline{\det(M)}=\overline{\sum\limits_{j=1}^{n}(-1)^{1+j}M_{ij}\det(\widetilde{M}_{ij})}=\sum\limits_{j=1}^{n}(-1)^{1+j}\,\overline{{M}_{ij}}\,\overline{\det(\widetilde{M}_{ij}})$
	 .
	 $=\sum\limits_{j=1}^{n}(-1)^{1+j}\,\overline{M_{ij}}\,{\det(\overline{\widetilde{M}_{ij}}})=\sum\limits_{j=1}^{n}(-1)^{1+j}\,\overline{M}_{ij}\,{\det(\widetilde{\overline{M}}_{ij}})=\det(\overline{M})$

$\therefore$  By Induction,  $\det(\overline{M})=\overline{\det(M)}$

(b)
Let $Q \in M_{n}(\mathbb{C})$ be unitary  { i.e. $Q \overline{Q^t}=I$ }

$\implies$ $1=\det(I)=\det(Q \overline{Q^t})=\det(Q)\overline{\det(Q)}=|\det(Q)|$

21.
Let $M\coloneqq\begin{bmatrix}A&B\\O_{n-r,\,r}&C\end{bmatrix}$  where  $A\in M_{r}(F)$,  $C \in M_{n-r}(F)$
   .
   $P\coloneqq\begin{bmatrix}I_{r}&B\\O_{n-r,\,r}&C\end{bmatrix}$  $Q\coloneqq\begin{bmatrix}A&O_{r,\,n-r}\\O_{n-r,\,r}&I_{n-r}\end{bmatrix}$ $\implies$ $PQ=M$
   .
   $\text{sub}_{f}(S)\coloneqq\tilde{S}_{11}$,  $\text{sub}_{l}(S)\coloneqq \tilde{S}_{kk}$  $\forall\,S\in M_{k}(F)$  $\forall\,k \in\mathbb{N}$


$\because$  $\det(P)=(-1)^{1+1}\cdot1\cdot\det(\text{sub}_{f}(P))$  { expansion along first column }
	 .
	 $\land$  $\det(\text{sub}_{f}{}^{\circ\, i}(P))=(-1)^{1+1}\cdot1\cdot\det(\text{sub}_{f}{}^{\circ\, i+1}(P))$  $\forall\,i=1,\,\cdots,\,r-1$
	 .
	 $\implies$ $\det(P)=\det(C)$
	 .
	 $\det(Q)=(-1)^{n+n}\cdot1\cdot\det(\text{sub}_{l}(Q))$  { expansion along last column }
	 .
	 $\land$  $\det(\text{sub}_{l}{}^{\circ\, i}(Q))=(-1)^{(n-i)+(n-i)}\cdot1\cdot\det(\text{sub}_{l}{}^{\circ\, i+1}(Q))$  $\forall\,i=1,\,\cdots,\,n-r-1$
	 .
	 $\implies$ $\det(Q)=\det(A)$

$\therefore$  $\det(M)=\det(PQ)=\det(P)\det(Q)=\det(C)\det(A)$