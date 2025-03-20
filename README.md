# Amateur Radio Experiments for Space (Türkiye)

This repository serves as an open-source initiative for amateur radio, software-defined radio (SDR), APRS, pico balloons, and CubeSat experiments. It provides a structured learning path for enthusiasts, researchers, and students.  

## Project Overview

- **Skill Level:** Beginner to Advanced  
- **Topics Covered:** Amateur radio, SDR, APRS, pico balloons, satellite communications, CubeSat development  
- **Contribution:** Open to the community  

## Table of Contents

- [Requirements](#requirements)  
- [Experiment Steps](#experiment-steps)  
  - [Basic Radio and Antenna Experiments](#basic-radio-and-antenna-experiments)  
  - [APRS and Data Transmission](#aprs-and-data-transmission)  
  - [Pico Balloon Experiments](#pico-balloon-experiments)  
  - [Satellite Communication and Radio Experiments](#satellite-communication-and-radio-experiments)  
  - [Introduction to CubeSat Development](#introduction-to-cubesat-development)  
- [Repository Structure](#repository-structure)  
- [Code Samples](#code-samples)  
- [License](#license)  
- [Contributing](#contributing)  

## Requirements

To complete the experiments, the following components and tools are required:

- **Hardware:**
  - Software-defined radio (RTL-SDR, HackRF, or equivalent)  
  - Microcontrollers (Raspberry Pi, ESP32, Arduino)  
  - GPS module for APRS tracking  
  - VHF/UHF radio (Baofeng UV-5R or equivalent)  
  - Helium gas for pico balloons  
  - Soldering equipment  

- **Software:**
  - SDR tools (GQRX, SDR#)  
  - APRS FI, HABHUB for tracking  
  - WxToImg for satellite imagery  

## Experiment Steps

### Basic Radio and Antenna Experiments

1. Listening to FM, AM, and SW signals using an SDR receiver.  
2. Building and measuring a basic dipole antenna.  
3. Designing a directional Yagi antenna for fox hunting.  
4. Implementing a 433 MHz transmitter and performing fox hunting tests.  

### APRS and Data Transmission

5. Introduction to APRS networks and the APRS FI map.  
6. Sending basic APRS messages using Raspberry Pi or ESP32.  
7. Implementing multi-APRS transmission and mobile tracking.  
8. Remote environmental data collection via APRS.  

### Pico Balloon Experiments

9. Understanding balloon physics and flight preparation.  
10. Launching a test pico balloon and tracking it via APRS.  
11. Calculating flight paths and landing predictions with HABHUB.  
12. Experimenting with long-duration solar-powered tracking.  

### Satellite Communication and Radio Experiments

13. Receiving weather images from NOAA and METEOR satellites.  
14. Listening to APRS and SSTV transmissions from the ISS.  
15. Monitoring amateur satellites such as Funcube and AO-91.  
16. Setting up an SDR-based ground station.  

### Introduction to CubeSat Development

17. Learning CubeSat structure, power, and communication systems.  
18. Simulating a CubeSat using open-source tools.  
19. Integrating SDR and APRS for CubeSat telemetry.  
20. Conducting ground-based CubeSat communication tests.  
21. Setting up a functional CubeSat ground station.  
22. Prototyping and pre-launch testing of a CubeSat module.  

## Repository Structure

Amateur-Radio-Experiments
│── docs/ # Documentation and guides
│── hardware/ # Circuit diagrams and hardware designs
│── software/ # Python, Arduino, and SDR scripts
│── aprs/ # APRS tracking and telemetry scripts
│── pico-balloon/ # Pico balloon flight scripts
│── cubesat/ # CubeSat prototype software
│── .gitignore # Git ignore file
│── LICENSE # License file
│── README.md # Project README
│── CONTRIBUTING.md # Contribution guidelines


## Code Samples

### SDR Signal Scanner (`software/rtl_sdr_scan.py`)

```python
import rtlsdr

sdr = rtlsdr.RtlSdr()

sdr.sample_rate = 2.048e6  
sdr.center_freq = 145000000  
sdr.gain = 4  

samples = sdr.read_samples(256*1024)
print("Captured samples:", len(samples))

sdr.close()
```
## Code Samples

### Sending APRS Messages (aprs/send_aprs.py)

```python
import aprslib

callsign = "N0CALL"
latitude = "40.7128N"
longitude = "74.0060W"
message = "Testing APRS transmission"

packet = f"{callsign}>APRS,TCPIP*::{latitude}/{longitude}: {message}"

AIS = aprslib.IS(callsign, passwd="12345", host="rotate.aprs2.net", port=14580)
AIS.connect()
AIS.sendall(packet)
AIS.close()
print("APRS packet sent!")
```



