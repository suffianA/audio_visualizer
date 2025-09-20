# audio_visualizer
A small project using the STM32 Nucleo F446RE and the ESP32 to analyze and visualize real-time signal input.

## Features:
- STM32: I2S microphone, DMA double buffering, FFT with CMSIS-DSP library
- ESP32: UART/SPI packet parsing, Wi-Fi server, WebSocket to browser
- Web UI: Real-time spectrum visualization

## Repo Layout
- firmware/stm32/ – STM32CubeIDE project
- firmware/esp32/ – ESP-IDF project
- shared/ – shared protocol code
- webui/ – browser UI
- docs/ – wiring, protocol, DSP notes
- tools/ – Python scripts for testing
