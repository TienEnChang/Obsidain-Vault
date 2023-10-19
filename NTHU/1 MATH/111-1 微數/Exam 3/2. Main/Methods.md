證明 limit
- 為使 $|f(x)-L|<\varepsilon$
  (1) case $g(x)\cdot|x-c|$:
        Because $|x-c|<1\implies g(x)<k$
        So let $\delta=min(1,\;\dfrac\varepsilon{k})$ s.t.
          $0< |x-c| < \delta\leq1\implies g(x)\cdot |x-c|<k\cdot\dfrac\varepsilon{k}=\varepsilon$
        if $k$ could be $0$
        then let $\delta=min(1,\;\dfrac\varepsilon{k+1})$ s.t.
          $0< |x-c| < \dfrac\varepsilon{k+1}\leq1\implies g(x)\cdot |x-c|<(k+1)\cdot\dfrac\varepsilon{k+1}=\varepsilon$

加一項 & 減一項
從相關形式去聯想

遇到|$\cdot$|or分段函數 => 分成 $x\to c^+$, $x\to c^-$
遇到$sin(\dfrac1x)$ => 夾擠

$\displaystyle\lim_{x\to c}\sqrt{x}\;\circ\, f(x)=\sqrt{x}\;\circ\,\lim_{x\to c}f(x)$ 前提：$\displaystyle\lim_{x\to c}f(x)\geq 0$


形式: 多項式/多項式 = 同除 > 羅必達

圓: $(x,\,y)$ => $\theta$


Solve ${\displaystyle\int}\sec^n(x)dx$
{
${\displaystyle\int}\sec^n(x)dx={\displaystyle\int}\sec^2(x)\sec^{n-2}(x)dx$
$=\tan(x)\sec^{n-2}(x)-(n-2){\displaystyle\int}\tan(x)\cdot\sec^{n-3}(x)\cdot\sec(x)\tan(x)dx$
$=\tan(x)\sec^{n-2}(x)-(n-2){\displaystyle\int}\sec^5+(n-2){\displaystyle\int}\sec^{n-2}(x)dx$
$\implies$
.
${\displaystyle\int}\sec^n(x)dx=\dfrac{1}{n-1}[\,\tan(x)\sec^{n-2}(x)+(n-2){\displaystyle\int}\sec^{n-2}(x)dx\,]$
}