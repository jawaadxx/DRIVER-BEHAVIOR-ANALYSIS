# DRIVER-BEHAVIOR-ANALYSIS
Driver Behavior Monitoring Using CNN
Driver Behavior Monitoring Using MobileNetV2
This project focuses on driver behavior classification using MobileNetV2, a lightweight and efficient Convolutional Neural Network (CNN). The goal is to detect various driver conditions such as safe driving, distracted driving, drowsiness, and dangerous actions to enhance road safety.

   Project Overview
1. Dataset: 14,000+ labeled images across six driver behavior categories.
2. Preprocessing: Applied data augmentation (rotation, flipping, brightness adjustments) to improve generalization.
3. Model: Used MobileNetV2 (pre-trained on ImageNet) with added Dense, Dropout, and Global Average Pooling layers for classification.
4. Optimization: Trained with Adam optimizer, learning rate scheduling, and early stopping.
5. Results: Achieved 94% test accuracy after fine-tuning MobileNetV2.

📌 Steps Implemented

1. Data Preparation: Loaded and augmented images using ImageDataGenerator to enhance model performance.
2. Model Architecture:

Used MobileNetV2 as a feature extractor (transfer learning).
Added Global Average Pooling, Dense layers, and Dropout for classification.
3. Training & Fine-Tuning:
Compiled using categorical cross-entropy loss and Adam optimizer.
Fine-tuned last 30 layers of MobileNetV2 for better feature extraction.
4. Evaluation: Tested on unseen data, achieving 94% accuracy.
5. Predictions: Model predicts driver actions, which can be integrated into real-time driver monitoring systems.

🚀 Potential Applications

1. Driver safety monitoring in autonomous & electric vehicles (EVs).
2. Smart alert systems for drowsiness detection.
3. Preventing accidents by detecting distracted driving.

This project is a step towards AI-powered driver assistance systems, ensuring safer roads and better driver awareness.

 Future Scope: Implementing real-time video inference, optimizing model size, and deploying on edge devices (e.g., Jetson Nano).

🔗 Check out the code & dataset in this repository! 
