# PET-degrading-proteins-identification
This repository contain all the code used to test different machine learning models in order to classify PET degrading proteins starting from data extracted from PlasticDB which is a 
database that contains all the experimentally validated PET degrading proteins.
In particulatar we have tried two different approaches:

-Sequence approach: starting from protein sequence and through a Natural Processing Model produce a vector for each protein and from them build a classification model able to distinguish PET degrading proteins from others. 


-Structural approach: Starting from atoms coordinate of the proteins obtain corrispective graph and through graph embbedding model produce a vector for each protein and from them build a classification model able to distinguish PET degrading proteins from others. 

