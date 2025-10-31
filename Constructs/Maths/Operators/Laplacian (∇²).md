---
tags:
  - math
  - physics
aliases:
  - Laplacian
  - ∇²
  - "`"
---
# Definition
The **Laplacian operator** ($\nabla^2$) measures how a scalar or vector field diverges from its local average. It appears in [[Poisson’s Equation]], [[Wave Equation]], and [[Diffusion Equation]].

> [!NOTE] Unit!
> The Laplacian has units of the **quantity divided by meters squared (1/m²)**.

**Related:**  
- [[Gradient]]  
- [[Divergence Operator]]  
- [[Poisson’s Equation]]  
- [[Wave Equation]]  

---

## Formula
For a scalar field $\phi(x,y,z)$:
$$
\nabla^2 \phi = \frac{\partial^2 \phi}{\partial x^2} + \frac{\partial^2 \phi}{\partial y^2} + \frac{\partial^2 \phi}{\partial z^2}
$$

In vector form:
$$
\nabla^2 \vec{A} = \nabla(\nabla \cdot \vec{A}) - \nabla \times (\nabla \times \vec{A})
$$
