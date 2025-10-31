---
tags:
  - physics
  - classicalmechanics
  - ee
aliases:
  - Electric Flux
  - Electric Field Flux
  - ΦE
---
# Definition
**Electric flux** ($\Phi_E$) measures the **total electric field** $\vec{E}$ passing **through a surface**.  
It represents how much electric “field flow” penetrates that area.

> [!NOTE] Unit!
> Electric flux has units of **volt·meters (V·m)** or equivalently **N·m²/C**.

---

# Formula
For any surface $S$:
$$
\Phi_E = \iint_S \vec{E} \cdot d\vec{A}
$$
Where  
- $\Phi_E$ is the **Electric Flux**  
- ∬ is the [[Surface Integral]] (means integrate over an entire surface)
- $\vec{E}$ is the **[[Electric Field (E)|Electric Field]]** (V/m)  
- $d\vec{A}$ is the **Area Vector**, normal to the surface (m²)  

---
# Physical Meaning
- Flux depends on **how the field lines intersect the surface**.  
- If the field is perpendicular, flux is **maximal**.  
- If parallel, flux is **zero**.  
- For a **closed surface**, the **net electric flux** is proportional to the **enclosed charge**.

---

# Gauss' Law Connection
[[Gauss' Law for Electricity]] relates electric flux through a closed surface to the **total enclosed free charge**:
$$
\underset{ S \;}{ {\rlap{\mspace{1mu} \boldsymbol{\bigcirc}}{\rlap{\int}{\;\int}}} } 
\text{ } \vec{E} \cdot d\vec{A} = \frac{Q_{\text{enc}}}{\varepsilon_0}
$$

Where  
Where:
- ∯ is the [[Closed Surface Integral]] (means integrate over an entire closed surface)
- $S$ is the surface you are integrating over
- $\vec{E}$ is the [[Electric Field Vector]]
- $d\vec{A}$ is the [[Infinitesimal]] Vector Element of Surface Area- $Q_{\text{enc}}$ is the **enclosed charge** (C)  
- $\varepsilon_0$ is the **[[Electric Permittivity of Free Space (ε0)]]** (F/m)  
- $Q_{enc}$ is the Total [[Electric Charge (q)|Charge]] enclosed within the Surface

This is the **integral form** of Gauss’ Law — one of [[Maxwell's Equations]].

---

# Magnetic Analog
The magnetic analog is **[[Magnetic Flux (ΦB)|Magnetic Flux]] ($\Phi_B$)**, defined for $\vec{B}$ instead of $\vec{E}$.

> [!HELP] Key Difference  
> Electric flux can be **nonzero** for enclosed charge.  
> Magnetic flux through any closed surface is **always zero**, because magnetic monopoles do not exist.

---

**Related:**  
- [[Flux]]  
- [[Electric Field (E)]]  
- [[Gauss' Law for Electricity]]  
- [[Electric Permittivity (ε)]]  
- [[Magnetic Flux (ΦB)|Magnetic Flux]]  
- [[Maxwell's Equations]]

