# Face Mask Detection System  
🚀 **Real-time face mask detection using deep learning and computer vision**  

![Project Banner](https://github.com/user-attachments/assets/9923d8d4-60c6-4369-8e33-ed14502716c5)
## 📌 Overview  
The **Face Mask Detection System** is designed to identify individuals wearing face masks in real-time using a webcam or image input. Built using **Convolutional Neural Networks (CNN)** with **Keras**, **TensorFlow**, and **OpenCV**, this system effectively classifies masked and unmasked faces and enhances public health monitoring.

## 📂 Project Structure  
*├── dataset*
*│   ├── with_mask (690 images)*
*│   ├── without_mask (689 images)*
*├── haarcascades (face detection classifier)*
*├── images (examples of detections)*
*├── models (trained models: .h5, .keras)*
*├── notebooks (Jupyter Notebooks for training & analysis)*
*├── scripts (Python scripts for execution)*

## 🛠 Technologies Used  
- **Python** (Programming Language)  
- **OpenCV** (Face detection)  
- **TensorFlow/Keras** (Deep Learning Model)  
- **CNN (Convolutional Neural Network)**  
- **Haarcascade Frontalface Default.xml** (Pre-trained Face Detector)  

## 🎯 Dataset & Model
**The dataset consists of images of people with and without masks, categorized into two classes:**
- Class 0 → With Mask
- Class 1 → Without Mask
**The trained model (mask-detector-model.model) can be used for real-time detection via a webcam.**

## 📸 Sample Predictions
**Below are some sample detections of the system:**
✅ Correctly detected "With Mask" image:
(https://github.com/user-attachments/assets/ad191a3b-ef30-4ace-96f7-3af74a195cde)

❌ Correctly detected "Without Mask" image:
(https://github.com/user-attachments/assets/5531b1d2-53bf-4de7-80da-de0c01d17ac9)



## 📜 License
**This project is open-source and free to use for educational and research purposes.**
## 🙌 Contributing
**Contributions are always welcome! Feel free to open issues or submit pull requests. 😊**
