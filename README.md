## Disease Detection from Chest X-Ray
 ## 🧠Project Goal

The goal of this project is to build a deep learning model that can classify chest X-ray images as either Normal or Pneumonia. This demonstrates how AI can assist medical professionals in early diagnosis and improve healthcare outcomes.

## 📦 Dataset

Dataset Name: Chest X-Ray Images (Pneumonia)
Source: Kaggle

Total images: 5,863

Split across training, validation, and test folders

Two classes:

**NORMAL**

**PNEUMONIA**

**Note:** The dataset is imbalanced, with more pneumonia images than normal images.

## 🛠️ Project Steps
**1. Data Exploration**

Visualize sample X-ray images to understand the data

Analyze class distribution to identify imbalances

**2. Data Preprocessing**

1-Resize images (e.g., 150x150 or 224x224)
2-Normalize pixel values for better model performance
3-Apply data augmentation (rotation, flipping, zooming) to:
4-Reduce overfitting
5-Balance the dataset

**3. Model Building**

1-Start with a basic Convolutional Neural Network (CNN)
2-Conv2D → MaxPooling → Flatten → Dense layers
3-Compile model using appropriate loss function and optimizer

**4. Model Evaluation**
Evaluate using metrics:
1-Accuracy
2-Precision
3-Recall
4-F1-score

Plot confusion matrix to visualize classification performance

Visualize training vs validation accuracy and loss curves
