
Pf. ^455612
- $\lim\limits_{n\to\infty}(1+\dfrac{x}n)^n$
- $=\lim\limits_{n\to\infty}\exp(\,\ln((1+\dfrac{x}n)^n)\,)=\lim\limits_{n\to\infty}\exp(\dfrac{\ln(1+xn^{-1})}{n^{-1}})$  { L'Hôpital: $\dfrac00$ }
- $=\lim\limits_{n\to\infty}\exp(\dfrac{(1+xn^{-1})^{-1}\cdot(-x{n^{-2}})}{-n^{-2}})=\lim\limits_{n\to\infty}\exp(\dfrac{x}{1+\dfrac{x}{n}})=e^x$