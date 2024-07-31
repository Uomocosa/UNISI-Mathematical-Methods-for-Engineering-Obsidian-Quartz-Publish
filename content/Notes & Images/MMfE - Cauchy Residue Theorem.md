### Cauchy Residue Theorem
#Mathematical_Methods_for_Engineering  #Theorem 
$$
\int_{\gamma} f(z) dz = 2\pi i \sum_i \operatorname{Res}\{f(z),\  p_i\} \kern 30 px
$$
Where:
- $f(z)$ is **holomorphic**
- $\gamma$ is a **simple closed positively oriented contour**
- $p_i$ are the **poles** of $f(z)$

> **NOTE**:
> - If the curve $\gamma$ is defined in the **ANTI-CLOCK wise** $\circlearrowleft$ sense then its $+2\pi i$.
> - If the curve $\gamma$ is defined in the **CLOCK wise** $\circlearrowright$ sense then its $-2\pi i$.

---
###### Residues:
$Res\{f(z), \ p_i\}$ is calculated as follows:
- If $p_i$ is **outside** the closed contour $\gamma$ :
$$
Res\{f(z), \ p_i\} = 0
$$
- If $p_i$ is **inside** $\gamma$, and is a **simple pole** (*multiplicity* = 1):
$$
Res\{f(z), \ p_i\} = \large \lim_{z\ \to \ p_i} \normalsize (z-p_i)\kern2px f(z)
$$
- If $p_i$ is **inside** $\gamma$, and is a **complex pole** of *multiplicity* = $k$ :
$$
Res\{f(z), \ p_i\} = \frac{1}{(k-1)!} \large \lim_{z\ \to \ p_i} \normalsize \frac{d^{k-1}}{d \kern2px z^{k-1}}\left\{(z-p_i)^k\kern2px f(z)\right\}
$$
<br>
- [[MMfE - Holomorphic or Analytical Functions|What's an Holomorphic Function?]]
- [[MMfE - Simple Closed Positively Oriented Contour|What's a Simple Closed Positively Oriented Contour?]]
- [[MMfE - Poles of a Function|What are the Poles of a Function?]]
- [[MMfE - Multiplicity|What's the Multiplicity?]]

---
### Original File:
[[Pasted image 20220604185021.png]] IL LIBRO HA SBAGLIATO, C'È UN ERRORE NELL'ULTIMA FORMA!
[[Integrals of holomorphic functions_220518_145829.pdf]]
[[cauchy residue theorem_220518_160518.pdf]]