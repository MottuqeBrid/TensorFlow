# TensorFlow Learning Repository

## Overview

A comprehensive collection of TensorFlow tutorials and examples, progressing from fundamental concepts to advanced deep learning techniques. This repository covers neural networks, gradient descent optimization, regularization methods, computer vision, transfer learning, and object detection.

## Prerequisites

- Python 3.13+
- pip package manager

## Installation

```bash
# Clone the repository
git clone https://github.com/your-username/TensorFlow.git
cd TensorFlow

# Create virtual environment (recommended)
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Key Dependencies

| Package | Version | Purpose |
|---------|---------|---------|
| TensorFlow | 2.21.0 | Deep learning framework |
| Keras | 3.15.0 | High-level neural network API |
| NumPy | 2.5.1 | Numerical computing |
| Pandas | 3.0.3 | Data manipulation |
| Matplotlib | 3.11.1 | Data visualization |
| Scikit-learn | 1.9.0 | Machine learning utilities |
| OpenCV | 5.0.0.93 | Computer vision operations |
| Seaborn | 0.13.2 | Statistical data visualization |

## Repository Structure

```
TensorFlow/
├── 1/                          # TensorFlow Fundamentals
│   ├── 1.ipynb                 # MNIST handwritten digit recognition
│   ├── 2.ipynb                 # Sigmoid function implementation
│   ├── 3.ipynb                 # Logistic regression from scratch
│   └── insurance_data.csv      # Sample dataset
│
├── 2/                          # Gradient Descent Optimization
│   ├── 1.ipynb                 # Batch & Stochastic GD for price prediction
│   └── data/                   # Home prices dataset
│
├── 3/                          # TensorBoard Integration
│   ├── 1.ipynb                 # MNIST with TensorBoard callback
│   └── logs/                   # TensorBoard log files
│
├── 4/                          # GPU Training
│   └── gpu.ipynb               # CIFAR-10 image classification with GPU
│
├── 5/                          # Customer Churn Prediction
│   ├── Customer churn prediction using ANN.ipynb
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── 6/                          # Regularization Techniques
│   ├── Dropout Regularization.ipynb
│   └── sonar_dataset.csv       # Sonar signals dataset
│
├── 7/                          # Handling Imbalanced Data
│   ├── handling_imbalanced_data.ipynb
│   └── customer_churn.csv
│
├── 8 Applications of computer vision/  # Computer Vision
│   ├── 1 Image classification using CNN.ipynb
│   ├── 2 Data augmentation to address overfitting.ipynb
│   └── cifar-10-data/          # CIFAR-10 dataset
│
├── 9 Transfer Learning/        # Transfer Learning
│   ├── 1 Transfer Learning.ipynb
│   ├── goldfish.jpg            # Sample test image
│   └── ImageNetLabels.txt      # ImageNet class labels
│
├── 10 Object detection using YOLO and pre trained model/  # Object Detection
│   ├── 1 Object detection using YOLO and pre trained model.ipynb
│   ├── original.jpg            # Sample images
│   └── yolo26n.pt             # YOLO model weights
│
├── requirements.txt            # Python dependencies
└── README.md                   # This file
```

## Tutorial Topics

### 1. TensorFlow Fundamentals
- Loading and exploring the MNIST dataset
- Understanding tensor shapes and data types
- Image visualization and preprocessing
- Building a simple neural network with Keras Sequential API
- Data normalization and flattening
- Model evaluation and confusion matrix visualization

### 2. Gradient Descent Optimization
- Implementing batch gradient descent from scratch
- Implementing stochastic gradient descent
- Feature scaling with MinMaxScaler
- Cost function visualization over epochs
- Comparing batch vs stochastic gradient descent performance

### 3. TensorBoard Integration
- Setting up TensorBoard callbacks
- Logging training metrics
- Visualizing model performance
- Running TensorBoard for analysis

### 4. GPU Training
- Utilizing GPU acceleration for faster training
- CIFAR-10 image classification (10 classes)
- Building deep convolutional neural networks
- Handling color images (3-channel RGB)

### 5. Customer Churn Prediction
- Binary classification with artificial neural networks
- Feature encoding and preprocessing
- Handling categorical variables
- Model architecture design for tabular data
- Evaluating classification performance

### 6. Dropout Regularization
- Understanding overfitting and underfitting
- Implementing dropout layers
- Training on sonar dataset (classification)
- Comparing model performance with/without regularization

### 7. Handling Imbalanced Data
- Techniques for dealing with class imbalance
- Resampling strategies (oversampling/undersampling)
- Adjusting class weights
- Evaluating models on imbalanced datasets

### 8. Computer Vision Applications
- **CNN Image Classification**: Building convolutional neural networks for CIFAR-10
- **Data Augmentation**: Addressing overfitting through image transformations
  - Rotation, flipping, zooming
  - Width/height shifts
  - Shear transformations

### 9. Transfer Learning
- Leveraging pre-trained models (ImageNet)
- Feature extraction from pre-trained networks
- Fine-tuning pre-trained models
- Image classification with transfer learning

### 10. Object Detection
- YOLO (You Only Look Once) object detection
- Loading and using pre-trained YOLO models
- Detecting objects in images
- Visualizing detection results with bounding boxes

## Key Concepts Covered

- **Neural Networks**: Dense layers, activation functions (ReLU, Sigmoid, Softmax)
- **Optimization**: Gradient Descent, Adam, SGD optimizers
- **Loss Functions**: Binary Crossentropy, Categorical Crossentropy
- **Regularization**: Dropout, Batch Normalization
- **Computer Vision**: CNN, Pooling, Data Augmentation
- **Transfer Learning**: Pre-trained models, Feature Extraction
- **Object Detection**: YOLO architecture
- **Evaluation**: Confusion Matrix, Accuracy, Precision, Recall

## Learning Path

1. Start with **Section 1** for TensorFlow basics
2. Progress to **Section 2** to understand gradient descent
3. Learn TensorBoard in **Section 3** for model monitoring
4. Move to **Sections 5-7** for practical classification problems
5. Explore **Section 8** for computer vision fundamentals
6. Advance to **Sections 9-10** for state-of-the-art techniques

## Running the Notebooks

```bash
# Activate your virtual environment first
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Start Jupyter Notebook
jupyter notebook

# Navigate to the desired section and run the notebooks
```

## License

This repository is for educational purposes. TensorFlow itself is licensed under the Apache License 2.0.
