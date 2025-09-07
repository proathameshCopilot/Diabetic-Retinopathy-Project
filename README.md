# 🩺 Diabetic Retinopathy Detection (ML Project)

This project is focused on building a **Machine Learning based system** to detect **Diabetic Retinopathy (DR)** from retinal fundus images.  
We are following a step-by-step approach, and this README documents the progress so far (≈30% completed).

---

## ✅ Current Progress (30% Implementation)

### 1. Environment Setup

- Installed **Python 3.13**
- Created and activated **virtual environment (`venv`)**
- Installed required libraries:
  - `numpy`, `pandas`, `matplotlib`, `opencv-python`
  - `scikit-learn`, `tensorflow`, `albumentations`

### 2. Dataset Setup

- Downloaded a **small Diabetic Retinopathy dataset (≈32 MB)** from Kaggle.
- Organized dataset into project folder:

### 3. Exploratory Data Analysis (EDA)

- Checked dataset structure and confirmed classes: **`DR` and `No_DR`**
- Counted number of images per class:
- DR : 1050 images
- No_DR : 1026 images
- Displayed **sample images** from each class for visualization.

### 4. Preprocessing (Initial Step)

- Implemented a **preprocessing function**:
- Resizes images to **224x224**
- Converts BGR → RGB
- Normalizes pixel values (0–1 range)
- Tested preprocessing on one sample image and displayed the result.

---

## 📂 Project Structure (till now)

Diabetic-Retinopathy/
│
├─ data/
│ └─ raw/
│ └─ Diagnosis of Diabetic Retinopathy/ # dataset folders
│
├─ notebooks/
│ └─ 01_EDA.ipynb # dataset exploration + preprocessing demo
│
├─ src/
│ ├─ preprocess.py # preprocessing utilities (future)
│ └─ model.py # baseline model (future)
│
├─ models/ # will store trained model weights
├─ requirements.txt # dependencies
└─ README.md # project documentation
