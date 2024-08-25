# process_simulator

## Overview

This C++ project simulates various CPU scheduling algorithms to model process management in an operating system. The simulation provides insights into different scheduling strategies and their performance.

## Features

- **First-Come, First-Served (FCFS)**
- **Shortest-Job-First (SJF)** (Non-Preemptive and Preemptive)
- **Round-Robin (RR)** (Configurable Time Slice)
- **Preemptive Priority Scheduling** (Processes with random priorities)

Processes have random arrival and CPU burst times, generated using an exponential distribution. The simulator includes a context switch time of 14 milliseconds.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/dixit2894/process_simulator.git
2. Navigate to the project directory:
   ```bash
   cd process_simulator
3. Compile the code using a C++ compiler:
   ```bash
   g++ -o cpu_scheduler main.cpp


