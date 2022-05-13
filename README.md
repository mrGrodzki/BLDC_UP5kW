# BLDC_UP5kW

The main task of the project: building a low-cost BLDC driver up to 5kW. The driver components should also be available during the market crisis.

To reduce the cost of the driver, each phase has a separate power module (half-bridge).

Module made on aluminum PCB, for better heat dissipation to the heat sink from the transistors in the smd housing.

# Concept:

On one heat sink there are 3 power modules (half bridge + current measurement) and one synchronous DC-DC converter for power supply. Power input and output from the boards by means of special nuts soldered to the printed circuit board.
Next to it, in the same housing, there is the main control board containing the main control microcontroller.
Large half-bridge plates made for better heat dissipation.

# SW:

Driver control code generated from STM Motor SDK. At the present stage I will not release SW because I tested HW.


# HW:

# V2.0:
Schematic:

![Alt Text](https://github.com/mrGrodzki/BLDC_UP5kW/blob/main/v2.0/schematicBLDCv2_0.png)

Aluminium PCB:

![Alt Text](https://github.com/mrGrodzki/BLDC_UP5kW/blob/main/v2.0/PCBBLDCv2_0.png)

Actual photos:

![Alt Text](https://github.com/mrGrodzki/BLDC_UP5kW/blob/main/v2.0/solPCBV2.jpg)

# V1.0:

Schematic:

![Alt Text](https://github.com/mrGrodzki/BLDC_UP5kW/blob/main/v1.0/schematicBLDCv1_0.png)

Aluminium PCB:

![Alt Text](https://github.com/mrGrodzki/BLDC_UP5kW/blob/main/v1.0/PCBBLDCv1_0.png)

Actual photos:

![Alt Text](https://github.com/mrGrodzki/BLDC_UP5kW/blob/main/v1.0/solPCBV1.jpg)

Testing as synchronous dc/dc converter:
