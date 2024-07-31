All Exercises (with Solutions) containing the "solve_differential_equation_using_Laplace_transform" tag:
- [[MMfE ~ exam_2020_06_10 - with solutions]]
- [[MMfE ~ exam_2020_06_24 - with solutions]]
- [[MMfE ~ exam_2020_07_15 - with solutions]]
- [[MMfE ~ exam_2021_06_25 - with solutions]]
- [[MMfE ~ exam_2021_09_10 - with solutions]]

---
# General Solution
1. Use the **Laplace Transforms** of:
$\mathcal{L}\left[\frac{d^n}{d\kern2px t^n}f(t)\right] = s^n \cdot F(s) + s^{n-1}\cdot f(0) + s^{n-2}\cdot f'(0)+ s^{n-3}\cdot f''(0) + \ldots + f^{(n)}(0)$
2. Then after finding the equation of $F(s) = \ldots$ use the **Residue theorem** to find the **Inverse Laplace Transform**.

- The **Inverse Laplace Transform** is given by:
$$
f(t) = \int_{\sigma - i \kern1px \infty}^{\sigma + i \kern1px \infty} F(s) \kern2px e^{st} \kern2px ds
$$
Where $\sigma$ is the [[MMfE - Find the Abscissa of Convergence|abscissa of convergence]]

- Then applying the [[MMfE - Jordan's Lemma|Jordan's Lemma]]:
![[Pasted image 20220604225041.png]]

- Here is a recap of the [[MMfE - Cauchy Residue Theorem|Residue Theorem]]

---
![[MMfE ~ exam_2020_06_10 - with solutions#Ex 2020_06_10 Point 4]]

---
![[MMfE ~ exam_2020_06_24 - with solutions#Ex 2020_06_24 Point 4]]

---
![[MMfE ~ exam_2020_07_15 - with solutions#Ex 2020_07_15 Point 4]]

---
![[MMfE ~ exam_2021_06_25 - with solutions#Ex 2021_06_25 Point 4]]

---
![[MMfE ~ exam_2021_09_10 - with solutions#Ex 2021_09_10 Point 4]]
