---
tags:
  - physics
aliases:
  - Complex Permittivity
  - ε̃
  - Complex Electric Permittivity
---
# Definition
**Complex permittivity** ($\tilde{\varepsilon}$) describes a material’s response to an **oscillating [[Electric Field (E)]]**, accounting for both **energy storage** and **energy loss** due to [[Absorption]] or [[Conductivity (σ)|Conduction]].  

It extends the [[Electric Permittivity (ε)|Permittivity]] by adding an imaginary term to represent [[Damping Rate (γ)|damping]] or loss ($\tilde{\varepsilon} = \varepsilon' - i\varepsilon''$). 


> [!NOTE] Unit!
> Permittivity has units of **F/m (farads per meter)**.

### Physical Meaning
- **Real part ($\varepsilon'$):** Energy stored in polarization.  
- **Imaginary part ($\varepsilon''$):** Energy dissipated as heat.

---
## Formula
$$
\tilde{\varepsilon} = \varepsilon' - i \varepsilon''
$$
Where  
- $\varepsilon'$ is the **real part**, representing **stored energy** (dielectric constant)  
- $\varepsilon''$ is the **imaginary part**, representing **losses** (dielectric loss)  

For conductive materials:
$$
\tilde{\varepsilon} = \varepsilon' - i \frac{\sigma}{\omega}
$$
Where  
- $\sigma$ is the **[[Conductivity (σ)|Conductivity]]** (S/m)  
- $\omega$ is the **[[Angular Frequency (ω)|Angular Frequency]]** (rad/s)

---
### Relation to Refractive Index
For nonmagnetic media ($\mu_r \approx 1$):
$$
\tilde{n}^2 = \tilde{\varepsilon}_r
$$
Thus, the **Complex Refractive Index** ($\tilde{n} = n + i\kappa$) arises directly from $\tilde{\varepsilon}$.

---
**Related:**  
- [[Electric Permittivity (ε)]]  
- [[Dielectric]]  
- [[Complex Refractive Index (ñ)]]  
- [[Conductivity (σ)]]  