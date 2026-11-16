# Closed-Loop DC-DC Buck Converter Design and Simulation

## Overview
This project focuses on the design and simulation of a DC-DC Buck Converter using MATLAB Simulink (Simscape Electrical). A buck converter is a DC-DC power electronic converter that steps down an input DC voltage to a lower output voltage using switching-based power conversion.

The model incorporates a closed-loop voltage feedback mechanism to study output voltage regulation under PWM-based switching control.

## Objectives
- Design and simulate a DC-DC buck converter.
- Understand switching-based voltage step-down conversion.
- Implement PWM-based gate control for the MOSFET switch.
- Study output voltage regulation using a feedback control mechanism.
- Analyse the role of passive components in power conversion.

## Circuit Components
- DC Voltage Source
- MOSFET Switching Device
- Diode
- Inductor
- Output Capacitor
- Resistive Load
- PWM Generator
- Voltage Measurement Blocks

## Working Principle

The buck converter operates by controlling the ON and OFF states of a MOSFET switch.

- **MOSFET ON:** Energy is transferred from the DC source to the inductor and load.
- **MOSFET OFF:** The freewheeling diode provides a path for inductor current to continue flowing through the load.
- **LC Filter:** The inductor and capacitor help smooth the output voltage and reduce ripple.
- **Feedback Control:** The output voltage is measured and compared with a reference voltage to regulate the switching control.

For an ideal buck converter operating in Continuous Conduction Mode (CCM):

**Vo = D × Vin**

Where:
- Vo = Output Voltage
- Vin = Input Voltage
- D = Duty Cycle

## Tools and Technologies
- MATLAB
- Simulink
- Power Electronics

## Model Architecture

DC Input → MOSFET Switching → Diode → LC Filter → Resistive Load

The output voltage is measured and fed back to the control circuit for closed-loop regulation.

## Simulation Status
The circuit model and control architecture have been developed in MATLAB Simulink. 


## Applications
- DC power supply systems
- Battery-powered devices
- Renewable energy systems
- Voltage regulation circuits

