- Think of the **Laurent Series** as [[MMfE - Taylor Series|Taylor Series]] for **complex numbers**.
- Online Resources: [Youtube](https://www.youtube.com/watch?v=RC15R-ktnUI) **REALLY GOOD**
- Online Resources: [Youtube](https://www.youtube.com/watch?v=0ZOMkmy-aTo)

---
### Def.: Laurent Series
#Mathematical_Methods_for_Engineering #Definition 
###### Objective:
Transform the function $f(z)$ in this form:
$$
\large
f(z) = 
	\sum_{n = 0}^{\infty}
	a_n\cdot\left(z-z_0\right)^{n}
+
	\sum_{n = 1}^{\infty}
	a_{-n}\cdot\left(z-z_0\right)^{-n}
$$
###### Useful Functions to Remember
$$
\begin{align}
&\large \frac{1}{1-c \kern1px z}= \sum_{n=0}^{\infty}\left(c \kern1px z\right)^n \kern30px \text{for} \ |z|\lt\frac{1}{|c|}
\\[7px]
&\large \frac{1}{1-\frac{b}{z}} = \sum_{n=0}^{\infty}\left(1-\frac{b}{z}\right)^n \kern30px \text{for} \ |z|\gt |b|
\end{align}
$$
---
###### ~Ex.:
$f(z) = \Large \frac{1}{(z-1)(z-2)}$

We can have it in 3 different forms, each with its own [[MMfE - Region of Holomorphicity]]
<br>
1. **Full Circle**:
![[Pasted image 20220605120011.png]]
$$
\begin{array}{rl}
f(z) = \Large \frac{1}{(z-1)(z-2)} &= \Large \frac{A}{(z-1)} + \frac{B}{(z-2)}
\\[1px] 
\normalsize 
(A = -1, \ B = 1)
\to &\ | \\[1px]
&= \Large \frac{1}{(z-2)} - \frac{1}{(z-1)}
\\[1px] 
\large
\frac{1}{z-2} =  -\sum_{n=0}^{\infty} \kern3px \frac{z^n}{2^{n+1}} \kern10px \normalsize \text{for}\ |z| < 2
\to &\ | \\[1px]
\\[1px] 
\large
\frac{1}{z-1} =  -\sum_{n=0}^{\infty} \kern3px z^n \kern10px \normalsize \text{for}\ |z| < 1
\to &\ | \\[1px]
&= \Large -\sum_{n=0}^{\infty} \kern3px z^n\left(1 + \frac{1}{2^{n+1}}\right) \kern10px \normalsize \text{for}\ |z| < 1
\end{array}
$$
<br>
3. **Donut**:
![[Pasted image 20220605121501.png]]
$$
\begin{array}{rl}
f(z) = \Large \frac{1}{(z-1)(z-2)} &= \Large \frac{1}{(z-2)} - \frac{1}{(z-1)}
\\[8px] 
\large
\frac{1}{z-2} =  -\sum_{n=0}^{\infty} \kern3px \frac{z^n}{2^{n+1}} \kern10px \normalsize \text{for}\ |z| < 2
\to &\ | \\[1px]
\\[1px] 
\large
\frac{1}{z-1} =  -\frac{1}{z} \cdot \sum_{n=0}^{\infty} \kern3px \left(\frac{1}{z}\right)^n \kern10px \normalsize \text{for}\ |z| > 1
\to &\ | \\[1px]
&= \Large -\sum_{n=1}^{\infty} (z)^{-n} - \sum_{n=0}^{\infty} \kern3px \frac{z^n}{2^{n+1}} \kern10px \normalsize \text{for}\ 1 < |z| < 2
\end{array}
$$
<br>
5. **Open Circle**: 
![[Pasted image 20220605122038.png]]
$$
\begin{align}
&\ldots
\\[7px]
&f(z) = \large 
-\sum_{n=1}^{\infty} (z)^{-n} - 2\cdot\sum_{n=1}^{\infty} \kern3px \left(\frac{z}{2}\right)^{-n} \kern10px \normalsize \text{for}\ |z| > 2
\end{align}
$$

---
# Original Files:
[[Laurent Series_220511_144338.pdf]]