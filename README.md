# sg-sdk-ml

# ML Projects on ESP32 with SG Wireless F1 Starter Kit

This repository demonstrates how to build machine learning (ML) projects for the **ESP32-based SG Wireless F1 Starter Kit**, using the [SG Wireless SDK (sg-sdk)](https://github.com/sg-wireless/sg-sdk).

We focus specifically on building and running the [TensorFlow Lite Micro `hello_world`](https://github.com/espressif/esp-tflite-micro/tree/master/examples/hello_world) example on the SG F1 Starter Kit.

---

## Overview

Machine learning on embedded devices like the ESP32 opens up exciting possibilities for real-time, low-power inference at the edge. This repository guides you through:

- Setting up the **SG SDK** development environment
- Integrating **TensorFlow Lite Micro** with SG SDK
- Compiling and flashing the `hello_world` example onto the **SG F1 Starter Kit**

---

## Prerequisites

Before getting started, make sure you have:

- An SG Wireless F1 Starter Kit
- [SG SDK](https://github.com/sg-wireless/sg-sdk) installed and configured
- build-essential, python3, python3-pip, python3-venv, curl 

---

## Cloning This Repository

```bash
git clone https://github.com/yourusername/sg-sdk-ml.git
cd sg-sdk-ml/
