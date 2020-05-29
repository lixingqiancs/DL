# DL
 Thank you for your advice during the conversation. I attached my very initial draft for the idea, apparently, more works are required including but not limited to theory, data, and simulations. 
    The link is about the KDD paper https://www.kdd.org/kdd2019/accepted-papers/view/learning-dynamic-context-graphs-for-predicting-social-events . 
   This is from IJCAI 2015 https://www.ijcai.org/Proceedings/15/Papers/329.pdf 
Deep Learning for Event-Driven Stock PredictionDeep Learning for Event-Driven Stock Prediction Xiao Ding y, Yue Zhangz, Ting Liu , Junwen Duany yResearch Center for Social Computing and Information Retrieval Harbin Institute of Technology, China fxding, tliu, jwduang@ir.hit.edu.cn zSingapore University of Technology and Design yue zhang@sutd.edu.sgwww.ijcai.org 

More data like macro(DJI), sector(TMT), and stocks(Apple) are required. The data is from last 10 year, or even from a subset last 5 years would be tested too. 

The structure of the graph requires solid clarifications and hidden information tell us what?
The cleaning process.
Current word embedding is following Glove[10], this is a generic word embedding that not only designed in the finance area. Actually, we need a more finance-related embedding method to further map the data.

Baseline results, in the original paper, the authors discuss the results with LSTM, GRU, RNN under temporal and non-temporal settings, we only compare the model with Naive Bayes, which further we need to run more machine learning baselines to compare.

Domain knowledge, more indices such as SNP, MSCI World, FTSE All-World index series should be valued. 

GIN GCN perfomances 
    
