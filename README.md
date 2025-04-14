# -Content-Based-Image-Retrieval-using-Machine-Learning
This project focuses on **Content-Based Image Retrieval (CBIR)** using deep learning techniques such as **VGG16**, **ResNet**, and **MobileNet**. It was developed as a mini-project submitted to **JNTU Hyderabad** in partial fulfillment of the requirements for the **Bachelor of Technology in Electronics and Communication Engineering**.

---

## ✨ Project Overview

Content-Based Image Retrieval (CBIR) systems search for images based on the actual content (such as color, texture, and shape) instead of metadata or keywords.  
This project enhances CBIR performance by using **Convolutional Neural Networks (CNNs)** for feature extraction and **cosine similarity** for image matching.

We experimented with:
- **VGG16**
- **ResNet**
- **MobileNet**

for efficient feature extraction.

---

## 🚀 Features

- Image retrieval based on visual content.
- Pre-trained deep learning models (VGG16, ResNet, MobileNet).
- Cosine similarity to compute image similarity.
- Efficient retrieval from large datasets.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- Scikit-learn
- Matplotlib
- NumPy

---

## 🧠 Models Used

- **VGG16**: Very Deep Convolutional Networks for Large-Scale Image Recognition.
- **ResNet**: Deep Residual Learning for Image Recognition.
- **MobileNet**: Lightweight deep neural network for mobile and embedded vision applications.

---

## 📈 Workflow

1. **Feature Extraction**: Extract deep features from the images using a pre-trained CNN model.
2. **Feature Vector Storage**: Store the extracted feature vectors.
3. **Similarity Computation**: Compute the cosine similarity between query and dataset images.
4. **Image Retrieval**: Retrieve and rank images based on similarity scores.

---

## 📂 Project Structure

```bash
├── models/
│   ├── vgg16_feature_extraction.py
│   ├── resnet_feature_extraction.py
│   └── mobilenet_feature_extraction.py
├── dataset/
│   ├── (your images)
├── retrieval/
│   ├── cosine_similarity.py
├── app.py
├── requirements.txt
├── README.md
