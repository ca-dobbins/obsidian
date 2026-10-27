# Topic: 2.3  
Date: 2026-08-27 | Suggested HW: 1-34, 39-48, 52-54
### Building Blocks
*the meat of limits*

***Identity:*** 

$$
\lim_{ x \to a } x=a
$$

***Constant:***

$$
\lim_{ x \to a } c=c
$$

***Major Limit Laws***

Suppose:

$$
\lim_{ x \to a } f(x)=L \quad\text{and}\quad \lim_{ x \to a } g(x)=M
$$

1. *Sum*:

$$
\lim_{ x \to a } [f(x)+g(x)]=\lim_{ x \to a } f(x)+\lim_{ x \to a } g(x)
$$

2. *Product*:

$$
\lim_{ x \to a } [f(x)g(x)]=\lim_{ x \to a } f(x) \times \lim_{ x \to a } g(x)
$$

3. *Constant Multiple*:

$$
\lim_{ x \to a } cf(x)=c\lim_{ x \to a } f(x)
$$

4. *Difference*:

$$
\lim_{ x \to a } f(x)-g(x)=\lim_{ x \to a } f(x) \ -\lim_{ x \to a } g(x)
$$

5. *Quotient*:

$$
\lim_{ x \to a } \frac{f(x)}{g(x)}=\frac{\lim_{ x \to a }f(x)}{\lim_{ x \to a } g(x)},\lim_{ x \to a } g(x)\neq0
$$

6. *Exponent*:

$$
\lim_{ x \to a } (f(x))^n=(\lim_{ x \to a } f(x))^n, \ \text{n is a real number}
$$

7. *Root*:

$$
\lim_{ x \to a } \sqrt[n]{ f(x) }=\sqrt[n]{ \lim_{ x \to a } f(x) }, \,\text{if n is even, }\,\lim_{ x \to a } f(x)\geq0
$$

##### Example(s):
A.

$$
\lim_{ x \to 4 } \frac{x^{2}-3x+6}{x^{3}+\sqrt{ x^{3} }}\to \frac{\lim_{ x \to 4 }(x^{2}-3x+6)}{\lim_{ x \to 4 } (x^{3}+x^{3/2})}=\dots=\frac{4^{2}-3(4)+6}{4^{3}+4^{3/2}}=\frac{10}{72}
$$

why tf did we do this mess
### Direct Substitution
If $f(x)$ is a polynomial or a rational function and $x=a$ is in its domain, then

$$
\lim_{ x \to a } f(x)=f(a)
$$

If $f(x)=g(x)$ except at $x=a$, then

$$
\lim_{ x \to a } f(x)=\lim_{ x \to a } g(x)
$$
##### Example(s):
A. 

$$
\lim_{ x \to 1 } \frac{x^{2}-1}{x-1}=\lim_{ x \to 1 } x+1=2
$$

B.

$$
\lim_{ x \to 2 } \frac{x^{2}+x-6}{x^{2}-5x+6}=\lim_{ x \to 2 } \frac{\cancel{ (x-2) }(x+3)}{\cancel{ (x-2) }(x-3)}=\lim_{ x \to 2 } \frac{x+3}{x-3}=-5
$$

C. 

$$
f(x)=
\begin{cases}
\sqrt{ x-2 } & x>2 \\
4-2x & x<2
\end{cases}
$$

$$
\begin{align}
\lim_{ x \to 2^+ } f(x)=\sqrt{ x-2 }=0 \\
\lim_{ x \to 2^- } f(x)=4-2x=0
\end{align}
$$


### Squeeze Theorem
**

Suppose $f(x)\leq g(x)\leq h(x)$ for all $x$ near $a$, except possibly at $x=a$. If $\lim_{ x \to a }f(x)=\lim_{ x \to a }h(x)=L$, then $\lim_{ x \to a }g(x)=L$
![[Pasted image 20260901111227.png]]

##### Example(s):
A.
$$
\lim_{ x \to 0 } x^{2}\sin\left( \frac{1}{x} \right)
$$
We know $-1\leq \sin\left( \frac{1}{x} \right)\leq1$ for all $x\neq0$. We also know that $x^{2}>0$ for all $x\neq0$, so we can multiply an ineq. by $x^{2}$ without changing the direction. This gives $-x^{2}\leq x^{2}\sin\left( \frac{1}{x} \right)\leq x^{2}$, so
$$
\lim_{ x \to 0 } x^{2}\sin\left( \frac{1}{x} \right)=0
$$

