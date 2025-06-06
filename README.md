# Adaptive Noise-Cancelling Headphones

Developed wearable ANC headphones using an LMS adaptive filter running on an STM32F7 microcontroller. Achieves real-time broadband noise suppression with low latency.

## Hardware Architecture
- STM32F746 MCU
- PDM MEMS microphones (primary/reference)
- OPA1652 low-noise preamps
- 1000 mAh Li-Po battery

## Signal Processing Features
- LMS adaptive filter (8 kHz update rate)
- Real-time audio stream processing
- 12 dB noise reduction (200 Hz–2 kHz)
- Latency < 5 ms end-to-end

## PCB Design
- 4 cm × 6 cm custom board (Altium)
- BLE module (for future control interface)
- Power and charging management ICs

## Tools Used
- STM32CubeIDE
- Altium Designer
- MATLAB (filter prototyping)

## Project Status
In Progress – Summer 2025
