# Sentiment analysis and Topic Modeling of Amazon Alexa Reviews
Using Amazon Alex reviews from Kaggle:
https://www.kaggle.com/sid321axn/amazon-alexa-reviews

In recent times there has been a rise of smart home devices - these devices anticipate user input, responds, and can automate control of home amenities. Companies such as Amazon and Google have come out with such devices, there are numerous models of Amazon's Echo devices and Google's Nest Hub devices so determining which one is best is surely a difficult choice.
 
LDA Topic Modeling revealed three topics: Ease of use, users expressing how much they love the product, and sound quality.

Vader sentiment analysis revealed negative and positive sentiment scores

![test](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/positive_sentiment.jpg)
![test1](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/negative_sentiment.jpg?raw=true)

Looking at the different variations of Amazon Echo models, the average positive sentiment rating of the reviews is 10 times higher than the negative, suggesting that the calculated sentiment rating scores are reliable.

Lastly, using a Count Vectorizer (TFIDF), I looked at the words that contributed to positive and negative sentiments.

![test2](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/alexa_neg.jpg)
![test3](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/alexa_positive.jpg)

From these graphs we can see that for some users, they thought that the Echo was not worth the money and did not like the sound quality. For other users, they thought that the Echo was easy to use and worked well. NLP projects such as these are helpful for Amazon as it can look into the feedback of their users and understand which areas need improvement. Next steps include separating the variations of Echo models to see how the positive and negative feedback differ and which model is the best.
