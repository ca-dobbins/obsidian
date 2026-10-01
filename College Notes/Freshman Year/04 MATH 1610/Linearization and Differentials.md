# Topic: 3.10
Date: 2026-10-01
Suggest HW: 1-4, 11-39
### Linearization
*subtitle*
Consider $f(x)=\sqrt{ x }$. Sometimes we can compute this really easy, ex. $f(4)=\sqrt{ 4 }=2$. How about $\sqrt{ 4.05 } \;\text{or}\,\sqrt{ 3.98 }$? We can use the tangent line at $x=4$ to approximate these values. 
$$
f'(4)=\frac{1}{2\sqrt{ 2 }}=\frac{1}{4}
$$
Therefore tangent line is $y=\frac{x}{4}+1$. We can say that if $x\approx4$, then $\sqrt{ x }\approx \frac{x}{4}+1$.

The line tangent to the curve $f(x)$ at $x=a$ is:
$$
L(x)=f'(a)(x-a)+f(a)
$$
Which is known as the linearization of $f(x)$ at $a$.
##### Example(s):

### Differential
*subtitle*
***Def***: Let $y=f(x)$, then the differential of $y$, written as $dy$, is defined to be:
$$
dy=f'(x)dx
$$

##### Example(s):
A. $y=\sqrt{ x }$
$$
dy=\frac{1}{2\sqrt{ x }}dx
$$
For $\sqrt{ 4.05 }$, which is $x=4$ and $dx=0.05$:
$$
dy=\frac{1}{2\sqrt{ 4 }}(.05)=0.0125
$$
And plugging in:
$$
\sqrt{ 4.05 }\approx f'(4)+(0.0125)
$$
### Main Idea 3
*subtitle*

##### Example(s):
