# Sentiment-analysis
Sentiment analysis, the process of extracting the information from the texts. In this repo I'll build the sentiment analysis model from various NLP tasks and processes.


## About:
- In this project i build model which extract the information or sentimnet from the texts of dataset. The model detect whether the sentiment is positive or negative and give us the rating from the observed prediction.


## Dataset:
- I've used the amazon review dataset in which it has abuot 25000 collection of sentiment and its review.
- The dataset has two cloumns sentiment and review.
- It is divided into five categories by the rating from 1 to 5.


## Model:
- RNN model: In this model a simplernn layer was used for building the model along with the Dense and Dropout layers.
- LSTM model: In this model a LSTM layer was used along with Dense,Dropout and Embedding layers.


Training:
- In RNN model the training accuracy achieves 41% with the no. of 3 epochs.
- In LSTM model the training accuracy achieves 45% with 5 epochs.

## Accuracy plot:

<img width="2539" height="1806" alt="LSTM accuracy plt" src="https://github.com/user-attachments/assets/d7273a97-48ea-4178-8c87-35901a128910" />



## Confusion matrix:


<img width="2367" height="2037" alt="Confusion matrix" src="https://github.com/user-attachments/assets/1edec6eb-e0b1-413b-89b0-8f1a5c728a45" />

