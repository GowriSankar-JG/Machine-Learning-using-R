## Image-Classification-using-SVM

# 1.	Introduction
The project demonstrate application of SVM’s in image classification. 

The objective is to identify each of a large number of black-and-white rectangular pixel displays as one of the 26 capital letters in the English alphabet. The character images were based on 20 different fonts and each letter within these 20 fonts was randomly distorted to produce a file of 20,000 unique stimuli. Each stimulus was converted into 16 primitive numerical attributes (statistical moments and edge counts) which were then scaled to fit into a range of integer values from 0 through 15. We typically train on the first 16000 items and then use the resulting model to predict the letter category for the remaining 4000.
# 2.	Data Collection:

The dataset contains 20,000 examples of 26 English alphabet capital letters as printed using 20 different black and white fonts.

URL : http://archive.ics.uci.edu/ml

Source Information
		a) Creators:
		W. Frey and D. J Slate
Letter recognition using Holland-style adaptive
classifiers. Machine Learning. 1991; 6:161-182 



# 3.	Summary
The model shows that SVM’s are capable of learning complex patterns while being able to avoid noise in the data. They are able to understand visual patterns with a high degree of accuracy. 
The model was able to predict the letters correctly with a 97.05% accuracy. 


