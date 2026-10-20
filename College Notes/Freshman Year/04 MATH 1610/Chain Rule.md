# Topic: 3.4
Date: 2026-09-17
Suggested HW: 1-60, 65-71, 76-80
### Idea of the Chain Rule
*subtitle*
how do we find $\frac{d}{dx}\sqrt{ x^{3}+x }$?
Let $f(x)=\sqrt{ x^{3}+x }$. It turns out $f(x)$ is a composition of two functions. So $f(u)=\sqrt{ u }$ and $u=x^{3}+x$; meaning $f(x)=f(u(x))$.

$$
\begin{array}{l} \\
f(u)=\sqrt{ u } & u=x^{3}+x \\
f'(u)=\frac{1}{2}u^{-1/2} & u'(x)=3x^{2}+1
\end{array}
$$
***Def***: Suppose $f(x)$ and $g(x)$ are differentiable functions. Then:
$$
\frac{d}{dx}f(g(x))=f'(g(x))g'(x)
$$
or:
$$
\frac{dy}{dx}=\frac{dy}{du}\cdot \frac{du}{dx}  
$$
So the derivative of $\frac{d}{dx}\sqrt{ x^{3}+x }$ is:
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
### Going Further
*subtitle*
***Power-Chain***

$$
\frac{d}{dx}u^n=n u^{n-1}\frac{du}{dx}
$$
***Nested Chain***

$$
\frac{d}{dx}u(g(x))=u'(g(x))\frac{dg}{dx}  
$$
***Exponentials***
$$
\frac{d}{dx}b^u=b^u\ln(b)\frac{du}{dx}  
$$
