# Mental Illness Prediction using Machine Learning

This project is focused on predicting various mental illnesses using machine learning techniques. It involves cleaning and preprocessing the dataset, visualizing feature relationships, and building a predictive model to identify mental illness types based on patient data.

## 📊 Dataset
- Source: CSV file containing psychological and behavioral traits.
- Target: `mental_illness_type` (e.g., Depression, Anxiety, OCD, etc.)
- Features: Includes sleep, diet, stress, family history, trauma, etc.

## 🔍 Key Steps
1. **Data Preprocessing**
   - Null value handling
   - Label encoding categorical features
   - Feature selection using `SelectKBest`

2. **Model Building**
   - Random Forest Classifier
   - SMOTE applied for class balancing
   - Train-Test Split (80-20)

3. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix
   - Classification Report

4. **Visualization**
   - Count plots of classes
   - Correlation heatmap
   - Feature importance bar plot

## 🧠 Libraries Used
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Imbalanced-learn (SMOTE)

## 📈 Model Performance
- Model Accuracy: ~86%
- Balanced metrics using SMOTE-enhanced data

## 📌 How to Run
1. Clone the repository or download the `.ipynb` file.
2. Run the notebook in Jupyter or Google Colab.
3. Make sure all required libraries are installed (`pip install -r requirements.txt` if available).

## 🤝 Contributions
Feel free to fork and contribute improvements to the model, visualizations, or dataset.

## ⚠️ Disclaimer
This model is for educational purposes and is not a substitute for professional mental health diagnosis or treatment.
