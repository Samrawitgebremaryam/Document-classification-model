# Document Classification Model

## Overview

The **Document Classification Model** is designed to categorize textual documents into predefined categories using supervised learning techniques. This project leverages the 20 Newsgroups dataset, a widely recognized collection for text classification tasks, to train and evaluate various classification models.

## Features

- **Data Preprocessing:** Cleans and prepares raw text data by removing stop words, special characters, and performing lemmatization.
- **TF-IDF Vectorization:** Transforms text data into numerical vectors, capturing the importance of terms within documents.
- **Model Training:** Trains multiple classification models, including Naive Bayes, Logistic Regression, and Support Vector Machines (SVM).
- **Performance Evaluation:** Assesses model performance using accuracy scores and detailed classification reports.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Performance Evaluation](#performance-evaluation)

## Requirements

This project requires the following Python libraries:

- `numpy`
- `pandas`
- `scikit-learn`

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Samrawitgebremaryam/Document-classification-model.git
2. **Jupiter run**

   Navigate to the Project Directory:

bash
Copy
Edit
cd document-classification-model
Set Up a Virtual Environment:

bash
Copy
Edit
python -m venv venv
Activate the Virtual Environment:

Windows:

bash
Copy
Edit
venv\Scripts\activate
macOS/Linux:

bash
Copy
Edit
source venv/bin/activate

Model Training
The project includes scripts to train the following models:

Naive Bayes Classifier: A probabilistic model based on Bayes' theorem, commonly used for text classification tasks.
Logistic Regression: A linear model for binary classification that can also handle multiclass problems.
Support Vector Machine (SVM): A powerful classifier that works well for high-dimensional spaces, such as text data.


Each model is trained on the 20 Newsgroups dataset, and their performance is evaluated using accuracy scores and detailed classification reports.

Performance Evaluation
After training, the models are evaluated on the test set using the following metrics:

Accuracy: The proportion of correctly classified documents out of the total documents.
Classification Report: Provides precision, recall, and F1-score for each class, offering a detailed view of the model's performance across different categories.
These metrics are crucial for understanding how well each model performs and where improvements might be needed.
