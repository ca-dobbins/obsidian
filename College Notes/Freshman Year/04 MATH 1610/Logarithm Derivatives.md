# Topic: 3.6
Date: 2026-09-24
Suggested HW: 1-40, 45-58, 63-78
### Basics
*subtitle*
Suppose $y=\log_{b}x$, $(b>0)$. What is $\frac{dy}{dx}$? This is equivalent to $x=b^y$ which is another implicit function.
$$\large\begin{array}{c}
b^y\ln(b)\frac{dy}{dx}=1 \\ 
\frac{dy}{dx}=\frac{1}{x\ln b} 
\end{array} 
$$
***Def***:

$$
\frac{d}{dx}\log_{b}u=\frac{1}{u\ln b}\frac{du}{dx}  
$$
More specifically:
$$
\frac{d}{dx}\ln(u)=\frac{1}{u}\frac{dy}{dx}  
$$
##### Example(s):

$$
\frac{d}{dx}\log_{2}(x^{3}+\cos x)=\frac{3x^{2}-\sin x }{(x^{3}+\cos x)\ln2}
$$

$$
\frac{d}{dx}\ln(x^{2}+\arctan x)=\frac{2x+\frac{1}{1+x^{2}}}{x^{2}+\arctan x} 
$$


### Log Differentiation
*subtitle*
Recall Log Rules:
1. $\ln(ab)=\ln (a)+\ln (b)$
2. $\ln\left( \frac{a}{b} \right)=\ln(a)-\ln(b)$
3. $\ln(a^b)=b\ln(a)$
To make a disgusting log function easier, just use the log rules to split it up and make it easier.
$$
\begin{array}{c} \\
\large
\ln\left( \frac{x^{2}+1}{\sqrt{ x^{3}-1 }} \right)=\ln(x^{2}+1)-\ln(\sqrt{ x^{3}-1 }) \\
\Large=\frac{2x}{x^{2}+1}-\frac{1}{2}\left( \frac{3x^{2}}{x^{3}-1} \right)
\end{array}
$$
or, alternatively for a regular function, take the log of both sides and use log rules to clean it up.
##### Example(s):

$$
y=\frac{(x^{2}+x)^5\sqrt[7]{ x^{3}+\tan x }}{(\csc ^{2}(x))(6^{\sin x})}\;|\;\ln y=\left( \ln(x^{2}+x^5)+\frac{1}{7}\ln(x^{3}+\tan x) \right)-(\ln (\csc ^{2}(x))+\sin x\ln6)
$$

### Main Idea 3
*subtitle*

##### Example(s):
