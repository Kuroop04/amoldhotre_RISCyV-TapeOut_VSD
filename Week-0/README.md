# Week 0 Assignment 
### Installation of Open Source EDA tools
#### 1. Yosys
```bash
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ git submodule update --init --recursive
$ make 
$ sudo make install
```
<img width="986" height="239" alt="Screenshot 2025-09-20 194759" src="https://github.com/user-attachments/assets/a6759f4c-f81e-4df0-a181-23d8749e045d" />
#### 2. Icarus Verilog  (iverilog)
```bash
$ sudo apt-get install iverilog
```
<img width="973" height="694" alt="Screenshot 2025-09-20 194956" src="https://github.com/user-attachments/assets/6cba27f4-70ca-47e4-9567-4c067ac0369c" />
#### 3. GTKwave
```bash
$ sudo apt install gtkwave
```
<img width="986" height="239" alt="Screenshot 2025-09-20 194759" src="https://github.com/user-attachments/assets/c639969d-7f41-441b-9d94-0d1733de735f" />
