🧠 Limen Neural
A solo research and engineering initiative focused on the boundary between neuromorphic computation, high-performance silicon, and biological feedback systems.

Limen Neural isn't a company; it is the infrastructure for a specific architectural goal: I built the Ship of Theseus—my workstation for AI workloads.  Software stack where every component is systematically upgraded and optimized for pure Spiking Neural Network (SNN) execution.

The Architecture: Ship of Theseus
The current focus is on developing a high-performance SNN chassis that bridges the gap between massive Large Language Models (LLMs) and biological temporal logic.

Host Environment: Fedora 43 / Blackwell-optimized Linux kernel.

Hardware Core: AMD Ryzen 9 9950X + ASUS ProArt RTX 5080 (16GB VRAM).

The SNN Engine: Spikenaut, a pure Spiking Neural Network designed to run natively on Blackwell silicon using custom sm_120 CUDA kernels and warp-level parallelization.

Current State
I am currently finalizing the "Chassis" phase:

Transplantation: Successfully migrated the myelin-accelerator CUDA core into the corinth-canal chassis.

Scaling: Standardized the full-path architecture to a 2048-neuron baseline to match the hidden dimensions of models like AllenAI’s OLMoE.

Modularity: Been working on refactoring the original private codebase into a standalone repo, a hardware-agnostic library that can be dropped into any project requiring rate, temporal, or neuromodulated encoding.

Optimization: Implementing a two-pass VRAM reduction system to extract SAAQ (Spiking Activity and Adaptive Quantization) telemetry directly from the RTX 5080 with minimal PCIe overhead.

Immediate Goals
Temporal Tick-Loop: Completing the real-time simulation loop that advances SNN physics (t = t + dt) natively on the GPU.

Telemetry Discovery: Using the SAAQ telemetry pipeline to map LLM latent spaces to SNN activity for real-time latent discovery via Julia-based symbolic regression.


The Philosophy
I believe that for AI to evolve, it must move closer to the efficiency of the biological brain. This requires moving away from the "black box" of backpropagation and toward the transparent, event-driven nature of spikes. Every line of code in this organization is written to prove that a single engineer, armed with a Blackwell chip and a custom Rust stack, can build a system more efficient and more "alive" than the industry giants.

Gemini drafted this documentation summary, a large language model built by Google, based on the specific research parameters and project history provided by Raul Montoya Cardenas
