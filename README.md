In this project I have used federated learning to train the model
The model used are:
1) Resnet-34
2) Alexnet
3) VGG
4) Densenet

I have trained the model in the decenteralised manner and the centeralised manner and compared for each model

ABOUT THE PROJECT:

- Created a classification model to classify chest disease with chest X-ray using federated learning which comes under machine learning concepts.

- This model classify X-ray into 8 categories:
1) Atelectasis
2) Consolidation
3) Mass
4) Pneumothorax
5) Fibrosis
6) Infiltration
7) Emphysema
8) No Finding

- federated learning : This classification model is created in a decentralized environment where multiple model of the same kind collaboratively train without sharing their raw data. Instead, they exchange only the insights from their learning to the central model. The central model learn from every model knowledge while keeping individual data private. 
- Used dataset from national Institute of Health to train the model
-The trained model achieved high accuracy of 83% and manage to achieve high security for the data
