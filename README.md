# Twitter-tweet-analysis

Twitter is one of the platforms widely used by people to express their opinions and showcase sentiments on various occasions. Sentiment analysis is an approach to analyze data and retrieve sentiment that it embodies.

Classify the user’s perspective via tweets into positive(non-racist) and negative (racist) by building supervised learning models using Python and NLTK library.

## Pre-processing:

Tokenization : used to describe the process of converting the normal text strings into a list of tokens.

Stemming : Reducing inflected (or sometimes derived) words to their stem, base or root form — generally a written word form.

Transformation : Adding the tidy tweets back to our main (merge) data frame.

### Extracting Features from Cleaned Tweets:

-- Bag-of-words

-- TF-IDF

-- Word2vec 

![image](https://user-images.githubusercontent.com/97394464/215276108-8cbd39b3-98e4-4d10-aec9-6134d4bfb52d.png)

## Classification and Evaluation:

### Logistic Regression:

Bag-of-Words Features -> F1_Score: 0.5307820299500832

TF-IDF Features -> F1_Score: 0.5446507515473032

Word2Vec Features -> F1_Score: 0.6214022140221402

![image](https://user-images.githubusercontent.com/97394464/215275810-95ed8b7a-ee89-47e9-8e6a-283d114752d4.png)

Doc2Vec Features -> F1_Score: 0.3802938634399308

### Naive Bayes

Bag-of-Words Features -> F1_Score: 0.5078534031413612

TF-IDF Features -> F1_Score: 0.5078534031413612

Word2Vec Features -> F1_Score: 0.4453781512605042

![image](https://user-images.githubusercontent.com/97394464/215275932-a6d7264e-1d40-44a7-a55a-6b946852b8a5.png)

Doc2Vec Features -> F1_Score: 0.3074018126888217

### Support Vector Machine

Bag-of-Words Features -> F1_Score: 0.5092592592592592

TF-IDF Features -> F1_Score: 0.5104831358249772

Word2Vec Features -> F1_Score: 0.6105100463678517

![image](https://user-images.githubusercontent.com/97394464/215276022-c9405011-97a3-4b54-abf2-65a3dc388558.png)

Doc2Vec Features -> F1_Score: 0.24944812362030905


## Result:

Comparing the three models , Support Vector Machine(SVM) works much better and gives better accuracy than the other two.








