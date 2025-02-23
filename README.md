# Natural Language Processing with Disaster Tweets

## Overview
This repository contains a solution for the Kaggle competition **"Natural Language Processing with Disaster Tweets"**. The goal of the competition is to build a machine learning model that can distinguish between tweets that describe real disasters and those that do not.

## Dataset
The dataset consists of 10,000 tweets that have been manually classified. Each tweet is labeled as either a real disaster (`1`) or not (`0`). The dataset is provided by Kaggle and is originally sourced from Figure-Eight.

## Evaluation Metric
The model is evaluated using the **F1-score**, which is calculated as follows:

```math
F1 = \frac{2 \times \text{precision} \times \text{recall}}{\text{precision} + \text{recall}}
```

where:
- **Precision** = `TP / (TP + FP)`
- **Recall** = `TP / (TP + FN)`

## Installation
To run this project, install the necessary dependencies using:

```bash
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook to train and evaluate the model:

```bash
jupyter notebook NLP_with_Disaster_Tweets.ipynb
```

## Approach
The solution follows these key steps:
1. **Data Preprocessing**: Cleaning and tokenizing the text data.
2. **Feature Engineering**: Using techniques such as TF-IDF, word embeddings, or transformers.
3. **Model Training**: Applying machine learning models such as Logistic Regression, Random Forest, or deep learning approaches like LSTMs or BERT.
4. **Evaluation**: Measuring performance using F1-score.
5. **Prediction & Submission**: Generating predictions and formatting them for submission to Kaggle.

## Results
The model achieves an **F1-score of 80.81%** on the validation set.

## Contributing
Feel free to fork this repository and submit pull requests for improvements!

## License
This project is open-source and available under the **MIT License**.

