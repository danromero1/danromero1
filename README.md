# Hi, I’m Daniel Romero

Electrical Engineering student focused on embedded systems, mixed-signal hardware, and reliability research. I like building real devices end-to-end: schematic → PCB → firmware → validation (scope + DMM on the bench).

- IC reliability research: predictive aging / degradation modeling for drone electronics (ESC-focused)
- Mixed-signal audio: 4-layer STM32-based guitar effects pedal with external ADC/DAC + real-time DSP
- Digital design: FPGA/Verilog projects (timing, video, hardware state machines)
- Open to entry-level EE roles, co-ops, and internships
- Contact: daniel.romero@ieee.org
- Portfolio: https://electricalromero.com

---

## Core skills

Embedded / firmware: C, C++, peripheral bring-up, timing-sensitive protocols, fixed-point math, FSM-based control  
Hardware / PCB: KiCAD, 4-layer layout, grounding/return paths, decoupling, mixed-signal partitioning  
Digital design: Verilog, FPGA development, VGA timing, synthesized game/state logic  
Validation: oscilloscope + DMM, interface debugging, sensor/ADC verification  
Tools: STM32CubeIDE, MPLAB X, LTspice, Git

---

## Featured projects

### Mixed-Signal Guitar Effects Pedal (STM32 + external ADC/DAC)
Programmable guitar effects pedal built on a 4-layer mixed-signal PCB with real-time DSP on an STM32. Designed for low-noise audio conversion and deterministic buffering.
- Highlights: 3rd-order Butterworth anti-aliasing, EQ, soft-clipping distortion, USB-C power
- Engineering focus: analog/digital isolation, signal integrity, power distribution, firmware DSP pipeline  
Repo: [Mixed-Signal-Guitar-Effects-Pedal](https://github.com/danromero1/Mixed-Signal-Guitar-Effects-Pedal)

### WBGT Heat Stress Monitor (PIC18F4321)
Portable WBGT heat stress monitor that fuses temperature/humidity, light, and wind measurements to compute heat risk levels and display real-time safety guidance.
- Highlights: DHT11 single-wire protocol, BH1750 bit-banged I²C, ADC wind sensing, 20×4 LCD UI
- Engineering focus: timing-sensitive comms, fixed-point computation, resource-aware firmware  
Repo: [Wet-Bulb-Globe-Temperature-Embedded-Project](https://github.com/danromero1/Wet-Bulb-Globe-Temperature-Embedded-Project)

### Verilog Pong Game (Nexys A7 FPGA + VGA)
Hand-written Verilog implementation of Pong on an FPGA with VGA output, real-time paddle control, and hardware collision detection.
- Highlights: 640×480@60Hz VGA timing, 25 MHz pixel clock, frame-synced updates
- Engineering focus: synchronous design, counters/timing, combinational collision logic, modular RTL  
Repo: [Verilog-Pong-Game](https://github.com/danromero1/Verilog-Pong-Game)

### Wireless PID Motor Control System (Arduino + nRF24L01 + LabVIEW)
Closed-loop motor speed control with wireless command and telemetry plus a LabVIEW dashboard for monitoring and tuning.
- Highlights: encoder-based RPM feedback, anti-windup PID, bidirectional RF packets, real-time plotting/logging
- Engineering focus: real-time scheduling, interrupt-driven measurement, control stability, system integration  
Repo: [Wireless-Motor-Control-PID](https://github.com/danromero1/Wireless-Motor-Control-PID)

### STM32 Demo PCB (KiCAD)
First end-to-end STM32 board design created to learn professional schematic and PCB fundamentals.
- Highlights: clock/reset/boot circuitry, regulation and decoupling, SWD header, manufacturing-ready outputs
- Engineering focus: datasheet-driven design, ERC/DRC compliance, layout fundamentals  
Repo: [STM32-Demo-PCB](https://github.com/danromero1/STM32-Demo-PCB)

---

## Connect

LinkedIn: https://www.linkedin.com/in/daniel-romero-ee/  
GitHub: https://github.com/danromero1  
Email: daniel.romero@ieee.org  
Portfolio: https://electricalromero.com
