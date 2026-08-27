# Topic: 2.3  
Date: 2026-08-27
Suggested HW: 1-34, 39-48, 52-54
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
*subtitle*

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
\lim_{ x \to 2 } \frac{x^{2}+x-6}{x^{2}-5x+6}=\lim_{ x \to 2 } 
$$