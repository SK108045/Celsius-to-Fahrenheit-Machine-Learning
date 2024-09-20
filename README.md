# Celsius-to-Fahrenheit-Machine-Learning
# Celsius to Fahrenheit Converter using TensorFlow

This project demonstrates a simple machine learning model built with TensorFlow to convert Celsius temperatures to Fahrenheit. It serves as a basic introduction to neural networks and TensorFlow.

## Project Description

The project consists of a Python script that:
1. Creates a simple neural network model
2. Trains the model on a small dataset of Celsius to Fahrenheit conversions
3. Saves the trained model
4. Allows users to input Celsius temperatures and get Fahrenheit predictions

## Requirements

- Python 3.7+
- TensorFlow 2.x
- NumPy

## Usage

1. Run the script:

2. The script will train the model, save it, and then prompt you to enter Celsius temperatures.

3. Enter Celsius temperatures when prompted. The model will predict the corresponding Fahrenheit temperature.

4. Enter 'q' to quit the program.

## Model Details

- The model is a simple neural network with one dense layer.
- It is trained on a small dataset of 7 Celsius-Fahrenheit pairs.
- The model is saved as `celsius_to_fahrenheit_model.keras` after training.

## Example Output
```bash
Enter a Celsius temperature (or 'q' to quit): 27
1/1 ━━━━━━━━━━━━━━━━━━━━ 0s 30ms/step
27.0°C is predicted to be 78.15°F
```

