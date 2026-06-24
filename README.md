# ML Production Practice

A refactoring project that transforms statistical and machine learning analyses from exploratory Jupyter notebooks into production-grade Python code.
This repository demonstrates the full DS-to-MLE engineering transformation: taking existing data science work across machine learning, Bayesian statistics, regression analysis, and statistical inference, and rebuilding it with software engineering best practices — modular structure, type hints, docstrings, unit tests, CI/CD pipelines, and REST API serving.

What this shows:

* Refactoring notebook-style code into clean, modular Python packages
* Type-annotated functions with full docstrings
* pytest test suites covering data loading, model training, and prediction validation
* GitHub Actions CI pipeline running linting and tests on every push
* FastAPI serving endpoints exposing trained models as REST APIs
* Experiment tracking with Weights & Biases
* Configuration management separating code from parameters

**Topics covered**: Machine Learning · Bayesian Statistics · Regression Analysis · Statistical Inference · Multivariate Analysis · Time Series

**Stack**: Python · PyTorch · scikit-learn · FastAPI · pytest · GitHub Actions · W&B · ruff
