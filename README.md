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

# Handwritten Text Generation (CodSoft Task 3)

## Objective

Implement a character-level recurrent neural network (RNN) to generate handwritten-like text. Train the model on a dataset of handwritten text examples, and let it generate new text based on the learned patterns.

## Technologies Used

- Python
- Pandas
- NumPy
- TensorFlow / Keras
- Matplotlib
- Jupyter Notebook
- Character-Level RNN
- Embedding Layer
- LSTM (Long Short-Term Memory)

## Model Architecture

- Embedding Layer (64-dimensional embeddings)
- LSTM Layer (128 units)
- Dense Output Layer with Softmax Activation

## Training Details

- Sequence Length: 100 characters
- Vocabulary Size: 65 unique characters
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Batch Size: 64
- Epochs: 5

## Results

- Training Accuracy: **48.1%**
- Validation Accuracy: **48.8%**

The trained model successfully learned character-level language patterns and generated Shakespeare-style text. Probability-based sampling was used during text generation to produce more diverse and natural-looking outputs.

## Project Structure

- `task3/notebooks/` – Jupyter Notebook
- `task3/data/` – Training, Validation and Test datasets
- `task3/models/` – Saved trained LSTM model
- `task3/outputs/` – Generated text samples

## About

Machine Learning Internship Tasks completed during the CodSoft Virtual Internship Program.