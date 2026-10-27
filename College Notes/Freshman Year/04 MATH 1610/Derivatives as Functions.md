# Topic: 2.8
Date: 2026-09-08 | Suggest HW: 1-31, 47-52
### Taking the Derivative
*thank god*
Let $f(x)=\sqrt{ x }$:

$$
\lim_{ h \to 0 } \frac{\sqrt{ x+h }-\sqrt{ x }}{h} \cdot \left( \frac{\sqrt{ x+h }+\sqrt{ x }}{\sqrt{ x+h }+\sqrt{ x }} \right)=\frac{1}{2\sqrt{ x }}
$$

So that means,

***Def***:

$$
f'(x)=\lim_{ h \to 0 } \frac{f(x+h)-f(x)}{h},
$$

provided the limit exists.

Let $y=f(x)$, all of the following mean the same:

$$
f'(x)=y'=\frac{dy}{dx}=\frac{df}{dx}=\frac{d}{dx}y=\frac{d}{dx}f(x)    
$$

The last two are also known as differential operators, ($Df(x)=D_{x}f(x)$ are also diff operators)
So:
$$
\frac{d}{dx}\sqrt{ x }=\frac{1}{2\sqrt{ x }} 
$$
### Differentiability
*subtitle*

***Non-diff***
1. Corner
2. Cusp
3. Vertical Line
4. Discontinuity

***Theorem***:
	If $f'(a)$ exists, then $f(x)$ must be continuous, at $x=a$. Not necessarily true in reverse.
### Higher Order Derivatives
*subtitle*
Let $f(x)=x^4$. Find $f'(x)$.
$$
f'(x)=\lim_{ h \to 0 } \frac{(x+h)^4-x^4}{h}
$$
![[Pasted image 20260908113840.png]]
So,
$$
f'(x)=4x^{3},
$$
finding it's tangent lines:
$$
f''(x)=\lim_{ h \to 0 } \frac{4(x+h)^{3}-4x^{3}}{h}=12x^{2}
$$
This can continue, so for example, the third derivative:
$$
f'''(x)=24x
$$
Fourth derivative:
$$
f^4(x)=24
$$
Fifth derivative:
$$
f^5(x)=0
$$
