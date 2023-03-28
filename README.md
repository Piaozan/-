# 银行贷款违约风险预测

## 项目背景：数据来源于Kaggle，要求选手依据客户的信用卡信息，分期付款信息，信用局信息等预测客户贷款是否会违约。
- kaggle : https://www.kaggle.com/competitions/home-credit-default-risk/overview

## 数据介绍：本项目主要使用两个数据包，application_train & application_test
- 其中包含关于每个贷款申请的信息，每笔贷款都有自己的行，并有独立的SK_ID_CURR标识
- test数据带有target，0表示：贷款已偿还，1表示：贷款未偿还
