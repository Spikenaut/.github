# Spikenaut

**A real-time spiking neural network (SNN) that turns mining telemetry + market micro-movements into sub-millisecond decisions.**

Built by Raul Montoya Cardenas as both a technical project and a personal recovery story. From traumatic brain injury (TBI) and zero-insurance engineering to a full open-source neuromorphic ecosystem running on FPGA at **97 mW**.

### The Lion in the Temporal Domain
Spikenaut is not just another SNN. It is a **16-channel adaptive Liquid State Machine** designed for chaotic, real-world environments:

- Live blockchain node telemetry (Kaspa, Monero, Dynex, Quai, Qubic, Ocean, Verus), only so far some node telemetry have been used in training.   Plan to add the rest later.
- Thermal "pain" sensors for hardware self-protection
- Ghost-money HFT engine with reward-modulated learning

It processes asynchronous spike trains, adapts online with E-prop + OTTT, and outputs confidence signals for high-frequency trading decisions — all while staying extremely lightweight (1.6 KB memory, Q8.8 fixed-point).

**Key Hardware Metrics (Artix-7 FPGA)**
- Power: **97 mW**
- Inference: **0.9 ms/tick**
- Training: **35 µs/tick**
- Memory: **1.6 KB**
- Bridge: Zero-copy Rust ↔ Julia (< 1 µs IPC)


Profits from personal HFT and mining optimization directly fund R&D in:
- BCI focus loops (ADHD & neuro-regulation)
- Neuromorphic prosthetics
- Human Check Light (preventative wearable health)
- Sustainable crypto mining
- An future ETF to create wealth among average retail investor

> "The lion didn’t roar for attention. It roared because it had no other choice."  
> — Built by an uninsured studnet engineer in Texas, turning brain fog and hardware stress into actionable spikes.

### Core Repositories

#### Rust Crates (Performance & FPGA Layer)
- **[neuromod](https://github.com/Spikenaut/neuromod)** — Reward-modulated neuromodulators (dopamine, cortisol, acetylcholine) + R-STDP
- **[soma-engine](https://github.com/Spikenaut/soma-engine)** — Core SNN inference engine
- **[synapse-link](https://github.com/Spikenaut/synapse-link)** — UART/FPGA serial I/O bridge
- **[synapse-spike](https://github.com/Spikenaut/synapse-spike)** — Spike encoding & routing

#### Julia Packages (Training & Strategy)
- **[SpikenautLSM.jl](https://github.com/Spikenaut/SpikenautLSM.jl)** — 65k-neuron sparse GPU-accelerated Liquid State Machine
- **[SpikenautExecution.jl](https://github.com/Spikenaut/SpikenautExecution.jl)** — Async trade pipeline (ZMQ → Kelly sizing → dYdX)
- **[SpikenautDistill.jl](https://github.com/Spikenaut/SpikenautDistill.jl)** — E-prop training + Q8.8 FPGA distillation
- **[SpikenautSignals.jl](https://github.com/Spikenaut/SpikenautSignals.jl)** — Streaming time-series features for SNNs
- **[spikenaut-capital](https://github.com/Spikenaut/spikenaut-capital)** — Corporate blueprint & capital engine

#### Hardware & Acceleration
- **[spikenaut-bridge-sv](https://github.com/Spikenaut/spikenaut-bridge-sv)** — Synthesizable UART-neural cortex bridge (SystemVerilog)
- **[myelin-accelerator](https://github.com/Spikenaut/myelin-accelerator)** — CUDA spiking kernels

### Main Model & Data
- **HF Model**: [rmems/Spikenaut-SNN-v2](https://huggingface.co/rmems/Spikenaut-SNN-v2) — 16-channel adaptive LSM with live telemetry + ghost HFT results
- **Dataset**: Linked telemetry (132k+ events from real blockchain nodes) with weights and parameters

### Get Involved
- **Star** the org or key repos if this resonates.
- **Fork & experiment** — everything is open (mostly GPL-3.0) for research and non-commercial use.
- **Contributions welcome** on modularity, FPGA targets, BCI extensions, or documentation.
- Looking for collaborators in neuromorphic hardware, quant trading, or med-tech.

### Philosophy
Zero-gatekeeper engineering.  
Hardware-aware, biologically inspired, built for the edge and the uninsured.  
HFT capital fuels deep-tech R&D — the Wheel Funnel in motion.

**"Defining the Threshold of Intelligence."**

---

**Made in Texas • 2026**  
Raul Montoya Cardenas — Founder, Limen Neural Holdings  
[HF Model](https://huggingface.co/rmems/Spikenaut-SNN-v2) • [Instagram](https://www.instagram.com/raccooncity_resident/) • [X](https://x.com/KeepOnSpiking)
