# Topic: 3.9
Date: 2026-09-29
Suggested HW: 1-33
### Technique
*subtitle*
Steps:
1. Read the problem ***carefully***
2. Draw a picture/diagram
3. Notation: Label the diagram
	1. make sure that everything has a symbol
4. Express given information in terms of chosen notation
5. Note required rate/your unknown as a derivative
6. Find an equation that relates everything
	1. you may need a substitution if they are errant variables
7. Use the [[Chain Rule]] to differentiate the equation with respect to time
8. Solve for the desired rate.

##### Example(s):
Air is being pumped into a spherical balloon so that its volume is increasing at a rate of $100 \frac{cm^{3}}{s}$ How fast is the radius increasing when the diameter of the balloon is $50cm$? 
$r$ is radius
$V$ is volume
$d$ is diameter 
$$
\begin{array}{c}
r=25cm & \frac{dV}{dt}=100 & \text{Find:} \frac{dr}{dt} \\
V=\frac{4}{3}\pi r^{3} \\
\frac{dV}{dt}=4\pi r^{2}\frac{dr}{dt} & \text{so,} & \frac{dr}{dt} =\frac{\frac{dV}{dt}}{4\pi r^{2}} \\
 & =\frac{1}{25\pi} \frac{cm}{s} 
\end{array}
$$

### Substituting
*subtitle*
A water tank has the shape of an inverted circular cone with base diameter and the height are 4m. Water is pumped in at a rate of $2 \frac{m^{3}}{min}$. How fast is the water level rising when the water is 3m deep?
$r$ is water base radius
$h$ is water depth
$V$ is water volume 
$$
\begin{array}{c}
\text{Given:}  & h=3 & \frac{dV}{dt}=2 \\
\text{Find:} & \frac{dh}{dt}  \\
\text{Equation} & V=\frac{1}{3}\pi r^{2}h 
\end{array}
$$
however we don't know $\frac{dr}{dt}$, so we should replace $r$ in terms of $h$. And drawing a picture (put the picture here) reveals similar triangles 
$$
\frac{r}{h}=\frac{2}{4}\to r=\frac{1}{2}h
$$
So, 
$$\begin{array}{}
V=\frac{\pi}{12}h^{3} & \frac{dV}{dt}=\frac{\pi}{4}h^{2}\frac{dh}{dt} \\
\text{Find:}\frac{dh}{dt} & \frac{dh}{dt}=\frac{8}{9\pi}    
\end{array}
$$
##### Example(s):

### Main Idea 3
*subtitle*
##### Example(s):
