---
tags:
  - physics
  - classicalmechanics
  - ee
aliases:
  - Magnetic Dipole Moment
  - m
  - Magnetic Moment
---
# Definition
The **magnetic dipole moment** quantifies the **strength and orientation** of a [[Dipole|Magnetic Dipole]] — a circulating current loop or aligned electron spins — that produces a magnetic field resembling that of an [[Electric Dipole Moment (p)|electric dipole]].

It indicates how strongly the dipole interacts with an external [[Magnetic Field (B)|Magnetic Field]] and the direction of that interaction.

> [!NOTE] Unit!
> Magnetic dipole moment ($\vec{m}$) has units of **A·m² (ampere-square-meters)**.

> [!HELP] Electric Analog  
> The electric analog is the **[[Electric Dipole Moment (p)]]**, which represents separated charges in an electric field.

---

# Formula
For a current loop:
$$
\vec{m} = I \vec{A}
$$
Where  
- $\vec{m}$ — **Magnetic Dipole Moment Vector** (A·m²)  
- $I$ — [[Current]] in the loop (A)  
- $\vec{A}$ — [[Area Vector]] normal to the loop (m²)

For continuous current distributions:
$$
\vec{m} = \frac{1}{2}\int \vec{r} \times \vec{J}\, dV
$$
where $\vec{J}$ is the [[Current Density (J)|current density]] (A/m²).

---

# Potential Energy and Torque
A magnetic dipole in an external field experiences **torque** and **potential energy** analogous to an electric dipole:

$$
\vec{\tau} = \vec{m} \times \vec{B}
$$
$$
U = -\vec{m} \cdot \vec{B}
$$

- $\vec{\tau}$ — torque acting to align $\vec{m}$ with $\vec{B}$  
- $U$ — potential energy of the magnetic dipole in $\vec{B}$

A dipole aligned with $\vec{B}$ has the **minimum potential energy**.

---

# Atomic and Quantum Moments
In atoms, magnetic moments arise from two sources:
1. **Orbital motion** of electrons — current loops around the nucleus  
2. **Spin angular momentum** of electrons and nuclei  

The fundamental quantum unit is the **Bohr magneton**:
$$
\mu_B = \frac{e\hbar}{2m_e} = 9.274\times10^{-24}\ \text{A·m²}
$$
Magnetic dipole moments are essential in explaining **paramagnetism**, **ferromagnetism**, **NMR**, and **ESR** phenomena.

---

# Relation to Fields
A collection of microscopic magnetic dipoles gives rise to **[[Magnetization (M)]]**:
$$
\vec{M} = \frac{\sum_i \vec{m}_i}{V}
$$
and contributes to the total magnetic field:
$$
\vec{B} = \mu_0(\vec{H} + \vec{M})
$$

---

# Analogs
| Magnetic Quantity      | Symbol                 | Electric Analog                                                 | Symbol    |
| ---------------------- | ---------------------- | --------------------------------------------------------------- | --------- |
| Magnetic Dipole Moment | $\vec{m}$              | [[Electric Dipole Moment (p)]]                                  | $\vec{p}$ |
| Magnetization          | $\vec{M}$              | [[Electric Polarization Density (P)\|Polarization Density (P)]] | $\vec{P}$ |
| Torque                 | $\vec{m}\times\vec{B}$ | $\vec{p}\times\vec{E}$                                          |           |
| Energy                 | $-\vec{m}\cdot\vec{B}$ | $-\vec{p}\cdot\vec{E}$                                          |           |

---

**Related:**  
- [[Dipole]]  
- [[Magnetization (M)]]  
- [[Magnetic Field (B)]]  
- [[Magnetic Field (H)]]  
- [[Torque (τ)]]  
- [[Electric Dipole Moment (p)]]  
- [[Bohr Magneton]]  
