# Embodied AI Lab — Project Index

> Status labels and update rules: [Governance policy](GOVERNANCE.md).

## Independent systems

| Repository or direction | Capability | Status | Hub action |
| --- | --- | --- | --- |
| [FitGround](https://github.com/Benjamindaoson/FitGround) | Physics-grounded next-edit decision engine | **Flagship** | Link only; remain independent |
| [Embodied-DataOps](https://github.com/Benjamindaoson/Embodied-DataOps) | Embodied data infrastructure and VLA workflow | **Research** · active build | Link only; remain independent |
| SmolVLA + LIBERO-Plus OOD adaptation | Matched-checkpoint adaptation study | **Research** · private | Describe direction only; no private link |

## Research tracks

| Track | Core artifact | Status and evidence required |
| --- | --- | --- |
| Embodied DataOps | Dataset schema, validation, lineage, replay, storage | **Research** · runnable pipeline and data-quality reports |
| VLA adaptation | Matched checkpoints and controlled OOD protocol | **Research** · frozen eligibility, repeated evaluation, uncertainty |
| Teleoperation | Demonstration collection and operator workflow | **Research** · latency, failure, and intervention records |
| Simulation-to-real | Comparable task and observation contracts | **Research** · explicit sim/real gap and transfer protocol |
| Remote robotics | Node health, recovery, and exception handling | **Research** · auditable safety and recovery events |
| Tactile learning | DIGIT-aligned observations and policies | **Research** · calibrated, synchronized data |

## Current infrastructure plan

| Component | Planned role |
| --- | --- |
| reBot B601-DM ×1 | Central dual-arm / integrated manipulation platform |
| SO-ARM101 ×8 | Distributed learning and demonstration nodes |
| Intel RealSense D405 ×1 | Close-range RGB-D sensing |
| DIGIT ×2 | Tactile sensing and contact-rich manipulation |

This is a plan, not a procurement or deployment claim.

## Intake rule

New demos enter this Hub only when bounded and reproducible. They remain independent if they represent a flagship capability; private experiments are described without repository links.
