# 🩺 Chest X-ray Pneumonia Detection 

A deep learning project to detect **Pneumonia** from **Chest X-ray images** using **Convolutional Neural Networks (CNNs)**.

---

## 📌 Project Overview

Pneumonia is a serious lung infection that can be life-threatening if not diagnosed early.  
This project applies **CNN-based deep learning models** to automatically classify chest X-ray images into:

- **NORMAL**
- **PNEUMONIA**

The objective is to build a reliable image classification pipeline that can assist in early medical screening.

---

## 📁 Project Structure

```
.
├── data/           # Dataset (ignored in git)
├── notebooks/      # Experiments, EDA, and analysis
├── src/            # Model training and evaluation code
├── models/         # Saved trained models (ignored)
├── reports/        # Metrics, plots, and results
└── README.md
```

---

## 📊 Dataset

The project uses the **Chest X-Ray Images (Pneumonia)** dataset, which contains labeled chest X-ray images.

### Dataset Classes
- **NORMAL**
- **PNEUMONIA**

> ⚠️ Dataset is not included in this repository due to size constraints.

---

## 📥 How to Download the Dataset

### Option 1: Download from Kaggle (Recommended)

1. Visit the dataset page:  
   https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

2. Click **Download**

3. Extract the downloaded ZIP file

4. Place the dataset inside the `data/` directory as follows:

```
data/
└── chest_xray/
    ├── train/
    │   ├── NORMAL/
    │   └── PNEUMONIA/
    ├── test/
    │   ├── NORMAL/
    │   └── PNEUMONIA/
    └── val/
        ├── NORMAL/
        └── PNEUMONIA/
```

---

## 🛠️ Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, OpenCV  

---

## 🚧 Project Status

Work in progress 🚧  

---

## 📜 License

This project is for educational and research purposes.
