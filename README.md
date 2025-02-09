# STM32H7 based isolated Audio DSP Plattform

This repository includes PCB-project files for a STM32 based isolated auido DSP-Plattform

# Board Features

- MCU: STM32H747IGT6, ARM Cortex M7 with 480MHz and AMD Cortex M4 with 240 MHz
- Memory: External: 1x 64 Mbit SDRAM ; External: 1x 128 Mbit  QSPI Flash
- USB: USB 2.0 Transceiver Speeds up to 480 Mbit/s (HS), USB-C compatible Interface
- USB: Fullspeed 12 MBit/s
- Debug: Serial-Wire-Debug
- CODEC: TAC5142IRGER 2-Channel ADC 2 Channel DAC up to 192 kHz sampling Frequency audio CODEC
- BNC Connectors for audio input and Output

# Applications:

- Ultrasound
- Audio algorithm development testing plattform
- Audio Analyzer
- Other Embedded audio Systems

# Absolute Maximum Ratings

- Supply Voltage: +5V0 to +5V5 (recommended: +5V0) USB feeded
- ADC input Voltage: +3.3 V to 3.6 V

# Manufacturing Information

- Length = 100mm, Width = 75mm, Thickness = 1.6 mm
- Layers = 6
- Min. Via Hole diameter = 0.3 mm
- Via-Type: Epoxy Filled and Capped
- Impedance Control: JLC06161H-3313
- Surface Finish: ENIG
- Material Type: FR-4 TG155

# Progress

- Schematic design: complete
- Layouting: complete
- Manufacturing & assembly: In progress
- Bring-Up: In progress

I make no guarantees as to device funtionality. Please review the components, schematics carefully before production.

![test](https://github.com/myildirim6198/STM32BasedAudioDSPPlattform/blob/main/Images/AudioDAQOverview.png?raw=true)
