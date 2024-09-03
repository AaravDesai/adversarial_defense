# Adversarial Machine Learning Defense Framework

## Project Overview
This project implements a robust framework for defending machine learning models against adversarial attacks, focusing on image classification tasks. It demonstrates the implementation of adversarial attacks and defenses, along with tools for evaluating model robustness.

## Features
- Implementation of Fast Gradient Sign Method (FGSM) attack
- Adversarial training as a defense mechanism
- Convolutional Neural Network (CNN) for MNIST digit classification
- Tools for visualizing adversarial examples
- Evaluation of model robustness against adversarial attacks

## Requirements
- Python 3.7+
- TensorFlow 2.x
- NumPy
- Matplotlib

## Project Structure
- `adversarial_defense.ipynb`: Main script containing model definition, FGSM attack, adversarial training, and evaluation
- `README.md`: This file

## How It Works
1. A CNN model is trained on the MNIST dataset for digit classification.
2. The FGSM attack is implemented to generate adversarial examples.
3. Adversarial training is used as a defense mechanism to improve model robustness.
4. The model's performance is evaluated against both clean and adversarial examples.
5. Adversarial examples are visualized to demonstrate the attack's effect.

## Results
The script outputs:
- Standard accuracy on clean test data
- Adversarial accuracy before and after adversarial training
- Visualizations of original and adversarial examples
