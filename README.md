Sure! Here's a **clean, professional, and visually engaging rewrite** of your `README.md` with improved formatting, clarity, and emoji-enhanced sections:

---

# 🧠 Brain Tumor Detector

A deep learning–powered web application that detects **brain tumor types** from MRI scans. This tool uses a custom-trained **Convolutional Neural Network (CNN)** to classify MRI images into one of four categories:

* 🎯 **Glioma Tumor**
* 🎯 **Meningioma Tumor**
* 🎯 **Pituitary Tumor**
* ✅ **No Tumor**

It also provides a list of **common symptoms** associated with the detected tumor type — helping raise awareness and aid understanding.

---

## 🌟 Demo Features

Upload an MRI scan, and the model will:

* 🧠 Predict **whether a brain tumor is present**
* 🔍 Identify the **type of tumor**
* 🩺 Display **common symptoms** associated with the tumor type

> ⚠️ **Disclaimer:** This app is a proof of concept and not intended for clinical diagnosis.

---

## 📂 Dataset Used

Trained on the open-source Kaggle dataset:
🔗 [Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

### 🧪 Dataset Classes:

* **Glioma Tumor**
* **Meningioma Tumor**
* **Pituitary Tumor**
* **No Tumor**

---

## 🤖 Model Overview

The model is a **custom CNN** developed using **PyTorch**, trained from scratch with the following specs:

* 🖼️ **Input Size:** 64×64 grayscale images
* 🧱 **Architecture:** 3 Convolutional Layers + 2 Fully Connected Layers
* ⚙️ **Optimizer:** Adam
* 🎯 **Loss Function:** Cross Entropy Loss
* 📈 **Validation Accuracy:** \~94%

### 🧹 Preprocessing Steps:

* Convert to grayscale
* Resize to 64×64
* Normalize pixel values

📦 **Saved model file:** `brain_tumor_model.pth`

---

## 🌐 Web Application

The app is built with:

* 🐍 **Flask** (Backend)
* 💻 **HTML/CSS** (Frontend)
* 🧠 animated background

### ✨ Features:

* Upload and display MRI images
* Show predicted tumor type
* List related symptoms

---

## 🚀 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Pranshu936/Brain-Tumor-Detector
cd Brain-Tumor-Detector
```

### 2. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate      # Linux/Mac
# OR
venv\Scripts\activate         # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app/app.py
```

🖥️ Open your browser and navigate to:
[http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 💡 Project Motivation

Brain tumors can be **life-threatening** and require **early detection** for better prognosis.
This project demonstrates how **AI can assist in medical diagnostics** by offering an initial, automated screening tool — helping make healthcare more accessible.

> ⚠️ **Note:** This app is not a substitute for professional medical diagnosis.

---

## 🙏 Acknowledgements

* 📊 [Kaggle Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
* 🔧 PyTorch, Flask, PIL, torchvision


---

## 📄 License

📝 **MIT License** — free to use for personal and educational purposes.

---

