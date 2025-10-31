---
tags:
  - math
aliases:
  - ⋅
---
The dot product is a fundamental way we can combine two vectors. Intuitively, it tells us how aligned on unaligned two vectors are, with positive being closer to the same direction, 0 being perpendicular, and negative being closer to opposite directions.

## Definition and Intuition
We write the dot product with a little dot ⋅ between the two vectors (pronounced "a dot b"):

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mrow data-mjx-texclass="ORD">
    <mover accent="true" accentunder="false">
      <mrow>
        <mi>a</mi>
      </mrow>
      <mo stretchy="false">→</mo>
    </mover>
  </mrow>
  <mo>⋅</mo>
  <mrow data-mjx-texclass="ORD">
    <mover accent="true" accentunder="false">
      <mrow>
        <mi>b</mi>
      </mrow>
      <mo stretchy="false">→</mo>
    </mover>
  </mrow>
  <mo>=</mo>
  <mo data-mjx-texclass="ORD" fence="false" stretchy="false">‖</mo>
  <mrow data-mjx-texclass="ORD">
    <mover accent="true" accentunder="false">
      <mrow>
        <mi>a</mi>
      </mrow>
      <mo stretchy="false">→</mo>
    </mover>
  </mrow>
  <mo data-mjx-texclass="ORD" fence="false" stretchy="false">‖</mo>
  <mo data-mjx-texclass="ORD" fence="false" stretchy="false">‖</mo>
  <mrow data-mjx-texclass="ORD">
    <mover accent="true" accentunder="false">
      <mrow>
        <mi>b</mi>
      </mrow>
      <mo stretchy="false">→</mo>
    </mover>
  </mrow>
  <mo data-mjx-texclass="ORD" fence="false" stretchy="false">‖</mo>
  <mi>cos</mi>
  <mo data-mjx-texclass="NONE">⁡</mo>
  <mo stretchy="false">(</mo>
  <mi>θ</mi>
  <mo stretchy="false">)</mo>
</math>
If we break this down factor by factor, the first two are $|\vec{a}|$ and $|\vec{b}|$. These are the magnitudes of $\vec{a}$ and $\vec{b}$, so the dot product takes into account how long the vectors are. The final factor is $\cos(\theta)$, where $\theta$ is the angle between $\vec{a}$ and $\vec{b}$.  This tells us the dot product has to do with direction.

Specifically, when $\theta = 0$, the two vectors point in exactly the same direction. Not accounting for vector magnitudes, this is when the dot product is at its largest, because $\cos(0) = 1]$. In general, the more two vectors point in the same direction, the bigger the dot product between them will be.

![](https://cdn.kastatic.org/ka-perseus-graphie/0e3ec3ecd9c28ab9a809a780f613bda99a916189.svg)


## A better way to compute the dot product

When we need to find a dot product in multivariable calculus, we typically have only the coordinates of $\vec{a}$ and $\vec{b}$. Calculating $\| \vec{a} \| \| \vec{b} \| \cos(\theta)$ would force us to find two square roots and a cosine, which is a lot of work! Luckily, there is an easier way. Just multiply corresponding components and then add:

> [!NOTE] A Better Way!
> $$
> \begin{aligned}  
> \vec{a} &= (a_1, a_2, a_3) \\ \\  
> \vec{b} &= (b_1, b_2, b_3) \\ \\  
> \vec{a} \cdot \vec{b} &= a_1b_1 + a_2b_2 + a_3b_3  
> \end{aligned}\
> $$

Although the example above features 3D vectors, this formula extends for vectors of any length.
![A vector diagram is shown on a coordinate plane. The vertical axis is labeled y and ranges from negative 1 to 5, and the horizontal axis is labeled x and ranges from negative 1 to 5. Two vectors, labeled a and b, are drawn from the origin. Vector a points to approximately (2, 4), and vector b points to approximately (5, 2). The magnitude of vector a is labeled as the norm of a, and the magnitude of vector b is labeled as the norm of b. The angle between the two vectors is labeled theta. A third vector, representing b minus a, is drawn from the endpoint of a to the endpoint of b, forming a triangle. The magnitude of b minus a is labeled as the norm of b minus](https://cdn.kastatic.org/ka-perseus-graphie/fc90705cc477962b5b15eff11f1cb7c9efcda8ce.svg)

