# Fashion Mnist Project Structure

fashion-mnist/
├── data/
│   └── fashion/
│       ├── [training data .gz files]
│       └── [test data .gz files]
├── artifacts/
│   ├── model_comparison/
│   ├── models/
│   │   └── xgboost/
│   └── parameters/
│       └── xgboost/
├── config/
│   ├── configs.py
│   └── __init__.py
├── notebooks/
│   ├── 01-notebook.ipynb
│   ├── train.py
│   ├── predict.py
│   ├── evaluate.py
│   ├── tuning.py
│   └── compare_models.py
└── utils/
    ├── __init__.py
    ├── mnist_reader.py
    └── utility.py
