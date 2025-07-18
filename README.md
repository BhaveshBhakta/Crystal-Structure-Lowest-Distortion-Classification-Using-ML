# Crystal Structure Lowest Distortion Classification Using Machine Learning

## Project Overview

This project focuses on predicting the **lowest distortion space group** for different crystal structures using supervised machine learning models. The dataset contains structural and physical properties of crystals, and the task is to classify the `lowest_distortion` group, which plays a crucial role in understanding phase transitions and material behavior.

---

## Technical Highlights

* **Dataset Source**: Kaggle — [Crystal Structure Dataset](https://www.kaggle.com/datasets/saurabhshahane/crystal-structure-classification)
* **Objective**: Classify the `lowest_distortion` from other features like `crystal_system`, `space_group`, `cell_volume`, etc.

### 🧪 Data Processing & Exploration:

* Dropped irrelevant columns such as `id`, `material_id`, and `formula`
* Converted categorical columns (`space_group`, `crystal_system`, `structure`) using label encoding
* Used `MinMaxScaler` for feature normalization
* Visualized:

  * Class distribution of `lowest_distortion`
  * Boxplots of feature spread
  * Correlation matrix (heatmap)

### 🧠 Modeling:

multiple algorithm

### 📊 Evaluation:

* Classification report (Precision, Recall, F1-score)
* Confusion matrix heatmaps
* Accuracy scores
* Comparison of model performance before and after applying SMOTE for class imbalance

---

## Purpose and Applications

* **Material Science Research**: Assist scientists in identifying symmetry-breaking distortions in crystals.
* **Accelerated Materials Discovery**: Predict structural transitions using AI instead of costly simulations.
* **Educational Tools**: Help students and researchers understand the link between crystal features and space group distortions.

---

## Installation

 **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/Crystal-Structure-Lowest-Distortion-Classification-Using-ML.git
   cd Crystal-Structure-Lowest-Distortion-Classification-Using-ML
   ```

---

## Collaboration

We welcome contributions and suggestions to improve the models or expand the dataset analysis.

* Fork the repository
* Create a new branch (`feature/your-feature-name`)
* Commit and push your changes
* Submit a pull request
