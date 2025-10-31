---
tags:
  - math
aliases:
  - ⨯
---
The cross product is a fundamental way we can combine two vectors. Intuitively, it tells us the area of the parallelogram formed by the vectors. It gives back a vector with the magnitude of this area, in a direction that is 90° from both original vectors.  

## Definition and Intuition
We write the cross product between two vectors as $\vec{a} \times \vec{b}$ (pronounced "a cross b"). Unlike the dot product, which returns a number, the result of a cross product is another vector. Let's say that $\vec{a} \times \vec{b} = \vec{c}$. This new vector $\vec{c}$ has two special properties.

First, it is perpendicular to both $\vec{a}$ and $\vec{b}$. Phrasing this in terms of the dot product, we could say that $\vec{c} \cdot \vec{a} = \vec{c} \cdot \vec{b} = 0$. This property alone makes the cross product quite useful. 

> [!NOTE]
> This is also why the cross product ==only works in three dimensions==. In 2D, there isn't always a vector perpendicular to any pair of other vectors. In ==four and more dimensions, there are infinitely many== vectors perpendicular to a given pair of other vectors.  
> 

Second, the length of $\vec{c}$ is a measure of how far apart $\vec{a}$ and $\vec{b}$ are pointing, augmented by their magnitudes:
$$\|\vec{c}\| = \|\vec{a}\| \|\vec{b}\| \sin(\theta)$$
It's similar to the dot product, but instead of $\cos(\theta)$ the cross product uses $\sin(\theta)$, where $\theta$ is the angle between $\vec{a}$ and $\vec{b}$. That way, when the angle is $90^\circ$, the cross product is at its largest. In this sense, the dot product and the cross product complement each other.  

There's one interpretation of the length of $\vec{c}$ that is particularly useful. Think of the parallelogram formed by $\vec{a}$ and $\vec{b}$. The base of this parallelogram has length $\|\vec{a}\|$, and the height has length $\|\vec{b}\| \sin(\theta)$. That means the **area of the parallelogram** in total is precisely the magnitude of the cross product.

![[Cross Products-20251028113905316.png|296x221]]![[{59793A86-CE38-4C04-9A6E-84C24C21ABE0}.png|257x195]]

## The Right Hand Rule
Notice that in the image above, the cross product is perpendicular to $\vec{a}$ and $\vec{b}$, as expected. But there are actually **two** vectors that could be perpendicular to $\vec{a}$ and $\vec{b}$. If $\vec{c} = \vec{a} \times \vec{b}$, then these two choices are $\vec{c}$ and $-\vec{c}$. How do we decide which of the two perfectly valid choices is *the* cross product?

We have a convention called the **right-hand rule** to resolve this ambiguity:  If you hold up your right hand, point your **index finger** in the direction of $\vec{a}$, and your **middle finger** in the direction of $\vec{b}$, then your **thumb** will point in the direction of $\vec{a} \times \vec{b}$.
![[Cross Products-20251028114335988.png|276x250]]
## Formula
$$\begin{aligned}
\vec{a} &= (a_1, a_2, a_3) \\ \\
\vec{b} &= (b_1, b_2, b_3) \\ \\
\vec{a} \times \vec{b} &= \begin{bmatrix}
a_2b_3 - a_3b_2 \\ \\
a_3b_1 - a_1b_3 \\ \\
a_1b_2 - a_2b_1
\end{bmatrix}
\end{aligned}
$$

