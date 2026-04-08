🧠 Spikenaut: Neuromorphic Systems Research
Welcome to the Spikenaut organization. This ecosystem is dedicated to the research, development, and deployment of Spiking Neural Networks (SNNs) for high-frequency data environments, ranging from hardware telemetry and crypto-mining optimization to hybrid LLM architectures.

⚠️ The Great Reset: Current Status (April 2026)
We are currently in a "Ground Zero" rebuilding phase. After a successful initial prototype, the project's scale expanded rapidly. To ensure long-term stability and scientific integrity, we are systematically verifying the entire pipeline from hardware telemetry up to high-level logic.

Current Objective: Absolute verification of the telemetry ingest layer.

🛠 Active Research Tracks
1. Hardware Telemetry & Baseline Verification (spikenaut-telemetry)
The foundation of the research is grounded in real-world hardware dynamics. I use Dynex mining hardware as our primary baseline.

Goal: Stable, high-fidelity capture of GPU/CPU metrics and mining algorithm efficiency.

Status: Re-verifying the telemetry layer to eliminate noise and ensure 100% data integrity before feeding it into the SNN reservoirs.

Focus: Consolidating from multiple miners back to a singular, rock-solid Dynex baseline.

2. HFT-SNN Research (The Financial Layer)
Applying neuromorphic temporal processing to High-Frequency Trading (HFT) environments.

Goal: Utilizing the low-latency nature of SNNs to process market micro-structures.

Status: Project listed for stability testing once the hardware telemetry baseline is verified.

3. SpikeLMo: SNN-Infused LLM Logic
The most ambitious track—exploring the fusion of SNN temporal gating with the OLMoE (Mixture of Experts) 7B architecture.

Concept: Utilizing SNNs to act as the "Neuromorphic Router" for LLM experts, optimizing for efficiency and real-time responsiveness.

Status: Theoretical architecture and initial logic mapping.

🏗 System Architecture
The research is developed on the Ship of Theseus workstation (Fedora 43), utilizing a specialized tech stack:

Languages: Rust (Core logic/Hardware I/O), Julia (Mathematical modeling/Research), SystemVerilog (FPGA deployment).

Core Crate: neuromod - The proprietary brain of the project, handling LIF neurons and STDP plasticity.

Hardware: Deployment targets include AMD/NVIDIA GPUs for simulation and Digilent Basys 3 FPGAs for physical spike verification.

📜 Contributing
Spikenaut is currently in a closed-rebuild phase. While the repositories are public for transparency and open-source compliance (GPL-3.0), I am prioritizing a steady research foundation is bulletproof.
