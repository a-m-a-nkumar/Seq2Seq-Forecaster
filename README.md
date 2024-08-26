# Seq2Seq-Forecaster



## Introduction

In the realm of predictive analytics, particularly in forecasting, traditional methods like regression and ARIMA models are giving way to more robust deep learning approaches. **Sequence to Sequence Learning with Encoder-Decoder Neural Network techniques** has emerged as a powerful tool in handling complex time series forecasting tasks, especially amidst the influx of big data.

This document aims to demystify the implementation of Seq2Seq models using an LSTM-based Encoder-Decoder architecture, specifically applied to predicting daily customer visits in a restaurant setting.

## Files Overview

- **`How it works.md`**: Main document explaining the functionality and implementation of the model.
- **`Seq2Seq (LSTM).ipynb`**: Jupyter notebook containing the implementation script for the model.

## Reproducing Results

1. **Download Input Files**:
   - Navigate to the `data` folder and retrieve the following files: `train_final.zip`, `test_final.csv`, and `sample_submission`.
   
2. **Setup Environment**:
   - Ensure the notebook file (`Seq2Seq (LSTM).ipynb`) is placed in the same directory as the downloaded data files.

3. **Execution**:
   - Open and execute the entire notebook (`Seq2Seq (LSTM).ipynb`) in a Jupyter environment or compatible IDE.

## References

### Seq2Seq Learning
- [Kaggle: LSTM Encoder-Decoder via Keras](https://www.kaggle.com/ievgenvp/lstm-encoder-decoder-via-keras-lb-0-5)
- [Keras Blog: Introduction to Seq2Seq Learning](https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html)

### LSTM Networks
- [Medium: Understanding LSTM Networks](https://medium.com/datadriveninvestor/how-do-lstm-networks-solve-the-problem-of-vanishing-gradients-a6784971a577)

### Attention Mechanism
- [Distill: Augmented RNNs](https://distill.pub/2016/augmented-rnns/)
- [WildML: Attention and Memory in Deep Learning](http://www.wildml.com/2016/01/attention-and-memory-in-deep-learning-and-nlp/)
