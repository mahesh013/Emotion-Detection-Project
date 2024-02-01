# Emotion-Detection-Project


## Overview

This project implements an Emotion Detection system using a pre-trained neural network. The system analyzes facial expressions in images and predicts the emotion expressed, such as anger, happiness, sadness, etc.

## Features

- Upload an image to the GUI for emotion detection.
- Utilizes OpenCV for face detection and PIL (Pillow) for image processing.
- Integrates a trained neural network for emotion classification.

## Prerequisites

- Python 3.x
- Install required Python packages using `pip install -r requirements.txt`

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/mahesh013/emotion-detection.git
    ```

2. Navigate to the project directory:

    ```bash
    cd emotion-detection
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the GUI application:

    ```bash
    python gui2.py
    ```

2. Click the "Upload Image" button to select an image for emotion detection.

3. Click the "Detect Emotion" button to analyze the uploaded image and display the predicted emotion.

## File Structure

- `gui.py`: Main GUI application.
- `model_a1.json`: JSON file containing the trained neural network architecture.
- `model_weights1.h5`: Weights file for the trained neural network.
- `haarcascade_frontalface_default.xml`: Haarcascades file for face detection.
- `requirements.txt`: List of required Python packages.
- `README.md`: Project documentation.

## Contributing

Contributions are welcome! Please follow the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to [author name] for the inspiration and initial project structure.

