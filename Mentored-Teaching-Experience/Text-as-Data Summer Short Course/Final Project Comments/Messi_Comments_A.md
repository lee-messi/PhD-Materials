
## Comments
+ Enjoyed reading the proposal very much. Detailed explanations of the data, pre-processing steps, models, and the analyses that you intend to use were very helpful for me to follow along. 

+ The purpose of the classifier that you are hoping to train, if I am reading correctly, seems to be to identify whether an article is about a violent event or not. This reminded me of a very popular [Kaggle competition](https://www.kaggle.com/competitions/nlp-getting-started) where Kagglers are expected to build a classifier that predicts whether a tweet is about an actual disaster or not. The input of the classifier is the tweet text (location information can be used as well), and the output of the classifier is 0/1 (1 for actual disaster). 

+ Although, I can't be certain that a classifier such as these (fine-tuning LLMs such as DeBERTa and RoBERTa, more DeBERTa these days) would work on your specific data set, I can imagine how LLMs, in general, would be more useful for you if you are hoping to build a text classifier. My only concern is the training data size. Many of these models take 5,000+ to achieve validation accuracy of 80%+, and it seems that the news article data set is smaller than that. 

+ Also, I can imagine how you could use fine-tuned models on hugging face that have already been trained on a larger collection of NER data sets. Here is an example of a [tutorial leveraging a pre-trained NER model on the Disaster Tweets compeition](https://www.kaggle.com/code/eneszvo/ner-named-entity-recognition-tutorial).

+ Fascinating project! Look forward to hearing more about it!