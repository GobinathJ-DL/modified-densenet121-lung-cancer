Lung Cancer Detection Using Modified DenseNet121

Overview

This repository contains the implementation of a deep learning framework for lung cancer detection from histopathological images using a modified DenseNet121 architecture with a Min–Max transition layer. The proposed model enhances feature representation and classification performance for lung cancer detection.

Dataset

The model was trained and evaluated using histopathological lung cancer image datasets.

Dataset characteristics:

Image size: 224 × 224 × 3
Three-class classification
Histopathology images

https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images



Model Architecture

The proposed framework includes:

DenseNet121 backbone
Min–Max Transition Layer
Global Average Pooling
Fully Connected Classification Layer

The architecture improves feature extraction and classification performance compared to conventional DenseNet models.

Requirements

To run the code install the following dependencies:

Python 3.8+
TensorFlow / PyTorch
NumPy
OpenCV
Scikit-learn
Matplotlib

Install packages using:

pip install -r requirements.txt
How to Run the Code

Clone the repository

git clone   https://github.com/GobinathJ-DL/modified-densenet121-lung-cancer
Navigate to the folder

cd modified-densenet121-lung-cancer

Train the model

python train.py
Results

The proposed model achieves high performance in lung cancer classification.

Evaluation metrics include:

Accuracy
Precision
Recall
F1 Score
Sensitivity
Specificity

Citation

If you use this code in your research, please cite the corresponding paper.

Code Availability

The code is publicly available to support transparency and reproducibility of the research.
