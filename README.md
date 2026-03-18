# Karthik Swaminathan
### Embedded Firmware Engineer · ARM Cortex-M & RISC-V

Firmware engineer focused on **ISA-level performance profiling**, bare-metal optimisation,
and DSP/NN kernel benchmarking on resource-constrained microcontrollers.

Currently completing **M.Sc. Embedded Systems** at TU Chemnitz,
thesis conducted in collaboration with **Infineon Technologies**, Dresden.

---

### What I work on

- Cycle-accurate benchmarking using **DWT** (ARM) and **NDS_MCYCLE / NDS_MINSTRET CSRs** (RISC-V)
- Cross-architecture **CMSIS-DSP/NN vs NMSIS/Andes** kernel analysis — FFT, FIR, convolution, pooling
- Bare-metal firmware: linker scripts, RAM execution, stack-paint measurement
- **TFLite Micro** inference deployment on ARM Cortex-M4 (PSoC6)
- Hardware simulation: **QEMU**, **Renode** — bare-metal firmware without physical boards
- Python tooling: objdump call-graph parser, .map file code-size analyser

### Platforms

| Board | Core | Toolchain |
|---|---|---|
| CY8CKIT-062 (PSoC6) | ARM Cortex-M4 (Armv7E-M) | GNU ARM 13.3 / ModusToolbox 3.4 |
| Telink B91 | Andes D25F (RV32IMACFDBP) | riscv-32-elf-gcc 7.4 / AndeSight RDS |
| STM32 | ARM Cortex-M | Keil / GCC |
| ESP32 | Xtensa LX6 | ESP-IDF |

### Tools & Libraries

`CMSIS-DSP` `CMSIS-NN` `NMSIS-DSP` `NMSIS-NN` `Andes-DSP`
`objdump` `GDB` `JTAG/SWD` `ModusToolbox` `AndeSight` `QEMU` `Renode`

---

### Pinned repos

| Repo | What it is |
|---|---|
| [arm-riscv-dsp-benchmark](https://github.com/Karthik-Swaminathan98/arm-riscv-dsp-benchmark) | Thesis benchmarking harness — cycle/stack/code-size on real silicon |
| [embedded-benchmark-analysis](https://github.com/Karthik-Swaminathan98/embedded-benchmark-analysis) | Python scripts — objdump call-graph parser, .map analyser, visualisation |

---

📍 Chemnitz / Dresden, Germany &nbsp;·&nbsp; Open to full-time EU roles
📧 karthik94870@gmail.com
🔗 [linkedin.com/in/karthik-swaminathan98](https://linkedin.com/in/karthik-swaminathan98)
