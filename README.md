# Masters Dissertation- Twitter sentiment analysis uising BERT

Masters Dissertation solution for MSc Data Science. This solution is a Python based deep learning algorithms.


**Data Description**

Twitter is a social networking and real-time microblogging service. Messages posted by Twitter users are called tweets and restricted to a length of 140 characters. Usually, tweets can be considered informal to contain colloquial language, emoticons, and numerous spelling errors. Another characteristic of Twitter is the use of hashtags to refer to specific topics.

The first dataset was created by CrowdFlower  but filtered a lot by Chanran Kim . The dataset was named "apple-twitter-sentiment-texts.csv", and it was about the tweets post by different people about apple products on Twitter. 

The second dataset used in this study was obtained from the Kaggle website and was created by William Jiang .  The dataset is named "Big Tech Companies - Tweet Sentiment.csv" and reviews ten major tech companies. The author of the data has created two different datasets of tweets fetched from two different time frames. The first dataset contains tweets brought from 20-09- 2020 till 13-10-2020 and has about 266 thousand rows. The second dataset includes tweets that were fetched from 12-07-2020 till 19-09-2020 and contains approximately 860 thousand rows. For this research, the smaller dataset, which includes 266 thousand rows, was used.  
Reviews related to the tech companies were collected from Twitter. The hashtag method was used in retrieving the tweets. Hashtags used to convey the tweets were:  Apple, Microsoft, Nvidia, Google, YouTube, Netflix, Amazon, Twitch, AMD, and Tesla. Each row represents a tweet about these companies.




**Abstract** 

Online social networks have developed as new platforms that allow people to share their views and perspectives on different issues and subjects with their friends, family, and other users. Companies have started to analyse reviews and post on social media (related to their products) to get a sentiment for their product (becky, 2021).
Sentiment analysis is a form of Natural Language Processing that identifies and quantifies text data, emotional states, and personal information of the topics. Applying machine learning algorithms used to be more common. Nowadays, Deep Learning methods achieve better accuracy on most NLP tasks than other methods. 

**Research objectives and question** 

The main objective of this thesis is to design and develop a pre-trained deep learning algorithm on two different datasets that can classify people's opinions and sentiments based on the textual information they post on social media.

**Objectives:** 
• To prepare Twitter to review text data for classification by applying preprocessing methods. 
• To convert the text and aspects terms into tokens by the corresponding tokeniser.
• To use a pre-trained embedding in a deep learning algorithm.
• T develop the BERT model (by applying the two different Twitter datasets).
• To analyse, compare, and report the results of the pre-trained BERT classification based on performance metrics such as Accuracy and F1- score.
• To compare the results with the previous studies.

**Question** 
• How can deep learning models be used to detect positive, natural, or negative from the Textual data?

**Results:**  Applied transformer deep learning algorithm (BERT) in two different datasets. The algorithm is evaluated concerning the metrics, namely accuracy, F1 score, recall, and compared with the outcomes of previous studies. BERT algorithm in the deep learning model is best suited for sentiment analysis on Twitter datasets.
**Method:**  The method chosen to address the research question and objectives is an experiment. Through which the identified algorithms are evaluated with the selected metrics. 
**Conclusion:**  This research aims to design the transformer deep learning algorithms for sentiment analysis on Twitter datasets. Pre-trained BERT model results of having an accuracy of 99% and F1 of 99.2% for first datasets and - an accuracy of 96% and F1 of 97% for the second dataset. It is proved by comparison with past studies that used the same datasets (on different models), BERT model gained the highest accuracy and F1 score, compared to other machine learning and deep learning models from previous studies.

**Keywords**

Deep learning, Sentiment Analysis, Twitter Sentiment Analysis, natural language processing (NLP), text mining, BERT

