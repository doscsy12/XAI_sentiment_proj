# Explainable Artificial Intelligence Sample Project
Explainable Artificial Intelligence (XAI) means making Artificial Intelligence systems (AI) more transparent, such that their decisions can be understood. 

Here, deep learning is used to classify a chosen text as positive, negative or neutral, on the basis of it's content. After the classification, a method called LRP (Layer-wise Relevance Propagation) is applied to explain why the deep learning system came to it's decision, making it an XAI system instead of a black-box system.

The LRP implementation is based on the following papers:

https://doi.org/10.1371/journal.pone.0130140
<br>https://doi.org/10.18653/v1/W17-5221

And the functions are based on implementations from Layer-wise Relevance Propagation (LRP) for LSTMs:

https://github.com/ArrasL/LRP_for_LSTM
