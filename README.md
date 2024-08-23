# SGAT-SP

For an extended period, stock market volatility has been a major focus of research by both industry professionals and academic scholars. Much of the existing literature concentrates on using single features like closing prices, opening prices, or news articles to predict stock movements. Some studies have explored the use of graph neural networks to aggregate features from related stocks, typically focusing on node aggregation and edge attention methods. This work extends previous research that examined the performance of a Sparse Graph Attention Mechanism in predicting stock trends. The proposed approach introduces a novel transformer model to capture the long-term dependencies in stock price data, replacing the commonly used LSTM, which is often employed in time-series stock forecasting. This component is one of three modules designed for feature extraction, and these features are then fed into the sparse graph attention network. Additionally, the model constructs the graph using the top 10 relations identified in ML-GAT (Multilevel Graph Attention Network), which helps to eliminate irrelevant and noisy relations that don't improve accuracy. The model is used to predict trends across the GICS (Global Industry Classification Standard) sectors of the S&P 500 index. When compared to the leading benchmark model, SGAT-SP (Sparse Graph Attention Network for Stock Prediction), the enhanced model, eSGAT-SP, achieves an average accuracy score of 0.842 and an average F1 score of 0.77. It also delivers an almost perfect recall, with an average value of 0.84 across all GICS sectors, despite utilizing fewer edges.


![Architechture Diagram_page-0001](https://github.com/user-attachments/assets/ff7c54a9-f07c-4c61-8bd1-d38e8109fa2c)



