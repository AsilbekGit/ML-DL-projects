# Handwritten Digit Recognition using TensorFlow and Keras

## Overview
This project implements a neural network to recognize handwritten digits using the **MNIST dataset**. The model is built with TensorFlow and Keras, and trained on the **Google Colab** platform. The dataset is loaded directly from TensorFlow without the need for external downloads.

## Features
- **Dataset**: MNIST (built-in TensorFlow dataset)
- **Model Architecture**:
  - Input layer: Flattened 28x28 images
  - Hidden layer: Dense layer with 128 neurons and ReLU activation
  - Dropout layer: 20% dropout to prevent overfitting
  - Output layer: 10 neurons (softmax activation for digit classification)
- **Training**: 10 epochs with validation on test data
- **Evaluation**: Prints final test accuracy
- **Visualization**: Displays predictions on sample test images
- **Model Saving**: Saves the trained model and allows download from Colab

## Requirements
This project requires **Google Colab** or a Python environment with TensorFlow installed.

### Install Dependencies (if running locally)
```sh
pip install tensorflow numpy matplotlib
```

## How to Run
1. Open **Google Colab** and create a new notebook.
2. Copy and paste the provided Python script into a code cell.
3. Run all cells sequentially.
4. The script will:
   - Load the dataset
   - Normalize the images
   - Train the model on **10 epochs**
   - Evaluate accuracy
   - Save and download the trained model
   - Display sample predictions

## Expected Output
- The final model should achieve an accuracy of approximately **98%** on test data.
- Sample digit predictions will be displayed along with actual labels.

## Model Download
After training, the model is saved as `mnist_digit_recognition.h5` and can be downloaded for future use.

## Troubleshooting
- If encountering TensorFlow errors, restart the Colab runtime and rerun the script.
- Ensure GPU is enabled in Google Colab for better performance (`Runtime > Change runtime type > GPU`).

## License
This project is open-source and free to use for educational purposes.

---
Developed with ❤️ using TensorFlow & Keras 🚀

