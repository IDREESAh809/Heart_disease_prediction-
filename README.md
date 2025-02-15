# Heart Disease Prediction

This project is a beginner-friendly machine learning classification task aimed at predicting heart disease based on patient health data. The project follows a well-structured machine learning pipeline, covering data preprocessing, feature engineering, model training, and evaluation.

## Project Structure
```
Heart_Disease_Predict/
│── data/
│   ├── raw/                # Original dataset
│   ├── processed/          # Cleaned & feature-engineered data
│── models/                 # Saved trained models
│── notebooks/              # Jupyter notebooks for EDA & experiments
│── src/                    # Source code for training and evaluation
│── requirements.txt        # Project dependencies
│── .gitignore              # Files & folders to ignore in Git
│── README.md               # Project documentation
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Heart_Disease_Predict.git
   cd Heart_Disease_Predict
   ```
2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
The dataset used in this project contains patient medical records with multiple features relevant to heart disease. The data undergoes preprocessing, including handling missing values, feature selection, and scaling.

## Models Used
The following classification models were applied:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting

### Model Performance
Currently, the trained models do not achieve high accuracy due to dataset limitations and basic preprocessing. This project is primarily focused on structuring a beginner-friendly workflow rather than achieving state-of-the-art performance.

Best Model: **SVM** with an accuracy of **0.5272**

## Future Improvements
- Improve feature engineering
- Tune hyperparameters
- Experiment with deep learning models
- Collect more diverse data

## License
This project is open-source and available for learning purposes.
