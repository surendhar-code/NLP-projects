# NLP-projects

## 1. IMDB Movie Reviews Sentiment Analysis
Dataset link : https://drive.google.com/file/d/1sD_cMYr18gJZzthVfDnClSmhJmSVCYcs/view?usp=sharing <br>
Notebook link : https://colab.research.google.com/drive/19i2pnIMRSK-Ie6_hzGzONoaQsaZDt0sW?usp=sharing

## 2. SMS Spam detection
Dataset link:https://github.com/surendhar-code/NLP-projects/blob/main/SMS%20spam%20detection/spam.csv <br>
Notebook link:https://github.com/surendhar-code/NLP-projects/blob/main/SMS%20spam%20detection/SMS_Spam_Detection_1_Text_pre_processing.ipynb <br><br>
About Dataset:<br>
1. This dataset is taken from kaggle platform.

2. The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. 
3. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.
4. The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

5. This corpus has been collected from free or free for research sources at the Internet.

Text pre-processing<br>
1.For text pre processing NLTK library.<br>

Model Development<br>
1.I created multiple models and found the accuracy of each model.<br>
2.Multinomial Naive Bayes model gave best accuracy of 0.9739910313901345.<br>

Model efficiency:<br>
1.Our model correctly detected the five top spam texts for 2012 revealed in AdaptiveMobile’s Ongoing Threat Analysis as spam message.<br>
2.This proves that our model is very efficient.
## 3. Fake News Detection Classifier
Dataset link : True.csv - https://drive.google.com/file/d/1LAVPYqtb81Unnbbk2VJ5Jg-RxfeYn7vL/view?usp=sharing<br>
               fake.csv - https://drive.google.com/file/d/1J8WHwY1tHor_X5S98ya5E3ix08WXdXeC/view?usp=sharing<br>
Notebook link : https://github.com/surendhar-code/NLP-projects/tree/main/Fake%20News<br>
About Dataset<br>
1.The dataset was taken from the kaggle platform<br>
2.There are two datasets involved in this problem.<br>
    -> Fake.csv file - This dataset contains a list of articles considered as "fake" news<br>
    -> True.csv file - This dataset contains a list of articles considered as "True" news<br>
3.Label '1' denotes - The news is fake.<br>
4.Label '0' denotes - The news is real.<br>

Text pre-processing<br>
1.For text pre processing NLTK library.<br>

Model Development<br>
1.I created multiple models and found the accuracy of each model.<br>
2.Since Multinomial Naive Bayes and AdaboostClassifier using bag of Words almost gives same accuracy of 0.9567 <br>
3. So I choose Multinomial Naive Bayes model for this usecase<br>

Model Efficiency:<br>
1.Though our model gave good accuracy,it misclassifies some of the real world data.<br>

2.This can be improved by getting large datasets containing all types of news.





