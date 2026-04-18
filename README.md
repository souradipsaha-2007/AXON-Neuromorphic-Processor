# AXON-Neuromorphic-Processor
# AXON X6.2 — Adaptive Neuromorphic Control Processor

**Designer:** Souradip Saha  
**Age:** 19 | **Location:** Howrah, West Bengal, India  
**Background:** Self-taught | Bengali medium government school  
**Status:** Silicon specification complete · FPGA implementation planned

---

## What is AXON X6.2?

AXON X6.2 is a fully λ-actuated hybrid neuromorphic control 
processor designed for edge robotics, drone systems, and 
brain-computer interfaces.

It implements a 19-stage synchronous pipeline combining 
event-driven spiking computation with continuous rate-coded 
processing — unified under a single adaptive scalar control 
variable λ.

---

## Core Innovation

No production neuromorphic chip today does this:

> λ continuously modulates membrane integration gain, 
> noise level, plasticity balance, and homeostatic 
> threshold speed — all as one coherent closed-loop system.

| Feature                | AXON X6.2 | BrainChip Akida | Intel Loihi 2 |
|------------------------|-----------|-----------------|---------------|
| Runtime mode switching | ✅        | ❌              | ❌            |
| Thermal closed-loop    | ✅        | ❌              | ❌            |
| Dual-timescale STDP    | ✅        | ⚠️              | ✅            |
| Lyapunov stability     | ✅        | ❌              | ❌            |
| Commercial silicon     | 🔄        | ✅              | ❌            |

---

## Architecture Highlights

- **λ-actuated gain** — membrane integration speed scales with λ
- **λ-actuated noise** — stochastic exploration scales with λ  
- **λ-actuated plasticity** — fast STDP dominant at λ=0, 
  slow Hebbian dominant at λ=1
- **λ-actuated homeostasis** — threshold adaptation rate 
  scales with λ
- **Queue-based NoC** — congestion feeds back into λ controller
- **Thermal dynamics** — T[k] is first-class state variable
- **Lyapunov-certified** — engineering stability guarantee 
  with explicit contraction rate

---

## Specification Files

- [`specs/AXON_X6.2_Final.md`](specs/AXON_X6.2_Final.md) 
  — Complete silicon-ready specification
- [`docs/AXON_X6.2_Summary.md`](docs/AXON_X6.2_Summary.md) 
  — 150-word technical summary

---

## Development History

| Version | Key Milestone |
|---------|--------------|
| X4.3    | First complete pipeline spec |
| X5.0    | Energy + thermal model added |
| X5.9    | Zero critical bugs — RTL ready |
| X6.2    | Full λ-actuation across all subsystems |

---

## Target Applications

- Autonomous drones (adaptive power-latency control)
- Robotic motor control (continual on-chip learning)
- Brain-computer interfaces (always-on, thermally safe)
- Edge AI (variable workload adaptation)

---

## Contact

**Souradip Saha**  
📧 [ssouradip440@gmail.com]  
📍 Howrah, West Bengal, India

---

*Designed independently. All work is original.*
