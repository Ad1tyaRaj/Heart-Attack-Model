# Heart Attack Prediction Model

## Overview
This repository contains a machine learning project that predicts the likelihood of a heart attack based on a dataset of 170,501 rows and 25 features. The current model achieves an accuracy of **75%**, with ongoing improvements through feature engineering and scaling.

## Features
- **Dataset Size**: 170,501 rows and 25 columns.
- **Model Accuracy**: 75%.
- **Techniques Used**:
  - Feature Engineering: Enhancing feature selection and transformation.
  - Scaling: Standardizing feature values for better model performance.

## Objectives
1. Improve the model's accuracy and robustness.
2. Optimize feature selection and scaling techniques.
3. Provide a user-friendly interface and detailed documentation.

## Project Structure
```
HeartAttackPrediction/
│
├── data/                   # Dataset files
├── notebooks/              # Jupyter notebooks for data analysis and modeling
├── Heart_Attack_test1/     # Source code for data processing and model training
├── Heart_Attack_70/        # Saved trained models
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies
```

## Feature Engineering and Scaling
1. **Current Focus**:
   - Identifying redundant or irrelevant features.
   - Transforming features (e.g., normalization, log transformation).
   - Encoding categorical variables.
2. **Scaling**:
   - StandardScaler for numerical features.
   - RobustScaler to handle outliers.

## Future Goals
- Improve accuracy to 90% or higher.
- Experiment with ensemble methods (e.g., Random Forest, Gradient Boosting).
- Deploy the model using a web app (e.g., Flask, FastAPI).
- Conduct hyperparameter tuning for further optimization.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/HeartAttackPrediction.git
   cd HeartAttackPrediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model:
   ```bash
   python src/train_model.py
   ```

## Usage
1. Add your dataset to the `data/` directory.
2. Use the provided Jupyter notebooks for data analysis and feature engineering.
3. Train the model with the command above or customize the pipeline as needed.

## Acknowledgments
- **Dataset Source**: [Include dataset link/source if applicable].
- **Contributions**: Feel free to contribute via pull requests or open issues for feedback and suggestions.

## License
This project is licensed under the [MIT License](LICENSE).
