### Domain classification of customer messages

## Problem Statement:
Haptik is one of the world's largest conversational AI platforms. It is a personal assistant mobile app, powered by a combination of artificial intelligence and human assistance. It has its domain in multiple fields including customer support, feedback, order status and live chat.

We have with us the dataset of Haptik containing the messages it receives from the customers and which topic(class) the messages refer to.

We need to create a model predicting which class a particular message belongs to using NLP. We will also try to use techniques like **LSA** (Latent Semantic Analysis*) and **LDA** (*Latent Dirichlet Allocation*) to assign topics to new messages.

The dataset consists of message column along with the different column associated with the topic they could associated with it.

We have with us two variations of the same dataset

Train data(**40000 rows**) [We will train our model on this]

Test data(**10000 rows**) [We will validate our model on this]
