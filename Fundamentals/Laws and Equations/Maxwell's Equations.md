---
tags:
  - physics
  - ee
  - classicalmechanics
aliases:
---
# Maxwell’s Equations
Maxwell’s equations describe how **electric and magnetic fields** are generated and altered by **[[Electric Charge (q)|charges]]**, **[[Current|currents]]**, and **changes in each other**.  
They exist in two equivalent forms:
- **Differential form** → local behavior (pointwise, using ∇)
- **Integral form** → global behavior (over surfaces or loops)

---
## Gauss’ Law for Electricity
**Differential form:**
$$
\nabla \cdot \vec{D} = \rho \quad \text{or (in free space)} \quad \nabla \cdot \vec{E} = \frac{\rho}{\varepsilon_0}
$$

**Integral form:**
$$
\oint_{S} \vec{D} \cdot d\vec{A} = Q_{\text{enc}} 
\quad \text{or} \quad 
\oint_{S} \vec{E} \cdot d\vec{A} = \frac{Q_{\text{enc}}}{\varepsilon_0}
$$
Where  
- $\vec{E}$ is the [[Electric Field (E)|Electric Field (E)]] (V/m)  
- $\vec{D}$ is the [[Electric Displacement Field (D)|Electric Displacement Field]] (C/m²)  
- $\rho$ is the [[Volume Charge Density (ρ)|Volume Charge Density]] (C/m³)  
- $\varepsilon_0$ is the [[Electric Permittivity of Free Space (ε0)|Vacuum Permittivity]] ($8.854\times10^{-12}$ F/m)  
- $Q_{\text{enc}}$ is the **enclosed [[Electric Charge (q)|Electric Charge]]** (C)  
- $d\vec{A}$ is the **[[Infinitesimal]] [[Area Vector]]** (m²)  

> [!NOTE]
> States that the **total electric flux** through a closed surface equals the **enclosed charge** divided by permittivity.

**Related:** [[Electric Flux (ΦE)]] • [[Volume Charge Density (ρ)]] • [[Electric Field (E)]]

---

## Gauss’ Law for Magnetism
**Differential form:**
$$
\nabla \cdot \vec{B} = 0
$$

**Integral form:**
$$
\oint_{S} \vec{B} \cdot d\vec{A} = 0
$$
Where  
- $\vec{B}$ is the [[Magnetic Field (B)|Magnetic Flux Density]] (T, tesla)  
- $d\vec{A}$ is the **[[Area Vector]]** (m²)

> [!NOTE]
> Indicates that there are **no [[Magnetic Charge (g)|Magnetic Monopole]]** — magnetic field lines are **closed loops**.

**Related:** [[Magnetic Flux (ΦB)]] • [[Magnetic Field (B)]]

---

## Faraday’s Law of Induction
**Differential form:**
$$
\nabla \times \vec{E} = -\frac{\partial \vec{B}}{\partial t}
$$

**Integral form:**
$$
\oint_{C} \vec{E} \cdot d\vec{l} = -\frac{d}{dt} \int_{S} \vec{B} \cdot d\vec{A}
$$
Where  
- $\vec{E}$ is the [[Electric Field (E)|Electric Field (E)]] (V/m)  
- $\vec{B}$ is the [[Magnetic Field (B)|Magnetic Flux Density]] (T)  
- $t$ is **time** (s)  
- $C$ is the **closed loop** bounding the surface $S$  
- $d\vec{l}$ is an **infinitesimal line element** (m)  
- $d\vec{A}$ is the **surface area vector** (m²)

> [!NOTE]
> A **changing magnetic flux** through a surface induces an **electric field** (basis of generators and transformers).

**Related:** [[Electromagnetic Induction]] • [[Magnetic Flux (ΦB)]] • [[Faraday’s Law]]

---

## Ampère–Maxwell Law
**Differential form:**
$$
\nabla \times \vec{H} = \vec{J} + \frac{\partial \vec{D}}{\partial t} 
\quad \text{or (in free space)} \quad
\nabla \times \vec{B} = \mu_0 \left( \vec{J} + \varepsilon_0 \frac{\partial \vec{E}}{\partial t} \right)
$$

**Integral form:**
$$
\oint_{C} \vec{H} \cdot d\vec{l} = I_{\text{enc}} + \frac{d}{dt} \int_{S} \vec{D} \cdot d\vec{A}
$$
Where  
- $\vec{H}$ is the [[Magnetic Field Intensity]] (A/m)  
- $\vec{B}$ is the [[Magnetic Field (B)|Magnetic Flux Density]] (T)  
- $\vec{J}$ is the [[Displacement Current|Current Density]] (A/m²)  
- $\vec{D}$ is the [[Electric Displacement Field (D)|Electric Displacement Field]] (C/m²)  
- $\mu_0$ is the [[Magnetic Permeability of Free Space (μ0)|Vacuum Permeability]] ($4\pi \times 10^{-7}$ H/m)  
- $\varepsilon_0$ is the [[Electric Permittivity of Free Space (ε0)|Vacuum Permittivity]] ($8.854\times10^{-12}$ F/m)  
- $I_{\text{enc}}$ is the **enclosed electric [[Current]]** (A)  
- $t$ is **time** (s)  

> [!NOTE]
> The **magnetic field** around a closed path is produced by both **electric current** and **changing electric fields**.  
> This correction by Maxwell allowed electromagnetic waves to exist.

**Related:** [[Displacement Current]] • [[Magnetic Field (H)]] • [[Current Density (J)]]

---

# Summary Table

| Equation             | **Differential Form**                                                   | **Integral Form**                                                                             |
| -------------------- | ----------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| **Gauss (Electric)** | $\nabla \cdot \vec{D} = \rho$                                           | $\oint_S \vec{D} \cdot d\vec{A} = Q_{\text{enc}}$                                             |
| **Gauss (Magnetic)** | $\nabla \cdot \vec{B} = 0$                                              | $\oint_S \vec{B} \cdot d\vec{A} = 0$                                                          |
| **Faraday’s Law**    | $\nabla \times \vec{E} = -\frac{\partial \vec{B}}{\partial t}$          | $\oint_C \vec{E} \cdot d\vec{l} = -\frac{d}{dt} \int_S \vec{B} \cdot d\vec{A}$                |
| **Ampère–Maxwell**   | $\nabla \times \vec{H} = \vec{J} + \frac{\partial \vec{D}}{\partial t}$ | $\oint_C \vec{H} \cdot d\vec{l} = I_{\text{enc}} + \frac{d}{dt}\int_S \vec{D} \cdot d\vec{A}$ |

---

# Special Case: Free Space Simplifications

In **vacuum**:
$$
\vec{D} = \varepsilon_0 \vec{E}, \quad \vec{B} = \mu_0 \vec{H}
$$

Then Maxwell’s equations become:
$$
\begin{align}
\nabla \cdot \vec{E} &= \frac{\rho}{\varepsilon_0} \\
\nabla \cdot \vec{B} &= 0 \\
\nabla \times \vec{E} &= -\frac{\partial \vec{B}}{\partial t} \\
\nabla \times \vec{B} &= \mu_0 \left( \vec{J} + \varepsilon_0 \frac{\partial \vec{E}}{\partial t} \right)
\end{align}
$$
