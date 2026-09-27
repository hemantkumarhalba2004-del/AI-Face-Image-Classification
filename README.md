# AI-Based Authentic Face Image Classification and Verification System

## Project Overview

This project develops a machine learning-based system to classify facial images as **REAL (Authentic)** or **FAKE (Manipulated)**.

The project analyzes facial image characteristics along with available demographic and image-quality information to build a classification model and evaluate its performance.

## Objectives

- Preprocess and analyze the facial image dataset
- Extract meaningful visual features from facial images
- Analyze demographic and image-quality characteristics
- Train machine learning classification models
- Classify images as REAL or FAKE
- Evaluate model performance using Accuracy, Precision, Recall, and F1-score
- Analyze prediction confidence scores
- Explore the potential of AI for future image verification applications

## Dataset

The dataset contains facial images and associated metadata, including:

- Image ID
- REAL/FAKE label
- Gender
- Age group
- Image quality
- Resolution
- Confidence score
- Detection difficulty
- Dataset split

The dataset contains standardized high-quality facial images.

> Note: Original/private facial images are not included in this repository.

## Project Workflow

1. Dataset loading
2. Data preprocessing
3. Exploratory data analysis
4. Visual feature extraction
5. Feature preparation
6. Machine learning model training
7. REAL vs FAKE classification
8. Model evaluation
9. Demographic and image-quality analysis
10. Confidence score analysis

## Visual Features

Basic visual characteristics were extracted from available facial images, including:

- Brightness
- Sharpness
- Saturation

These features help analyze differences in image characteristics between REAL and FAKE samples.

## Machine Learning

The project uses machine learning classification techniques to predict whether an image belongs to the REAL or FAKE class.

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Confidence Score

Prediction probabilities are analyzed to obtain a confidence score for each prediction.

The confidence score represents how strongly the trained model supports its predicted class.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pillow
- Machine Learning

## Results

The final results include:

- Classification performance metrics
- Confusion matrix
- REAL vs FAKE prediction analysis
- Demographic analysis
- Image-quality analysis
- Prediction confidence analysis

## Future Scope

The project can be further improved using:

- Deep learning models
- CNN-based facial image classification
- Transfer learning using models such as MobileNet or EfficientNet
- Advanced facial feature extraction
- Larger and more diverse datasets
- Advanced deepfake detection techniques

## Author

**Hemant Kumar**  
Life Sciences  
National Institute of Technology Rourkela (NIT Rourkela)

## Project Domain

**Data Science / Machine Learning / Computer Vision**
