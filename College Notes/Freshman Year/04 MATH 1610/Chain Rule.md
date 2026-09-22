# Topic: 3.4
Date: 2026-09-17
Suggested HW: 1-60, 65-71, 76-80
### Idea of the Chain Rule
*subtitle*
how do we find $\frac{d}{dx}\sqrt{ x^{3}+x }$?
Let $f(x)=\sqrt{ x^{3}+x }$. It turns out $f(x)$ is a composition of two functions. So $f(u)=\sqrt{ u }$ and $u=x^{3}+x$; meaning $f(x)=f(u(x))$.

$$
\begin{align}
f'(u)=\frac{1}{2}u^{-1/2} \\
u'(x)=3x^{2}+1
\end{align}
$$
***Def***: Suppose $f(x)$ and $g(x)$ are differentiable functions. Then:
$$
\frac{d}{dx}f(g(x))=f'(g(x))g'(x)
$$
or:
$$
\frac{dy}{dx}=\frac{dy}{du}\cdot \frac{du}{dx}  
$$
The derivative of $\frac{d}{dx}\sqrt{ x^{3}+x }$ is:
$$
\frac{3x^{2}+1}{2\sqrt{ x^{3}+1 }}
$$

##### Example(s):
A.
$$
f(x)=\sin ^{2}x
$$

$$
\frac{d}{dx}f(x)=2\sin x\cos x 
$$
B.
$$
\frac{d}{dx}\left( \frac{x^{2}}{x^{3}+1} \right)^5 
$$

$$
=\frac{(x^{3}+1)(2x)-x^{2}(3x^{2})}{(x^{3}+1)^{2}}\cdot5\left( \frac{x^{2}}{x^{3}+1} \right)^4
$$
### Main Idea 2
*subtitle*

##### Example(s):

### Main Idea 3
*subtitle*

##### Example(s):
