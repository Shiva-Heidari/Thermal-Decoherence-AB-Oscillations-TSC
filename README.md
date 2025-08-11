# Decoherence-AB-Oscillations-TSC

# Aharonov–Bohm Interference in Fe(Te,Se) Superconducting Rings

This repository contains the **supplementary theoretical modeling and derivations** for our submitted paper:  
**[Aharonov–Bohm interference from coherent spin-polarized edge transport in Fe(Te,Se) superconducting rings](https://arxiv.org/pdf/2508.05030)**.

The work develops a **helical Luttinger liquid (HLL) framework** to describe interacting spin-polarized one-dimensional edge states in a topological superconductor ring geometry. The model captures the impact of **magnetic flux, finite temperature, and electron–electron interactions** on the quantum coherence of Aharonov–Bohm (AB) oscillations.

## Overview
- **Framework:** Helical Luttinger liquid theory for interacting 1D fermions with spin–momentum locking.
- **Bosonization:** Fermionic fields expressed via bosonic charge and current modes \(\phi(x,t)\) and \(\theta(x,t)\).
- **Flux coupling:** Magnetic flux enters exclusively through the zero-mode sector, modifying the boundary conditions and producing an AB phase shift.
- **Finite-temperature effects:** Thermal correlation functions derived via conformal mapping to quantify interaction-induced dephasing.
- **Key prediction:** Temperature-dependent AB oscillation amplitude \(A_{AB}(T)\) with a crossover at \(T_L = \frac{\hbar \nu}{\pi k_B L}\).

## Key Equations

**Helical Luttinger Liquid Hamiltonian:**
$$\[
H = \frac{\hbar \nu}{2\pi} \int_0^L dx \left[ K(\partial_x \theta)^2 + \frac{1}{K} (\partial_x \phi)^2 \right]
\]$$

**Interaction parameter:**
$$\[
\gamma = \frac{1}{2}\left(K + \frac{1}{K}\right) - 1
\]$$

**AB amplitude at finite temperature:**
$$\[
A_{AB}(T) = \frac{1}{2\pi \zeta} \left[ \frac{\pi \zeta k_B T}{\hbar \nu \sinh\left(\frac{\pi L k_B T}{\hbar \nu}\right)} \right]^\gamma
\]$$

## Physical Insights
- **Non-interacting limit** ($$\(K=1, \gamma=0\)$$): AB amplitude is temperature-independent.
- **Interacting regime**: Electron–electron interactions induce dephasing, leading to linear decay of $$\(A_{AB}(T)\)$$ at $$\(T > T_L\)$$ for weak interactions.
- **Low-temperature regime** ($$\(T < T_L\)$$): AB amplitude saturates, reflecting maximal quantum coherence.




