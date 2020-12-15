# Sentiment analysis and Topic Modeling of Amazon Alexa Reviews
Using Amazon Alex reviews from Kaggle:
https://www.kaggle.com/sid321axn/amazon-alexa-reviews

In recent times there has been a rise of smart home devices - these devices anticipate user input, responds, and can automate control of home amenities. Companies such as Amazon and Google have come out with such devices, there are numerous models of Amazon's Echo devices and Google's Nest Hub devices so determining which one is best is surely a difficult choice.

![test4](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/Distribution_EchoRatings.png)
The Echo, Echo Dot, and Echo Show are most popular according to rating
 
LDA Topic Modeling revealed three topics for the Echo: Ease of use, users expressing that they love that the Echo plays music, and sound quality.
LDA Topic Modeling revealed three topics for the Echo Dot: Works great, speaker, and music.
LDA Topic Modeling revealed three topics for the Echo Show: Love the videos, like it!, and love the screen

Vader sentiment analysis revealed negative and positive sentiment scores

![test](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/top3_positive_sent.png)
![test1](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/top3_negative_sent.png)

Looking at the three variations of Amazon Echo models, the average positive sentiment rating of the reviews is 10 times higher than the negative, suggesting that the calculated sentiment rating scores are reliable.

Lastly, using a Count Vectorizer (TFIDF), I looked at the words that contributed to positive and negative sentiments.
Here are results for the Echo Dot

![test2](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/echodot_positive.jpg)
![test3](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/echodot_neg.jpg)

For the Echo Dot, we can see for some users it is a great device and easy to use, and for other users, the Echo Dot did not play music and did not like that you needed prime.

For the Echo:
![test8](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/echo_positive.jpg)
![test7](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/echo_neg.jpg)

From these graphs we can see that for some users, they thought that the Echo worked awesome and provided helpful responses, while for others, the Echo device hardly worked and had too many features.

For the Echo Show:
![test9](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/echoshow_positive.jpg)
![test10](https://github.com/mkosaka1/amazonalexa_nlp/blob/master/Photos/echoshow_neg.jpg)

From these graphs, users enjoy that they are able to make calls, use youtube and the Echo Show is fairly easy to use, while for other users, the Echo Show is “dumb” and recommend not to buy this device.

Analyzing Amazon Alexa devices by model is nsightful than examining all devices as a whole, as this does not tell us areas that need improvement for which devices and what attributes users enjoy the most.
