- Online Resources: [mathisfun](https://www.mathsisfun.com/calculus/fourier-series.html)

---
### Def.: Fourier Series
Given a function $f(x)$ we can rewrite it as:
$$
f(x) = a_0 + 
\sum_{n \ = \ 1}^{\infty} a_n \cdot \cos(n \kern2px x \frac{\pi}{L}) + 
\sum_{n \ = \ 1}^{\infty} b_n \cdot \sin(n \kern2px x \frac{\pi}{L})
$$
Where:
$$
\begin{align}
a_0 &= \frac{1}{2L} \int_{-L}^{+L} f(x) \ dx
\\[10px]
a_n &= \frac{1}{L} \int_{-L}^{+L} f(x) \kern2px \cos(n \kern2px x \frac{\pi}{L}) \ dx
\\[10px]
b_n &= \frac{1}{L} \int_{-L}^{+L} f(x) \kern2px \sin(n \kern2px x \frac{\pi}{L}) \ dx
\end{align}
$$
---