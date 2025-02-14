# Skin Disease Prediction using Deep Learning

## Overview
This project focuses on **Skin Disease Classification** using **Convolutional Neural Networks (CNNs)**. The model is designed to predict different types of skin diseases based on medical images. It aims to assist healthcare professionals by providing a reliable and automated diagnosis.

## Features
- **Image Classification**: Uses deep learning to classify skin diseases.
- **Pretrained Models**: Utilizes transfer learning with models like VGG16 or ResNet.
- **User Interface**: Provides a user-friendly interface for easy disease prediction.
- **Visualization**: Displays model confidence scores and predictions.
- **Scalability**: Can be extended with more classes and enhanced datasets.

## Dataset
The dataset consists of **labeled images** of various skin conditions, collected from open-source medical datasets. The data is preprocessed, including resizing, normalization, and augmentation to improve model accuracy.

## Technologies Used
- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **Scikit-Learn**
- **Matplotlib & Seaborn** (for visualization)

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/Rana-Ahmed24/SkinDiseasePrediction.git
   ```
2. Install the required libraries:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the model training script:
   ```sh
   python train.py
   ```
4. Use the model for predictions:
   ```sh
   python predict.py --image path/to/image.jpg
   ```

## Model Performance
The CNN model achieves **high accuracy** in classifying different skin diseases. Evaluation metrics such as **precision, recall, and F1-score** are used to assess the model's performance.

## Results & Visualization
- **Confusion Matrix**
- **Accuracy & Loss Plots**
- **Sample Predictions**

## Future Enhancements
- Implement real-time skin disease detection via a mobile app.
- Train on larger and more diverse datasets.
- Integrate Explainable AI (XAI) techniques to improve trust in predictions.


