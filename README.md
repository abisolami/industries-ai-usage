# AI Tool Adoption Across Industries

## Overview
An end-to-end data science project analysing the adoption of AI tools 
(ChatGPT, Claude, Midjourney, Bard, Stable Diffusion) across various 
industries and countries in 2023 and 2024.

## Dataset
- **Source**: [Kaggle — Global AI Content Impact Dataset](https://www.kaggle.com/datasets/mohanz123/global-ai-content-impact-dataset)
- **Size**: 145,000 rows, 9 features
- **Target Variable**: `adoption_rate` (0–100%)

## Project Structure
- Data Cleaning
- Exploratory Data Analysis & Visualization
- Feature Engineering
- Model Training & Evaluation

## Models Used
| Model             | MAE   | RMSE  | R²    |
|-------------------|-------|-------|-------|
| Linear Regression | 24.95 | 28.83 | 0.00  |
| Random Forest     | 25.62 | 29.96 | -0.08 |
| XGBoost           | 25.12 | 29.11 | -0.02 |

## Key Finding
The dataset was synthetically generated, meaning adoption rates have 
no real relationship with the available features. This was identified 
early through correlation analysis and uniform target distribution, 
and confirmed by model performance. All models performed near baseline, 
which was the expected outcome.

## Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, XGBoost

## Author
[Abisolami] — [https://github.com/abisolami]
