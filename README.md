🧠 Brain Tumor Detection Using CNN

👨‍🎓 About the Project:
This project is developed as part of my engineering learning journey in Deep Learning and Computer Vision. 
It uses a Convolutional Neural Network (CNN) to classify brain MRI images into:
Tumor
No Tumor
The model is trained on MRI scan images sourced from a Kaggle dataset and learns visual patterns to assist in brain tumor detection.

🎯 Objective
To build a deep learning model that can automatically detect brain tumors from MRI images with good accuracy using CNN.

📂 Dataset
The dataset used is publicly available on Kaggle:
Brain MRI Images for Brain Tumor Detection

📁 Dataset Structure
brain_tumor_dataset/
├── yes/   (MRI images with tumor)
└── no/    (MRI images without tumor)

🧠 Model Architecture
The CNN model consists of:
-Convolutional Layers (feature extraction)
-ReLU Activation
-MaxPooling Layers
-Flatten Layer
-Fully Connected Dense Layers
-Output Layer with Sigmoid Activation

⚙️ Technologies Used
-Python 
-TensorFlow / Keras
-NumPy
-Matplotlib
-OpenCV
-Google Colab

🧪 Model Training
-Image size: 128×128 / 150×150
-Batch size: 32
-Epochs: 100
-Optimizer: Adam
-Loss Function: Binary Crossentropy
-Metric: Accuracy

📊 Results
After training the model:
✅ Training Accuracy: 98.02955
✅ Validation Accuracy: 83.99999
📉 Loss decreased steadily over epochs

📈 Observation
Model shows good learning behavior
No major overfitting observed (if validation curve is stable)

🖼️ Prediction Output
The model predicts MRI images as:
🧠 Tumor Detected
✅ No Tumor Detected

Shagun Garg
🎓 Engineering Student
🔗 GitHub: https://github.com/shagun53
