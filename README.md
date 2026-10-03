# 🎮 Video Game User Rating Prediction

## Project Overview

This project uses supervised machine learning to predict video game user ratings based on characteristics such as price, game length, platform, genre, and other game features.

The project demonstrates a complete machine learning workflow using Python, including data exploration, preprocessing, model training, evaluation, and interpretation.

## Dataset

The dataset contains **47,774 video game records** and **18 features**.

The features include:

- Game Title
- User Rating
- Price
- Platform
- Genre
- Developer
- Publisher
- Release Year
- Game Length
- Graphics Quality
- Soundtrack Quality
- Story Quality
- Multiplayer
- Game Mode
- Minimum Number of Players
- And other game characteristics

## Objective

The goal of this project was to determine whether video game characteristics could be used to predict User Rating.

### Main Question

**Can supervised machine learning predict video game user ratings based on game characteristics?**

## Machine Learning Workflow

1. Data loading
2. Data exploration
3. Missing-value analysis
4. Data type inspection
5. Feature analysis
6. Train/test splitting
7. Data preprocessing
8. Linear Regression
9. Random Forest Regression
10. Feature importance analysis
11. Residual analysis
12. Cross-validation
13. Model comparison

## Models

### Linear Regression

Linear Regression was used as the baseline model.

**Results:**

- MAE: **1.001**
- RMSE: **1.158**
- R²: **0.977**

### Random Forest Regression

Random Forest was tested to determine whether a more complex model could improve prediction performance.

**Results:**

- MAE: **1.033**
- RMSE: **1.212**
- R²: **0.975**

## Model Comparison

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 1.001 | 1.158 | 0.977 |
| Random Forest | 1.033 | 1.212 | 0.975 |

Five-fold cross-validation produced a mean R² of **0.9764** with a standard deviation of approximately **0.00026**.

## Key Findings

Price and Game Length were the strongest predictors of User Rating.

A simplified model using only **Price** and **Game Length** achieved an R² of approximately **0.977**, nearly matching the full model.

The calculated rating based on Price and Game Length also had a correlation of approximately **0.988** with the actual User Rating.

## Limitations

The unusually strong relationship between Price, Game Length, and User Rating suggests that the dataset contains a highly structured relationship.

The analysis may be consistent with synthetic data generation, although this cannot be confirmed from the analysis alone.

The relationships identified in this project are associations within the dataset and should not be interpreted as evidence that changing a game's price or length would directly cause its rating to change.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Kaggle
- GitHub
- Jupyter Notebook

## Project Files

**`video-game-rating-prediction.ipynb`** contains the complete analysis, visualizations, machine learning models, evaluation metrics, and conclusions.

## Author

**Isaac Hocker**

Data Science Student
