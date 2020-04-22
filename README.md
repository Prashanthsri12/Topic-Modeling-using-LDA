Topic Modeling in Python : Using LDA to find topics of Articles


Topic modeling is an unsupervised technique that intends to analyze large volumes of text
data by clustering the documents into groups. In the case of topic modeling, the text data
do not have any labels attached to it. Rather, topic modeling tries to group the documents
into clusters based on similar characteristics.

Two approaches are mainly used for topic modeling: Latent Dirichlet Allocation and 
Non-Negative Matrix factorization; Latent Dirichlet Allocation (LDA) is one of the 
most popular in this field.

The LDA is based upon two general assumptions:
- Documents that have similar words usually have the same topic
- Documents that have groups of words frequently occurring together usually have the 
same topic.

These assumptions make sense because the documents that have the same topic, for instance, 
Business topics will have words like the "economy", "profit", "the stock market", "loss", 
etc. The second assumption states that if these words frequently occur together in 
multiple documents, those documents may belong to the same category.


You can find the dataset and the sample python file in this repository for your reference
