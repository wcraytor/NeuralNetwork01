# NeuralNetwork01 - Cat Detection

A neural network project for detecting cats in images using PyTorch and computer vision techniques.

"""
  SPECIAL NOTES: 
1.  If you haven't run Jupyter programs.  They are written in blocks. If you put the cursor on the code, it
    will show a border around the block to execute the block, push the shift key and hit enter--- and wait..
2.  The Jupyter file "organize_data_set.ipynb" will organize the 25K+ cat and dog photos into training, 
    validation, and test data sets.  The 25,000 photos will be far more than can be processed in a reasonable
    time using Github Binder (using the link in the README.md file).  It is set to 7% or 0.07, which should take
   about 40 minutes using Binder.  If you download the file and run it on a Mac Studio M2 Ultra with 64G of memory
    and set the percentage to 10 or 20%, it should provide a model with over 90% accuracy and run in about 20 
    minutes.  You could use a mac-mini M4 Pro (maxed out with CPUs, GPUs and memory), but it will be very slow.
3.  The "organize_data_set.ipynb" itself is very fast and should take little time to run. There is just one
    block to execute.  After is completed, run cat_detection.ipynb. #4.  The CNN program is "cat_detection.ipynb"   It is just one block.  Click on it, then click Shift-Enter -
    and wait.  Output will be under the code.
 """


## 🚀 Quick Start


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wcraytor/BaseEnvPython01/main)

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
