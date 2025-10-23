# ⚙️ Dynamic Modeling of a Ball Regulator System

> A dynamic simulation and analytical study of a **ball regulator mechanism** modeled using **Lagrangian dynamics**.  
> Conducted as part of the *Modeling of Mechanical Systems* course at **Université de Toulon** (Erasmus Mundus MIR Programme).

---

## 🧭 Overview

This project analyzes the **Ball Regulator**, a classic mechanical system composed of two rotating arms, springs, and masses.  
It demonstrates how mechanical equilibrium, energy transfer, and motion constraints can be expressed using **Lagrangian equations**.

The main goal was to derive, from first principles:
- The **geometric constraints** and **degrees of freedom**
- The **Jacobian matrix** relating generalized and Cartesian coordinates
- The **Lagrangian** of the system (T – U)
- The **equations of motion** in matrix form:  
  `M(q)q̈ + C(q, q̇)q̇ + G(q) = 0`
- And to study how the system behaves when the **pivot rotation speed changes**

---

## 📂 Repository Structure

| Path | Description |
|------|--------------|
| **Dynamic_Modeling_2024_2025_Assignment.pdf** | Full report containing all derivations, equations, and final results (17 pages) |
| **assignment_explanation.pdf** | Simplified explanation of the modeling process and theoretical background |
| **README.md** | Project overview, structure, and key results (this file) |

---

## 🧮 Project Scope

| Step | Description |
|------|--------------|
| **1. System Definition** | Defined geometry and constraints for the rhombus-based ball regulator (r, θ, ϕ) |
| **2. Coordinate Transformation** | Expressed Cartesian coordinates (x, y, z) of the ball as functions of θ and ϕ |
| **3. Jacobian Derivation** | Computed the Jacobian matrix to relate coordinate variations |
| **4. Forces Analysis** | Calculated generalized forces for weight, spring, and reaction forces |
| **5. Energy Formulation** | Derived kinetic and potential energies (T and U) for both masses |
| **6. Lagrangian & Equations of Motion** | Formulated the Lagrangian and obtained motion equations in matrix form |
| **7. Equilibrium Study** | Analyzed how angular velocity Ω₀ affects the equilibrium position and stability |

---

## ⚙️ Key Equations (Conceptual Summary)

| Equation | Meaning |
|-----------|----------|
| `L = (ML² + Is)θ̇² + (ML²sin²θ + Is)ϕ̇² + 2MgLcosθ - 2ka²cos²θ` | Lagrangian formulation |
| `M(q)q̈ + C(q, q̇)q̇ + G(q) = 0` | General form of the dynamic model |
| `cosθ = (mgL) / (mL²Ω₀² + 2ka²)` | Equilibrium relation between pivot speed and arm angle |

---

## 🔍 Simulation Insight

- At **constant angular velocity Ω₀**, the system stabilizes at an equilibrium angle θ defined by the balance of centrifugal, spring, and gravitational forces.  
- When Ω₀ increases → **arms rise** (θ increases) due to higher centrifugal force.  
- When Ω₀ decreases → **arms drop** (θ decreases) as gravitational torque dominates.  
- This illustrates the **self-regulating behavior** of mechanical governors and regulators.

---

## 🧠 Learning Outcomes

| Concept | Gained Understanding |
|----------|----------------------|
| **Lagrangian Dynamics** | How to derive equations of motion from kinetic and potential energy |
| **Jacobian Analysis** | Relationship between angular and Cartesian variations |
| **Force Decomposition** | Translating weight, spring, and constraint forces into generalized torques |
| **Dynamic Equilibrium** | How rotation speed influences mechanical stability |
| **Energy Methods** | Using potential and kinetic energy for modeling mechanical systems |

---

## 🧩 Tools & Techniques

- Symbolic computation (MATLAB / manual derivation)
- Classical mechanics and energy-based modeling
- Analytical verification of equilibrium states

---

## 👩‍🔬 Authors

**Hyejoo Kwon**  
**Akira Techapattaraporn**  

📍 Erasmus Mundus Master’s in *Marine & Maritime Intelligent Robotics (MIR)*  
🧑‍🏫 Instructor: *Prof. Vincent Hugel*  
📅 Submitted: October 2025  

🔗 [GitHub Repository](https://github.com/S1194789/Dynamic-Modeling_Ball-Regulator)
