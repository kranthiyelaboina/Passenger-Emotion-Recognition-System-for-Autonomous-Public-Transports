# Passenger Emotion Recognition System for Autonomous Public Transport

Welcome to the repository for the Passenger Emotion Recognition System for Autonomous Public Transport project! This project was developed by **Team Z-18** as part of a hackathon conducted by the Career Development Centre (CDC) at the Institute of Aeronautical Engineering (IARE). The goal of this project is to create a system that utilizes artificial intelligence techniques, specifically using TensorFlow and the FER-2013 dataset, to recognize and analyze the emotions of passengers in autonomous public transport.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [System Overview](#system-overview)
- [Usage](#usage)
- [Benefits](#benefits)

## Introduction

The Passenger Emotion Recognition System aims to enhance the safety and comfort of passengers in autonomous public transport vehicles by monitoring and analyzing their emotional states. By accurately detecting emotions, the system can provide valuable insights into passenger satisfaction and well-being, enabling timely interventions when necessary.

This project leverages TensorFlow, an open-source machine learning framework, and the FER-2013 dataset, which contains facial images labeled with seven different emotions: anger, disgust, fear, happiness, sadness, surprise, and neutral. By training a deep learning model on this dataset, we have developed a robust emotion recognition system.

## Getting Started

To get started with the Passenger Emotion Recognition System, follow the steps below.

### Prerequisites

- **Python**: Ensure that Python is installed on your system. You can download it from the official [Python website](https://www.python.org).

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/kranthiyelaboina/Passenger-Emotion-Recognition-System-for-Autonomous-Public-Transports.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Passenger-Emotion-Recognition-System-for-Autonomous-Public-Transports
   ```

3. **Install the required Python packages**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Download the FER-2013 dataset**:

   - Obtain the FER-2013 dataset (`fer2013.csv`) from a reliable source.
   - Place the `fer2013.csv` file into the project's root directory.

## System Overview

The Passenger Emotion Recognition System comprises the following components:

1. **Data Preparation**: Preprocessing the FER-2013 dataset to prepare it for training the emotion recognition model.

2. **Model Training**: Utilizing a deep learning model, such as a Convolutional Neural Network (CNN), trained on the preprocessed dataset using TensorFlow.

3. **Emotion Recognition**: Applying the trained model to predict the emotions of passengers based on their facial expressions.

4. **Analysis and Visualization**: Providing tools to analyze and visualize the detected emotions, offering insights into passenger experiences.

## Usage

To use the Passenger Emotion Recognition System, follow these steps:

1. **Train the Model**:

   - Execute the `emotion_training.ipynb` notebook to train the emotion recognition model on the FER-2013 dataset.

2. **Test the Model**:

   - Run the `emotion_test.py` script to evaluate the model's performance on test images.

3. **Deploy the System**:

   - Integrate the trained model into the autonomous public transport system to process and analyze passenger facial expressions in real-time.

4. **Emotion Analysis**:

   - Utilize the system's analysis and visualization tools to gain insights into passenger emotions, facilitating improvements in passenger experience and satisfaction.

## Benefits

Implementing the Passenger Emotion Recognition System in autonomous public transport offers several real-world benefits:

1. **Enhanced Passenger Safety**: By monitoring passengers' emotional states, the system can detect signs of distress or aggression, enabling timely interventions to prevent potential incidents. citeturn0search2

2. **Improved Service Quality**: Understanding passenger emotions allows service providers to tailor the environment and services to enhance comfort and satisfaction. citeturn0search1

3. **Increased Social Acceptance of Autonomous Transport**: Addressing passenger emotions can alleviate anxiety associated with autonomous vehicles, fostering trust and acceptance among users. citeturn0search5

4. **Data-Driven Decision Making**: Collecting and analyzing emotional data provides valuable insights for continuous improvement of transport services and policies.

For detailed instructions and additional information, please refer to the project's [GitHub repository](https://github.com/kranthiyelaboina/Passenger-Emotion-Recognition-System-for-Autonomous-Public-Transports). 
