# Low-Power CAM Architecture (LP-TG-PCAM)

## Project Overview

This project presents the design and simulation of a low-power, precharge-free Content Addressable Memory (CAM) architecture implemented in 45nm CMOS technology.The objective is to reduce dynamic power consumption caused by traditional matchline precharge mechanisms while maintaining reliable and scalable search performance.

---

## Objectives

- Eliminate the conventional precharge phase  
- Reduce matchline switching activity  
- Improve signal integrity using Transmission-Gate based XNOR logic  
- Optimize Power-Delay Product (PDP)  
- Validate performance using 1000-sample Monte Carlo simulation  

---

## Architecture Features

- Transmission-Gate based full-swing XNOR comparison cell  
- Static mismatch-based evaluation mechanism  
- Segmented matchline structure  
- Reduced clock dependency  
- Improved robustness under voltage scaling  

---

## Tools and Technology

- Cadence Virtuoso  
- 45nm CMOS Technology  
- Transient Analysis  
- Monte Carlo Simulation  

---

## Performance Summary

| Design        | Power (nW) | Delay (ns) | PDP (aJ) |
|---------------|------------|------------|----------|
| N-PCAM        | 187.2      | 13.21      | 2.47     |
| TG-PCAM       | 745.4      | 13.13      | 9.79     |
| LP-TG-PCAM    | 129.1      | 25.23      | 1.96     |

---

## Applications

- AI accelerators  
- High-speed search engines  
- Networking hardware  
- Fully associative cache systems  
- Edge computing platforms  
