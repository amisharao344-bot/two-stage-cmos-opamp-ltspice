# Two-Stage CMOS Operational Amplifier Design (LTspice)

## Overview

This project presents the **design and simulation of a two-stage CMOS operational amplifier** using LTspice.

The goal was to design a stable op-amp with high gain and MHz-level bandwidth using CMOS transistor stages and Miller compensation.



## Specifications

| Parameter            | Value            |
| -------------------- | ---------------- |
| DC Gain              | **63 dB**        |
| Unity Gain Bandwidth | **~1 MHz**       |
| Phase Margin         | **~60°**         |
| Supply Voltage       | **1.8 V**        |
| Compensation         | Miller Capacitor |



## Architecture

The op-amp consists of three main blocks:

### 1️ Differential Input Stage

* NMOS differential pair
* PMOS current mirror load
* Converts differential input signal to single-ended output

### 2️ Second Gain Stage

* Common source amplifier
* Provides additional voltage gain

### 3️ Frequency Compensation

* Miller capacitor used for stability
* Improves phase margin and prevents oscillations



## Simulation Method

AC analysis was performed in **LTspice** to evaluate:

* Open-loop gain
* Frequency response
* Phase margin
* Unity gain bandwidth

The circuit was simulated using CMOS transistor models and a 1.8 V supply.


## Key Learning Outcomes

* CMOS analog circuit design
* Two-stage operational amplifier architecture
* Current mirror biasing
* Miller compensation
* Stability and phase margin analysis
* LTspice simulation techniques



## Tools Used

* **LTspice**
* CMOS transistor models




## Author

**Amisha Rao**

Electronics Engineering Student
Interested in **Analog IC Design and VLSI**
