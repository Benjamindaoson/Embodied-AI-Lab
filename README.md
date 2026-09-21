# Embodied AI Lab

A portfolio and research hub for **VLA systems, robot learning, simulation, embodied data, and physically grounded evaluation**.

The program connects model adaptation with the data, hardware, control, and evidence pipelines required to test behavior in the physical world.

## Technical focus

- Vision–Language–Action models
- Robot learning and cross-embodiment adaptation
- Teleoperation and demonstration collection
- Simulation and initial-state distribution shift
- ROS 2, MoveIt 2, and `ros2_control`
- Multimodal and tactile sensing
- Dataset quality, lineage, and evaluation
- Remote robotics operations and exception-only intervention

## Featured systems

| Project | Role | Focus |
| --- | --- | --- |
| [FitGround](https://github.com/Benjamindaoson/FitGround) | Flagship · independent repo | Physics-grounded decision engine using executable parameters, measured geometry, and simulation evidence |
| [Embodied-DataOps](https://github.com/Benjamindaoson/Embodied-DataOps) | Active build · independent repo | Data infrastructure for collection, teleoperation, simulation, evaluation, and VLA training workflows |
| `smolvla-libero-plus-micro-pilot` | Private research · independent repo | Controlled initial-state OOD adaptation protocol for SmolVLA and LIBERO-Plus |

See the [project index](./project-index.md) for maturity and release status.

## Lab workflow

```text
Robot / Simulator
      ↓
Teleoperation and Demonstrations
      ↓
Dataset Validation and Lineage
      ↓
VLA Training / Adaptation
      ↓
Simulation Evaluation
      ↓
Real-Robot Evaluation
      ↓
Failure Review and Data Iteration
```

## Evidence boundaries

The Lab distinguishes:

- simulation results from real-robot results;
- planned hardware from installed and tested hardware;
- current behavioral equivalence from adaptation outcomes;
- visual plausibility from measured physical evidence;
- prototype infrastructure from an operated robotics platform.

## Physical AI direction

The intended lab architecture supports a campus hub plus distributed robot nodes. The current equipment plan is centered on one reBot B601-DM, eight SO-ARM101 units, an Intel RealSense D405, and two DIGIT tactile sensors. Hardware plans are reported as plans until procurement and acceptance testing are complete.

## Repository policy

Flagship and active research systems remain independent. Small simulation or control demos may later be consolidated under `projects/`, but only after licenses, assets, and reproducibility are verified.


## Governance

This Hub follows the shared status taxonomy, link-only policy, private-research boundary, and release/archive synchronization checklist in [GOVERNANCE.md](GOVERNANCE.md).
