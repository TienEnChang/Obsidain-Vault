
Def.
- 假設 hypothesis $\implies$ conclusion 結論
	
- 充分條件 sufficient condition: $P$ $\implies$ 
- 必要條件 necessary condition:    $\implies$ $Q$

$P\implies Q$
$\equiv$ $\neg\, Q\implies \neg\, P$
$\equiv$ $\neg\, P\lor Q$       { $\because$ $\neg\, P\lor P$ & $\neg\, Q\lor Q$ $\implies$ $\neg P\lor Q$ }

($\forall x\in A$) $p(x)$:  ($x\in A$) $\implies$ $p(x)\!$ 
($\exists x\in A$) $q(x)$:  ($x\in A$) $\land$ $q(x)$     or  $\neg$ $[$ ($x\in A$) $\implies$ $\neg\,q(x)$ $]$

$\exists\,!\,x$  s.t. $P(x)$  $\iff$  $\exists\,x,\,y$  s.t. $P(x)$ $\land$ $P(y)$ $\implies$ $x=y$


---

Axiom of Choice (controversial, avoid if possible):
- Let
	- index set $I$
	- collection of sets { $A_i$ | $i\in I$ }
- $\implies$
	- $\exists f:I\to\bigcup\limits_{i\in I}A_i$  s.t. $f(i)\in A_i$  $\forall i\in I$