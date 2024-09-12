# Iris Classification

This repository focuses on classifying Iris species using Python libraries. The project utilizes various classification algorithms to analyze and predict species based on features from the Iris dataset.

## Overview

The goal of this project is to develop a model that accurately classifies Iris flowers into their respective species. The dataset is analyzed using several machine learning classifiers, including Logistic Regression, Decision Tree, Random Forest, Support Vector Classifier, Multi-layer Perceptron, Naive Bayes, and XGBoost.


## Features

- **Data Preprocessing**: Clean and preprocess the dataset, including handling missing values and encoding categorical variables.
- **Model Training**: Train multiple classifiers and compare their performance.
- **Hyperparameter Tuning**: Perform hyperparameter tuning using GridSearchCV to optimize model performance.
- **Evaluation**: Evaluate the models using metrics such as accuracy, precision, recall, F1 score, and confusion matrix.

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

Ensure you have Python 3.x installed. You'll also need the following Python libraries:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- XGBoost

You can install these dependencies using pip:

\```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
\```

### Running the Project

1. Clone the repository:

\```bash
git clone https://github.com/yourusername/Iris-Classification.git
\```

2. Navigate to the project directory:

\```bash
cd Iris-Classification
\```

3. Ensure you have the Iris dataset CSV file named `IRIS.csv` in the same directory or update the file path in the script.

4. Run the Python script to start the classification process:

\```bash
python iris_classification.py
\```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
