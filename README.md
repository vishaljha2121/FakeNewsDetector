<!-- ABOUT THE PROJECT -->

## About The Project

This is a Natural language processing project which identifies if a news is FAKE or REAL.

The datset used contains 6335 unique news articles with FAKE/REAL labels for each with no null values.

### Built With

- **LSTM architecture**.
- **Tokenizer**

The loss value of **0.0290** has been achieved which gives good results but the model is not generalised and will give a lower accuracy on data input from outside the testing data.

Training and testing data was tokenised with appling num_words limited to 2000 and max_len fixed at 400, and created a padded sequence.

Model evaluation resulted in 0.8245 accuracy metric.

# Dependencies

- Pandas
- Matplotlib
- Sklearn
- Keras
