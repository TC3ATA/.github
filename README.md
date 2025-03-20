Amateur Radio Experiments for Space (Türkiye)
This project provides a structured roadmap for those interested in amateur radio, software-defined radio (SDR), APRS, pico balloons, and CubeSats.

Each step is supported by documentation, allowing a gradual progression from basic to advanced experiments in radio and space communication.

Table of Contents
Contributing
Requirements
Experiment Steps
License
Contributing
This is an open-source project, and contributions are welcome. You can:

Complete any step and upload your work to GitHub.
Improve the documentation by adding new details.
Refer to the CONTRIBUTING.md file for contribution guidelines.

Requirements
To successfully complete the experiments, you will need:

Software-defined radio (RTL-SDR, HackRF, or similar)
Raspberry Pi / ESP32 / Arduino
GPS module
VHF/UHF radio (e.g., Baofeng UV-5R)
Helium gas (for pico balloons)
Soldering equipment
Open-source software (GQRX, SDR#, APRS FI, HABHUB, etc.)
Experiment Steps
A. Basic Radio and Antenna Experiments
1. Listening to Radio Signals with Standalone Receivers
Tuning into FM, AM, and SW signals
Understanding radio wave propagation
Getting started with SDR receivers
2. Simple Antenna Design and Measurements
Building a basic dipole antenna
Calculating antenna gain
3. Directional Antenna Design (Yagi and Helix Antennas)
Designing a Yagi antenna for fox hunting
Using open-source antenna simulation software
4. First Fox Hunting (Hidden Transmitter Hunting) Experiment
Using 433 MHz transmitter and receiver modules for direction finding
Conducting field tests
B. APRS and Data Transmission
5. Introduction to APRS and Its Applications
Exploring APRS FI map
Understanding open-source APRS servers
6. Sending Basic APRS Messages
Generating APRS signals using Raspberry Pi or ESP32
Integrating GPS modules
7. Multi-APRS Transmission and Tracking
Transmitting data from multiple stations
Setting up a mobile APRS station
8. Remote Sensor Monitoring with APRS
Transmitting temperature and pressure data via APRS
Comparing LoRaWAN and APRS
C. Pico Balloon Experiments
9. Introduction to Pico Balloons, Materials, and Preparation
Understanding helium balloon characteristics
Pre-flight calculations
10. First Basic Pico Balloon Launch
Conducting a small-scale test launch
Tracking signals on the APRS map
11. Flight and Landing Calculations
Predicting trajectory based on wind conditions
Using platforms like HABHUB
12. Long-Duration Pico Balloon Experiments
Implementing lightweight solar panels
Collecting data between 10,000m and 30,000m altitude
D. Satellite Communication and Radio Experiments
13. Receiving Images from NOAA and METEOR Satellites
Capturing signals using SDR
Processing satellite images with WxToImg
14. APRS and SSTV Experiments with the International Space Station (ISS)
Listening to the ISS APRS frequency
Receiving images via Slow Scan Television (SSTV)
15. Monitoring Amateur Satellites (CubeSats)
Receiving signals from Funcube, AO-91, and similar satellites
16. Setting Up an SDR Server with Raspberry Pi
Establishing a remote SDR station
E. Introduction to CubeSat Development
17. Understanding CubeSat: Structural and Electronic Components
Learning about CubeSat design processes
Studying power management and communication systems
18. Developing a Basic CubeSat Model (Desktop Simulation)
Planning missions using simulations
Utilizing open-source CubeSat software
19. Integrating SDR and APRS for CubeSats
Developing an SDR-based communication module
20. Initial Tests for CubeSat Development (Ground-Based Experiments)
Establishing communication with a ground station
21. Developing a Ground Station for Amateur Satellite Communication
Identifying hardware and software requirements for a small-scale ground station
22. Initiating CubeSat Development Process
Prototyping and testing
Preparing for ground and launch testing
License
This project is licensed under the MIT License.
