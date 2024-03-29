# Twitter Sentiment Analysis 👍👎 

Neural network models for tweet classification. That is, given a tweet, they return whether it is positive or negative.  
The dataset is available [here](https://drive.google.com/file/d/1dTIWNpjlrnTQBIQtaGOh0jCRYZiAQO79/view).  

## Models implemented
- Feed Forward Neural Network
  - with TF-IDF feature generation scheme
  - with GloVe pre-trained word embeddings 
- Recurrent Neural Network with GloVe pre-trained word embeddings
  and three types of RNNs:
  - simple RNN
  - with GRU cells
  - with LSTM cells

In the following table I include the links to Google Colaboratory for the various models.  
The _ipynb_ files are included in this repository as well.
Each notebook is fully documented.

|Method | Link to Google Colab |
|:-:|:-:|
| Feed Forward Neural Net using TF-IDF | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12Yh2X91JOkYBEG3yXfcBRjORjHh1KTPy?usp=sharing) |
| Feed Forward Neural Net using GloVe | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PbAQPiyTpwWAeKV5LC9bNCERwPZn1qC3?usp=sharing) |
| Bidirectional Stacked Recurrent Neural Net with GRU/LSTM | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/14Th2b3wAUN_3Ujh3MqFhMvAmtqHfVaBU?usp=sharing) |
