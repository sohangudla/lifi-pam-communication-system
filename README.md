# Wireless Li-Fi Communication System using Pulse Amplitude Modulation

System design project for **23ECE384 Communication Systems Laboratory** (B.Tech ECE, Amrita School of Engineering, Bengaluru, AY 2025-26).

A visible-light (Li-Fi) link built from discrete analog components on a breadboard that sends a sine wave through light and recovers it at the receiver.

## System
- **Transmitter:** a 390 Hz sine message is sampled by a 4 kHz square-wave carrier in a transistor switching circuit to form PAM; a BJT drives a high-brightness LED, so the light intensity follows the PAM signal.
- **Optical channel:** free-space visible light.
- **Receiver:** a solar panel acts as the photodetector, and an RC low-pass filter removes the 4 kHz carrier to recover the message, which is checked against the input on an oscilloscope.

## Files
- `LiFi_PAM_Communication_System_Report.pdf` — report with block diagram, circuit, components and results

Team project; team members are listed in the report.
