# Vahan-Chakshu: Automated Vehicle Safety System

Vahan-Chakshu is an advanced vehicle safety system designed to reduce accidents by monitoring driver fatigue and behavior. The system utilizes a combination of camera-based hardware and IoT sensors to provide real-time alerts and interventions.

## Features

- **Driver Fatigue Measurement**: Utilizes a camera-based hardware system to measure eye closure duration and percentage (PEC), providing insights into driver fatigue levels.
  
- **Alert Mechanisms**: Triggers alarms and seat vibrators to prevent accidents caused by driver drowsiness.

- **Behavior and Performance Monitoring**: Monitors driver behavior and vehicle performance using IoT sensors, including:
  - Accelerometer
  - Gyroscope
  - MQ3 sensor for detecting speed, acceleration, and proximity

## Machine Learning Models

To achieve accurate detection and reduce errors, we employed the following pre-trained Convolutional Neural Networks (CNNs):

- **VGG16**: Achieved an accuracy of 85%
- **VGG19**: Achieved an accuracy of 82%
- **DenseNet**: Achieved an accuracy of 90%

## Model Ensembling

To further enhance performance, we ensembled VGG16, VGG19, and DenseNet models. This approach helped in reducing errors and improving the overall accuracy of the system.

