# Data Science Machine Learning Demo

A data science demo script which trains two-layer LSTM models in Python, using an indoor air pollution dataset. Creates LSTM models for three indoor air pollution features.

Includes a basic EDA, dataset cleaning and preparation. Data scaling/normalisation has not been conducted.

By default, the model is trained using the following parameters:
* Two-layer LSTM model, using 32 neurons per layer
* Sequence length of 100
* Batch size of 64
* Dropout between layers of 0.2
* 20 epochs
* Adam optimiser using the mean squared error loss function

## How to Use:
First, ensure all requirements are installed using the provided requirements.txt file.

```
``` pip install -r requirements.txt
```

It is recommended to do this inside a venv. Created using Python 3.11, different package versions may be necessary if using a different version of Python.

Next, you'll need to download the dataset, which can be found here: https://doi.org/10.17632/2r232jpfb2.1

Update the file import path to match the downloaded file.

You should then be able to run the entire file, and play around with the LSTM training parameters.

