# LSTM Stock Predictor

I was assined to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data. I have to use deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price. These are the steps I need to follow:
1. [Prepare the data for training and testing](#prepare-the-data-for-training-and-testing)
2. [Build and train custom LSTM RNNs](#build-and-train-custom-lstm-rnns)
3. [Evaluate the performance of each model](#evaluate-the-performance-of-each-model)


![closing](https://github.com/padthai-sketch/Deep-Learning/blob/main/Images/closing.png)
The Model using the closing prices as indicators


![fng](https://github.com/padthai-sketch/Deep-Learning/blob/main/Images/fng.png)
The Model using the FNG as indicators

Based on the performance of both models, it can summarize that the first model, which uses the normal closing price data, performs better than the FNG one. It indicates lower loss and the ability to monitor the real values over time. In this experiment, I set window sizes to 10 and 20 to see which one is working better. Turns out that the shorter the window size, the better.
