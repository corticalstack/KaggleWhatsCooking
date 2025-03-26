# 🍳 What's Cooking? - Kaggle Recipe Cuisine Classification

A machine learning solution for the Kaggle "What's Cooking?" competition that predicts the cuisine of a recipe based on its ingredients.

## 📝 Description

This repository contains a Jupyter notebook solution for the Kaggle "What's Cooking?" competition. The challenge involves predicting the type of cuisine (e.g., Italian, Chinese, Mexican) based on the list of ingredients in a recipe. The solution uses natural language processing techniques and machine learning algorithms to classify recipes into their respective cuisines.

## ✨ Features

- 📊 **Exploratory Data Analysis** - Visualizes cuisine distribution and ingredient frequencies
- 🔍 **Ingredient Analysis** - Identifies the most common ingredients for different cuisines
- 📋 **Text Processing** - Transforms ingredient lists into a format suitable for machine learning
- 🧮 **Feature Engineering** - Uses TF-IDF vectorization to convert text data into numerical features
- 🤖 **Machine Learning Model** - Implements a Random Forest Classifier for cuisine prediction
- 📈 **Prediction & Submission** - Generates predictions and creates a submission file for Kaggle

## 🔧 Prerequisites

To run this notebook, you'll need:

- Python 3.x
- Jupyter Notebook or JupyterLab
- Required Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## 🚀 Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/corticalstack/KaggleWhatsCooking.git
   cd KaggleWhatsCooking
   ```

2. Download the competition data from Kaggle and place it in an `input` directory:
   - `train.json` - Training data with labeled cuisines
   - `test.json` - Test data for making predictions

3. Open and run the Jupyter notebook:
   ```bash
   jupyter notebook kernel.ipynb
   ```

4. The notebook will:
   - Load and analyze the data
   - Preprocess the ingredients
   - Train a Random Forest model
   - Generate predictions
   - Create a `submission.csv` file ready for Kaggle submission

## 📊 Model Performance

The Random Forest Classifier is used with TF-IDF vectorization of ingredients. The model evaluates performance using out-of-bag error estimation.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
