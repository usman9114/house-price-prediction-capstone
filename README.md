# House Price Prediction Capstone

IBM Advanced Data Science capstone notebook for house price prediction.

This early capstone is kept for education history. It covers exploratory data analysis, visualisation and predictive modelling in a Jupyter Notebook workflow.

## What the notebook does

```mermaid
flowchart LR
    A["Load data<br/>Spark DataFrame, 14 fields"] --> B["Check and explore<br/>completeness, statistics, EDA"]
    B --> C["Feature reduction<br/>RM, LSTAT, PTRATIO to predict MEDV"]
    C --> D["Train / test split"]
    D --> M1["Linear regression"]
    D --> M2["Decision tree"]
    D --> M3["Gradient-boosted trees"]
    D --> M4["Keras neural network<br/>tuned"]
    M1 --> E["Evaluate on test data<br/>R2, RMSE, MAPE"]
    M2 --> E
    M3 --> E
    M4 --> E
```

## How to use

Open the notebook in Jupyter and run the cells in order. Review the data preparation, visual analysis and modelling steps before drawing conclusions.

## Limitations

This is a capstone project, not a production pricing system. Results depend on the dataset, feature choices and modelling assumptions in the notebook.
