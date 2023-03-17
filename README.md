# kaggle-tabular-playground
Reusable codeset for kaggle's tabular playground series.

## Repository Structure

```text
.
├── .gitignore
├── config.yaml
├── data
│   ├── train_data.csv
│   └── test_data.csv
├── notebooks
│   └── exploratory_data_analysis.ipynb
├── src
│   ├── data.py
│   ├── ensemble.py
│   ├── evaluation.py
│   ├── hyperparameter_tuning.py
│   ├── inference.py
│   ├── main.py
│   └── models.py
└── README.md
```

## Files and Directories
**config.yaml:** 

This file will contain the configuration for your project, such as paths to data, model parameters, preprocessing options, and other settings.

**data.py:** 

This module will handle data loading, preprocessing, and splitting. It may include functions for handling missing data, feature creation, feature scaling, and outlier handling.

**models.py:** 

This module will define different ML models or algorithms. It may contain functions or classes for creating, training, and evaluating models based on the configuration settings.

**hyperparameter_tuning.py:** 

This module will include functions for hyperparameter tuning, such as GridSearchCV or RandomizedSearchCV, using cross-validation.

**ensemble.py:** 

This module will contain functions for creating and training ensemble models, such as stacking or voting, and for assigning weights to the models.

**evaluation.py:** 

This module will include functions for evaluating model performance, such as calculating accuracy, precision, recall, F1 score, or other relevant metrics for your specific problem.

**inference.py:** 

This module will handle test set inference, generating predictions for new data based on the trained models.

**main.py:** 

This script will bring all the components together, loading the config file, and orchestrating the process of data preprocessing, model training, evaluation, and inference.
