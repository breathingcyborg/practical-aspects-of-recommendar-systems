
# Practical aspects of recommendar systems (WIP)

There are lots of resources that explain how recommendar system works.
Most of them follow the same outline, at first they explain what content based
filtering, second they explain what colloborative filtering is, followed by
brief explaination about matrix factorization and few deep learning models.

But in general these resources don't clearly explain some practical aspects.

1. When most users are not logged in, is content similarity only option?
2. In case of new items, is content similarity only option?
3. What can be done when you don't have resources to train model online?
4. For deep learning based matrix factorization models do i have to retrain model
   when new user/item is added (because dimension of embedding layer has increased).
5. How do i know if the recommendar system is working?

This repo is currently work in progress, but in the end it will host series of notebooks that answers the questions mentioned above.

## Demo

[Word2vec for product recommendations](https://huggingface.co/spaces/breathingcyborg/word2vec-for-products)

## Notebooks

| Notebook | Colab Link | Description |
| :--- | :-- | :-- |
| Matrix Factorization | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/breathingcyborg/practical-aspects-of-recommendar-systems/blob/main/notebooks/morrisb_kaggle.ipynb) | Explore basics of recommendar systems using collobrative filtering and matrix factorization. |
| LightFM | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/breathingcyborg/practical-aspects-of-recommendar-systems/blob/main/notebooks/lightfm.ipynb) | Hybrid recommendar system that uses item metadata. Using variant of factorization machine |
| Product2Vec | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/breathingcyborg/practical-aspects-of-recommendar-systems/blob/main/notebooks/prod2vec.ipynb) | Adaption of word2vec for recommendar systems |
| Meta Product2Vec | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/breathingcyborg/practical-aspects-of-recommendar-systems/blob/main/notebooks/meta%20prod2vec.ipynb) | Like product2vec but can use metadata |

## Useful Resources

* [Maciej Kula Hybrid Recommendar](https://youtu.be/EgE0DUrYmo8)
* [Maciej Kula Neural Nets](https://youtu.be/ZkBQ6YA9E40)
* [Maciej Arciuch](https://youtu.be/muXTMnfPU0k)
* [Light FM](https://github.com/lyst/lightfm)
* [Spotlight](https://github.com/maciejkula/spotlight)
* [XGBoost](https://github.com/dmlc/xgboost)
* [Faiss](https://github.com/facebookresearch/faiss)
* [Airbnb Listing Embeddings](https://medium.com/airbnb-engineering/listing-embeddings-for-similar-listing-recommendations-and-real-time-personalization-in-search-601172f7603e)
* [Airbnb Experience Ranking](https://medium.com/airbnb-engineering/machine-learning-powered-search-ranking-of-airbnb-experiences-110b4b1a0789)
* [Airbnb Stays Ranking Models](https://medium.com/airbnb-engineering/improving-deep-learning-for-ranking-stays-at-airbnb-959097638bde)
* [Airbnb Stays Ranking Model Paper](https://arxiv.org/pdf/2002.05515.pdf)
