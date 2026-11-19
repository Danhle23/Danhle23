# Lê Thanh Danh (`@Danhle23`)

**Electronics & Telecommunications Engineering (Control & Automation Track) @ VNUHCM – University of Science (HCMUS)**  
**Digital IC (SystemVerilog RTL) · Embedded C/C++ & Industrial IoT · Scientific Computing**

[![Portfolio Website](https://img.shields.io/badge/Specification%20%26%20Live%20Bench-danhle23.github.io-141413?style=flat-square)](https://danhle23.github.io)
[![Email](https://img.shields.io/badge/Email-danhle2305%40gmail.com-C84B31?style=flat-square)](mailto:danhle2305@gmail.com)
[![RTL CI](https://github.com/Danhle23/uart-controller/actions/workflows/rtl-ci.yml/badge.svg)](https://github.com/Danhle23/uart-controller)
[![IIoT C++17 CI](https://github.com/Danhle23/iiot-modbus-edge-gateway/actions/workflows/ci.yml/badge.svg)](https://github.com/Danhle23/iiot-modbus-edge-gateway)
[![ASan C++17 CI](https://github.com/Danhle23/smart-campus-parking-cpp/actions/workflows/ci.yml/badge.svg)](https://github.com/Danhle23/smart-campus-parking-cpp)

---

### Engineering Focus

- **Digital IC & RTL Verification:** Synthesizable **SystemVerilog (IEEE 1800-2012)** IP cores, **AMBA APB3** memory-mapped peripherals, synchronous FIFOs, 2-FF CDC synchronizers, BFM testbenches, and automated **Yosys Synthesis / Verilator / Icarus Verilog** CI (`2,081 cells / 427 DFFs / 0 latches`).
- **Systems C++17 & Industrial Fieldbus:** Deterministic **zero-heap C++17 / Embedded C** protocol engines, lock-free SPSC DMA ring buffers, EMI noise-resilient **RS485 / Modbus-RTU** codecs, and **ASan/UBSan**-verified custom data structures.
- **DSP, Numerical & Telemetry Systems:** **MATLAB OOP** numerical studios, FIR/IIR sensor noise filtering, Python/OpenCV tooling, and TypeScript/Next.js time-series telemetry.

---

### Selected Engineering Repositories

| Repository | Stack & Verification | Summary |
| :--- | :--- | :--- |
| **[uart-controller](https://github.com/Danhle23/uart-controller)** | `SystemVerilog` `AMBA APB3` `Verilator CI` | Synthesizable **AMBA APB3 UART SoC Peripheral IP Core** with dual `16×8` TX/RX FIFOs, 16-bit baud divider, 2-FF CDC, W1C parity/framing/overrun registers & maskable `IRQ`. |
| **[iiot-modbus-edge-gateway](https://github.com/Danhle23/iiot-modbus-edge-gateway)** | `Embedded C++17` `Zero-Heap` `Modbus-RTU` | Deterministic industrial telemetry engine featuring compile-time `constexpr` CRC-16, lock-free SPSC DMA ring buffer, RS485 glitch recovery & 3-phase/cold-chain fault latching. |
| **[smart-campus-parking-cpp](https://github.com/Danhle23/smart-campus-parking-cpp)** | `C++17` `Custom ADTs` `ASan/UBSan CI` | **Team Lead (8 members)** — Custom Hash Table, Binary Min-Heap Dijkstra routing, Levenshtein OCR plate recovery & two-phase transactional rollback (`24/24` tests, 0 leaks). |
| **[DoAn-PhuongPhapTinh-MATLAB](https://github.com/Danhle23/DoAn-PhuongPhapTinh-MATLAB)** | `MATLAB R2026a` `OOP AppBase` | 6-Tab Scientific Studio decoupling UI controllers from **16 standalone numerical solvers** passing `25/25` precision benchmarks ($10^{-15}$ accuracy). |
| **[giathat](https://github.com/Danhle23/giathat)** | `TypeScript` `Next.js` `Prisma` | Time-series e-commerce price-history tracker detecting synthetic pre-sale markups and visualizing genuine discount baselines. |

---

### Interactive Timing & Protocol Workbench

Explore live cycle-accurate **APB3 UART waveforms**, **RS485 Modbus-RTU CRC-16 frames**, **50Hz DSP IIR filtering**, and my **1-Page ATS Resume (PDF)** at **[danhle23.github.io](https://danhle23.github.io)**.
