# NeuralNetwork01 - Cat Detection

A neural network project for detecting cats in images using PyTorch and computer vision techniques.

## 🚀 Quick Start


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wcraytor/NeuralNetwork01/main)

Click the Binder button above to run this project in your browser!

## 📁 Project Structure

- `organize_data_set.ipynb` - Data preparation and organization
- `cat_detection.ipynb` - Main neural network training and inference
- `data/raw/` - Original image dataset
- `data/processed/` - Organized training/validation datasets
- `data/models/` - Saved model checkpoints

## 📚 Notebooks

### 1. Data Organization (`organize_data_set.ipynb`)
- Loads and organizes image datasets
- Splits data into training/validation sets
- Prepares data for neural network training
- **Run this first** to set up your data structure

### 2. Cat Detection (`cat_detection.ipynb`)
- Implements CNN for cat detection
- Training loop and model evaluation
- Inference on new images
- Model saving and loading

## 🔧 Environment

This project uses the [BaseEnvPython01](https://github.com/YOUR-USERNAME/BaseEnvPython01) base environment, which includes:
- PyTorch & Torchvision
- OpenCV & Pillow for image processing
- Jupyter, NumPy, Pandas, Matplotlib

## 🏃‍♂️ Running Locally

1. Clone this repository
2. Install requirements from [BaseEnvPython01](https://github.com/YOUR-USERNAME/BaseEnvPython01)
3. Run `organize_data_set.ipynb` first
4. Then run `cat_detection.ipynb`

## 📊 Workflow

1. **Data Setup**: Run `organize_data_set.ipynb` to prepare your dataset
2. **Training**: Use `cat_detection.ipynb` to train the neural network
3. **Inference**: Test the trained model on new images

## 🎯 Use Cases

This project demonstrates:
- Image classification with CNNs
- Data organization for machine learning
- PyTorch model training and evaluation
- Computer vision preprocessing techniques
