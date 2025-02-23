# Passenger Emotion Recognition System for Autonomous Transport

Welcome to the repository for the Passenger Emotion Recognition System for Autonomous Public Transport project! This project was developed as part of the Hackathon conducted by CDC of IARE.The goal of this project is to create a system that utilizes artificial intelligence techniques, specifically using TensorFlow and the FER-2013 dataset, to recognize and analyze the emotions of passengers in autonomous public transport.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [System Overview](#system-overview)
- [Usage](#usage)

## Introduction

The Passenger Emotion Recognition System for Autonomous Public Transport project focuses on utilizing artificial intelligence to understand the emotional states of passengers in autonomous public transport vehicles. By accurately detecting emotions, the system can provide valuable insights into passenger satisfaction, comfort, and overall well-being.

The project utilizes TensorFlow, an open-source machine learning framework, and the FER-2013 dataset. The FER-2013 dataset contains facial images labeled with seven different emotions: anger, disgust, fear, happiness, sadness, surprise, and neutral. By training a deep learning model on this dataset, we can create a robust emotion recognition system.

## Getting Started

To get started with the Passenger Emotion Recognition System for Autonomous Public Transport project, follow the steps below.

### Prerequisites

- Python: Make sure you have Python installed on your computer. You can download it from the official Python website (https://www.python.org).

### Installation

1. Clone the repository:

```bash
git clone https://github.com/karabunar/emotion.git
```

2. Install the required Python packages:

```bash
pip install -r requirements.txt
```

3. Download the FER-2013 dataset and place it in the appropriate directory.

4. Run the system using the provided scripts and configuration files.

## System Overview

The Passenger Emotion Recognition System for Autonomous Public Transport consists of several components:

1. Data Preparation: The FER-2013 dataset is preprocessed and prepared for training the emotion recognition model.

2. Model Training: A deep learning model, such as a convolutional neural network (CNN), is trained on the preprocessed dataset using TensorFlow.

3. Emotion Recognition: The trained model is utilized to predict the emotions of passengers based on their facial expressions.

4. Analysis and Visualization: The system provides tools to analyze and visualize the emotions detected, enabling insights into passenger experiences.

## Usage

To use the Passenger Emotion Recognition System for Autonomous Public Transport, follow the instructions below:

1. Train the model: Use the provided scripts and configuration files to train the emotion recognition model on the FER-2013 dataset.

2. Deploy the system: Integrate the trained model into the autonomous public transport system, ensuring that it can process and analyze passenger facial expressions in real-time.

3. Emotion analysis: Utilize the system's analysis and visualization tools to gain insights into passenger emotions, enabling improvements in passenger experience and satisfaction.

