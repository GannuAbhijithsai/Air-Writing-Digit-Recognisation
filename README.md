# Air Writing Digit Recognition

This project utilizes a gy-521 sensor to recognize handwritten digits using machine learning algorithms.

## Overview

Air Writing Digit Recognition is a project aimed at recognizing handwritten digits by tracking hand movements using a gy-521 sensor. This repository contains the code and resources required to train and deploy the machine learning model for digit recognition.

## Features

- Utilizes gy-521 sensor for tracking hand movements.
- Machine learning algorithms for digit recognition.
- Custom dataset creation for training.

## Requirements

- Arduino IDE
- Python 3.x
- Libraries: TensorFlow, NumPy, scikit-learn
- Gy-521 sensor

## Setup

1. Clone the repository:git clone https://github.com/your_username/air-writing-digit-recognition.git

2. Install the required libraries:pip install tensorflow numpy scikit-learn

3. Upload the Arduino code to the gy-521 sensor.

4. Train the machine learning model using the provided dataset.

5. Run the prediction script to recognize digits in real-time.

## Usage

- Ensure that the gy-521 sensor is properly connected to the Arduino board.
- Run the prediction script `predict.py` to start recognizing digits.
- Follow the instructions displayed on the screen for writing digits in the air.

## Dataset

The dataset used for training the machine learning model is collected using the gy-521 sensor. It consists of samples of handwritten digits drawn in the air.

## Model

The machine learning model used for digit recognition is trained using TensorFlow. It is a convolutional neural network (CNN) architecture optimized for handwritten digit recognition.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.





