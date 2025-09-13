# A Hybrid Stacked Ensemble Framework for Heart Disease Prediction

This repository contains the code and supporting material for the paper:

> **A Hybrid Stacked Ensemble Framework for Heart Disease Prediction**  
> Anamika Baruah, 2024  

The study evaluates a range of machine learning and deep learning models for early heart attack prediction using a pre-processed clinical dataset.  
The hybrid stacked ensemble — combining Logistic Regression, Random Forest, and XGBoost with a neural meta-learner — achieved the best overall performance.

---

## 📌 Contents

- `Hybrid_Model.ipynb` – Jupyter notebook implementing the Hybrid Stacked Model (LR + RF + XGB + MLP meta-learner).
- Preprocessing, SMOTE class balancing, feature scaling.
- Model training, evaluation metrics, and visualisations (confusion matrix, ROC curve).
- Code snippets for CNN + LSTM, BiGRU, RNN + BiLSTM, XGBoost with deep features, as described in the paper.

---

## 🗂 Dataset

This work uses the [Heart Disease Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset) by A. Teboul (2022).  
A pre-processed version (`preprocessed_heart_attack.csv`) with imputation, encoding, and scaling is used in the notebook.

---

## 🧑‍💻 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>

2. Install dependencies:
   pip install -r requirements.txt

3. Launch Jupyter Notebook:
   jupyter notebook Hybrid_Model.ipynb

4. Run all cells to reproduce training and evaluation.

## 📊 Results

On the held-out test set, the hybrid stacked model achieved:

Accuracy: 94.24%

Precision: 94.71%

Recall: 93.54%

F1 Score: 94.20%

AUC-ROC: 98%

Visualisations (confusion matrices, ROC curves) are generated in the notebook.

📝 Citation

If you use this code, please cite:
@misc{Baruah2024HybridStacked,
  author       = {Anamika Baruah},
  title        = {A Hybrid Stacked Ensemble Framework for Heart Disease Prediction},
  year         = {2024},
  howpublished = {\url{https://github.com/Pen-anamika/Heart-Attack-Prediction-Hybridmodel}}
}

## 📄 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
