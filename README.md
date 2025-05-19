# Face Mask Detection System  
🚀 **Real-time face mask detection using deep learning and computer vision**  

![Project Banner](images/banner.png)
## 📌 Overview  
The **Face Mask Detection System** is designed to identify individuals wearing face masks in real-time using a webcam or image input. Built using **Convolutional Neural Networks (CNN)** with **Keras**, **TensorFlow**, and **OpenCV**, this system effectively classifies masked and unmasked faces and enhances public health monitoring.

## 📂 Project Structure  
├── dataset
│   ├── with_mask (690 images)
│   ├── without_mask (689 images)
├── haarcascades (face detection classifier)
├── images (examples of detections)
├── models (trained models: .h5, .keras)
├── notebooks (Jupyter Notebooks for training & analysis)
├── scripts (Python scripts for execution)

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
(images/mask_detection.png)  
❌ Correctly detected "Without Mask" image:
(images/no_mask_detection.png)  


## **📜 LicenseThis project is open-source and free to use for educational and research purposes.**
## **🙌 ContributingContributions are always welcome! Feel free to open issues or submit pull requests. 😊**
