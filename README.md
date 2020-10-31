# DL
Reference
- KDD paper learning-dynamic-context-graphs-for-predicting-social-events, https://dl.acm.org/doi/pdf/10.1145/3292500.3330919 
- IJCAI 2015 https://www.ijcai.org/Proceedings/15/Papers/329.pdf 
- Deep Learning for Event-Driven Stock PredictionDeep Learning for Event-Driven Stock Prediction  
# LSTM, transformer, attention> papers            
- [Exploring the attention mechanism in LSTM-based Hong Kong stock price movement prediction](https://www.tandfonline.com/doi/abs/10.1080/14697688.2019.1622287)    
- [Forecasting future stock price movement by market sector using LSTM recurrent network](https://scholarworks.calstate.edu/concern/theses/xp68kg20b)    
- [BERT-based Financial Sentiment Index and LSTM-based Stock Return Predictability](https://arxiv.org/abs/1906.09024)   
- An Attention-Based LSTM Model for Stock Price Trend Prediction Using Limit Order Books        
- [Enhancing Stock Movement Prediction with Adversarial Training](https://www.ijcai.org/Proceedings/2019/0810.pdf)  IJCAI 19    

# Data 
More data like macro(DJI), sector(TMT), and stocks(Apple) are required. The data is from last 10 year, or even from a subset last 5 years would be tested too. 

The structure of the graph requires solid clarifications and hidden information tell us what?
# Cleaning process 

# Embedding
Current word embedding is following Glove[10], this is a generic word embedding that not only designed in the finance area. Actually, we need a more finance-related embedding method to further map the data.

# Results 
Baseline results, in the original paper, the authors discuss the results with LSTM, GRU, RNN under temporal and non-temporal settings, we only compare the model with Naive Bayes, which further we need to run more machine learning baselines to compare.

Domain knowledge, more indices such as SNP, MSCI World, FTSE All-World index series should be valued. 

GIN GCN perfomances 
    
