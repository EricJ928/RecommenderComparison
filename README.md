# Recommendation Systems

In this repository, I have recreate a project of comparing 3 recommendation systems:

1. Multi-class classification.
2. Collabrative filtering.
3. Deep matrix factorization.

This project was originally my final project for the Numerical Method course (a PhD course in NTU). I have modified it, changed the source data to an open-source data from [Kaggle](https://www.kaggle.com/datasets/mrmorj/insurance-recommendation?select=Train.csv), and rearange the code.

For more detail, check RecommenderComparison.ipynb

The deep-learning matrix factorization model is based on the deep matrix factorization similar to the Xue paper (ref. below). The idea is similar to collaborative filtering but with deep neural networks. The advantage of this model is that there is no need to know any personal information and product features. Based on user activities (e.g., view/purchase records), the model is able to make a good recommender system. In addition, it's a transferable model that allows us to use pretrained model and parameters to get a good prediction.

- Xue, Hong-Jian, et al. - ["Deep matrix factorization models for recommender systems." IJCAI. Vol. 17. 2017.](https://doi.org/10.24963/ijcai.2017/447)