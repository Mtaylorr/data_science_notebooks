This repo contains my work that I did for the challenge [gender-based-violence-tweet-classification-challenge](https://zindi.africa/competitions/gender-based-violence-tweet-classification-challenge). 

The file data-augmentation-for-gbv.ipynb represents the code for the data augmentation that I used to ameliorate the data because it was unbalanced. In the contest I used only the first part which is the synonym substitution using nltk library because automl was forbidden , but I just wrote the code to see the difference between the two methods.

The best model that I produced is the simplest one , logistic regression with countVectorizer on the data which gave me almost 80% accuracy at the private testing data which helped me to rank 23/140 contestant. In fact , I tried many methods from classic machine learning like logistic regression , random forest to deep learning with embeddings and lstm and finally transformers using BERT Base Uncased model.
