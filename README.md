# House Price Prediction on Indian Dataset

This project aims to predict house prices based on a dataset from India using various regression algorithms. The project explores different machine learning models to find the best predictor for house prices. This repository contains the code, data exploration, model implementation, and evaluation.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Models Used](#models-used)
- [Evaluation](#evaluation)
- [Results](#results)

## Introduction

The goal of this project is to develop a model that can accurately predict house prices based on various features such as square footage, location, and other relevant factors. The project utilizes multiple regression techniques to determine the most effective model for this task.

## Dataset

The dataset used in this project is specific to the Indian housing market. It includes various features such as:

- `SQUARE_FT`: The square footage of the house.
- `LATITUDE AND LONGITITUDE`: The latitude and longitute of the location
- `TARGET(PRICE_IN_LACS)`: The target variable representing the price of the house in lacs.
- Other relevant features that influence house prices.

## Project Structure

The project is organized as follows:

- `course-project.ipynb`: Jupyter Notebook containing the entire project code, including data exploration, visualization, model training, and evaluation I did an interesting feature engineering which helped the model a lot.
- `README.md`: This file, which provides an overview of the project.

## Installation

To run the notebook, you need to have Python installed along with the necessary libraries. Follow the steps below to set up your environment:
Download the data both Train and Test csv files

## Models Used

Used all standard Regression models out of them I got good results for XGBoost algo then after using GridSearchCV technique i pick the best hyperparameters for XGBoost model now my results got little better than earlier.

## Evaluation

RMS is used

## Results

Without proper Featurte Engineering XGBoost got aroung 0.75 as RMS value but with Proper Feature Engineering(Handling Lattitude and Longitiude)XGBoost got around 0.927 after tuning it became 0.934



