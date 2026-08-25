# Topic: 2.2
Date: 2026-08-25
Suggested HW: 1-12, 15-18, 29-42
### Limits
*getting reeeally close to a value we can't calculate*
Suppose:
$$
f(x)=x^{2}-x+2
$$
Investigate how $f(x)$ behaves near $x=2$
$$
(1,2)\to(1.99,3.97\dots)
$$

$$
(3,8)\to(2.01,4.03\dots)
$$
Looks like $f(x)$ approaches 4 as $x\to 2$.
$$
\lim_{ x \to 2 } x^{2}-x+2=4
$$
Definition:
- Suppose $f(x)$ is defined for all x near a, except (possibly) at x=a. Then we write:
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
**Heaviside Function:**

$$
H_{t}(x)=0,x<t|1,x\geq t
$$
so, 
$$
\lim_{ x \to a }H_{t}(x)=0 ||\text{if a<t}
$$

$$
\lim_{ x \to a } H_{t}(x)=1||\text{if a>t}
$$
That means $\lim_{ x \to t }H_{t}(x)=DNE$
- This is an example of a ***one-sided limit***

Definition:
- Suppose $f(x)$is defined for all x near a but smaller than a, except possibly at a. We say that:
$$
\lim_{ x \to a^- } f(x)=L
$$
	if $f(x)$ can be made arbitrarily close to L by choosing values of x smaller than a, sufficiently close to a.
	*right sided limit is similar to left sided limit*
$$
\lim_{ x \to a^+ } f(x)=L
$$

##### Examples:
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
g(x)={\frac{x^{2}-1}{x^{2}+1}}
$$
C.
$$

$$
### Main Idea 2
*subtitle*

##### Examples: