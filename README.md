# Sentiment_Analysis_of_Restaurant_Reviews 😄🙁
Sentiment analysis is a vital topic in the field of NLP(natural language processing). Basically its a text classification tasks where you are supplied with a phrase, or a list of phrases and your classifier is supposed to tell if the sentiment behind that is positive, negative or neutral. 

- Used **Python** and **scikit-learn**
- Algorithm applied - **RANDOM FOREST CLASSIFER** as predictive model for predicting sentiment of restaurant reviews
- **Accuracy = 72.5% and Precision score = 0.9**
- Custom prediction output :

   ![image](https://user-images.githubusercontent.com/54211989/134009012-2a311691-e90f-4c27-82d1-672005e126a3.png)


Some terms related to NLP:
- **Tokenization:** involves splitting sentences and words from the body of the text.
![image](https://user-images.githubusercontent.com/54211989/135706793-95ae2f06-4d13-417d-bc20-3c6471812161.png)


- **Stemming:** is the process of removing a part of a word, or reducing a word to its stem or root.
      Stemming algorithm reduces the words “chocolates”, “chocolatey”, “choco” to the root word, “chocolate” 

![image](https://user-images.githubusercontent.com/54211989/133938019-30266df1-8f25-4572-b607-58cc6260311c.png)

Stemming algorithms are: 

Porter’s Stemmer algorithm: Example: EED -> EE means “if the word has at least one vowel and consonant plus EED ending, change the ending to EE” as ‘agreed’ becomes ‘agree’. 

- **Stopwords:** words in any language which does not add much meaning to a sentence. They can safely be ignored without sacrificing the meaning of the sentence. For some search engines, these are some of the most common, short function words, such as the, is, at, a, can, which, I and on.

![image](https://user-images.githubusercontent.com/54211989/134460508-cd75a832-263a-482e-9bfa-a3e938614913.png)

- **Confusion matrix, Accuracy, Recall and Precision score:**  https://medium.com/analytics-vidhya/confusion-matrix-accuracy-precision-recall-f1-score-ade299cf63cd (for refer.)
