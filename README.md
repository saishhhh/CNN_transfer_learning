# CNN Transfer Learning

This repository contains a Jupyter Notebook that demonstrates how to use transfer learning with a Convolutional Neural Network (CNN) for image classification.

## Files
- `cnn_transfer_learning_.ipynb`: The main Jupyter Notebook containing the code for data preprocessing, model building, transfer learning, training, and evaluation.

## Dependencies
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

You can install the required packages using:
```bash
pip install tensorflow keras numpy matplotlib
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/CNN_Transfer_Learning.git
   ```
2. Navigate to the directory:
   ```bash
   cd CNN_Transfer_Learning
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook cnn_transfer_learning_.ipynb
   ```
4. Run all cells to perform transfer learning, train, and evaluate the CNN model.

## Model
The notebook uses a pre-trained CNN model (e.g., VGG16, ResNet) and fine-tunes it on a new dataset. The model includes:
- Convolutional layers
- Max Pooling layers
- Fully Connected (Dense) layers

## Results
The notebook includes the training process and evaluation metrics, such as accuracy and loss plots, as well as final model performance on the test set.
