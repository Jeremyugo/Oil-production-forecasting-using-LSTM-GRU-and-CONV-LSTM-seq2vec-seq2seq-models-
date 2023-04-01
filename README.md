# Oil Production Forecasting with LSTM, GRU, and CONV-LSTM Models
This machine learning project aims to forecast oil production using various recurrent neural network (RNN) models, including Long Short-Term Memory (LSTM), Gated Recurrent Unit (GRU), and Convolutional LSTM (CONV-LSTM). The CONV-LSTM model is implemented in two different variants: Sequence-to-Vector (Seq2Vec) and Sequence-to-Sequence (Seq2Seq).

## Dataset
The dataset used for this project contains over 5,000 historical oil production data points. However, other relevant features like wellhead pressure data can be added to improve the accuracy of the model. The dataset is preprocessed and split into training, and test sets for model development and evaluation.

## Models
The LSTM, GRU, and CONV-LSTM models are implemented and trained on the preprocessed data. The CONV-LSTM model is implemented in two variants: Seq2Vec and Seq2Seq. The models are evaluated on the test set to compare their forecasting performance.

## Results
The forecasting performance of each model is evaluated using performance metrics such as mean absolute error (MAE), mean squared error (MSE), and mean_absolute_percentage_error (MAPE). The results are presented and compared to determine the best performing model.

## Getting Started
To run this project, you will need to install the required libraries and dependencies, including TensorFlow, Keras, Pandas, NumPy, and matplotlib for visualization. The preprocessed dataset and trained models are also included in the project for easy replication of the results.

## Conclusion
This project demonstrates the effectiveness of RNN models for oil production forecasting and provides insights into the performance of different RNN architectures. The CONV-LSTM model with Seq2Vec variant shows the best forecasting performance and can be used for future oil production forecasting.

![image](https://user-images.githubusercontent.com/36512525/229262428-2532f11c-4bab-4bd7-9185-7833d5559a51.png)
