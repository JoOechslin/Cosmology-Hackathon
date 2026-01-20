# Cosmological Modelling – From Newton to ΛCDM

This repository is an **educational project** illustrating the historical and conceptual development of cosmology and gravitational physics, using **numerical simulations implemented as Jupyter notebooks**.

The notebooks progress through **four increasing levels of physical sophistication**, starting from classical Newtonian gravity and culminating in a cosmological **ΛCDM n-body simulation**. Together, they demonstrate which physical phenomena can (and cannot) be explained at each theoretical level, reflecting key milestones in the history of cosmology.

A detailed conceptual, historical, and physical discussion of all notebooks is provided in the accompanying **PowerPoint presentation** (000-cosmological_modelling_presentation.pptx) in this repository.

---

## Repository Structure

The repository contains four main Jupyter notebooks:

---

### 1. `001-Newton-n-body-v1.ipynb` — Newtonian N-Body Dynamics

Classical n-body simulations using Newton’s law of gravitation.

**Illustrates:**
- Solar system dynamics (26 bodies)
- Stable vs. unstable orbital configurations
- Figure-eight orbit
- Binary systems
- Plummer sphere
- Galaxy merger scenarios

**Can explain:**
- Planetary orbits
- Cold dark matter halos
- Isolated galaxy interactions

**Cannot explain:**
- Relativistic perihelion shift (e.g. Mercury)
- Light deflection
- Gravitational waves
- Cosmological expansion

---

### 2. `002-GR-1-body-v1.ipynb` — General Relativity: One-Body Problem

Motion of test particles and photons in the curved spacetime of a single massive rotating body (Kerr metric).

**Illustrates:**
- Deflection of light by the Sun
- Mercury’s anomalous perihelion precession
- Orbit of star S2 around Sagittarius A*
- Extreme photon and particle orbits near black holes

**Can explain:**
- Perihelion shift
- Light bending

**Cannot explain:**
- Gravitational radiation
- Binary inspiral dynamics
- Cosmological evolution

---

### 3. `003-GR-2-body-v1.ipynb` — General Relativity: Two-Body Problem

Post-Newtonian approximation of two interacting massive bodies with dynamical spacetime.

**Illustrates:**
- Gravitational-wave emission
- Orbital decay of binary systems
- Hulse–Taylor pulsar
- PSR J1757-1854
- OJ 287 blazar
- Inspiralling black hole binaries

**Can explain:**
- Gravitational waves
- Binary inspiral and orbital decay

**Cannot explain:**
- Large-scale cosmological structure formation

---

### 4. `004-LCDM-v2.ipynb` — Cosmological N-Body Simulation (ΛCDM)

A full cosmological simulation based on the **ΛCDM model**, combining:
- Friedmann equation for cosmic expansion
- Newtonian n-body dynamics in comoving coordinates
- Periodic boundary conditions
- FFT-based mesh gravity
- Thermal and baryonic components

**Illustrates:**
- Expansion of the universe from redshift *z = 99* to today
- Emergence of large-scale structure (filaments, walls)
- Formation of CDM halos and proto-galaxies
- Energy balance and baryon temperature evolution

---

## Presentation (Detailed Background)

The repository includes a **PowerPoint presentation** (000-cosmological_modelling_presentation.pptx) that provides:

- Historical context
- Theoretical background
- Physical interpretation of results
- Comparison between Newtonian, relativistic, and cosmological models

👉 **For detailed explanations and interpretation, please refer to the PPT presentation included in this repository.**

---

## Running the Notebooks Directly from GitHub (No Local Installation Required)

All notebooks can be **opened and executed directly in your browser** using **Google Colab**, without installing anything locally.

---

### Recommended Method (via Google Colab UI)

1. Open: https://colab.research.google.com
2. Click **File → Open notebook**
3. Select the **GitHub** tab
4. Enter:
   - GitHub username: **JoOechslin**
   - Repository name: **Cosmology-Hackathon**
5. Select any of the four notebooks
6. Click **Open**
7. Run the notebook cells directly in your browser

> This is the recommended way to explore this repository.

---

## Educational Purpose

This repository is intended for:
- Education and self-study
- Conceptual understanding of cosmology
- Numerical experimentation
- Illustration of historical breakthroughs in gravitational physics

The notebooks emphasize **physical insight and clarity**, not production-level simulation accuracy.

---

## Notes

- Numerical Relativity is **explicitly not pursued**, as it represents the next major level of complexity beyond this project.
- The notebooks are largely self-contained; `004-LCDM-v2.ipynb` includes additional supporting files included in the repository.

---
