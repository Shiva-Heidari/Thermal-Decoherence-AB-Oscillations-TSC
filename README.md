# Decoherence-AB-Oscillations-TSC

# Aharonov–Bohm Interference in Fe(Te,Se) Superconducting Rings

This repository contains theoretical modeling and analysis supporting our study on **Aharonov–Bohm (AB) interference from coherent spin-polarized edge transport in Fe(Te,Se) topological superconducting rings**. The model employs **helical Luttinger liquid (HLL) theory** to capture the interplay between magnetic flux, temperature, and electron–electron interactions in one-dimensional spin-polarized edge channels.

## Overview
- **Framework:** Helical Luttinger liquid theory for interacting 1D fermions with spin–momentum locking.
- **Bosonization:** Fermionic fields expressed via bosonic charge and current modes \(\phi(x,t)\) and \(\theta(x,t)\).
- **Flux coupling:** Magnetic flux enters exclusively through the zero-mode sector, modifying the boundary conditions and producing an AB phase shift.
- **Finite-temperature effects:** Thermal correlation functions derived via conformal mapping to quantify interaction-induced dephasing.
- **Key prediction:** Temperature-dependent AB oscillation amplitude \(A_{AB}(T)\) with a crossover at \(T_L = \frac{\hbar \nu}{\pi k_B L}\).

## Key Equations

**Helical Luttinger Liquid Hamiltonian:**
\[
H = \frac{\hbar \nu}{2\pi} \int_0^L dx \left[ K(\partial_x \theta)^2 + \frac{1}{K} (\partial_x \phi)^2 \right]
\]

**Interaction parameter:**
\[
\gamma = \frac{1}{2}\left(K + \frac{1}{K}\right) - 1
\]

**AB amplitude at finite temperature:**
\[
A_{AB}(T) = \frac{1}{2\pi \zeta} \left[ \frac{\pi \zeta k_B T}{\hbar \nu \sinh\left(\frac{\pi L k_B T}{\hbar \nu}\right)} \right]^\gamma
\]

## Physical Insights
- **Non-interacting limit** (\(K=1, \gamma=0\)): AB amplitude is temperature-independent.
- **Interacting regime**: Electron–electron interactions induce dephasing, leading to linear decay of \(A_{AB}(T)\) at \(T > T_L\) for weak interactions.
- **Low-temperature regime** (\(T < T_L\)): AB amplitude saturates, reflecting maximal quantum coherence.

## Repository Contents
- `theory/` — Analytical derivations in LaTeX format.
- `notebooks/` — Python scripts for numerical evaluation of \(A_{AB}(T)\).
- `figures/` — Plots illustrating theoretical predictions.



