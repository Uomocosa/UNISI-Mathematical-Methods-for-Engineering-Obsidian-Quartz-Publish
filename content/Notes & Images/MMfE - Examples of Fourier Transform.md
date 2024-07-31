All Exercises (with Solutions) containing the "**Fourier_transform**", "**is_Fourier_transformable**", "**inverse_Fourier_transform**" or "**properties_of_Fourier_transform**",  tag:
- [[MMfE ~ exam_2020_06_10 - with solutions]]
- [[MMfE ~ exam_2020_06_24 - with solutions]]
- [[MMfE ~ exam_2020_07_15 - with solutions]]
- [[MMfE ~ exam_2021_02_17 - with solutions]]

---
# General Solution

![[Pasted image 20220531200831.png]]

- If a function belongs to at least the first [[MMfE - Lp Spaces of Functions (Lebsgue Spaces)|Lobsgue space]], so $f(x) \in L^1$ (or $L^2$, $L^3$, $\ldots$), then we can say that it's Fourier Transform exist, so we should assert:
$$
\large \int_{-\infty}^{+\infty}\left|f(t)\right| \ dt \ < \ \infty
$$
We say that the function $f(t)$ is [Lebesgue-measurable (Wikipedia)](https://en.wikipedia.org/wiki/Fourier_transform#:~:text=Here%20we%20assume,%C4%A5(%CE%BE)%20respectively.)

- Then we can proceed with the actual transformation, usually done with the definition of **Fourier Transformation**:
$$
\large F(w) = \int_{-\infty}^{+\infty}  f(t) \cdot e^{-iwt}\ dt
$$

- The **inverse Fourier Transform** is given by:
$$
\large f(t) = \frac{1}{2\pi}\int_{-\infty}^{+\infty}  F(w) \cdot e^{iwt}\ dw
$$
---
![[MMfE ~ exam_2020_06_10 - with solutions#Ex 2020_06_10 Point 2]]

---
![[MMfE ~ exam_2020_06_10 - with solutions#Ex 2020_06_10 Point 3]]

---
![[MMfE ~ exam_2020_06_24 - with solutions#Ex 2020_06_24 Point 3]]

---
![[MMfE ~ exam_2020_07_15 - with solutions#Ex 2020_07_15 Point 3]]

---
![[MMfE ~ exam_2021_02_17 - with solutions#Ex 2021_02_17 Point 4]]