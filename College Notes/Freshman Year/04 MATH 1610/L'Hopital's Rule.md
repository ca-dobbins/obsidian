# Topic: 4.4
Date: 2026-10-20
Suggest HW: 1-70
### Rule
Suppose $f(x)$ and $g(x)$ are differentiable functions on some interval containing $x=a$ (except possibly at $a$). Suppose $g'(a)\neq 0$. If either:
1. $\lim_{ x \to a }f(x)=\lim_{ x \to a }g(x)=0$ or,
2. $\lim_{ x \to a }f(x)=\pm \infty \;\text{and}\; \lim_{ x \to a }g(x)=\pm \infty$.
Then,
$$
\lim_{ x \to a } \frac{f(x)}{g(x)}=\lim_{ x \to a } \frac{f'(x)}{g'(x)}
$$
##### Example(s): 
$$
\lim_{ x \to 1 } \frac{x^{2}-1}{x-1}=2 \;,\;\lim_{ x \to 0 } \frac{\sin x}{x}=1
$$

### Indeterminate Forms
$\frac{0}{0}$ and $\frac{\infty}{\infty}$ are called indeterminate forms. These are the only forms that L'Hopital's Rule works for. However there are other forms:
1. $\frac{0}{0}$, $\frac{\infty}{\infty}$
2. $0\cdot\pm \infty$
3. $\infty-\infty$
4. $0^0$
5. $\infty^{0}$
6. $1^{\infty}$
Note:
$$
\lim_{ x \to a } f(x)g(x)=\lim_{ x \to a } \frac{f(x)}{\frac{1}{g(x)}}
$$
##### Example(s):
$$
\lim_{ x \to 0^+ } x\ln x = \lim_{ x \to 0^+ } \frac{\ln x}{\frac{1}{x}}
$$

$$
\lim_{ x \to 1^+ } \frac{1}{\ln x}-\frac{1}{x-1}=\lim_{ x \to 1^+ } \frac{(x-1)-\ln x}{(x-1)\ln x}
$$

$$
\lim_{ x \to \infty } e^x-x=\lim_{ x \to \infty } x\left( \frac{e^x}{x}-1 \right)=(\lim_{ x \to \infty } x)\left( \lim_{ x \to \infty } \frac{e^x}{x}-\lim_{ x \to \infty } 1 \right)
$$
