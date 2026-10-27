# Topic: 2.2
Date: 2026-08-25 | Suggested HW: 1-12, 15-18, 29-42
### Basic Limits
*getting reeeally close to a value we can't calculate*

Suppose:

$$
f(x)=x^{2}-x+2
$$

Investigate how $f(x)$ behaves near $x=2$

$$
\begin{align}
(1,2)\to(1.99,3.97\dots) \\
(3,8)\to(2.01,4.03\dots)
\end{align}
$$

Looks like $f(x)$ approaches 4 as $x\to 2$.

$$
\lim_{ x \to 2 } x^{2}-x+2=4
$$

***Limit Definition***: Suppose $f(x)$ is defined for all $x$ near $a$, except (possibly) at $x=a$. Then we write:

$$
\lim_{ x \to a } f(x)=L
$$

if the value of $f(x)$ can be made sufficiently close to $L$ by choosing values of $x$ sufficiently close to $a$.

Now,

$$
f(x)=\frac{\sin(x)}{x}
$$

Investigate how $f(x)$ behaves near 0:

$$
(\pm0.1,0.988\dots)
$$

Therefore,

$$
\lim_{ x \to 0 } \frac{\sin(x)}{x}=1
$$
##### Example(s):
A. 

$$
f(x)= \frac{x^{2}-1}{x^{2}+1}
$$

Note: $f(-1)$ DNE, but

$$
\lim_{ x \to -1 } \frac{x^{2}-1}{x^{2}+1}=-2
$$

B.

$$
g(x) = \begin{cases}
\frac{x^{2}-1}{x^{2}+1} & x \neq -1\\
2 &x=-1
\end{cases}
$$
### One-Sided and Infinite Limits
*the juicy stuff*

**Heaviside Function:**

$$
H_{t}(x)=
\begin{cases}
0 & a<t \\
1 & a\geq t
\end{cases}
$$

so, 

$$
\begin{align}
\lim_{ x \to a }H_{t}(x)=0 \quad \text{if a<t} \\
\lim_{ x \to a } H_{t}(x)=1\quad\text{if a>t}
\end{align}
$$

That means $\lim_{ x \to t }H_{t}(x)=DNE$
- This is an example of a ***one-sided limit***

****Definition***: Suppose $f(x)$ is defined for all x near a but smaller than a, except possibly at a. We say that:

$$
\lim_{ x \to a^- } f(x)=L
$$

if $f(x)$ can be made arbitrarily close to L by choosing values of x smaller than a, sufficiently close to a. *right sided limit is similar to left sided limit:*

$$
\lim_{ x \to a^+ } f(x)=L
$$

**Infinite Limits**

Suppose:

$$
f(x)=\frac{1}{x^{2}}
$$

Investigate $x$ near $0$

$$
(\pm 1,1)\to \left( \pm \frac{1}{1000}, 1000000 \right)
$$

So,

$$
\lim_{ x \to 0 } \frac{1}{x^{2}}=\infty
$$

However this does not mean the limit exists. This is saying the limit does not exist, specifically because it grows without bound.
##### Example(s):
A.

$$
\begin{align}
\lim_{ x \to a^- } H_{t}(x)=0  \\
\lim_{ x \to a^+ } H_{t}(x)=1
\end{align}
$$

B.

$$
\lim_{ x \to 0 } -\frac{1}{x^{2}}=-\infty
$$
### Vertical Asymptotes
Where should we look for V.A?
1. places where $f(x)$ is undefined
2. edge cases (ex. edges of domain), changes in a piecewise function
##### Example(s):
A. Find any V.A for $f(x)=\ln(x)$

$$
\text{Domain:}\,(0,\infty),\, \text{check} \, x=0
$$

$$
\lim_{ x \to 0^+ } \ln(x)=-\infty
$$

B. Find all V.A for $f(x)=\tan(x)$

$$
\tan(x)=\frac{\sin(x)}{\cos(x)},\,\text{so we should look where}\,\cos(x)=0
$$

So:

$$
x=\frac{\pi}{2}+k\pi
$$

$$
\begin{align}
\lim_{ x \to \frac{\pi}{2}^+ } \frac{\sin(x)}{\cos(x)} \to \frac{1}{-0.00\dots1}=\frac{1}{0^-}=-\infty\\
\lim_{ x \to \frac{\pi}{2}^- } \frac{\sin(x)}{\cos(x)}\to \frac{1}{0.00\dots 1}=\frac{1}{0^+}=\infty
\end{align} 
$$

C. Find V.A for $g(x)=\frac{x^{2}+1}{x-3}$

$x=3$ is the only undefined input.

$$
\lim_{ x \to 3^- } g(x)\to \frac{10}{0^-}=-\infty
$$