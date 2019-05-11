# **Social Networks Node Classification**

## 1. Project Description

For this project, we mainly focus on doing node classification on popular social media networks. There are three parts in realizing our goal.

First part is feature engineering. From common social network datasets, two kinds of features can be adopted, node feature and graph feature. For node feature, we will construct features based on node properties, like user 	information. For graph feature, adjacent matrix will be applied to represent graph structure, based on which more info like betweenness and centrality could be extracted.

The Second one is model selection. Basically, some traditional machine learning classification methods will be used to fit features collections in part one as our baselines. On the other hand, Graph Convolutional Networks will also be adopted as the deep learning solution.

In the last, the multiple models in part two will be tested and evaluated on several social media network datasets to compare the difference and find the characteristics of each model.

## 2. Notices

### 2.1 Dataset

* [**Stanford Large Network Dataset Collection**](https://snap.stanford.edu/data/)

### 2.2 Output

Expected output format should be

| Experiments Batch | Model | Params  | feature53 | feature54 | feature55 | accuracy |        Notes        |
| :---------------: | :---: | :-----: | :-------: | :-------: | :-------: | :------: | :-----------------: |
|     example 1     |  GCN  | lr=0.01 |    0.3    |    0.3    |    0.3    |   0.67   | use adjacent matrix |



## 3. Submission

* **Report LaTeX Template**: https://neurips.cc/Conferences/2019/PaperInformation/StyleFiles