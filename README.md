# Heart Disease Prediction

This project applies machine learning to predict the presence of heart disease based on clinical data. It explores the relationship between various health indicators and heart disease using data visualization and classification modeling.

---

## 📌 Objective

To build a classification model that predicts whether a patient is likely to have heart disease based on medical attributes. This helps demonstrate how data science can support preventive healthcare and risk stratification.

---

## 🧾 Dataset

- File used: `heart.csv`
- Features include:
  - Age, Sex, Chest pain type
  - Resting blood pressure, Cholesterol
  - Fasting blood sugar, Maximum heart rate
  - ST depression (oldpeak), Exercise-induced angina

Target variable:
- `target`: 1 = heart disease present, 0 = no heart disease

---

## 📊 Exploratory Data Analysis (EDA)

The notebook includes:
- Count plots for categorical features
- Histograms and boxplots for numeric variables
- Heatmap of feature correlations

These visualizations reveal potential patterns and relationships between features and the disease outcome.

---

## 🧹 Preprocessing

Steps:
- Handling missing values (if any)
- Encoding categorical variables
- Normalizing numerical columns
- Splitting dataset into training and testing sets

---

## 🤖 Model Building

Classifier used:
- Random Forest Classifier
- Multinomial Logistic Regression
- SVM
- Ensemble Model

Evaluation:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 🧠 Key Findings

- Features like chest pain type, oldpeak, and exercise-induced angina show strong influence on predictions.
- Random Forest performed well with a solid accuracy on test data.
- Balanced performance across both classes (with minor improvement potential).

---

## 🛠️ Technologies Used

- Python  
- pandas, numpy  
- seaborn, matplotlib  
- scikit-learn (RandomForestClassifier, train_test_split, etc.)

---

## 📈 Results

- Model Accuracy:
Logistic Model Accuracy: 0.88
SVM Model Accuracy: 0.84
Random forest Accuracy: 0.86
Ensemble Model Test Accuracy: 0.89

The ensemble model outperforms individual classifiers, demonstrating the power of combining different models to enhance predictive accuracy.

---

## 📄 License

This project is intended for academic and research purposes only.

---

## 👩‍💻 Author

Vishwajyothi Reshmi
Master’s Student – Data Science
