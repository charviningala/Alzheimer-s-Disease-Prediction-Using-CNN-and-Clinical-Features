# 🧠 Alzheimer’s Disease Prediction Using CNN and Clinical Features

## 📌 Overview

This project presents a **hybrid Alzheimer’s disease prediction model** that combines a **Convolutional Neural Network (CNN)** with **clinical features** to improve diagnostic accuracy.
The primary objective is to **reduce false positives and false negatives** commonly observed when relying solely on imaging-based CNN models.

The implementation is provided in **`model.ipynb`** and is intended for **research, academic, and applied learning purposes**.

---

## 🎯 Problem Statement

CNN-based models trained only on brain imaging data (such as MRI scans) can:

* Overpredict Alzheimer’s disease in borderline cases (false positives)
* Miss early-stage or atypical cases (false negatives)

Clinical indicators such as cognitive scores, age, and other patient attributes provide **contextual information** that imaging alone cannot capture.

---

## 💡 Proposed Solution

This notebook implements a **multi-modal learning approach** that:

1. Uses a **CNN model** to extract deep features from medical images
2. Incorporates **clinical features** (e.g., demographic and cognitive data)
3. Combines both representations to make a final prediction
4. Improves robustness and reduces misclassification errors

---

## 🔬 Model Architecture

### 1. CNN-Based Feature Extraction

* Extracts spatial and structural features from brain images
* Learns disease-specific visual patterns

### 2. Clinical Feature Integration

Clinical attributes may include:

* Age
* Gender
* Cognitive test scores
* Other numerical clinical indicators

These features are:

* Preprocessed and normalized
* Concatenated with CNN feature embeddings

### 3. Final Classification Layer

* Uses combined features for prediction
* Balances imaging and clinical signals
* Aims to minimize false positives and false negatives

---

## 📊 Key Advantages

* ✔ Reduced false positives compared to CNN-only models
* ✔ Improved sensitivity for early-stage detection
* ✔ Better generalization across patient profiles
* ✔ Clinically interpretable and more realistic predictions

---

## 🧪 Notebook Contents (`model.ipynb`)

The notebook includes:

* Data preprocessing and normalization
* CNN model loading / training
* Clinical feature handling
* Feature fusion strategy
* Model evaluation and analysis
* Performance comparison with baseline CNN

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras or PyTorch (depending on implementation)
* NumPy & Pandas
* Scikit-learn
* Jupyter Notebook

---

## ▶️ How to Run

1. Open the notebook:

   ```bash
   jupyter notebook model.ipynb
   ```
2. Ensure required libraries are installed.
3. Run cells sequentially to reproduce results.
4. Modify clinical features or thresholds for experimentation.

---

## 📈 Evaluation Focus

* Accuracy
* Reduction in false positives
* Reduction in false negatives
* Comparative performance with CNN-only model

---

## 📌 Disclaimer

This project is intended **strictly for educational and research purposes**.
It is **not a medical diagnostic tool** and should not be used for clinical decision-making.

---

## 👤 Author

**Charvi Ningala**

