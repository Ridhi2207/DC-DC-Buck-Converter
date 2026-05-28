# DC-DC-Buck-Converter
# B2-G1: Buck Converter Project
Course: EE 252: Electrical Machines and Power Electronics Lab (EMPEL)
Institution: Indian Institute of Technology (IIT) Indore
Batch & Group: B2-G1
Team Members: Ridhi Shakkar, Nishank, Abhishek Lariya, Piyush

## Project Overview

This project presents the design, hardware implementation, and waveform analysis of a DC-DC Buck Converter. The converter is designed to step down an input voltage of 12.5 V to an output voltage of 7.5 V at 1 A load current. The operation is verified in both Continuous Conduction Mode (CCM) and Discontinuous Conduction Mode (DCM).

## Specifications

* Input Voltage: 12.5 V
* Output Voltage: 7.5 V
* Switching Frequency: 12.5 kHz
* Output Current: 1 A
* Group: G2-B1

## Hardware Implementation

The hardware setup includes a gate driver board, soldered driver circuit, perf board implementation, and complete buck converter setup. The output voltage was measured experimentally and the hardware waveforms were observed using an oscilloscope.

## Waveform Analysis

The converter was tested in CCM and DCM modes. In CCM, the inductor current remains continuous throughout the switching cycle. DCM was demonstrated by reducing the switching frequency, causing the inductor current to fall to zero before the next switching cycle. The diode voltage, switch current, and output current waveforms were also observed and analyzed.

## MATLAB Simulation

MATLAB simulation was performed to verify the converter operation. CCM and DCM waveforms were obtained, with DCM demonstrated at a reduced switching frequency of 1 kHz.

## Conclusion

The buck converter successfully steps down 12.5 V DC input to approximately 7.5 V output at 1 A load current. Hardware and MATLAB results confirm the expected operation in CCM, and DCM is demonstrated by reducing the switching frequency.
