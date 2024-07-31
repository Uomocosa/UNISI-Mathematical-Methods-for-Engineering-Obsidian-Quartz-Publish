### Classification of Singularities
#Mathematical_Methods_for_Engineering #Theorem 
Given an **holomorphic** function $f(z)$, if such function has a pole in $z_0$, so it can be written as:
$$
f(z) = \frac{g(z)}{(z-z_0)^k}
$$
Where $k$ is the **multiplicity** of the pole $z_0$ .

Then suppose we can write it with the **Laurent Series** such as:
$$
f(z) = \sum_{k \ \in \ \mathbb{Z}} c_k(z - z_0)^k
$$
Then we can classify the *singularity* $z_0$ as:
- ***REMOVABLE***: if $k \ge 0$ (The **Lauren Series** has no negative exponents)
- ***POLE***: if $k \in \mathbb{R},\  \text{and} \  k \lt 0$
- ***ESSENTIAL***: if $k = -\infty$

---
### Another way:
Another way to classify a singularity is to solve the following limit:
$$
\large \lim_{z \ \to \ z_0} |f(z)|
$$
Then we can classify the *singularity* $z_0$ as:
- ***REMOVABLE***: if the limit exist and it's **finite**
- ***POLE***: if the limit is equal to $\pm \infty$
- ***ESSENTIAL***: if the limit **does not** exist

---
# Original Files:
![[Pasted image 20220605162927.png]]
![[Pasted image 20220605163011.png]]
![[Pasted image 20220605163036.png]]
![[Singularities Classification_220512_110806.pdf]]
