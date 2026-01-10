<div style="text-align:center; margin-top:20px;">
  <h1 style="font-size:32px; font-weight:bold; color:#2c3e50;">
    LungAI: Deep Learning-Based Lung Disease Detection Using ResNet-50
  </h1>
  <p style="font-size:18px; color:#555;">
    A Group Project by <strong>Neural Rookies</strong>
  </p>
</div>

<hr style="border:1px solid #e0e0e0; width:80%;">
<h2 style="color:#1f6feb;">👥 Team Name</h2>
<p style="font-size:18px;">
  <strong>Neural Rookies</strong>
</p>
<hr>

<h2 style="color:#1f6feb; display:flex; align-items:center; gap:10px;">
  👨‍💻 Team Members & Contributions
  <img 
    src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" 
    alt="Coding Animation" 
    width="40"
  >
</h2>

<ul style="list-style-type:none; padding-left:0; font-size:16px;">

  <li style="margin-bottom:10px;">
    <strong>Ansh Kumar</strong> — Group Lead, project planning and coordination
  </li>

  <li style="margin-bottom:10px;">
    <strong>Deepak Chaurasiya</strong> &amp; <strong>Anshul Kundu</strong> — 
    Code development, model implementation, experimentation, and performance evaluation
  </li>

  <li style="margin-bottom:10px;">
    <strong>Bidisha Kundu</strong> — Analysis support, documentation, and overall project assistance
  </li>

</ul>
## 📌 Overview

LungAI is a deep learning–based medical imaging system designed to detect multiple lung diseases from chest X-ray images.
The system leverages a transfer learning approach using the ResNet-50 architecture to classify X-ray images into four categories:
**COVID-19, Normal, Pneumonia, and Tuberculosis**.

The project aims to assist healthcare professionals by enabling rapid, reliable, and interpretable lung disease diagnosis.

---

## 👥 Team Name
**Neural Rookies**
---

## 👨‍💻 Team Members & Contributions
- **Ansh Kumar** – Group Lead, project planning and coordination  
- **Deepak Chaurasiya** And - **Anshul Kundu** – Code development, model implementation, experimentation, and performance evaluation  
- **Bidisha Kundu** – Analysis support, documentation, and overall project assistance  

---

## 🧠 Methodology
- Transfer learning using **ResNet-50** as the base CNN architecture  
- Combined chest X-ray datasets sourced from Kaggle  
- Total dataset size: **2,303 X-ray images**  
- Image classes:
  - COVID-19  
  - Normal  
  - Pneumonia  
  - Tuberculosis  
- Dataset split into **training, validation, and testing** sets  
- Model interpretability achieved using **Grad-CAM visualization**

---
## 📊 Results
- Overall classification accuracy: **91.87%**  
- Area Under Curve (AUC): **99.20%**  
- Grad-CAM visualizations were used to highlight disease-relevant regions in X-ray images
---

## 📁 Dataset
⚠️ The dataset is currently **not included** in this repository.  
It will be added or linked in a future update.
 **I will upload on github later**
---

## ▶️ How to Run
1. Open the notebook (`.ipynb`) in **Google Colab**
2. Upload the dataset when prompted
3. Run the cells sequentially to train and evaluate the model
---

## 🛠️ Technologies Used
- Python  
- TensorFlow / Keras  
- ResNet-50  
- Google Colab  
- Grad-CAM  
---

## 📌 Keywords
Deep Learning, ResNet-50, Lung Disease Detection, Chest X-ray, CNN, COVID-19, Pneumonia, Tuberculosis, Grad-CAM
