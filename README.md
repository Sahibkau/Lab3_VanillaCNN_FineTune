Practical Lab 3 - Vanilla CNN and Fine-Tune VGG16 - for Dogs and Cats Classification

A professional deep learning classification project focused on distinguishing between images of cats and dogs using PyTorch.

📁 Dataset Summary

Source: Kaggle Dogs vs Cats

Training Images: 5,000 total (2,500 cats + 2,500 dogs)

Test Images: Unlabeled dataset (used for prediction only)

Image Size: Resized to 128x128

🔍 Exploratory Data Analysis (EDA)

✅ Bar plot showing class distribution

✅ Sample images visualized for sanity checks

✅ Image size distribution (before and after resizing)

✅ Channel-wise mean and standard deviation

✅ Pixel intensity distribution histograms

🧠 Model Architectures

1. Vanilla CNN

2 convolutional layers (ReLU + MaxPool)

Flatten → Fully connected layer (128 units)

Dropout (p=0.3) for regularization

Final output layer with 2 logits (Cat or Dog)

2. VGG16 (Transfer Learning)

Pre-trained on ImageNet

Feature extractor layers frozen

Final classification layer replaced with custom 2-class layer

🏋️‍♂️ Training Configuration

Framework: PyTorch

Loss Function: CrossEntropyLoss

Optimizer: Adam

Epochs: 5

Batch Size: 32

Validation Split: 10% of training data

Model Saving: Best model per architecture based on validation accuracy

📊 Model Evaluation (on Validation Set)

✅ Classification Report (Precision, Recall, F1-score)

✅ Confusion Matrix (visualized with heatmap)

✅ Precision-Recall Curve

✅ Misclassified image gallery

🧪 Inference on Unlabeled Test Set

✅ Predictions made using both trained models

✅ Visual gallery of predictions with file name and predicted label

✅ Confidence score displayed for each prediction

✅ Class distribution bar chart to assess prediction balance

- Submitted by : Manpreet Kaur 
- Student Id:8946613
