# NLP with disaster tweets

This is a knowledge competition on Kaggle. The goal is to predict which tweets are about real disasters and which ones are not.  

In this project, I tried different neural networks in this text classification task, inlcuding Simple RNN, GRU, LSTM, CNN, and BERT. I found BERT model give me the best accuracy. I also tried to assemble different models to improve the prediction accuracy.  

In the end, using BERT model with bagging, I was able to increase the test accuracy to 84%, which ranks top 10% of the leader board.  

The Notebooks were run on Goole Colab with GPU.

### what I learned
- text preprocessing: text tokenization and sequence padding
- build, train, and evaluate different neural network models using TensorFlow, including simple RNN, GRU, LSTM, CNN, and BERT
- bagging is an effective approach to improve the performance of small models, though it's very costly because the model needs to be trained for several times. 
