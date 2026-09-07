## Abhishek Ray

**Robotics — 6-DOF manipulators, from the kinematics to the metal.**

I build the whole stack rather than gluing libraries together. The forward kinematics,
Jacobians and IK solvers in my work are derived and implemented from first principles, then
verified numerically against an independent implementation before anything depends on them.
The same habit runs through the mechanical side: every criterion recomputed from the exported
CAD geometry rather than from the parameters that authored it.

---

### Featured work

**[robotics-engineering-portfolio](https://github.com/Abhishek4650/robotics-engineering-portfolio)** — what I've built
> Sine-trajectory tracing on a myCobot 280 (modified-DH FK, velocity-propagation Jacobian,
> damped-least-squares IK — verified to ~1e-15 m against the URDF) · **ARM-450**, a clean-sheet
> 6-DOF arm designed entirely in parametric Python, 450.0 mm and 1365 g against a 1450 g
> ceiling, with a 60-check pre-print verification gate · ESP32 + STS3215 serial-bus servo
> bring-up, from a dead bus to a moving arm.

**[robotics-research-portfolio](https://github.com/Abhishek4650/robotics-research-portfolio)** — what I'm researching
> Task-constrained workspace and inverse kinematics for surface tracing. A manipulator's
> *reachable* workspace is the quantity everyone quotes; the set where it can work with the
> tool held at a required orientation is strictly smaller, shaped differently, and full of
> holes. I compute that set, quantify it, and design against it.

---

### What I work with

`ROS 2 Jazzy` · `Python` · `NumPy / SciPy` · `PyBullet` · `RViz` · `TF`
`Modified/Craig DH` · `Jacobians` · `DLS / Levenberg–Marquardt IK` · `manipulability analysis`
`parametric CAD in code` · `STEP / STL` · `FEA` · `DFM for FDM printing`
`serial-bus servos` · `ESP32` · `register-level protocols` · `pyserial`

---

### Currently

Extending the task-constrained workspace analysis toward a thesis chapter, and taking the
ARM-450 design from verified geometry to printed, measured hardware — the predictions are
already recorded, which is the point.

Open to **PhD positions** in robotic manipulation, workspace analysis and space robotics, and
to **robotics engineering roles**.

📫 royabhishek4650roy@gmail.com
