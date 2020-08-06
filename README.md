# Fake-News-Classifier

## **Problem:**

In this repository, I tried to address the Fake news problem. Fake News in the United States became a global subject and was widely introduced to billions as a prominent issue, especially due to the 2016 U.S. presidential election. Numerous political commentators and journalists wrote and stated in media that 2016 was the year of fake news and as a result, nothing will ever be the same in politics and cybersecurity.


## **Approach:**

I downloaded the dataset from Kaggle. I tried to classify the news with the help of the Tensorflow and nltk libraries in python. I Performed the following steps:

* Converted the news to OneHot representation
* Stemmed the words in the news text
* Converted the OneHot representation of news to word embedding representation
* Developed a neural network model with word embedding, LSTM, and output layers
* Classified the news with the help of neural network model

## **Result**

With the help of the above approach, the model successfully classified the news with 90.77% accuracy 


Hyperparameter tuning and other approaches can increase the model's accuracy and then it can be deployed. I think this model will pepole to identify between fake and real news. With this model follwing fake news issue could ahve been prevented:

* Nancy Pelosi diverting Social Security money for the impeachment inquiry
* Ilhan Omar Holding Secret Fundraisers With Islamic Groups Tied to Terror
* NYC coroner who declared the death of Jeffrey Epstein a suicide made half a million dollars a year working for the Clinton Foundation until 2015
