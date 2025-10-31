---
tags:
  - physics
  - ee
  - classicalmechanics
aliases:
  - Magnetization
  - Magnetization Vector
  - M
  - Magnetic Dipole Density
  - Magnetic Moment Density
---
# Definition
**Magnetization** describes the **alignment or induction of [[Dipole|magnetic dipoles]]** within a material when exposed to an external [[Magnetic Field (H)|Magnetic Field]]. To be magnetized is to be in a state where atomic or molecular magnetic moments align, generating a net [[Magnetic Dipole Moment (m)|Magnetic Moment]] per unit [[Volume]].

Unlike the case of [[Polarization (Matter)|electric polarization]], where a distinction is made between “polarization” (the phenomenon) and “[[Electric Polarization Density (P)|polarization density]]” (the quantity), **magnetization ($\vec{M}$)** *already* represents a **density** — the **magnetic dipole moment per unit volume**.

> [!NOTE] Unit!
> Magnetization $\vec{M}$ has units of **A/m (amperes per meter)** — magnetic dipole moment per unit volume.

> [!HELP] Electric Analog  
> The electric analog of **[[Magnetization (M)|Magnetization]]** is **[[Electric Polarization Density (P)|Polarization Density]]**, which represents electric dipole moment per unit volume.

---

## Outcomes
There are **two main forms** of magnetization depending on the material’s microscopic response:

1. **Induced Magnetization**  
	- Arises when atomic magnetic moments align *temporarily* with an applied $\vec{H}$ field.  
	- Found in **paramagnetic** and **diamagnetic** materials.

2. **Permanent Magnetization**  
	- Occurs when magnetic domains align *spontaneously* and persist even without an external field.  
	- Found in **ferromagnetic**, **ferrimagnetic**, and **antiferromagnetic** materials.

As a result, magnetization modifies the internal field of a material, just as polarization modifies the internal [[Electric Field (E)|Electric Field]] within a dielectric.

---

## Mechanisms
There are several microscopic mechanisms by which a material can become magnetized:

1. **Electron Spin Alignment**  
	- The intrinsic spin of electrons contributes to a magnetic moment.  
	- Alignment of spins produces a net $\vec{M}$.

2. **Orbital Magnetic Moment**  
	- Electrons orbiting nuclei generate small current loops.  
	- Alignment of these orbital moments also contributes to $\vec{M}$.

3. **Domain Alignment**  
	- In ferromagnetic materials, groups of atoms form aligned **magnetic domains**.  
	- An external $\vec{H}$ field grows domains aligned with it.

---

## Bound Currents
When a material is magnetized, the movement of internal dipoles gives rise to **bound currents**:

$$
\vec{J}_b = \nabla \times \vec{M}
$$

These are **not free conduction currents**, but effective currents due to microscopic dipole circulation.  
They are analogous to **bound charge densities** ($\rho_b = -\nabla \cdot \vec{P}$) in polarized materials.

> [!HELP] Electric Analog  
> The bound current density $\vec{J}_b = \nabla \times \vec{M}$ is the magnetic analog of **bound charge density** $\rho_b = -\nabla \cdot \vec{P}$ in dielectrics.

---

## Formula
Magnetization is defined as the **magnetic dipole moment density**:
$$
\vec{M} = \frac{\sum_i \vec{m}_i}{V}
$$
Where  
- $\vec{M}$ — **[[Magnetization (M)|Magnetization Vector]]** (A/m)  
- $\vec{m}_i$ — **[[Magnetic Dipole Moment (m)|Magnetic Dipole Moment]]** of the $i$th molecule (A·m²)  
- $V$ — **[[Volume]]** (m³)

In a **linear magnetic material**:
$$
\vec{M} = \chi_m \vec{H}
$$
Where  
- $\chi_m$ — **[[Magnetic Susceptibility (χm)|Magnetic Susceptibility]]** (dimensionless)  
- $\vec{H}$ — **[[Magnetic Field (H)|Magnetic Field Intensity]]** (A/m)

and thus:
$$
\vec{B} = \mu_0 (\vec{H} + \vec{M})
$$
Where  
- $\vec{B}$ — **[[Magnetic Field (B)|Magnetic Flux Density]]** (T)  
- $\mu_0$ — **[[Magnetic Permeability of Free Space (μ0)|Vacuum Permeability]]** (H/m)

---

**Related:**  
- [[Magnetic Field (B)]]  
- [[Magnetic Field (H)]]  
- [[Magnetic Dipole Moment (m)]]  
- [[Magnetic Susceptibility (χm)]]  
- [[Magnetic Permeability (μ)]]  
- [[Electric Polarization Density (P)]]  
- [[Polarization (Matter)]]
