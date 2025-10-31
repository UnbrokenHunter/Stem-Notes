---
tags:
  - math
aliases:
  - Nabla
  - Del
  - ∇
---
A Gradient is a way of packing together all of the [[Partial Derivative]] information of a function. 
# Computation
To compute the gradient of a multivariable function, first you take the [[Partial Derivative]] of all of the variables. Then you pack them together in a vector as such:
$$\begin{aligned}
f(x,y)=x^2\sin(y) \\ \\
\frac{\partial f}{\partial x} = 2x\sin(y) \\
\frac{\partial f}{\partial y} = x^2\cos(y) \\ \\ 
\nabla f(x,y) = \begin{bmatrix}
 2x\sin(y) \\
 x^2\cos(y) \\
\end{bmatrix}
\end{aligned}
$$

Or more generally: 
$$\begin{aligned}
\nabla f = \begin{bmatrix}
 \frac{\partial f}{\partial y} \\
 \frac{\partial f}{\partial y} \\
\end{bmatrix}
\end{aligned}
$$
In a sense, a gradient is a completed partial derivative. **It will always point in the direction of steepest ascent**.