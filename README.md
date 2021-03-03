# RNN-Shakespeare-Text-Generation

# RNN (Recurrent Neural Network)
Recurrent neural networks (RNN) are a class of artificial neural networks that is powerful for modelling sequence data such as time series or natural language. Vanilla neural networks have one shortcoming when compared to RNNs, they cannot solve machine learning problems which need to remember information about the past inputs. When processing sequential data, it is key that we remember the relationships in the data, and plain CNNs are not good at length-varying input and output. Hence, I am using RNNs for the task of text generation.

I use a special type of RNN called LSTM, which are equipped to handle very large sequences of data. Simple RNNs have a problem called the vanishing gradient problem, because of which they cannot handle large sequences. LSTMs are designed to handle long-term dependencies.


# Development Environment
- Flask==1.1.2
- Werkzeug==1.0.1
- tensorflow-cpu
- numpy
- gunicorn

# Model Summary

- Model: "sequential_2"
_________________________________________________________________
- Layer (type)-----                 Output Shape-----              Param  

- embedding_2 (Embedding)-----      (1, None, 256)-----            16640     
- lstm_2 (LSTM)-----                (1, None, 1024)-----           5246976   
- dense_2 (Dense)-----              (1, None, 65)-----             66625
- Total params: 5,330,241
- Trainable params: 5,330,241
- Non-trainable params: 0
_________________________________________________________________
