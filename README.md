# Quadcopter Drone Mechanical CAD Assembly

Custom 3D quadcopter drone designed, modeled, and assembled in **SOLIDWORKS**. The design integrates truss-reinforced lightweight arms, vibration-isolated electronic mounts, and a multi-tier central chassis for avionics and power distribution.

---

## Visualizations

### Exploded Assembly & Kinematics
<p align="center">
  <img src="media/SolidWorks_Drone_Assembly_Animation.gif" alt="Quadcopter Exploded View Animation" width="750">
</p>

### Assembled Isometric View
<p align="center">
  <img src="media/Drone_Full_Assembly_Isometric_View.png" alt="Quadcopter Fully Assembled View" width="750">
</p>

---

## Subsystems & Architecture

* **Structural Airframe:**
  * Modular multi-plate central chassis housing the flight controller stack and power distribution.
  * Webbed truss motor arms optimized for high torsional stiffness while minimizing overall airframe weight.
  * Fastened standoffs and hardware interface points providing clearance for wire routing.

* **Propulsion & Actuation:**
  * 4× Brushless DC outrunner motors with threaded collet prop adapters.
  * Matched dual-blade aerodynamic propellers.
  * Individual arm-mounted Electronic Speed Controller (ESC) bays with direct motor lead routing.

* **Avionics & Power Integration:**
  * Top-mounted modular battery tray designed for LiPo balance and center-of-gravity (CG) stability.
  * Central internal bay for flight controller board mounting, receiver, and sensor routing.

---

## CAD Modeling Details

* **Software:** Dassault Systèmes SOLIDWORKS
* **Techniques Used:** Parametric Part Modeling, Bottom-Up Assembly, Mechanical Mates, Interference Detection, Exploded View Animations, PhotoView 360 / Visualize Rendering.
* **Deliverables:** High-resolution renders, exploded assembly animations, and single combined assembly mesh export (`.STL`).

---

## 3D CAD Files

* **Complete Assembly STL:** [`Final Project Drone.STL`](Final%20Project%20Drone.STL) *(Interactive 3D viewable directly on GitHub)*
* **Visual Media:** High-resolution renders and kinematics are available in the [`media/`](media/) directory.
