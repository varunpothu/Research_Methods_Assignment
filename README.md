# Research_Methods_Assignment
# Sentiment Analysis of Diversity, Equity, and Inclusion (DEI) Articles Using Fine-Tuned BERT

## Project Overview

This project focuses on developing a text classification model to analyze and predict the sentiment of articles related to Diversity, Equity, and Inclusion (DEI). By fine-tuning a BERT model, our goal is to enhance its ability to understand and categorize sentiments in DEI contexts. This can help organizations and researchers gain better insights into public attitudes and discourse on DEI issues.

## Problem Statement

Accurate sentiment analysis of DEI-related articles is essential for understanding public sentiment and discourse. This project aims to develop a robust machine learning model that predicts the sentiment of DEI articles based on their content and associated DEI topics. Fine-tuning a BERT model on a DEI-specific dataset is expected to improve automated sentiment analysis.

## Dataset

The dataset used in this project comprises DEI-related articles with the following columns:
- **Title**: The title of the article.
- **Content**: The full text of the article.
- **URL**: Link to the article.
- **Sentiment Label**: The sentiment expressed in the article (e.g., positive, negative, neutral).
- **Basis**: The DEI topic categorized into four types:
  - Gender
  - Race
  - Disability
  - Other

**Dataset Link**: [Diversity Dataset on Hugging Face](https://huggingface.co/datasets/deancgarcia/Diversity)

## Project Workflow

1. **Importing Libraries**: Install and import necessary Python libraries for data processing, model training, and evaluation.
2. **Data Loading**: Load the dataset using Hugging Face’s datasets library.
3. **Data Investigation**: Perform descriptive statistics and visualizations to understand sentiment distribution and content length relationships.
4. **Data Cleaning and Preprocessing**: Drop unnecessary columns and split the dataset into training, validation, and test sets.
5. **Exploratory Data Analysis (EDA)**: Analyze data with visualizations of sentiment distribution, content length, and DEI topic distribution.
6. **Text Tokenization**: Use the BERT tokenizer to prepare the text data for input into the BERT model.
7. **Model Training and Evaluation**: Fine-tune the BERT model using two different strategies:
   - **Strategy 1**: Learning Rate = 3e-5, Epochs = 25
   - **Strategy 2**: Learning Rate = 2e-5, Epochs = 25
   Evaluate the models on the test set and generate detailed classification reports.
8. **Predictions**: Make predictions on sample texts using the fine-tuned models and provide detailed explanations.

## Results

The BERT model was fine-tuned using two different strategies, and their performances were compared. Detailed classification reports and accuracy scores were analyzed to assess the effectiveness of each fine-tuning strategy.

## Files in the Repository

- **R_M__Assignment_3.ipynb**: The main notebook containing code for data loading, model training, and predictions.
- **README.md**: This file, providing an overview of the project.

## How to Run the Project

1. **Clone the repository**:
    ```bash
    git clone [https://github.com/varunpothu/Research_Methods_Assignment]
    ```
2. **Open the Jupyter notebook** `R_M__Assignment_3.ipynb` and run the cells to execute the project steps.

## Acknowledgments

- **Hugging Face**: For providing the dataset and tools to work with transformer models.

## License

This project is licensed under the MIT License. See the [LICENSE](https://huggingface.co/datasets/deancgarcia/Diversity#licensing-information) file for details.
