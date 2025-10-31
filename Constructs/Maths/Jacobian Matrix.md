---
tags:
  - math
aliases:
  - Jacobian
---
# Definition
The Jacobian Matrix (or simply Jacobian) of a vector-valued function $𝑓 : \mathbb R^n \rightarrow \mathbb R^𝑚$ is the matrix of first-order partial derivatives. It describes how small changes in the input vector $\vec{x} = (x_{1},x_{2}, \dots,x_{n})$ affect changes in the output vector $\vec{f}=(f_{1},f_{2},\dots,f_{m})$. In other words, it takes in a vector of multivariable functions, and returns a [[Matrix]], denoted $J_{f}$, contains all of the local linear approximations of the function it applies to.  

Mathematically, 
$$
J_f(x) =
\begin{bmatrix}
\frac{\partial f_1}{\partial x_1} & \cdots & \frac{\partial f_1}{\partial x_n} \\
\vdots & \ddots & \vdots \\
\frac{\partial f_m}{\partial x_1} & \cdots & \frac{\partial f_m}{\partial x_n}
\end{bmatrix}
$$

It is constructed by finding the first [[Partial Derivative]] of each variable, with respect to each variable, and placing them in a Matrix as such: 
$$
\begin{align}
f(x)=\begin{bmatrix}
f_{1}(x_{1},x_{2}) \\
f_{2}(x_{1},x_{2}) \\
\end{bmatrix} =
\begin{bmatrix}
x_{1}^2+x_{2} \\
x_{1}+x_{2}^2
\end{bmatrix}
\\ \\

J_{f} = \begin{bmatrix}
\frac{\partial f_{1}}{\partial x_{1}} &
\frac{\partial f_{1}}{\partial x_{2}} \\
\frac{\partial f_{2}}{\partial x_{1}} &
\frac{\partial f_{2}}{\partial x_{2}}
\end{bmatrix} =
\begin{bmatrix}
2x_{1} & 1 \\
1 & 2x_{2}
\end{bmatrix}
\end{align}
$$
## Usage
By analyzing the Jacobian, you can observe how a function will behave locally around a given point. 
