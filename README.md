# Pocket Oscilloscope

A compact, low-cost, and portable oscilloscope designed for basic signal visualization and analysis. Built using a microcontroller and interfaced with a PC or mobile app for real-time waveform display.

## 🔧 Features

- Signal visualization up to [insert frequency range, e.g., 10kHz]
- Real-time waveform display via serial communication
- Adjustable time base and voltage scaling
- USB-powered, pocket-sized design
- Cross-platform visualization software (Python/Processing/Arduino Serial Plotter)

## 🧰 Tech Stack / Tools

- **Microcontroller:** [e.g., Arduino Nano / STM32 / ESP32]
- **Analog Front-End:** Signal conditioning with Op-Amps and voltage dividers
- **ADC Sampling:** Inbuilt MCU ADC or external ADC
- **Communication Interface:** USB / UART Serial
- **Software Tools:** Arduino IDE, Python (for GUI), Serial Plotting libraries

## 🖥️ How It Works

1. Analog signal is fed to the microcontroller via a conditioning circuit.
2. Microcontroller samples the signal using its ADC.
3. Data is sent to a PC or mobile device via serial communication.
4. A GUI or serial plotter visualizes the waveform in real-time.

## 🚀 Getting Started

### Hardware Requirements

- Microcontroller board
- USB cable
- Signal generator / test signal source
- Basic components (resistors, capacitors, op-amps)

### Software Setup

1. Install Arduino IDE
2. Upload the code from `/firmware` folder to the microcontroller
3. (Optional) Run the Python GUI from `/visualizer` folder:
   ```bash
   python oscilloscope_gui.py
