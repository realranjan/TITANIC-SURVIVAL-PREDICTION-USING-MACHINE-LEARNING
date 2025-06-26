# Titanic Survival Prediction Using Machine Learning

![OIP](https://github.com/Neo28A/Titanic_Survival_Prediction_Using_ML/assets/102372671/60d9bd0a-0aaa-465f-9e9a-2263801862ae)

## Overview

This repository contains a machine learning project that predicts the survival outcomes of passengers aboard the Titanic using various machine learning algorithms. The project includes data analysis, visualization, and the development of predictive models.

## Project Structure

- `dataset/titanicsurvival.csv`: The Titanic dataset used for training and evaluation.
- `TitanicSurvivalPrediction.ipynb`: Jupyter notebook for exploratory data analysis, visualization, and model development.
- `titanicsurvivalprediction.py`: Standalone Python script for data analysis, model training, and making predictions via command-line input.

## Dataset

The dataset is located at `dataset/titanicsurvival.csv` and contains the following columns:
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Sex`: Gender (`male` or `female`)
- `Age`: Age in years
- `Fare`: Passenger fare
- `Survived`: Survival (0 = No, 1 = Yes)

## Analysis and Visualization

Data analysis and visualization are performed in the Jupyter notebook (`TitanicSurvivalPrediction.ipynb`). The notebook explores:
- Gender and class distribution
- Survival rates by gender and class
- Data preprocessing and feature engineering
- Model comparison and evaluation

## Machine Learning Models

Several machine learning algorithms are employed to create predictive models, including:
- Logistic Regression
- Decision Tree Classifier
- Gaussian Naive Bayes
- K-Nearest Neighbors
- Support Vector Classifier (SVC)

### Model Performance

Among the algorithms tested, the logistic regression model achieved a cross-validation score of approximately 81% and a test accuracy of 77%, making it the most robust and reliable for this task.

## How to Run

### Using the Jupyter Notebook
1. Open `TitanicSurvivalPrediction.ipynb` in Jupyter Notebook or Google Colab.
2. Follow the cells to perform data analysis, visualization, and model training.
3. You can modify and experiment with the code interactively.

### Using the Python Script
1. Ensure you have Python 3 and the required libraries installed (`pandas`, `numpy`, `matplotlib`, `scikit-learn`).
2. Place `titanicsurvivalprediction.py` and the dataset (`dataset/titanicsurvival.csv`) in the same directory or update the script to point to the correct dataset path.
3. Run the script:
   ```bash
   python titanicsurvivalprediction.py
   ```
4. The script will prompt you to enter passenger details (class, gender, age, fare) and will predict survival based on the trained model.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

You can install the dependencies using:
```bash
pip install pandas numpy matplotlib scikit-learn
```

## License
This project is for educational purposes.

---

### Quantized Resume Points
- Designed and implemented a full-stack machine learning pipeline for Titanic survival prediction, including data cleaning, feature engineering, and model selection.
- Achieved 81% cross-validation and 77% test accuracy using logistic regression, outperforming other tested algorithms.
- Developed both a Jupyter notebook for interactive analysis and a Python script for command-line predictions, enhancing project accessibility.
- Automated model evaluation and comparison across five algorithms using scikit-learn.
- Visualized key data insights and model results to support data-driven decision making.
- Documented the project with clear instructions, reproducibility, and user guidance, improving usability for non-technical users.

