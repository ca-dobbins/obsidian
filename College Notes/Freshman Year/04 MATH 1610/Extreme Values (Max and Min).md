# Topic: 4.1
Date: 2026-10-13
Suggested HW: 1-48, 57-66
### Max & Min
*subtitle*

***Def***: Let $c$ be a # in the domain $D$ of $f$. Then $f(c)$ is:
- the abs max of $f$ if $f(c)\geq f(x)$ for all $x$ in $D$
- the abs min of $f$ if $f(c)\leq f(x)$ for all $x$ in $D$
- a local max of $f$ if $f(c)\geq f(x)$ for all $x$ *near* $c$
- a local min of $f$ if $f(c)\leq f(x)$ for all $x$ *near* $c$
	*near* being some interval in $D$ containing $C$

These can be called *extreme* values, with the plural being **extrema**. The pluralization of *maximum* and *minimum* is **maxima** and **minima** respectively.

Every absolute extreme value is also a local extreme value, *UNLESS* it's at an endpoint. Endpoints cannot be local extrema.
##### Example(s):
$f(x)=\sin x$
The absolute max is $1$, occurring at $x=\frac{\pi}{2}+2k\pi$
The absolute min is $-1$, occurring at $x=-\frac{\pi}{2}+2k\pi$

### The Extreme Value Theorem (EVT)
*subtitle*

***Def***: If $f$ is continuous on a closed interval $[a,b]$, then $f$ must attain both an abs max $f(c)$ and an abs min of $f(d)$ for some $c,d$ in $[a,b]$.

However if the domain is not closed $f(x)=\frac{1}{x},\;(0,2)$, looking at the graph of $\frac{1}{x}$, there is no abs max (because $0^+$ goes to $\infty$) and there is no abs min (because $2$ is not defined).

As well, if the function $f$ is not continuous,
$$f(x)=
\begin{cases}{}
\frac{1}{x} & x\neq0 \\
0 & x=0
\end{cases}
$$
the example has no extrema.

##### Example(s):
$g(x)=x^{2}, \;-1\leq x\geq3$
has an abs max of $9$ when $x=3$
has an abs min of $0$ when $x=0$


### Fermat's Theorem
*subtitle*

***Def***: If $f$ has a local extreme value at $x=c$
##### Example(s):
