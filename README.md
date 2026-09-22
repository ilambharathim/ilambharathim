<!-- ================================================================= -->
<!-- ILAM BHARATHI — NEXT-GEN VLSI & HARDWARE ENGINEERING PORTFOLIO   -->
<!-- Aesthetic: Obsidian Silicon & EDA Workstation Theme               -->
<!-- Target: VLSI / ASIC / RTL / Verification / FPGA / Edge AI         -->
<!-- ================================================================= -->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./header.svg">
  <source media="(prefers-color-scheme: light)" srcset="./header-light.svg">
  <img src="./header.svg" width="100%" alt="Ilam Bharathi — Semiconductor Architecture Header">
</picture>

</div>

<br>

`ash
$ sys_info --target ilambharathim
  Identity    : Electronics & Communication Engineering Undergraduate
  Domain      : VLSI / RTL Architecture / Digital Verification / FPGA / Edge AI
  HDL Stack   : SystemVerilog (IEEE 1800) • Verilog-2001 • VHDL
  EDA Tooling : Cadence Virtuoso & Spectre • Synopsys VCS & Verdi • KLayout • Vivado
  Focus       : Hardware-efficient neural accelerators & automated RTL verification
`

<div align="center">
  <img src="./telemetry.svg" width="100%" alt="Hardware Telemetry & Benchmarks Dashboard">
</div>

<br>

---

## ⚡ 01 // CORE ARCHITECTURAL FOCUS

<table width="100%">
  <tr>
    <td width="50%" valign="top" style="background-color:#131923; padding:12px; border-radius:6px;">
      <h4 style="color:#F59E0B; margin:0;">🔶 VLSI &amp; Semiconductor Design</h4>
      <p style="color:#8B949E; font-size:12px; margin:4px 0 8px 0;"><code>ANALOG • FinFET • 6T SRAM • LAYOUT</code></p>
      <ul>
        <li><b>Device Scaling:</b> 22nm FinFET area optimization &amp; 180nm CMOS device sizing.</li>
        <li><b>Physical Layout:</b> DRC/LVS rule verification, guard ring isolation, and parasitic extraction.</li>
        <li><b>Corner Analysis:</b> PVT sensitivity characterization across extreme operating regimes.</li>
      </ul>
    </td>
    <td width="50%" valign="top" style="background-color:#131923; padding:12px; border-radius:6px;">
      <h4 style="color:#38BDF8; margin:0;">🔷 RTL &amp; Digital Architecture</h4>
      <p style="color:#8B949E; font-size:12px; margin:4px 0 8px 0;"><code>SYSTEMVERILOG • FSM • PIPELINING</code></p>
      <ul>
        <li><b>Micro-Architecture:</b> High-throughput pipelined datapaths, multi-stage FIFOs, and arbiter logic.</li>
        <li><b>Control Design:</b> Robust Mealy/Moore synchronous FSMs with glitch-free state transitions.</li>
        <li><b>Timing Closure:</b> Setup/hold slack margin budgeting and clock-domain crossing (CDC) sanitization.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top" style="background-color:#131923; padding:12px; border-radius:6px;">
      <h4 style="color:#10B981; margin:0;">🟢 Verification &amp; EDA Simulation</h4>
      <p style="color:#8B949E; font-size:12px; margin:4px 0 8px 0;"><code>VCS • XCELIUM • SVA • VERDI</code></p>
      <ul>
        <li><b>Logic Simulation:</b> High-performance regression runs with Synopsys VCS and Cadence Xcelium.</li>
        <li><b>Formal &amp; Assertions:</b> SystemVerilog Assertions (SVA) for automated functional violation trapping.</li>
        <li><b>Signal Tracing:</b> Deep-dive signal debugging using Synopsys Verdi and VCD/FST waveform inspection.</li>
      </ul>
    </td>
    <td width="50%" valign="top" style="background-color:#131923; padding:12px; border-radius:6px;">
      <h4 style="color:#A855F7; margin:0;">🟣 FPGA &amp; Hardware-Efficient AI</h4>
      <p style="color:#8B949E; font-size:12px; margin:4px 0 8px 0;"><code>POLARFIRE SOC • SNN • ACCELERATION</code></p>
      <ul>
        <li><b>Target Silicon:</b> Microchip PolarFire SoC FPGA (integrated multi-core RISC-V subsystem).</li>
        <li><b>Edge Neuromorphic AI:</b> Spiking Neural Network (SNN) hardware mapping with low static leakage.</li>
        <li><b>Synthesis Tooling:</b> AMD Xilinx Vivado bitstream generation and on-chip logic analyzer probing.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🛠️ 02 // HARDWARE & SILICON PROJECT DOSSIERS
*(Click any project drawer below to expand architectural schematics, waveform captures, and verification metrics)*

<br>

### 🔹 [PROJECT 01] RIVA — RTL Intelligent Verification Assistant
SystemVerilog RTL Validation Waveform Analysis Linting Assertion Engine
- Developing an automated verification framework combining SystemVerilog testbenches, simulation regressions, waveform analysis, and linting rules.
- Integrates specification-driven debugging techniques to trace functional discrepancies from testbench assertions down to failing RTL datapath signals.
- **Repository:** [github.com/ilambharathim/AI_RTL_ASSISTANT](https://github.com/ilambharathim/AI_RTL_ASSISTANT)

<details>
<summary><b>🔍 [CLICK TO EXPAND] ARCHITECTURAL SPECIFICATION &amp; WAVEFORM ANALYSIS</b></summary>
<br>

<div align="center">
  <img src="./waveform_analysis.svg" width="100%" alt="RIVA Waveform Timing Simulation Trace">
</div>

`
+---------------------------------------------------------------------------------------+
| RIVA VERIFICATION ARCHITECTURE PIPELINE                                              |
|                                                                                       |
|  [ RTL DUT (.sv) ]                                                                    |
|         │                                                                             |
|         ▼                                                                             |
|  [ AST Parser & Linter ] ──▶ [ Static Rule Checker ] ──▶ [ Syntax & Clock Checks ]    |
|         │                                                                             |
|         ▼                                                                             |
|  [ Synopsys VCS / Xcelium ] ──▶ [ Simulation Run ] ──▶ [ VCD / FST Waveform Trace ]   |
|         │                                                                             |
|         ▼                                                                             |
|  [ SVA Assertion Engine ] ──▶ [ Anomaly Trap ] ──▶ [ Auto-Root Cause Diagnostic Log ]|
+---------------------------------------------------------------------------------------+
`
- **Assertion Coverage:** 100% protocol assertions passing for handshakes ( ssert_handshake_valid).
- **Target EDA Integrations:** Cadence Xcelium, Synopsys VCS, Verilator, and GTKWave/Verdi tracers.
</details>

---

### 🔹 [PROJECT 02] SNN-Based Object Detection (Microchip PolarFire SoC)
Spiking Neural Networks PolarFire SoC FPGA RISC-V Co-Design Edge AI Acceleration
- Exploring hardware-oriented deployment of Spiking Neural Networks on the PolarFire SoC FPGA platform.
- Evaluates event-driven neural computation, low-power neuromorphic architectures, and systolic-array acceleration under strict thermal and memory budgets.

<details>
<summary><b>🔍 [CLICK TO EXPAND] HARDWARE ACCELERATOR MAPPING SPEC</b></summary>
<br>

`
  PolarFire SoC FPGA Hardware Subsystem:
  ┌────────────────────────┐      AXI4 Bus      ┌────────────────────────────────┐
  │ 4x 64-bit RISC-V Cores │ ◀────────────────▶ │ Neuromorphic SNN Accelerator   │
  │ (Control & Supervisory)│                    │ • Leaky Integrate & Fire (LIF) │
  └────────────────────────┘                    │ • Event-Driven Spike Sparsity  │
                                                │ • Fixed-Point Synaptic Weights │
                                                └────────────────────────────────┘
`
- **Power Optimization:** Leverages PolarFire non-volatile flash architecture for near-zero static power dissipation.
- **Compute Efficiency:** Employs spike-based event computation to eliminate multiplications during idle pixel frames.
</details>

---

### 🔹 [PROJECT 03] 22 nm 6T FinFET SRAM Cell — Area Scaling & Layout
FinFET SRAM Memory KLayout SEMulator3D Synopsys Custom Compiler
- Designed and analysed a 6-Transistor (6T) FinFET SRAM memory cell targeting the 22 nm process node.
- Evaluated 3D process emulation profiles using SEMulator3D, transistor fin pitch sizing, read/write static noise margins (SNM), and silicon area scaling in KLayout.

<details>
<summary><b>🔍 [CLICK TO EXPAND] MEMORY CELL CHARACTERISTICS &amp; SNM METRICS</b></summary>
<br>

| Parameter | 22nm FinFET Dimension | Design Implication |
| :--- | :--- | :--- |
| **Fin Pitch (FP)** | 30 nm | Minimizes parasitic capacitance between adjacent channel fins |
| **Gate Length ($)** | 22 nm | Delivers high drive current ({on}$) with mitigated DIBL |
| **Contact Poly Pitch (CPP)** | 60 nm | Dictates overall 6T bitcell area footprint |
| **Read SNM** | > 180 mV | Ensures non-destructive read operations under supply variation |
| **Hold SNM** | > 280 mV | Guaranteed data retention down to {DD,min} = 0.65	ext{V}$ |
</details>

---

### 🔹 [PROJECT 04] 180 nm CMOS Capacitance-to-Digital Converter (CDC)
Cadence Virtuoso Spectre Simulator 180 nm CMOS Analog Layout PVT Sensitivity
- Designed and simulated an analog Capacitance-to-Digital Converter at the transistor level using Cadence Virtuoso and Spectre.
- Investigated device aspect ratios, switch charge injection, parasitic extraction, and sensitivity across process, voltage, and temperature (PVT) variations.

<details>
<summary><b>🔍 [CLICK TO EXPAND] TRANSISTOR SIZING &amp; SIMULATION LOG</b></summary>
<br>

`
  Process Technology : 180 nm Bulk CMOS (TSMC/SCL PDK)
  Supply Voltage     : 1.8 V Nominal
  Sampling Topology  : Switched-Capacitor Charge-Redistribution Architecture
  PVT Test Matrix    :
    • Corners : TT (27°C), FF (-40°C), SS (125°C), SF, FS
    • Sensitivity : < 0.15% deviation across ±10% VDD swing
    • Output     : Monotonic 10-bit digital capacitive representation
`
</details>

---

### 🔹 [PROJECT 05] 4.8 GHz PLL Analog & Mixed-Signal Verification
Cadence Virtuoso Spectre PLL Subsystem Phase Noise Analog Verification
- Verified a 4.8 GHz Phase-Locked Loop (PLL) sub-system consisting of a Phase Frequency Detector (PFD), charge pump, passive loop filter, Voltage-Controlled Oscillator (VCO), and frequency divider.
- Validated lock range, settling behaviour, jitter performance, phase noise, and open-loop stability criteria.

<details>
<summary><b>🔍 [CLICK TO EXPAND] PLL PERFORMANCE TARGETS &amp; JITTER BUDGET</b></summary>
<br>

- **Center Frequency:** 4.8 GHz (Lock range: 4.4 GHz to 5.2 GHz).
- **Phase Noise:** $-112	ext{ dBc/Hz}$ offset at 1 MHz.
- **Settling Time:** $< 1.8\ \mu	ext{s}$ to within 100 kHz frequency error window.
- **Phase Margin:** ^\circ$ open-loop stability margin across all corners.
</details>

---

### 🔹 [PROJECT 06] Gesture-to-Speech FPGA System
Verilog HDL Xilinx Vivado FSM Controller Sensor Interfacing Real-Time Signal Processing
- Developed an FPGA-based real-time gesture interpretation system utilising analog flex sensors and ADC signal translation.
- Synthesized a low-latency Mealy/Moore finite state machine in Verilog to translate multi-finger kinematic profiles directly into audio output indices.

<details>
<summary><b>🔍 [CLICK TO EXPAND] FSM ARCHITECTURE &amp; TIMING</b></summary>
<br>

`
  [ ADC Sensor Stream ] ──▶ [ Glitch Filter & Debounce ]
                                    │
                                    ▼
       [ FSM State Engine: IDLE ➔ CAPTURE ➔ CLASSIFY ➔ AUDIO_INDEX ]
                                    │
                                    ▼
                            [ Audio Codec Output ]
`
- Fully offline, deterministic latency ($< 15	ext{ ms}$ sensor-to-speech response).
</details>

---

### 🔹 [PROJECT 07] [SEMICON India 2026] Semiconductor Image Restoration
Python PyTorch 2.0 NAFNet Semiconductor Metrology SEM Denoising KLA Track
- Developed an end-to-end deep learning restoration architecture for degraded Scanning Electron Microscope (SEM) semiconductor wafer inspection signals.
- Implemented non-linear activation-free (NAFNet) blocks achieving **35.10 dB PSNR** and **0.9885 SSIM** with sub-2.4ms inference for critical-dimension (CD) metrology.
- **Repository:** [github.com/ilambharathim/TEAM-KIRAH_KLA_PSO1](https://github.com/ilambharathim/TEAM-KIRAH_KLA_PSO1)

<details>
<summary><b>🔍 [CLICK TO EXPAND] BENCHMARK METRICS &amp; KLA TEST PROTOCOL</b></summary>
<br>

| Metric | Target Baseline | TEAM KIRAH NAFNet | Improvement Margin |
| :--- | :--- | :--- | :--- |
| **Peak SNR (PSNR)** | 29.40 dB | **35.10 dB** | **+5.70 dB Gain** |
| **Structural Similarity (SSIM)**| 0.9200 | **0.9885** | High Edge Fidelity |
| **LPIPS Perceptual Loss** | 0.1450 | **0.0520** | 64% Distortion Reduction |
| **Inference Latency (H100)** | 12.0 ms | **&lt; 2.4 ms** | Real-Time Metrology Speed |
</details>

---

## 🧰 03 // TECHNICAL SKILLS MATRIX

<table width="100%">
  <tr>
    <td width="33%" valign="top">
      <b style="color:#38BDF8;">⚡ HDL &amp; RTL</b><br>
      • SystemVerilog (IEEE 1800)<br>
      • Verilog-2001 (IEEE 1364)<br>
      • VHDL<br>
      • Datapath Pipelining &amp; FSMs
    </td>
    <td width="33%" valign="top">
      <b style="color:#F59E0B;">🔬 Cadence Toolchain</b><br>
      • Virtuoso Schematic Capture<br>
      • Virtuoso Layout Suite<br>
      • Spectre Circuit Simulator<br>
      • Xcelium Logic Simulator
    </td>
    <td width="33%" valign="top">
      <b style="color:#10B981;">💻 Synopsys Toolchain</b><br>
      • Custom Compiler<br>
      • HSPICE Analog Simulator<br>
      • VCS (Verilog Compiled Sim)<br>
      • Verdi Advanced Debugger
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <b style="color:#EC4899;">📐 Physical &amp; TCAD</b><br>
      • KLayout (GDSII / OASIS)<br>
      • SEMulator3D (Process Emulation)<br>
      • 22nm FinFET &amp; 180nm CMOS<br>
      • DRC / LVS Physical Rules
    </td>
    <td width="33%" valign="top">
      <b style="color:#A855F7;">🚀 FPGA &amp; Embedded</b><br>
      • Microchip PolarFire SoC (RISC-V)<br>
      • AMD Xilinx Vivado Suite<br>
      • Microcontroller Bus I/O (SPI/I2C)<br>
      • Logic Analyzer Hardware Tracing
    </td>
    <td width="33%" valign="top">
      <b style="color:#06B6D4;">⚙️ Automation &amp; Scripting</b><br>
      • Python (PyTorch, NumPy, SciPy)<br>
      • C / C++ (Hardware Drivers)<br>
      • Linux Shell / Bash Automation<br>
      • Git Version Control
    </td>
  </tr>
</table>

---

## 💼 04 // ENGINEERING EXPERIENCE

`
May 2026 – Jun 2026   Research Intern
                      IIITDM Kancheepuram
                      • Researched hardware-efficient AI accelerator architectures for edge platforms.
                      • Studied quantization and memory-bandwidth optimization for resource-constrained inference.

Oct 2025 – Nov 2025   Project Intern — Synopsys Centre of Excellence
                      Chennai Institute of Technology
                      • Designed and simulated a 180 nm CMOS Capacitance-to-Digital Converter in Cadence Virtuoso.
                      • Executed transistor-level AC/transient simulations, device sizing, and parasitic analysis.

May 2025 – Jun 2025   Embedded Systems & Firmware Intern
                      Phoenix Soft Tech
                      • Developed firmware routines for microcontroller peripherals and communication buses (SPI/I2C/UART).
                      • Integrated sensor acquisition modules with low-power embedded processing workflows.
`

---

## 📐 05 // SEMICONDUCTOR IMPLEMENTATION PIPELINE

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./pipeline.svg">
  <source media="(prefers-color-scheme: light)" srcset="./pipeline-light.svg">
  <img src="./pipeline.svg" width="100%" alt="Hardware Engineering Pipeline">
</picture>

</div>

---

## 🎓 06 // EDUCATION &amp; CREDENTIALS

**Chennai Institute of Technology**  
*Bachelor of Electronics and Communication Engineering*  
2024 – 2028  

#### 🏆 Technical Honors
- **DVCon India 2026** — Contributing to technical work on AI-assisted hardware verification and intelligent design analysis.
- **Central India Hackathon** — Top 7 Finalist (100+ national teams); engineered automated air-quality response system under SDG-3.
- **SEMICON India Hackathon 2026 (KLA Track PS01)** — Team Leader (Team KIRAH); engineered SOTA deep-learning restoration pipeline for degraded semiconductor SEM inspection images.

#### 📜 Certifications
VLSI for Beginners • VLSI Design (Internshala) • System Design through Verilog (NPTEL) • Verilog HDL (Udemy) • Introduction to IoT (Cisco) • Industrial IoT (Cisco) • Sensors and Actuators (NPTEL)

---

## 📬 07 // CONNECT &amp; COLLABORATE

- **Official Email:** [ilambharathim.ece2024@citchennai.net](mailto:ilambharathim.ece2024@citchennai.net)
- **GitHub Profile:** [github.com/ilambharathim](https://github.com/ilambharathim)
- **Primary Domain:** Chennai, India
