# Compact Drone – Design, Motion, and Aerodynamic Analysis

This project demonstrates the complete workflow for designing, simulating, and analysing a compact drone using SolidWorks. The goal was to create a stable, efficient drone design that integrates well-functioning mechanical parts with optimised aerodynamics.

## 🎯 Project Objectives
- Design a drone with a functional impeller, gears, and frame.
- Simulate real-world motor-driven motion using SolidWorks Motion.
- Perform aerodynamic CFD analysis to evaluate thrust and pressure distribution.
- Visualise motion and airflow via animations.

## 🛠️ Software Used
- **SolidWorks CAD** – for 3D modeling and full assembly.
- **SolidWorks Motion Study** – for simulating motor-driven movement.
- **SolidWorks Flow Simulation** – for CFD-based aerodynamic testing.

## 📂 Project Structure
- `Assembly.SLDASM` – Main drone assembly
- `1-Impeller Blades.SLDPRT`, `2-Arm Gear.SLDPRT`, `3-Gearing.SLDPRT`, `4-Legs.SLDPRT`, `5-Main Structure.SLDPRT`, `6-Camera.SLDPRT`
- `Motion.mp4` – Visual output of mechanical simulation
- `Flow Simulation.mp4` – Airflow trajectory and CFD result visualisation
- `Final_Report.pdf` – Detailed written analysis

## 🔁 Motion Simulation
- Simulated impeller rotation using a motor set at **100 RPM**.
- Mechanism includes motor → gear → belt → impeller linkage.
- Validated correct part interaction and gear meshing.

⚠️ *Note:* The motion simulation video contains a minor rotational mismatch in angle setup. The mechanical behaviour remains visually accurate for concept validation.

## 🌬️ CFD (Flow Simulation)
- Impeller rotation set at **150 RPM** to study aerodynamic effects.
- The rotating region technique was used to simulate airflow without mesh distortion.
- Generated flow trajectories and pressure contours.
- Mesh count: 4,018 cells, Solver iterations: 140 (converged)
- Result: Downward thrust confirmed, stable pressure profile, no major turbulence.

## 📈 Key Outcomes
- The drone exhibits good aerodynamic stability and lift performance.
- Design supports smooth mechanical operation.
- CAD, motion, and CFD integration within one platform (SolidWorks) streamlined the process.

## 👨‍💻 Author
Prathmesh Deepak Gondkar

## 📎 Downloads
- CAD Files, Videos, and a PDF report are included in this repository.

- ## 📬 Contact
Please contact me on [LinkedIn](www.linkedin.com/in/prathmeshgondkar) if you have any questions or need collaboration.

---

