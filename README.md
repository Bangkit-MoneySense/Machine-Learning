<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/e/e2/Bangkit-logo.png" alt="Bangkit Logo" width="300">
</p>
<br><br>

# 🏷️ Multi-Label Classification Project

This repository contains the implementation of a **multi-label classification model** for the dataset: `Multi-Label-Classification_V3_by-Ulhaq_Balance-Dataset_Kresna_Augmentation-Dataset`. The project leverages machine learning to accurately classify multiple labels for a given input.

---

## 🗂️ Project Structure

- **Dataset**:  
  - Includes balanced and augmented datasets.  
  - Preprocessing steps are provided in the Jupyter Notebook.  

- **Model**:  
  - TensorFlow-based multi-label classification model.  
  - Handles imbalanced data using oversampling and augmentation techniques.  

- **Notebook**:  
  - Jupyter Notebook for exploratory data analysis (EDA), preprocessing, training, and evaluation.  

---

## 📋 Prerequisites

1. **Install Dependencies**:  
   Ensure you have Python and the following packages installed:
   ```bash
   pip install tensorflow scikit-learn pandas matplotlib seaborn
   ```

2. **Prepare the Dataset**:  
   - Place the dataset file in the working directory.  
   - Update paths in the Jupyter Notebook as necessary.

3. **Notebook Environment**:  
   Install Jupyter Notebook if not already installed:
   ```bash
   pip install notebook
   ```

---

## 🚀 How to Run

1. Clone the repository and navigate to the project directory:
   ```bash
   git clone <repository-url>
   cd Multi-Label-Classification
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open the notebook `Multi-Label-Classification_V3_by-Ulhaq_Balance-Dataset_Kresna_Augmentation-Dataset.ipynb` and execute cells sequentially.

---

## 🧪 Model Performance

- **Evaluation Metrics**:  
  - **Accuracy**: Measures the overall correctness of predictions.  
  - **F1 Score**: Accounts for precision and recall.  
  - **Confusion Matrix**: Visualizes classification performance per label.  

- **Results**:  
  Detailed results and visualizations are provided in the notebook.

---

## 📡 Features

1. **Multi-Label Support**:  
   - Designed for datasets with multiple target labels.  

2. **Data Augmentation**:  
   - Improves model robustness by generating additional training samples.  

3. **Model Customization**:  
   - Supports hyperparameter tuning for better performance.  

---

## 📂 Folder Structure  

- `/data`: Contains the raw and preprocessed datasets.  
- `/models`: Stores trained models and checkpoints.  
- `/notebooks`: Includes Jupyter Notebooks for analysis and training.  
- `/visualizations`: Saves plots and performance metrics.  

---

## 🌐 Additional Information  

- **Dataset Details**:  
  - Balanced dataset with augmentation techniques.  
  - Ensures fairness in multi-label classification tasks.  

- **Code Dependencies**:  
  - TensorFlow for deep learning.  
  - scikit-learn for preprocessing and evaluation.  

- **References**:  
  Documentation and resources related to multi-label classification techniques are provided within the notebook.

---  

For questions or feedback, feel free to reach out! 📧
