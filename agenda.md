# VS Code Livestream

## Agenda



- Intro: 
  - Example ML problem
  - DVC: data versioning, reproducible pipelines, and experiment tracking
- DVC extension for VS Code:
  - Alternative to CLI
  - ML experimentation workflow into your IDE 
  - Interactive plots and tables for analyzing ML experiments
  

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

- Data Versioning
![](https://camo.githubusercontent.com/2e9f36da0d68a35ad70d4f7973471d1166b5c061792105efae3b914a41ced695/68747470733a2f2f6476632e6f72672f696d672f666c6f772e676966)
*image source: https://github.com/iterative/dvc*

- ML pipelines
![](https://martinfowler.com/articles/cd4ml/ml-pipeline-1.png)
*image source: https://martinfowler.com/articles/cd4ml.html*

- Experiment Tracking
![](https://dvc.org/img/graph.png)
