# SpamDetection-NLP
Spam detection using Enron Meetings data
Read all the data from train folder into a dataframe
Extracted the content(body) of the email.
Classified the email as spam or ham using a list of spam words. Due to shortage of time I classified the email as spam if any word from the spam list is found in the email. This can be improved by checking the frequency of spam words in an email and many other approaches.
Applied Naive Baiyes Classifier for classification. Other Classifiers can also be used like SVM for experimentation.
