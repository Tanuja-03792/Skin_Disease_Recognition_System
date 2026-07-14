🩺 Skin Disease Recognition and Medical Solution
This web-based project enables automated skin disease detection using deep learning and provides relevant medical information for diagnosis support. Built with a Python Flask backend and a simple, intuitive front end, the system allows users to upload or capture skin lesion images and receive instant predictions, along with details about the disease, its causes, symptoms, and possible treatments.


🚀 Features
🔍 Image Upload & Camera Capture
Upload an image or use your webcam to capture skin lesion images.

🧠 Deep Learning-Based Classification
Predicts skin disease using a trained Convolutional Neural Network model (skin_disease_model.h5) on the HAM10000 dataset.

💬 Medical Information Display
Shows disease name, symptoms, causes, and medical solutions for detected conditions.

💻 User-Friendly Interface
Simple UI built with HTML/CSS and JavaScript (or React, if used).

🔒 Privacy-Focused
All processing is done locally/server-side with no third-party data sharing.

🛠️ Tech Stack
Frontend: HTML/CSS, JavaScript (or React)
Backend: Python Flask
ML Model: CNN trained on Skin dataset
Libraries: TensorFlow/Keras, NumPy, OpenCV, Flask

📂 Dataset
Skin Dataset: A large collection of multi-source dermatoscopic images of common pigmented skin lesions.
✅ Usage
Upload or capture a skin image.
The model analyzes the image and predicts the disease.
The app displays detailed medical information to help users understand the diagnosis.


📌 Goal
To provide an accessible tool for early-stage skin disease detection and awareness using AI, especially for regions with limited access to dermatologists.
