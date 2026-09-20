# Embodied AI Lab — Project Index

## Independent systems

| Repository | Capability | Status | Hub action |
| --- | --- | --- | --- |
| [FitGround](https://github.com/Benjamindaoson/FitGround) | Physics-grounded decision engine | Public flagship | Link only; remain independent |
| [Embodied-DataOps](https://github.com/Benjamindaoson/Embodied-DataOps) | Embodied data infrastructure and VLA workflow | Active build | Link only; remain independent |
| `smolvla-libero-plus-micro-pilot` | SmolVLA + LIBERO-Plus OOD adaptation study | Private active research | Remain independent and private until evidence is stable |

## Research tracks

| Track | Core artifact | Evidence required |
| --- | --- | --- |
| Embodied DataOps | Dataset schema, validation, lineage, replay, storage | Runnable pipeline and dataset-quality reports |
| VLA adaptation | Matched checkpoints and controlled OOD protocol | Frozen eligibility rule, repeated evaluation, uncertainty |
| Teleoperation | Demonstration collection and operator workflow | Latency, failure, and intervention records |
| Simulation-to-real | Comparable task and observation contracts | Explicit sim/real gap and transfer protocol |
| Remote robotics | Node health, recovery, and exception handling | Auditable safety and recovery events |
| Tactile learning | DIGIT-aligned observations and policies | Sensor calibration and synchronized data |

## Current infrastructure plan

| Component | Planned role |
| --- | --- |
| reBot B601-DM ×1 | Central dual-arm / integrated manipulation platform |
| SO-ARM101 ×8 | Distributed learning and demonstration nodes |
| Intel RealSense D405 ×1 | Close-range RGB-D sensing |
| DIGIT ×2 | Tactile sensing and contact-rich manipulation |

This table is a plan, not a procurement or deployment claim.

## Migration candidates

No public repository is approved for migration yet. New small demos should enter this Hub only when they are bounded, reproducible, and do not duplicate the independent flagship systems.
