---
tags:
  - math
aliases:
---
# Definition
When we interpret matrices as movement, there is a sense in which some matrices stretch space out and others squeeze it in. This scaling factor has a name: the [[Determinant]]. If a matrix stretches things out, then its determinant is greater than 1. If a matrix doesn't stretch things out or squeeze them in, then its determinant is exactly 1. 

Some matrices shrink space so much they actually flatten the entire grid on to a single line. This happens whenever a matrix maps the unit vectors $\color{\lightblue}{\hat{ \imath}}$ and $\color{\pink}{\hat{\jmath}}$ to be multiples of each other, lying on the same line. These matrices have a determinant of 0.

Even though determinants represent scaling factors, they are not always positive numbers. The sign of the determinant has to do with the orientation of $\color{\lightblue}{\hat{\imath}}$ and $\color{\pink}{\hat{\jmath}}$. If a matrix flips the orientation, then its determinant is negative. Notice how $\color{\lightblue}{\hat{\imath}}$ is on the left of $\color{\pink}{\hat{\jmath}}$ in the image below, when normally it is on the right of $\color{\pink}{\hat{\jmath}}$.

One last important note is that the determinant only makes sense for square matrices. That's because square matrices move vectors from $n$-dimensional space to $n$-dimensional space, so we can talk about volume changing. For non-square matrices, linear algebra has the concepts of null space and range, but they are not multivariable calculus topics. All the formulas in the next section require a matrix with the same number of rows as columns.

## Formula
$$
\det\!\left(
\begin{bmatrix}
\color{\lightblue}{a} & \color{\pink}{b} \\
\color{\lightblue}{c} & \color{\pink}{d}
\end{bmatrix}
\right)
=
\left|
\begin{array}{cc}
\color{\lightblue}{a} & \color{\pink}{b} \\
\color{\lightblue}{c} & \color{\pink}{d}
\end{array}
\right|
$$
For the [[Matrix]] above, the determinant would be calculated as follows:
$$
\det\!\left(
\begin{bmatrix}
\color{\lightblue}{a} & \color{\pink}{b} \\
\color{\lightblue}{c} & \color{\pink}{d}
\end{bmatrix}
\right)
=\color{\lightblue}{a} \color{\pink}{d} - \color{\pink}{b} \color{\lightblue}{c}

$$

