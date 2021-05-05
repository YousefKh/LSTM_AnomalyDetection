# LSTM_AnomalyDetection
The training methodology for our LSTM network is fairly straightforward. We first extract all continuous length-n subsequences of data from the training input, treating the last point in each subsequence as the label for the sample.
