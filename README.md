# Probability-of-an-Occupation-Being-Analytical

This task is loosely based on the following paper from Osborn and Frey on the “Future of Employment”. The authors use a simple machine learning model and the ONET database to estimate a probability that each occupation will be automated. The ONET database is a survey of experts and current employees about the requirements of each occupation (job). Effectively, Osborn and Frey use the ONET data to predict an occupation’s probability of automation. Rather than predicting the probability of automation, here the task is to predict the probability of being ANALYTICAL (using a predictive model of your choice).

Dataset is the ONET data and is publicly available at https://www.onetcenter.org/database.html?p=2 . 
A subset of a subset of ONET occupations has been selected and hand labeled as either ANALYTICAL or not. Three models namely, Logistic Regression, Weighted Logistic Regression, Gaussian Process Classifier has been selected to estimate the probability of an occupation being
ANALYTICAL. Models has been ebaluated using evaluation ROC-AUC.Then selected model (Gaussian Process Classifier) was used to predict the probability of being ANALYTICAL on the rest of the
