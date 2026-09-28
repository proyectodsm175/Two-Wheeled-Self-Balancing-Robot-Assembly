# Two-Wheeled-Self-Balancing-Robot-Assembly
Here is a complete, professionally formatted `README.md` description for your GitHub repository in English:

---

# Two-Wheeled Self-Balancing Robot – 3D CAD Assembly

## Overview

This repository contains the complete 3D CAD assembly of a **Two-Wheeled Self-Balancing Robot** (inverted pendulum mechanism). The design combines official academic structural hardware with custom mechatronic mechanisms and embedded control components, providing a complete 3D reference model for dynamic balancing and autonomous control projects.

---

## Technical Features & Hardware Integration

### Mechanical Structure & Actuation

* **TETRIX MAX Academic Kit:** The primary chassis and structural frame are built using official 3D CAD models from the TETRIX MAX educational kit.
* **Linear Lifting Mechanism:** Integrates a lead screw (spindle) mechanism for vertical payload movement and height adjustment.
* **Traction Motors:** High-torque DC motors equipped with integrated quadrature encoders for precise speed and position feedback during dynamic balancing.

### Electronics & Control Subsystem

* **Primary Controller:** NI myRIO-1900 real-time embedded hardware interface for closed-loop control algorithms.
* **Inertial Measurement Unit (IMU):** MPU-6050 (6-DOF accelerometer + gyroscope) for real-time angle sensing and state estimation.
* **Motor Drivers:**
* **Cytron H-Bridge Driver:** High-performance motor driver allocated for main wheel traction and dynamic stabilization.
* **Classic H-Bridge Driver (L298N):** Secondary motor driver used to control auxiliary actuators, including the linear lead screw mechanism.



---

## Disclaimer & Component Attribution

* **Assembly:** The overall structural integration, component alignment, and CAD assembly were created by the author of this repository.
* **Component Models:** Individual 3D CAD models belonging to the TETRIX MAX ecosystem are the intellectual property of their respective copyright holders (e.g., Pitsco Education) and are included here strictly for educational and research purposes.
