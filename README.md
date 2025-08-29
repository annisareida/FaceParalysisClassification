# Face Paralysis Classification

This repository contains the implementation of the **Face Paralysis Classification System**, a trial-and-error experimental work for a final project developed by Informatics Engineering students at **Sriwijaya University**.  
The goal of this project is to assist in the early detection of facial paralysis by classifying facial images into two categories: **Paralysis** and **Normal**, using deep learning with transfer learning.

## 🌍 Live Demo
You can access the deployed system here:  
👉 [Face Paralysis Classification Web App](https://kelumpuhan-wajah-full-unsri.streamlit.app/)

---

## 🎯 Project Objective
The system aims to provide a **fast, consistent, and accessible screening tool** to help support preliminary detection of facial paralysis. In the future, the project is planned to be extended into a **multi-class classification system using the House–Brackmann scale** for standardized clinical evaluation.

---

## 📊 Dataset Description
- **Paralysis faces**: Private dataset from *Massachusetts Eye and Ear Infirmary (MEEI)*.  
- **Normal faces**: Public dataset from Kaggle — [CelebA Dataset](https://www.kaggle.com/datasets/jessicali9530/celeba-dataset).  
- **Total samples**: 115 images  
  - 65 Normal  
  - 50 Paralysis  

---

## 🔄 Project Workflow
1. **Dataset Preparation**  
   - Normal faces sourced from CelebA dataset  
   - Paralysis faces sourced from MEEI private dataset  
   - Images cleaned, resized, and preprocessed for model input  

2. **Model Training**  
   - Transfer learning with **MobileNetV2** using TensorFlow  
   - Achieved accuracy: **0.94**  

3. **Deployment**  
   - Model integrated into a Streamlit web app  
   - Accessible online for interactive predictions  

---

## ⚙️ How to Use
1. Open the web app at: [https://kelumpuhan-wajah-full-unsri.streamlit.app/](https://kelumpuhan-wajah-full-unsri.streamlit.app/)  
2. Choose your input method:
   - **Webcam** (capture face directly)  
   - **Upload a photo**  
3. Click **Predict**  
4. The system will instantly display the classification result: **Normal** or **Paralysis**  

---

## 🛠️ Tech Stack
- **Deep Learning Framework**: TensorFlow  
- **Model**: MobileNetV2 (Transfer Learning)  
- **Deployment**: Streamlit  

---

## 📌 Future Work
- Extend classification from binary (**Normal vs. Paralysis**) to **multi-class severity levels** using the **House–Brackmann scale**.  
- Expand dataset for broader generalization and clinical applicability.  

---

## 👨‍🎓 About
This project was developed by **Informatics Engineering students at Sriwijaya University** as a **Final Project** in the completion of their studies.  

---
