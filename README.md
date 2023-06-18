# Climate-Change-Tweet-Sentiment-Predictor-Project

The aim of this project is to label tweets into four categories: News, Pro (supporting climate change efforts), 
Neutral, and Anti (against climate change efforts). 

The dataset, the "Twitter Climate Change Sentiment Dataset," is a publicly available dataset on Kaggle. 
This dataset has been specifically curated to focus on tweets discussing climate change, global warming, and related topics. 
It comprises a total of over 40,000 tweets collected between April 27, 2015, and February 21, 2018.

There were many iterations to the creation of this project. The first model was a simple Naïve Bayes model, which 
achieved an accuracy of 0.66, providing a baseline for comparison with more sophisticated models. Then the Universal
Sentence Encoder (USE) was introduced to create more meaningful representations of the text. Undersampling was then introduced
to create an even number of samples for each category. Then weights were introduced to allow for the use of the entire dataset 
and better represent underrepresented classes to improve performance. After, to address overfitting, early stopping was 
introduced. For additional improvement in performance, the BERT tokenizer was introduced for fine-tuning. The BERT tokenizer 
was too slow for my hardware, so to speed up the training process, I switched over to DistilBERT (a lighter version of BERT).
Then after playing around with token sizes, the final model was able to produce the highest accuracy prediction of 0.78. 
