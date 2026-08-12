FPGA Digital Clock & Alarm - Simulation Testbench

This repository contains the Verilog HDL testbench used to simulate and verify the FPGA Digital Clock & Alarm design.

📌 Purpose

The testbench is used to verify the functional behavior of the digital clock and programmable alarm before FPGA hardware implementation.

Simulation is performed using Xilinx Vivado.

🧪 Verification Areas

The testbench verifies:

- Clock initialization
- Clock progression
- Hour setting
- Minute setting
- Alarm hour setting
- Alarm minute setting
- Alarm enable/disable
- Alarm triggering
- Buzzer activation
- Alarm LED operation
- STOP button functionality
- MODE button functionality

⚙️ Simulation

For simulation purposes, the clock timing is adjusted so that clock and alarm operations can be observed efficiently in simulation.

This allows the functionality to be verified without waiting for real-time intervals.

🔍 Expected Results

During simulation:

1. The digital clock starts from the configured initial time.
2. The clock increments continuously.
3. Clock hours and minutes can be configured.
4. The alarm time can be programmed.
5. When the current time matches the alarm time, the alarm output is activated.
6. The STOP control deactivates the alarm.

📂 Project Files

FPGA-Digital-Clock-Testbench/
│
├── README.md
└── digital_clock_tb.v

🖥️ Simulation Waveform

Add a screenshot of your Vivado simulation waveform here.

🛠️ Tools Used

- Verilog HDL
- Xilinx Vivado
- Vivado Simulator

🔗 Related Project

Main FPGA Digital Clock & Alarm:

https://github.com/arun-013-s/FPGA-Digital-Clock-alarm1

👨‍💻 Author

Arun S

ECE Student | FPGA & Digital Design | Verilog HDL 
