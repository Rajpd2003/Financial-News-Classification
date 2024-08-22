# Financial-News-Classification
This model uses LSTM to classify news about companies as positive, negative or neutral thus helping to decide upon investment startegies.
The sentences in the news are modeled as matrices with words represented by the rows.To convert the words to vectors Doc2Vec model is used and cosine similarity between similar words is used to check the performance of word the embedding model.

# Structure of Model
The model consists of LSTM with 50 units followed by a dense layer with 3 units to give the probability of positive, negative or neutral sentiments.

![image](https://github.com/user-attachments/assets/a7f9034a-49d4-46e8-b691-67bb243176b4)
