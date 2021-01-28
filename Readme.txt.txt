Data mining project

Authors: Hamza Bouzidi (1915027), David Mauricio Guzman Delgado (1909580)

Reference paper: Using Social Media to Enhance Emergency Situation Awareness
(https://ieeexplore.ieee.org/document/6148196/)


1: Tweet filtering
Task:
As in the article, the idea is to implement a classification for impact assessment. For this purpose, we
propose two classifiers:
	Disaster or not : binary classifier that classifies whether or not a tweet is related to a disaster event.
	Disaster type : multiclass classifier that separates the different types of disasters.

Dataset Link: https://crisisnlp.qcri.org/lrec2016/lrec2016.html

Description: Crisis NLP contains tagged tweets for different crisis events that can be useful for
training the multiple class classifier. Also, kaggle contains dataset for the binary classifier.

2: Clustering disasters on tweets
Task:
As in the article, the idea is to try to cluster similar event tweets classified as disaster type. For this, as
in the article, it would be important to use an online algorithm to take into account new tweets
generating a new event and thus a new cluster.

Dataset Link: https://crisisnlp.qcri.org/lrec2016/lrec2016.html

Description: Crisis NLP contains multiple dataset with tweets related to crisis events. Useful to check
how good the algorithm is clustering events
