# 🧠 Animal Disease Detection using CNN

A Convolutional Neural Network (CNN) model for detecting common animal diseases from images. The model classifies images into three categories: Healthy, Mouth and Foot Disease, and Fur-based Disease.

## 🚀 Features

- Custom CNN architecture using TensorFlow & Keras
- Image classification using visual symptoms
- Train/Validation/Test split using train_test_split
- Evaluation with precision, recall, and accuracy
- Saved model for easy deployment (.keras format)

## 🛠 Tech Stack

- Python 3.9.13
- TensorFlow 2.19 (Keras 3)
- NumPy, Scikit-learn, Matplotlib
- Flask (for optional web interface)

## 📦 How to Run

```bash
pip install -r requirements.txt
python train.py         # Train the model
python evaluate.py      # Evaluate performance
