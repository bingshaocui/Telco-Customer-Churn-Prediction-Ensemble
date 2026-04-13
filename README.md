# Telco-Customer-Churn-Prediction-Ensemble

5-model stacking ensemble (LGB+XGB+Cat+RF+MLP) for telco customer churn prediction. CV AUC: 0.91645.

## 项目简介
使用5个模型（LightGBM、XGBoost、CatBoost、RandomForest、MLP）进行堆叠集成，预测电信客户流失。

## 模型效果
- CV AUC: **0.91645**
- 特征工程 + 目标编码 + 阈值优化

## 文件说明
- `5-stack-ensemble.ipynb` - 完整训练和预测代码

## 数据集
来源：[Telco Customer Churn on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 运行环境
- Python 3.x
- 依赖：pandas, numpy, scikit-learn, lightgbm, xgboost, catboost, tensorflow

## 使用方法
1. 克隆仓库
2. 下载数据集放到指定目录
3. 运行 `5-stack-ensemble.ipynb`

## 许可证
MIT
