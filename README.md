# ⚡ Edge-Guard | TinyML Anomaly Detection
Building AI that doesn't need the Internet to think.

### What it does
This is a high-performance C++ inferencing library designed to detect anomalies in real-time sensor data using the Edge Impulse SDK. It’s built to run on microcontrollers (like ESP32 or STM32) where memory and power are extremely limited.

### Key Technical Feats
- **Hardware-Agnostic Porting:** Optimized the C++ codebase to be portable across different embedded targets using the CMSIS-DSP library.
- **On-Device Inferencing:** Integrated a TensorFlow Lite Micro model to perform sub-100ms anomaly detection on the "Edge."
- **Signal Processing:** Implemented custom DSP blocks to extract features from raw time-series data, reducing the noise fed into the neural network.

### Tech Stack
C++, TensorFlow Lite Micro, Edge Impulse SDK, CMSIS-DSP.
