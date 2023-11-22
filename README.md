# deep-learning-challenge

Charitable Project Funding Prediction Model

Overview

This repository contains a binary classifier model aimed at predicting the funding success of charitable projects. The analysis involves thorough data preprocessing, model compilation, training, and an optimization strategy.

Contents

Code: Jupyter Notebook and Python script files.


Data: Raw and preprocessed datasets.


Model: Saved model files.


Process

Data Preprocessing:
Drop irrelevant columns (EIN, NAME).


Bin application types and classification counts.


Convert categorical data to numeric binaries.


Scale numerical data.


Model Compilation, Training, and Initial Evaluation:


Sequential model with input, hidden, and output layers.


Benchmark accuracy set at 75%.


Model Optimization:


Focus on binning the "NAME" column for enhanced patterns.


Outcome:


Initial accuracy: 72%.


Optimized accuracy: 78%.


Results

Initial Accuracy: 72%


Benchmark Accuracy: 75%


Optimized Accuracy: 78%


Optimization Strategy: Binning the "NAME" column.


How to Use

Ensure Python and necessary libraries are installed.


Run the Jupyter Notebook or Python script for model implementation.


Explore the preprocessed data and trained model for insights.
