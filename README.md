> ## **Topic Modelling using BERTopic Transformer Model**

**BERTopic is a topic modeling technique that leverages 🤗 transformers and a custom class-based TF-IDF to create dense clusters allowing for easily interpretable topics whilst keeping important words in the topic descriptions**

![image](https://user-images.githubusercontent.com/90597433/232711431-7feeb2d9-8e33-4eff-ba61-7d5ed9d7dd39.png)

**For More Details on Bertopic check following Links:**
- Visual Overview:  https://maartengr.github.io/BERTopic/algorithm/algorithm.html#visual-overview

- Research Paper : https://arxiv.org/abs/2203.05794

**NOTE**: BERTopic is stocastich which mmeans that the topics might differ across runs. This is mostly due to the stocastisch nature of UMAP.

> ## ✔**Dataset Information:**
**We use the popular scikit learn 20 Newsgroups dataset which contains roughly 18000 news articles.**

> ## ✔**Objective :** 
**Our objective is to perform topic modelling on this news collection and analyze central theme of data.**

> ## 🎨**Visualization of Topic Modelling**
There are different kind of **Interactive Visualization available under BERTTOPIC**. 
On this News Dataset I have performed following visualzation to get more insight.

```
 1. Inter Topic Distance Map
 2. Topic Probabilty Distribution
 3. Hierarchical Clustering of Top 50 Topics
 4. Topic Word Score
 5. Topic Similarity Score
 6. Term Score Decline Per Topic
 ```
 
***Note : As Visualation are Interactive in Nature they are not getting render properly in Github. To check Visualizaton you will need to open Notebook in Google colab. You can open Notebook Google Colab via click on `Open in Colab` in Notebook file and Check Visualization.***
 
