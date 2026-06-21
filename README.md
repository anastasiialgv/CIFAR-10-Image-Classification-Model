# CIFAR-10 Image Classification Model

A deep learning project featuring a pre-trained neural network model designed to classify images from the classic CIFAR-10 dataset into 10 distinct categories (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck).

## 📁 Project Structure
* `cifar10_model.keras` — The saved, pre-trained neural network model weights and architecture in the native Keras format[cite: 1].

## 🛠️ Tech Stack
* **Python 3**
* **TensorFlow / Keras** (for loading and running the `.keras` model)[cite: 1]

## 🚀 Quick Start
To load and use this pre-trained model for making predictions in your own Python script, use the following snippet:

```python
import tensorflow as tf
from tensorflow.keras.models import load_model

# Load the pre-trained model
model = load_model('cifar10_model.keras')

# Verify the model architecture
model.summary()
