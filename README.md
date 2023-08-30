# LLM-review-sentiment
data source link: https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset       
This is a review santiment analysis project. In this project, we explore the best modeling way for building sentiment classifier. The LLM we use is RoBERTa.     

mask_language_model_fine_tune.ipynb:         
To fine tune mask language model on domain knowledge, in this project which is movie reviews.

classifier_roberta.ipynb:
Use two type of llm to test fro reviews from different movie categories,           
1)to train several classifiers by genre or                  
2)to train one classifier by all or       
3)combine 1&2 that is ensemble.
