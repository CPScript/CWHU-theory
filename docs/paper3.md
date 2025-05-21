## **Document 3: Simulation Protocol — Modeling the Cyclic Bounce Theory on a Computer**

**Title**: *Simulation Design for Quantum-Bounce-Driven White Hole Cosmology*

---

### **1. Objective**

Simulate a black hole collapse, quantum bounce, and the emergence of a new universe from a white hole — showing spacetime behavior across the event horizon and inside the quantum regime.

---

### **2. Software and Libraries**

* **Language**: Python, C++, or Rust
* **Libraries**:

  * `NumPy` / `SciPy` for numerical simulation
  * `Matplotlib` / `Plotly` for visualization
  * `Blender` / `Unity` for advanced 3D simulation
  * `EinsteinPy` or `GRChombo` for general relativity simulation
  * `SymPy` for symbolic manipulation of Einstein equations
  * GPU acceleration via CUDA or OpenCL (for performance)

---

### **3. Simulation Stages**

#### **Stage 1: Black Hole Formation**

* Model spherically symmetric collapse of matter using GR (Tolman–Oppenheimer–Volkoff equations).
* Animate curvature tensors and horizon formation.

#### **Stage 2: Quantum Gravity Regime**

* Introduce LQG corrections at Planck density.
* Modify Friedmann and Einstein equations:

  $$
  H^2 = \frac{8\pi G}{3} \rho \left(1 - \frac{\rho}{\rho_c} \right)
  $$
* Simulate time-reversal behavior near $\rho_c$ to create "bounce."

#### **Stage 3: White Hole Emergence**

* Simulate rapid spacetime expansion (inflation phase).
* Model quantum fluctuations (Gaussian noise) becoming structure seeds.
* Show emergence of a new universe from the opposite "pole" of the collapsed geometry.

---

### **4. Simulation Features**

* **Time-reversible engine** for running collapse/bounce/expansion.
* 3D spacetime mesh grids showing curvature and expansion.
* **Color-coded curvature** to visualize gravitational density.
* Adjustable parameters:

  * Initial mass
  * Matter composition (dust, radiation)
  * Quantum correction strength
* UI panel to toggle between:

  * Black hole frame (parent universe)
  * Interior bounce frame
  * White hole/bang frame (child universe)

---

### **6. Output**

* Exportable visuals, datasets (CSV, JSON), and time-evolution graphs.
* Optional video export of the whole bounce cycle.
* Log entropy changes and curvature values through the bounce.

---
