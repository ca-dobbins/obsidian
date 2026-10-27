# Topic: 2.6
Date: 2026-09-01 | Suggested HW: 1-10, 13-42, 47-52
### Inf
Suppose:

$$
f(x)=\frac{x^{2}-1}{x^{2}+1}
$$

How does this behave far away from $x=0$ (basically $\lim_{ x \to \pm\infty }$)?

Looks like $f(x)$ approaches $1$ as $x$ grows very large

$$
\begin{align}
\lim_{ x \to \infty } f(x)=1 \\
\lim_{ x \to -\infty } f(x)=1
\end{align}
$$

***Def***: Let $f(x)$ be defined on $(a,\infty)$. If the values of $f(x)$ can be made arbitrailiy close to $L$ by choosing sufficiently large values of $x$, we say:

$$
\lim_{ x \to \infty } f(x)=L
$$

Similarly for $x\to-\infty$.
### Asymptotes
***Def***: The line $y=L$ is a horizontal asymptote for $f(x)$ if either $\lim_{ x \to \infty }f(x)=L$ or $\lim_{ x \to -\infty }f(x)=L$

How many asymptotes can there be?

| Vertical             | Horizontal |
| -------------------- | ---------- |
| As many as necessary | At most 2  |

A graph *can* touch it's asymptotes:


$$
f(x)
\begin{cases}
\frac{1}{x} & x<0 \\
3 & x\geq0
\end{cases}
$$

y=0 is a H.A since: $\lim_{ x \to -\infty }f(x)=0$

y=3 is a H.A since: $\lim_{ x \to \infty }f(x)=3$

***Building Blocks***

$$
\begin{align}
\text{Constant:}\lim_{ x \to \pm \infty } c=c \\
\text{Reciprocal:}\lim_{ x \to \pm \infty } \frac{1}{x}=0 \\
\text{If}\, r>0,\, \text{then}\lim_{ x \to \pm \infty} \frac{1}{x^r}=0 
\end{align}
$$

***Defs***: If $f(x)$ grows w/o bound as $x$ grows large, we say $\lim_{ x \to \infty } f(x)=\infty$. Similarly large and negative.
##### Example(s):
A.
$$
f(x)=x^{2}
$$
no asymptotes

B.
$$
g(x)=\frac{1}{x}
$$
$y=0$ is a vertical asymptote

C.
$$
h(x)=e^x
$$
$x=0$ is a horizontal asymptote

D.
$$
t(x)=\arctan(x)
$$
$y=\pm \frac{\pi}{2}$ are vertical

E.
$$
\lim_{ x \to -\infty } \frac{3x^{2}-x+2}{5x^{2}-5x+3} \times \left( \frac{\frac{1}{x^{2}}}{\frac{1}{x^{2}}} \right)=\frac{3}{5}
$$
F.
$$
f(x)=e^x
$$

$$
\begin{align}
\lim_{ x \to -\infty } e^x = 0 \\
\lim_{ x \to \infty } e^x = \infty
\end{align}
$$
