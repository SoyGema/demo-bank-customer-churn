# VS Code Livestream

## Agenda

- Intro: 
  - Example ML problem
  - DVC: data versioning, reproducible pipelines, and experiment tracking
- DVC extension for VS Code:
  - Alternative to CLI
  - ML experimentation workflow into your IDE 
  - Interactive plots and tables for analyzing ML experiments

## Target Audience

1. Train ML models
2. Deploy ML models
3. Learn ML

### Example ML problem
![](https://miro.medium.com/max/456/1*Dvx1j18vyKyvLlIpxzVSmQ.png)

*image source: https://medium.com/@islamhasabo/predicting-customer-churn-bc76f7760377*

Data source:
https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers

Dataset
| RowNumber | CustomerId | Surname  | CreditScore | Geography | Gender | Age | Tenure | Balance   | NumOfProducts | HasCrCard | IsActiveMember | EstimatedSalary | Exited |
|-----------|------------|----------|-------------|-----------|--------|-----|--------|-----------|---------------|-----------|----------------|-----------------|--------|
| 1         | 15634602   | Hargrave | 619         | France    | Female | 42  | 2      | 0         | 1             | 1         | 1              | 101348.88       | 1      |
| 2         | 15647311   | Hill     | 608         | Spain     | Female | 41  | 1      | 83807.86  | 1             | 0         | 1              | 112542.58       | 0      |
| 3         | 15619304   | Onio     | 502         | France    | Female | 42  | 8      | 159660.8  | 3             | 1         | 0              | 113931.57       | 1      |
| 4         | 15701354   | Boni     | 699         | France    | Female | 39  | 1      | 0         | 2             | 0         | 0              | 93826.63        | 0      |
---

### DVC

![](https://miro.medium.com/max/700/1*gN7Xru3A-PTavPI6adpJPQ.png)

- **Experiment tracking**: Record training data, parameters, and metrics on top of Git. Navigate your experiments, compare their results, and find the best ML models.


- **Visualization**: Plot performance data in a customizable dashboard including one or more overlaid experiments.


- **Live tracking**: Capture and see metrics changing in real time.


- **Reproducibility**: Make sure that anyone can recover or confirm previous experiments, and run new experiments based on their results.


- **Data Management**: Handle and version large datasets, files, and models effectively right from VS Code.