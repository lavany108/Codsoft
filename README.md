# Movie Genre Classification (CodSoft Task 1)

## Objective
Predict the genre of a movie based on its plot summary using Natural Language Processing (NLP) and Machine Learning.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- LinearSVC

## Experiments
- TF-IDF + Logistic Regression (Baseline): **58.38%**
- Improved TF-IDF + Logistic Regression: **57.14%**
- Improved TF-IDF + LinearSVC: **59.31%** ✅

## Best Model
The Improved TF-IDF + LinearSVC model achieved the highest validation accuracy and was selected as the final model.

## Project Structure
- `task1/notebooks/` – Jupyter notebook
- `task1/data/` – Dataset and predictions

# Customer Churn Prediction (CodSoft Task 2)

## Objective
Develop a Machine Learning model to predict whether a customer is likely to churn based on customer demographics, account information, and banking behavior.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Logistic Regression
- Random Forest
- Gradient Boosting

## Experiments
|        Model        |  Accuracy  |
|---------------------|------------|
| Logistic Regression | **81.10%** |
| Random Forest       | **86.65%** |
| Gradient Boosting   | **86.75%** |

## Best Model
The **Gradient Boosting Classifier** achieved the highest accuracy (**86.75%**) and was selected as the final model.

## Project Structure
- `task2/notebooks/` – Jupyter Notebook
- `task2/data/` – Dataset
- `task2/models/` – Saved trained model
