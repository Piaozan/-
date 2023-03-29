# 银行贷款违约风险预测

## 项目背景：
- 数据来源于Kaggle，要求选手依据客户的信用卡信息，分期付款信息，信用局信息等预测客户贷款是否会违约。
- kaggle : https://www.kaggle.com/competitions/home-credit-default-risk/overview

## 数据介绍：
- 本项目主要使用两个数据集，application_train & application_test （来自home_credit）
- 其中包含关于每个贷款申请的信息，每笔贷款都有自己的行，并有独立的SK_ID_CURR标识
- test数据带有target，0表示：贷款已偿还，1表示：贷款未偿还

## 补充数据集：
- 在两个训练集与测试集的数据基础上，增添了信用局信息与历史贷款信息的两个数据集
- 通过两个额外的数据集再进行预测 （来自bureau）
