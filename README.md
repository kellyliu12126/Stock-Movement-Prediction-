In recent years, sequential pattern recognition has achieved state of the art in numerous applications. Stock movement prediction is one of the learning tasks due to the sequential nature of time series. To forecast the stock movement, it is critical to model the dynamic structure. Therefore, we first introduce Hidden Markov Models (HMM) and Recurrent Neural Network (RNN), which have proven suitability to represent the arbitrary nonlinear dynamic systems by extracting patterns from temporal data. We then focus on the variants of the RNN, Long-Short term memory (LSTM) and Gated Recurrent Units (GRU), to solve the problem of long-term dependency in time series and provide better interpretation of the hidden dynamics. This paper aims to predict the stock price movements based on the HMM and different recurrent neural network architectures (RNN, LSTM, GRU). In particular, we consider the performance results and propose a reliable trading strategy. The experiments are based on a high-risk stock market and a mature stock index. The performance result shows the HMM with four observation sequences along with 6 states better represents the hidden states among other HMMs. Comparing among the RNN architectures, the GRU obtains up to 77% of accuracy and has the lowest prediction errors in terms of RMSE and MAE. Our comparative analysis indicates that the RNN architectures are better than the HMMs in both accuracy and profit test performances. Specifically, the GRU is the outstanding model in our scenario, which achieves the maximum cumulative profit.
