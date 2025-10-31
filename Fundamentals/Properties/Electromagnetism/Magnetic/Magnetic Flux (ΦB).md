---
tags:
  - physics
  - classicalmechanics
  - ee
aliases:
  - ΦB
  - Magnetic Field Flux
  - Magnetic Flux
  - B-Flux
---
# Definition
**Magnetic flux** ($\Phi_B$) measures the **total [[Magnetic Field (B)|Magnetic Field]]** $\vec{B}$ passing **through a surface**.  
It quantifies the amount of magnetic field lines that cross a given area.

> [!NOTE] Unit!
> Magnetic flux has units of **webers (Wb)**, where **1 Wb = 1 T·m²**.

---

# Formula
For any surface $S$:
$$
\Phi_B = \iint_S \vec{B} \cdot d\vec{A}
$$
Where  
- $\Phi_B$ is the **Magnetic Flux** (Wb)  
- ∬ is the [[Surface Integral]] (means integrate over an entire surface)
- $\vec{B}$ is the **[[Magnetic Field (B)|Magnetic Flux Density]]** (T)  
- $d\vec{A}$ is the **[[Area Vector]]**, normal to the surface (m²)

---
# Physical Meaning
- Magnetic flux indicates how much **magnetic field** passes through an area.  
- It’s highest when the field is perpendicular to the surface and zero when parallel.  
- If $\Phi_B$ changes over time, it induces an **[[Electromotive Force (EMF)]]**, according to **[[Faraday's Law of Induction]]**.

---

# Gauss' Law Connection
According to [[Gauss' Law for Magnetism]]:
$$
\underset{ S \;}{ {\rlap{\mspace{1mu} \boldsymbol{\bigcirc}}{\rlap{\int}{\;\int}}} } 
\text{ } \vec{B} \cdot d\vec{A} = 0
$$
Where:
- ∯ is the [[Closed Surface Integral]] (means integrate over an entire closed surface)
- $S$ is the surface you are integrating over
- $\vec{B}$ is the [[Magnetic Field Vector]]
- $d\vec{A}$ is the [[Infinitesimal]] Vector Element of Surface Area

This means **no net magnetic flux** passes through a closed surface —  
there are **no magnetic monopoles**; magnetic field lines form closed loops.

---

# Electric Analog
The electric analog is **[[Electric Flux (ΦE)|Electric Flux]] ($\Phi_E$)**, defined for $\vec{E}$ instead of $\vec{B}$.

> [!HELP] Key Difference  
> - Electric flux through a closed surface can be **nonzero** (enclosed charge).  
> - Magnetic flux through a closed surface is **always zero** (no monopoles).

---

**Related:**  
- [[Flux]]  
- [[Magnetic Field (B)]]  
- [[Faraday's Law of Induction]]  
- [[Gauss' Law for Magnetism]]  
- [[Electromotive Force (EMF)]]  
- [[Electric Flux (ΦE)|Electric Flux]]  
- [[Maxwell's Equations]]
