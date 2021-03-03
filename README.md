# RNN-Shakespeare-Text-Generation

# Requirements
- Flask==1.1.2
- Werkzeug==1.0.1
- tensorflow-cpu
- numpy
- gunicorn

# Model Summary

- Model: "sequential_2"
_________________________________________________________________
- Layer (type)                 Output Shape              Param #   
=================================================================
- embedding_2 (Embedding)      (1, None, 256)            16640     
_________________________________________________________________
- lstm_2 (LSTM)                (1, None, 1024)           5246976   
_________________________________________________________________
- dense_2 (Dense)              (1, None, 65)             66625     
=================================================================
- Total params: 5,330,241
- Trainable params: 5,330,241
- Non-trainable params: 0
_________________________________________________________________
