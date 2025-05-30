Predicting Instagram Hashtag Frequency for #mentalhealth Using LSTM
Project Overview
This project focuses on forecasting the future usage frequency of a single Instagram hashtag — #mentalhealth — based on its historical daily frequency data. Using an LSTM (Long Short-Term Memory) neural network, the model predicts how often the hashtag will be used on the next day, leveraging time-series analysis.

What This Project Does NOT Do
It does not predict which hashtags will trend or identify new popular hashtags.

It does not classify or cluster different hashtag types.

The scope is limited to time-series forecasting of one hashtag’s frequency.

Why This Approach?
Instagram hashtag trends can be volatile and influenced by many external factors. However, for specific hashtags like #mentalhealth, historical usage patterns can provide valuable insight into near-future behavior. This project demonstrates how to leverage LSTM neural networks to capture temporal dependencies in usage data and generate short-term forecasts.

Dataset
Daily frequency counts of #mentalhealth hashtag usage collected over a period.

Data is preprocessed and normalized before feeding into the model.

Model Architecture
LSTM layer with 64 units to capture temporal patterns.

Followed by a Dense output layer to predict the next day’s frequency.

Mean Squared Error (MSE) used as the loss function for regression.

How to Use
Prepare time-series data of hashtag usage frequencies.

Normalize data.

Create sequences of length 7 (past 7 days) to predict the 8th day.

Train the LSTM model on the sequences.

Use the model to predict next-day hashtag frequencies.

Results
Model outputs predicted numerical values representing estimated hashtag counts.

Can be used to monitor and anticipate short-term shifts in hashtag usage trends.

Tech Stack
Python 3.x

TensorFlow / Keras

NumPy, Pandas, Scikit-learn (for preprocessing and splitting data)

Future Work
Extend model to predict multiple hashtags simultaneously.

Incorporate external factors (events, news) for improved accuracy.

Build a trend discovery system to identify emerging hashtags.

License
MIT License © 2025 Uday Trivedi

Contact
For questions or collaboration, reach out at [your-email@example.com]


