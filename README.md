# Sealed-WEC 3D Co-Design Studio — Interactive Showcase

**Live Interactive 3D Demo:** [https://yman95.github.io/sealed-wec-demo/](https://yman95.github.io/sealed-wec-demo/)

Interactive 60 FPS WebGL1 3D engineering showcase for hermetically sealed, single-hull point-absorber wave energy converters (WECs) with enclosed internal power take-off (PTO) drivetrains (no ocean-exposed moving rods, seals, or pistons).

---

## Capabilities in This Public Showcase

* **Interactive 60 FPS WebGL1 3D Viewport:**
  * Orbit, pan, zoom, switch camera presets (**Hull & Cutaway PTO** vs. **Full Mooring & Seabed**), toggle **X-Ray Cutaway** opacity to inspect the sealed internal PTO kinematics, and toggle live linear **Airy Wave Animation**.
* **Curated 10-Site North American Wave Atlas & 15-Hull Architectural Showcase:**
  * Explore **10 reference coastal & offshore test sites** (Port Hardy BC, Humboldt Bay CA, Sitka AK, Newport/PacWave OR, US Atlantic NY/NJ, Gulf of Maine, Hawaii North Shore, Grand Banks NL, San Francisco Offshore, S. California Channel).
  * Compare **15 representative hull geometries** spanning canonical buoys, filleted/chamfered low-drag hulls, slender spars, CalWave-style & CETO-style submerged stealth bodies, curved-wall concave/convex profiles, tapered frustums, and asymmetric pitching hulls paired with **3 sealed internal PTO architectures**:
    1. **Arch A:** Internal Translating Heave Mass (Linear Rack/Generator)
    2. **Arch B:** Inclined Compound Pendulum (Low-Frequency Rotational Drive)
    3. **Arch C:** Control-Moment Vacuum Flywheel Gyroscope (CMG)
* **Interactive Design Customization & Live Engineering Guardrails:**
  * Scale circumdiameter ($D_{\text{circ}}$), array units, PTO type, and mooring topology (`catenary_chain`, `semi_taut_hybrid`, `taut_synthetic`, `taut_buoyant`) / anchor class, and inspect real-time pass/fail checks for intact metacentric stability ($\text{GM}$), 50-year storm mooring safety factor, anchor uplift, seabed clearance, and steep-wave Mathieu pitch stability.
* **Optional Private API Hook:**
  * Authorized engineering partners with a private backend token can click **Connect Private API** inside the studio to unlock the full **200-hull NEMOH BEM library**, arbitrary global coordinates, custom metocean inputs, and turnkey Pre-FEED `.ZIP` CAD/MoorDyn exports.

---

## Intellectual Property & Confidentiality Notice

This public repository publishes **only** compiled client-side WebGL display assets and pre-computed showcase metrics for a **15-hull representative subset**.

All underlying proprietary solvers, `200`-hull NEMOH hydrodynamic databases, `80,952`-run nonlinear WEC-Sim parquet training sets, calibrated machine-learning surrogates, mooring structural synthesis algorithms, and full-precision `.stl` / `MoorDyn v2` CAD exporters remain strictly confidential inside private repositories (`Copyright © 2026 Yi Man. All Rights Reserved.`).

For commercial Pre-FEED site assessments, API access tokens, or licensing inquiries, please contact the author via [GitHub (@yman95)](https://github.com/yman95).
