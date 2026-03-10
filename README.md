# ⚡ E&M Interactive Animations

Interactive browser-based animations for a 1st-year Engineering **Electricity & Magnetism** course.

**Live demo:** https://mikeatm.github.io/em-animations/

---

## Scenes

| # | Topic | Key concept illustrated |
|---|-------|------------------------|
| 1 | **Flux vs Angle** | Φ_E = EA cosθ — rotate a surface, watch flux drop to zero |
| 2 | **Gauss — Sphere** | Flux is independent of Gaussian sphere radius |
| 3 | **Field Lines** | Single charge · Dipole · Two like charges; Gaussian surface overlay |
| 4 | **Conductor Shielding** | Induced charges, E = 0 inside, hollow cavity with charge |
| 5 | **Electric Potential** | V = kQ/r heatmap; equipotentials; hover to probe |
| 6 | **Capacitor Charging** | C = κε₀A/d; dielectric effect; live C/Q/E readouts |
| 7 | **Series vs Parallel** | Kirchhoff's laws; current glow proportional to I |
| 8 | **Magnetic Flux** | Φ_B = BA cosθ — rotating current loop |

---


## Related repos

- [basicLabs](https://github.com/mikeatm/basicLabs) — Basic physics digital labs
- [crystal-symmetry-explorer](https://github.com/mikeatm/crystal-symmetry-explorer) — Crystal symmetry visualiser
- [bohr-blackbody-solar](https://github.com/mikeatm/bohr-blackbody-solar) — Bohr model / blackbody / solar spectrum

---

## Changelog

**v1.1** (current)
- Fixed `roundRect` polyfill for Safari ≤15 and older browsers
- Fixed θ arc label in Flux and Magnetic Flux scenes — was invisible at θ = 0
- Fixed magnetic flux units: Wb (not Wb/m²)
- Clamped current glow `normI` so it doesn't saturate at high EMF values
- Info panel in Magnetic Flux scene now clamps to canvas width on mobile

**v1.0**
- Initial release — 8 interactive scenes
