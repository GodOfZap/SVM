
# Chess Outcome Prediction Using SVM

This project uses Support Vector Machines (SVM) to predict the outcome (Win, Loss, Draw) of chess games for specific players based on historical game data.

## Features
- Parses PGN files to extract game info
- Engineers features like opening performance, rivalry stats, ELO difference, game length, and recent form
- Uses 80/20 train-test split
- Applies SVM with hyperparameter tuning (Grid Search and Bayesian Optimization)
- Compares kernels (Linear vs. RBF)
- Visualizes decision boundaries and performance metrics
- Incorporates advanced models like XGBoost

## Requirements
- Python 3.9+
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, python-chess, scikit-optimize, xgboost

## Installation
```bash
pip install pandas numpy scikit-learn matplotlib seaborn python-chess scikit-optimize xgboost
```
## Usage
- Load your PGN files at specified paths
- Run the cells sequentially to train and evaluate models
- Visualize results and decision boundaries

## Note
- Ensure your PGN files contain valid game data for the players of interest.
