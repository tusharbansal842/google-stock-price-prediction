# Google Stock Price Prediction

This project explores the use of Recurrent Neural Networks (RNN), Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU) models for predicting Google stock prices. The goal is to determine the optimal number of days to consider for accurate predictions. The project includes three files, each corresponding to different sequence lengths.

## Files in the Repository

### 1. `tushar_sequence_10.ipynb`
- **Description:** Uses a sequence length of 10 days to predict the stock price for the next day.
- **Objective:** Evaluate how short-term dependencies affect model performance.

### 2. `tushar_sequence_30.ipynb`
- **Description:** Uses a sequence length of 30 days to predict the stock price for the next day.
- **Objective:** Examine whether a medium-term sequence length captures better patterns.

### 3. `tushar_sequence_50.ipynb`
- **Description:** Uses a sequence length of 50 days to predict the stock price for the next day.
- **Objective:** Assess whether long-term dependencies improve prediction accuracy.

## Project Highlights

- **Purpose:** Analyze the impact of different sequence lengths on stock price prediction.
- **Models Used:** GRU-based architecture for sequential data modeling.
- **Results:** The sequence of 10 days provided the best results, suggesting that short-term dependencies are most relevant for this dataset.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/tusharbansal842/google-stock-price-prediction.git
