---
tags:
  - physics
  - chemistry
aliases:
  - Electric Dipole Moment
  - Dipole Moment
  - p
  - μ
  - Electric Moment
  - p-vector
---
# Definition
The **electric dipole moment** quantifies the **strength and orientation** of a [[Dipole]] consisting of two equal and opposite [[Electric Charge (q)|charges]] separated by a distance. It represents how strongly positive and negative charges are separated and points **from the negative to the positive charge**.

> [!NOTE] Unit!
> Electric dipole moment ($\vec{p}$) has units of **C·m (coulomb-meters)**.

> [!HELP] Magnetic Analog  
> The magnetic analog is the **[[Magnetic Dipole Moment (m)]]**, which describes a current loop or spin dipole in a magnetic field.

## Two Variables
In #chemistry, a dipole moment is often represented by $\mu$, however it is common to use $p$ in #physics.  They can functionally be used interchangeably though. Both are quantities that measure the separation of positive and negative charges in a molecule or system and are calculated by multiplying the magnitude of the charge by the distance of separation:
$$
p = \mu = qd
$$
---
## Two Meanings
When discussing an individual bond, the units of [[Electric Dipole Moment (p)|Dipole Moments]] are often used ($p$ or $\mu$). It describes the strength and orientation of a single electric dipole, however it is much more common to speak of dipoles in terms of [[Vector Field|Vector Fields]], instead using units $\vec{p}$ or $\vec{\mu}$ to describe a "molecular" [[Electric Dipole Moment (p)|Electric Dipole Moment]].  

In reality, speaking in terms of vectors is so often the intended meaning, that the vector notation (the arrow) is usually dropped. Except for a few very specific fields, such as [[Intramolecular]] #chemistry, the vector can be assumed.  

> [!NOTE]
> This sign convention (negative → positive) is used in physics, while the opposite sign convention is sometimes used in chemistry.

---

# Formula
For a simple dipole:
$$
\vec{p} = q \vec{d}
$$
Where  
- $\vec{p}$ — **Electric Dipole Moment Vector** (C·m)  
- $q$ — magnitude of the **[[Electric Charge (q)|Charge]]** (C)  
- $\vec{d}$ — **Displacement Vector** (m) from the negative to positive charge  

### Continuous Charge Distributions
For an extended charge distribution:
$$
\vec{p} = \int \vec{r}\,\rho(\vec{r})\,dV
$$
Where $\rho(\vec{r})$ is the local [[Volume Charge Density (ρ)|Charge Density]] (C/m³).

---

# Potential Energy and Torque
When placed in an external [[Electric Field (E)|Electric Field]], an electric dipole experiences **torque** and **potential energy**:

$$
\vec{\tau} = \vec{p} \times \vec{E}
$$
$$
U = -\vec{p} \cdot \vec{E}
$$

- $\vec{\tau}$ — [[Torque (τ)|Torque]] acting to align $\vec{p}$ with $\vec{E}$  
- $U$ — potential energy of the dipole in the field  

A dipole aligned parallel to $\vec{E}$ has the **lowest potential energy**.

---

# Chemistry Context
In **chemistry**, “dipole moment” *always* refers to the **electric dipole moment** — describing **uneven charge distribution** in molecules or bonds.  

It is often denoted by $\mu$ and measured in **debye (D)**:
$$
1\ \text{D} = 3.336\times10^{-30}\ \text{C·m}
$$

**Examples**
- **H₂O** → large dipole moment → polar molecule  
- **CO₂** → net dipole = 0 → nonpolar molecule  

> [!NOTE]
> The physics convention defines $\vec{p}$ from negative → positive charge.  
> Chemistry sometimes uses the reverse convention.

---

# Relation to Fields
A collection of electric dipoles forms a **[[Electric Polarization Density (P)|Polarization Density]]** field:
$$
\vec{P} = \frac{\sum_i \vec{p}_i}{V}
$$
and affects the total electric displacement field:
$$
\vec{D} = \varepsilon_0 \vec{E} + \vec{P}
$$

---

# Analogs
| Electric Quantity      | Symbol                 | Magnetic Analog                | Symbol    |
| ---------------------- | ---------------------- | ------------------------------ | --------- |
| Electric Dipole Moment | $\vec{p}$              | [[Magnetic Dipole Moment (m)]] | $\vec{m}$ |
| Polarization Density   | $\vec{P}$              | [[Magnetization (M)]]          | $\vec{M}$ |
| Torque                 | $\vec{p}\times\vec{E}$ | $\vec{m}\times\vec{B}$         |           |
| Energy                 | $-\vec{p}\cdot\vec{E}$ | $-\vec{m}\cdot\vec{B}$         |           |

---

**Related:**  
- [[Dipole]]  
- [[Polarization (Matter)]]  
- [[Electric Polarization Density (P)|Polarization Density (P)]]  
- [[Electric Field (E)]]  
- [[Potential Energy (U)]]  
- [[Torque (τ)]]  
- [[Magnetic Dipole Moment (m)]]  
