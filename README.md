# A DEEP LEARNING APPROACH TO RESUME CLASSIFICATION
## INTRODUCTION

Text classification is a widely used natural language processing task in different domain specific problems. The goal is to automatically classify the text documents into predefined classes. Examples for some text classification problems are sentiment analysis, spam filtering, categorization of news articles etc. Resume classification is a text classification problem, where each resume assigned to predefined job classes. So that it becomes easier to manage and sort by the companies when people drop their resumes at company’s website or email. Deep learning methods are efficient for text classification problems. 

## MOTIVATION

Most of the companies depend hiring agencies to find talented job seekers. The hiring agencies collect resume and manually  allocate them to appropriate positions in different companies.  Such hiring system demands a lot of cost and time, also the resume need to be manually classified. If we can automate this process, we do not require a third party act as a middlemen between the company and the candidate. An intelligent system can automatically assign a candidate to specific job position by making use of natural language processing. Traditional approach to classification is simply a rule based approach.  The resumes are often heterogeneous in representing data. People use different terms and structure while creating them. A lot of ambiguities cause rule based systems to result misclassification. The  machine learning techniques can solve this problem using annotated data. Machine learning approach normally go through four stages; dataset preparation, feature engineering, learning and validation. The features selected for learning highly influence the classification accuracy. 

Deep learning allows features learned automatically. It eliminate the requirement of costly, time consuming feature engineering as in machine learning approach. It make use of artificial neural networks, such as deep neural networks(DNN), convolutional neural networks (CNN), and recurrent neural networks (RNN).  Deep learning is highly data driven, large volume of data is required for learning. Performance is high in many text classification problems.


## PROBLEM DEFINITION

People apply for different positions in company, it can be broadly classified into technical and non-technical. Technical class can be again classified into developers, testers, administrators, etc. and non-technical class can be again classified into marketing, HR , business, etc. The proposed system will helps companies to effectively manage resumes by classifying them into predefined job classes without any human intervention.

## REQUIREMENTS

**Dataset**: Dataset should contain large number of resumes since deep learning is used for classification, it requires large volume of training data. Resumes are highly confidential document, not publicly available. Manual annotation of resumes is required since it is a supervised learning method.

**Preprocessing** : Characters and texts which are irrelevant to classification should be removed. Regular expressions and basic programming can be used to address this problem.

**Word embedding**: The text features are to be represented as vectors in higher dimensional space. The neural networks like Word2Vec or Glove can be used for word embedding.

**Classification model**: Deep learning methods like RNN, CNN, DNN can be used to construct a classification model. This classification model is used to predict the job class of unseen resumes.

## PROPOSED SYSTEM DESIGN
![alt text](https://github.com/rahulgullan/ML_Project/blob/master/icfoss2.png)

## FUTURE SCOPE

The document parsing using deep learning method is an important application. It is the next level of document classification. For example, if a company more interested in candidate’s technical skills, they can prioritize resumes by only considering required specific information. Parsing helps to identify various semantic sections in documents and extract relevant information.

Both classification and parsing can be applied to any kind of document in an organization like resumes, tender applications, proposals etc.
