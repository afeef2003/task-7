# Advanced Stock Price Prediction by Syeda Shamama Afeef

This project provides a simple implementation for predicting the next day's closing price of Amazon (AMZN) stock using historical data and machine learning models. It utilizes data either downloaded from Yahoo Finance via `yfinance` or uploaded manually, and applies models like Linear Regression and Random Forest Regressor to perform the prediction.

## 📑 Table of Contents

- Introduction
- Installation
- Usage
- Features
- Dependencies
- Configuration
- Examples
- Troubleshooting
- Contributors
- License

## 📘 Introduction

The project demonstrates the full pipeline of a stock price prediction task:
- Downloading or uploading stock data.
- Engineering relevant features.
- Training machine learning models.
- Evaluating performance using common metrics.

It is implemented in a Jupyter Notebook and is Colab-compatible.

## 🛠 Installation

Run the following command to install required packages:


## 🚀 Usage

1. Clone or open the notebook:

   You can run it directly on Colab using the badge below:

   [Open In Colab](https://colab.research.google.com/github/afeef2003/task-7/blob/main/task_07.ipynb)

2. Data Input Options:
   - Download from Yahoo Finance (code commented out by default)
   - Upload CSV manually using Colab's file uploader
   - Load from Google Drive (if enabled)

3. Train Models:
   - Random Forest
   - Linear Regression

4. Evaluate Performance:
   - MSE (Mean Squared Error)
   - R² Score

## ✨ Features

- Support for multiple data sources
- Basic feature engineering
- Train/test split with scikit-learn
- Side-by-side model comparison

## 📦 Dependencies

- yfinance
- pandas
- numpy
- matplotlib
- scikit-learn

## ⚙️ Configuration

No custom configuration is needed. You may replace the dataset file if using manual uploads or drive access.

## 📊 Examples

Example Prediction Output:


Visualization:

- Line chart comparing true vs predicted values for both models

## 🧯 Troubleshooting

- Ensure your CSV matches expected Yahoo Finance columns: Open, High, Low, Close, Volume
- If using Google Drive, make sure to mount it properly before reading the file

## 👥 Contributors

- @afeef2003 (https://github.com/afeef2003)

## 📄 License

This project is intended for educational purposes. No official license is defined in the notebook—please clarify if needed.
