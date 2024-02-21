# VHDL Assignment
This repository contains VHDL code and test cases for embedded system assignment. The code is compiled using GHDL and the waveforms is visualized using GTKWave. The development environment used is Notepad++.

# Prerequisites
Ensure you have the following software installed on your system:
- GHDL
- GTKWave
- Notepad++

# Installing GHDL
Follow the instructions on the GHDL GitHub repository to install GHDL on your system.

# Installing GTKWave
Follow the instructions on the GTKWave website to install GTKWave on your system.

# Running the Test Cases 
Describe how to run the test cases using GHDL and how to visualize waveforms with GTKWave.

# Example Command for Running GHDL
```bash
ghdl -a vhdl_code.vhdl
ghdl -a test_bench.vhdl
ghdl -e test_bench_entity
ghdl -r test_bench_entity --vcd=vcd_file.vcd
```

# Example Command for GTKWave
```bash
gtkwave vcd_file.vcd
```
