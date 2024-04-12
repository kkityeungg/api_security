# Detection of API Access behavior anomaly

## Dataset
The dataset for this project is from [Kaggle](https://www.kaggle.com/datasets/tangodelta/api-access-behaviour-anomaly-dataset/data?select=remaining_call_graphs.json) (Licensed under GPL-2).

Distributed micro-services applications are commonly accessed through APIs, which can be targeted by attackers exploiting exposed business logic. User and attacker API access patterns differ, with numerous APIs often called in varying orders due to factors like browser or session refreshes. Analyzing long-term API call patterns reveals attack anomalies, but traditional numerical methods don't suit this data. To address this, we offer datasets featuring user access behaviors as numerical features and raw API call graphs. Additionally, two notebooks on classification, node embeddings, and clustering support dataset use.

## Objectives
> **To build Machine Learning model will be able to detech anomalities based on the behaviour of the API Access**

1. To perform exploratory data analysis of the both datasets
2. To create more new features to help the predictive model
3. To develop a supervised model to classify behaviour
