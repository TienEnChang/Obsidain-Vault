
Pf. ${\rm Span}({\beta})=V$

Let $\beta\in\mathcal{T}$ where $|\beta|\geq|T|$ $\forall\,T\in\mathcal{T}$  (maximal element of $\mathcal{T}$)

Suppose ${\rm Span}({\beta})\subsetneq V$

By Thm. $\exists\,T\in\mathcal{T}$ s.t. ${\rm Span}(T)=V$

==>>  $\exists\,v\in {\rm Span}(T)$  where  $v=\displaystyle\sum_{u\in T}a_u\,u$  $\forall\,a_u\in F$  s.t. $v\not\in{\rm Span}(\beta)$
==>>  $\exists\,u\in T$  s.t. $u\not\in\beta$  ==>>  By Thm. {$u$}$\cup\beta\in\mathcal{T}$

|{$u$}$\cup\beta$| > |$\beta$|  ==>>  $\beta$ is not maximal element of $\mathcal{T}$ (=><=)


Pf. Replacement Thm.

Let Span($G$) = V

(1) case m = 0:  $L=\varnothing$, $H=G$  ==>>  Span($L\cup H$) = Span($G$)

(2) case m = k:  $L$k = {v1, ... , vk}
                 $\exists\,H$n-k  s.t. Span($L$k $\cup$ $H$n-k) = Span($G$)

Let $L$k+1 = $L$k + {vk+1}

vk+1 $\in$ V = Span($L$k $\cup$ $H$n-k)

==>>  vk+1 = (a1v1 + ... akvk) + (b1u1 + ... + b(n-k)u(n-k))

Because $L$k+1 is linearly indep.

So, b1, ... , b(n-k) not all zero, WLOG, assume b1 $\neq$ 0

==>>  u1 = 1/b1 \[ vk+1 - (a1v1 + ... akvk) 
                       - (b2u2 + ... b(n-k)u(n-k)) ]

Let $H$n-k-1 = $H$n-k - {u1}

==>>  u1 $\in$ Span($L$k+1 $\cup$ $H$n-k-1)