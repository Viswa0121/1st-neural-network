# MNIST Neural Network

My first neural network built using TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

## 📌 About the Project

The MNIST dataset contains 70,000 grayscale images of handwritten digits from 0 to 9.

Each image is:

- 28 × 28 pixels
- Grayscale
- Classified into one of 10 classes (0–9)

This project uses a neural network to learn patterns in these images and predict which digit each image represents.

## 🧠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Jupyter Notebook

## 📊 Dataset

The MNIST dataset is loaded directly using TensorFlow:

```python
tf.keras.datasets.mnist.load_data()
