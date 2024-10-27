# Object Classification

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)

## Overview
A machine learning model that can identify objects within images across 10 different classes. The object classes are plane, car, bird, cat, deer, dog, frog, horse, ship, and truck.

## Features
- Trained on the CIFAR10 dataset, featuring 60,000 32x32 colour images across 10 classes.
- Utilized 3 convolutional layers, followed by 2 full-connected layers, along with pooling and dropout layers.
- Incorporated data augmentation techniques to reduce overfitting. 

## Technologies Used
- **Language**: Python
- **Libraries**: PyTorch, tqdm, Matplotlib, NumPy

## Installation
1. **Prerequisites**: Install the following libraries:
   - PyTorch
   - tqdm
   - Matplotlib
   - Numpy
2. **Fork** this repository.
3. **Clone the repository**:  
   ```bash
   git clone https://github.com/<your_username>/CIFAR10-Object-Classification.git
   ```
4. **Navigate to the directory**:
   ```bash
   cd CIFAR10-Object-Classification
   ```

## Usage
1. Execute every code cell from top to bottom.
2. The last few code cells, under the heading "_For demonstration_", will randomly select an image from the test set and display the image, true label, and the model's prediction.
