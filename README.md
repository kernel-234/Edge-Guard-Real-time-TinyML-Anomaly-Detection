
# Automated Quality Inspector (Edge AI)
An industrial-grade computer vision solution developed for a HackerRank Hackathon. This project demonstrates the deployment of Machine Learning models on resource-constrained hardware (Microcontrollers) to automate quality control.

## 🛠 Tech Stack
* **Language:** C++
* **Framework:** TensorFlow Lite Micro
* **Tooling:** Edge Impulse SDK, CMake
* **Hardware Target:** ARM Cortex-M Series (MCU)

## 🚀 Features
* **Real-time Inference:** On-device processing for zero-latency defect detection.
* **Optimized Model:** Uses a quantized TFLite model to fit within limited MCU RAM/Flash.
* **Industrial Scalability:** Designed for "Edge" deployment where cloud connectivity is unavailable.

## 📂 Repository Structure
* `/tflite-model`: Contains the compiled C++ math for the neural network.
* `/model-parameters`: Metadata regarding signal processing and model architecture.
* `/edge-impulse-sdk`: The core libraries required to run inference on hardware.
