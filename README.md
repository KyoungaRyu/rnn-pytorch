# RNN(Recurrent Neural Network) 

### Naver Sentiment Movie Corpus

This is a sentiment analysis of Naver Movie Reviews using PyTorch. 
To analyze movie corpus, Konlpy needs to be installed with twitter(Open Korean Text) as Korean tokenizer. 

**1. Dataset** 

Data from Naver Movie Review(https://movie.naver.com/movie/point/af/list.nhn)
Tabular dataset includes id, document, and label, which is 'tsv' format. 
('tsv' format delimits columns with tabs.)


**2. Model**

Recurrent Neural Network(RNN: LSTM-based model)
The model uses the nn.LSTM module to get better results. 

**3. Architecture**

Long-Short-Term-Memory (LSTM) Architecture

![](/lstm.png)
                                                         [Reference](https://excelsior-cjh.tistory.com/185)

There are several architectures of LSTM usually consists of three regularators, called gates, 
of the flow of information inside the LSTM unit: an input gate, an output gate and a forget gate. 

**4. Conclusion**

It shows pos(1) and neg(0) as the results. 


