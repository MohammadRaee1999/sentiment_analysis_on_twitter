
# Introduction
Emotion analysis or opinion analysis means discovering or recognizing the positive and negative feelings of people about an issue or product in the texts. The growing importance of sentiment analysis has coincided with the growth of social media such as polls, forum discussions, blogs, Twitter, and social networks. Sentiment analysis systems are used in almost all business and social contexts because opinions and ideas are important to all human activities and have a key impact on our behavior.
The text emotion analysis project has been done with the help of various Python machine learning algorithms. In this project, the process of recognizing emotions in a text is performed on a spoken text data set. The analysis was performed during the project by combining several machine learning algorithms including random forest, SVM with linear kernel, and SVM with RBF.
This project is done in four parts. The first part includes preprocessing of data, the second part includes word-to-word conversion (word2vec), the third part includes data reduction and data classification, and the fourth part includes evaluation.
## Part 1:
In this part, with the help of nltk library, pre-processing has been done on the data and the data is ready to be processed.
Pre-processing includes converting uppercase to lowercase letters, deleting numbers, deleting hyphens, deleting addresses, deleting lowercase letters, and inserting 3 consecutive expressions with 2 expressions.
## Part 2:
In this part, with the help of the genism library, the preprocessed data is converted into vectors like them. The algorithm used for this section, word2vec, tries to simulate the properties and relationships of words as much as possible.
## Part 3:
In this section, first the importance of each word in the text was determined by the component tf_idf. After that, with the help of the vectors of each data, the vector was assigned to the whole text, and then a set of these vectors (text vectors) was stored in a presentation for classification. In this step, classification operations were performed on the data by 3 types of common algorithms for classification, namely random forest, SVM with linear kernel, and SVM with RBF.
## Part 4:
In this section, the results were evaluated. Finally, for each of the three algorithms mentioned in Section 3, the confusion matrix was drawn and the accuracy was assessed by accuracy, precision, recall, and f1-score criteria. Finally, the random forest algorithm was evaluated better than the others.
## requirements
#### pandas~=1.2.0
#### numpy~=1.19.2
#### matplotlib~=3.3.1
#### seaborn~=0.11.1
#### nltk~=3.5
#### wordcloud~=1.8.1
#### scikit-learn~=0.23.2
#### gensim~=3.7.3
