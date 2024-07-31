All Exercises (with Solutions) containing the "Laplace_transform" tag:
- [[MMfE ~ exam_2021_02_17 - with solutions]]
- [[MMfE ~ exam_2021_06_25 - with solutions]]
- [[MMfE ~ exam_2021_09_10 - with solutions]]

---
# General Solution
Lets start by answering the question:
- "Is $f(t)$ Laplace Transformable?"

If 
$$
\exists \ \alpha \in \mathbb{R}, M \gt 0: 
\kern 15px  
|f(t)| \le Me^{\alpha t}
\kern 25px 
\text{for} \ t > 0
$$
-> $F(s) = \mathcal{L}[f(t)]$ is well-defined for all complex values of $s$ such that: $\operatorname{Re}\{s\} \gt \alpha$.

> More Reading: [[MMfE - Is Laplace Transformable]]

- The **Laplace Transform** is given by:
$$
f(t) = \int_{0}^{\infty} f(t) \kern2px e^{-st} \kern2px dt
$$
Where $\sigma$ is the [[MMfE - Find the Abscissa of Convergence|abscissa of convergence]]


- The **Inverse Laplace Transform** is given by:
$$
f(t) = \int_{\sigma - i \kern1px \infty}^{\sigma + i \kern1px \infty} F(s) \kern2px e^{st} \kern2px ds
$$
Where $\sigma$ is the [[MMfE - Find the Abscissa of Convergence|abscissa of convergence]]



---
![[MMfE - Cheatsheet 'Laplace Transform']]

---
###### ~Ex.: 2021_02_17 Point 4.
![[Written Exam MMfE 17 02 2021-4.jpg]]
![[Written Exam MMfE 17 02 2021-5.jpg]]

---
###### ~Ex.: 2021_06_25 Point 3.
![[Written Exam MMfE 25 06 2021-4.jpg]]

---
###### ~Ex.: 2021_06_25 Point 4.
![[Written Exam MMfE 25 06 2021-5.jpg]]

---
###### ~Ex.: 2021_09_10 Point 3.
![[Written Exam MMfE 10 09 2021-5.jpg]]
![[Written Exam MMfE 10 09 2021-6.jpg]]

---
###### ~Ex.: 2021_09_10 Point 4.
![[Written Exam MMfE 10 09 2021-7.jpg]]
![[Written Exam MMfE 10 09 2021-8.jpg]]

---