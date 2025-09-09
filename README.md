# AquaAura-Research
AquaAura

AquaAura is an edge AI–powered soil moisture prediction and smart irrigation system designed to support sustainable agriculture. The framework combines lightweight neural networks with low-cost IoT hardware to optimize irrigation scheduling and reduce water consumption in resource-constrained environments.

Overview

The system integrates an ESP32 microcontroller, environmental sensors (soil moisture, temperature, humidity, light), and a compact TensorFlow Lite model. It enables real-time prediction of soil moisture trends and automates pump control based on AI-driven decision making.

Key Features

Lightweight Artificial Neural Network trained on environmental and soil data.

Model conversion to TensorFlow Lite and deployment on ESP32.

Automatic irrigation activation when predicted moisture falls below threshold.

Built-in web server for real-time monitoring of environmental parameters and system status.

Designed for low-cost deployment in rural and small-scale agricultural settings.

Repository Structure

model_training/ → Python scripts for data preprocessing, ANN training, and TensorFlow Lite conversion.

firmware/ → ESP32 firmware implementing sensor acquisition, AI inference, pump control, and web server.

 
Experimental Results

Initial trials demonstrate significant water-use reduction compared to fixed-interval irrigation strategies, while maintaining healthy soil moisture levels. The system shows the potential for scalable deployment in sustainable precision agriculture.

Authors

Ayush Verma – Author, Independent Researcher (India)

Shreyash Jitendra Sarade – Co-Author, B.Tech CSE, Smt. Kashibai Navale College of Engineering, Savitribai Phule Pune University (India)
