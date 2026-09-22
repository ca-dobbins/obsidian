# Topic: 3.5
Date: 2026-09-22
Suggested HW: 1-36, 39-42
### Basics
*subtitle*
Take the equation $x^{2}+y^{2}=25$, an implicit function, we can either solve for $y$ giving us the equation $y=\pm \sqrt{ 25-x^{2} }$ which is an explicit function now, or we could use implicit differentiation:
$$
\frac{d}{dx}(x^{2}+y^{2})=\frac{d}{dx}25  
$$
taking this derivative gives us
$$
2x+2y\frac{dy}{dx}=0 
$$
...and solving for $\frac{dy}{dx}$:

$$
\frac{dy}{dx}=\frac{-2x}{2y}=\frac{-x}{y}. 
$$
If we take the equation solved for $y$, we get the same derivative:
$$
y'=\pm \frac{1}{2}(25-x^{2})^{-\frac{1}{2}}(2x)
$$
##### Example(s):
A.
$$
\frac{d}{dx} (x^{3}+y^{3})=\frac{d}{dx} 6xy
$$

$$
3x^{2}+3y^{2}\frac{dy}{dx}=\left( 6x\frac{dy}{dx}+6y  \right) 
$$

$$
\frac{dy}{dx}(3y^{2}-6x)=-3x^{2}+6y 
$$

$$
\frac{dy}{dx}=\frac{-3x^{2}+6y}{3y^{2}-6x} 
$$
### Higher Order I.D
*subtitle*
Now let's take the 2nd derivative of the function $x^4+y^4=16$. We first begin by taking the first derivative, and we end up with this equation.

$$
\frac{dy}{dx}=\frac{-x^{3}}{y^{3}} 
$$
Next, we take the derivative of this new equation and we end up with something that looks like this:
$$
\frac{d^2y}{dx^2} =\frac{y^{3}(-3x^{2})+x^{3}\left( 3y^{2}\frac{dy}{dx}  \right)}{y^6}
$$
Now obviously we can't have three variables $\left( x,y,\frac{dy}{dx} \right)$ in the equation when we only started out with two $(x,y)$. So we will plug in the first derivative,
$$
\frac{d^2y}{dx^2}=\frac{-3y^{3}x^{2}+3y^{2}x^{3}\left( -\frac{x^{3}}{y^{3}} \right)}{y^6} 
$$
...but do NOT clean it up unless you're doing a 3rd derivative (for some god forsaken reason).
##### Example(s):

### Inverse Trig
*subtitle*

##### Example(s):
