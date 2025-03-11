# MachineLearning

In the process of learning machine learning, individuals summarize the relevant documentation and source code

<br>

## 1 Linear Regression

```bash
LinearRegressionCode/
├── LinearRegression/                  # Directory for linear regression modules
│   ├── MultivariateLinearRegression.py  # Multivariate linear regression
│   ├── Non-linearRegression.py         # Non-linear regression
│   ├── UnivariateLinearRegression.py   # Uni variate linear regression
│   ├── linear_regression.py            # Main script for linear regression
├── LinearRegressionTest/
│   ├── img # Folder containing Jupyter Notebook related files
│   ├── LinearRegressionWithSKLearn.ipynb 
│   # Detailed analysis of each step of linear regression, combined with multiple experiments
├── data1
├── util
```
<br>

## 2 ModelEvaluationMethod
```bash
ModelEvaluationMethod/
├── data1  # Datasets
├── img # Images related to Jupyter Notebooks
├── ModelEvaluationMethod.ipynb 
# Code related to model evaluation methods, learning sklearn
```
<br>

## 3 Logistic
```bash
LogisticRegressionCode/
│
├── data1/
│
├── logistic_regression/
│   ├── logistic_regression.py       # 实现逻辑回归算法
│   ├── logistic_regression_with_linear_boundary.py  # 带有线性边界的逻辑回归
│   └── NonLinearBoundary.py         # 非线性边界处理
│
└── util/
    ├── features/              # 特征处理相关的工具函数
    │   ├── __init__.py         # 初始化
    │   ├── generate_polynomials.py  # 生成多项式特征
    │   ├── generate_sinusoids.py    # 生成正弦波特征
    │   ├── normalize.py          # 数据归一化处理
    │   └── prepare_for_training.py  # 准备训练数据
    └── hypothesis/             # 假设相关的工具函数
        ├── __init__.py         # 初始化
        ├── sigmoid.py          # 实现sigmoid激活函数
        └── sigmoid_gradient.py  # 实现sigmoid梯度计算
```