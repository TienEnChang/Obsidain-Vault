
Def. RREF
- (1) $\exists$ $r\geq 0$  s.t. $R_{i*}=\begin{cases} {\rm not\;all\;zero} & {\rm if}\;1\leq i\leq r \\ {\rm all\;zero}&{\rm if}\;r< i\leq m \end{cases}$   { $\vec 0$ at the bottom }
	
- $\exists$ $(j_1,\,\cdots,\,j_r)$ increasing                $\,\,\;\!${ pivot markers }
	- (2) $j_i:=\min\,\{\,j\;|\;R_{ij}\neq 0\,\}$            { 1st nonzero at $i$th row }
	- (3) $R_{*j_i}=e_i:=(0,\,\cdots,\,1_{(i\text{th})},\,\cdots,\,0)\,$   { unique nonzero at $j_i$th column }

Prop. $R_{*j_i}\not\in{\rm span}\{R_{*j_1},\,\cdots,\,R_{*j_{(i-1)}}\}$


Def.
- $A_1x=b_1\,$ & $\,A_2x=b_2$ equivalent:  ${\rm Sol}(A_1x=b_1)={\rm Sol}(A_2x=b_2)$

Prop.
- For $C\in M_n(F)$ invertible,  $Ax=b\,$ and $\,CAx=Cb$ are equivalent
Cor.
- For $(A'|\,b'):=$ RREF of $(A|\,b)$,  $Ax=b\,$ and $\,A'x=b'$ are equivalent




