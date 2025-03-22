# Brain Tumor Detection using Deep Learning

## 📌 Overview  
Brain tumors are caused by the abnormal growth of cells in the brain, some of which may lead to cancer. The traditional method for detecting brain tumors involves **Magnetic Resonance Imaging (MRI)** scans, which help identify abnormal tissue growth.  

In this project, we leverage **Deep Learning** techniques, particularly a **self-defined Convolutional Neural Network (CNN)**, to detect brain tumors from MRI images. Applying deep learning algorithms enhances **accuracy, speed, and efficiency**, assisting radiologists in making quick and precise decisions.  

---

## 🏥 Problem Statement  
- **Early detection** of brain tumors is crucial for effective treatment.  
- Manual diagnosis of MRI scans is time-consuming and prone to human error.  
- AI-powered deep learning models can **automate and enhance the diagnostic process** with high accuracy.  

---

## 🔬 Methodology  

### 1️⃣ Image Pre-Processing  
To improve image quality, we apply several filtering techniques:  
✅ **Mean Filter**  
✅ **Median Filter**  
✅ **Wiener Filter**  
✅ **Hybrid Filter**  
✅ **Modified Hybrid Median Filter**  
✅ **Morphology-Based Denoising**  

### 2️⃣ Image Segmentation  
To isolate the tumor region, we use:  
✅ **Threshold Segmentation**  
✅ **Morphology-Based Segmentation**  
✅ **Convolutional Neural Network (CNN) Algorithm**  

### 3️⃣ Feature Extraction  
To analyze key characteristics in MRI images:  
✅ **Edge Detection using Prewitt, Robert, and Sobel methods**  
✅ **Feature Extraction using Histogram of Oriented Gradients (HOG)**  

---
### Types of Brain Tumors
Tumors are of three types:
- **1.Glioma** – A type of tumor that occurs in the glial cells of the brain or spine, often aggressive in nature.
- **2.Meningioma** – A usually benign tumor that forms in the meninges, the protective layers covering the brain and spinal cord.
- **3.Pituitary Tumor** – A growth in the pituitary gland, which can affect hormone production and various bodily functions.
  
  🚀 This project leverages Convolutional Neural Networks (CNNs) to preprocess MRI images and classify brain tumors into these categories, aiding in early diagnosis and treatment planning. 
---

## 🛠️ Technologies Used  
- **Python**  
- **TensorFlow / Keras** – Deep Learning Framework  
- **OpenCV** – Image Processing  
- **NumPy & Pandas** – Data Handling  
- **Matplotlib & Seaborn** – Data Visualization  
- **Scikit-learn** – Machine Learning Algorithms  

---

## 🎯 Results  
The proposed **CNN-based model** successfully detects the presence of brain tumors with **high accuracy**. The results demonstrate that deep learning can be an effective tool in medical imaging for early diagnosis, reducing dependency on manual assessment.  
