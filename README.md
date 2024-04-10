# Quant-Trading-Assignment Submission

## GitHub Repository: [Your Repository Link]

## Introduction:
This repository contains the code and results for the quant trading assignment, focusing on simulating trading using reinforcement learning.and evalutating agent performance.

## Data:
The dataset used for analysis or model training is described below: SPY_2018.csv

The trading agent dataset contains the following columns:

1. **Open:** This column represents the opening price of the financial instrument (e.g., stock, cryptocurrency) at the beginning of the trading period.

2. **High:** The high column denotes the highest price reached by the financial instrument during the trading period.

3. **Low:** This column indicates the lowest price reached by the financial instrument during the trading period.

4. **Close:** The close column represents the closing price of the financial instrument at the end of the trading period.

5. **Adjusted Close:** Adjusted close refers to the closing price of the financial instrument after accounting for any corporate actions, such as dividends, stock splits, or mergers. It provides a more accurate reflection of the instrument's true value.

6. **Volume:** Volume represents the total number of shares or contracts traded during the trading period. It reflects the level of market activity or liquidity for the financial instrument.

These columns provide essential data points for analyzing the price movements, volatility, and trading volume of the financial instrument over time. They are commonly used in technical analysis, quantitative modeling, and algorithmic trading strategies.

## Code:

To run the code locally, follow these instructions:

1. Clone the repository: `git clone [Your Repository Link]`
2. Navigate to the code directory: `cd [Code Directory]`
3. Execute the main script: `python main.py`

## Results:
![OUTPUT](https://github.com/MrResilient/Quant-Trading-Assignment/blob/main/output_trading.png)





## Model/Strategy Implemented:
Details of the model or strategy implemented:

- Purpose: Reinforcement learning (RL) is used in stock market prediction for several reasons:

1. **Adaptability:** Stock market conditions are constantly changing and highly stochastic, making it difficult to create static predictive models. RL algorithms, such as Q-learning and Deep Q-Networks (DQN), can adapt to changing market dynamics by learning from past experiences and adjusting their strategies accordingly.

2. **Complex Decision Making:** Stock trading involves making complex decisions based on a wide range of factors, including market trends, company performance, news events, and investor sentiment. RL algorithms can handle this complexity by learning to make sequential decisions over time, taking into account the current state of the market and potential future outcomes.

3. **Optimization:** RL algorithms can optimize trading strategies to maximize returns while minimizing risk. By formulating trading as a sequential decision-making problem, RL agents can learn to balance between exploration (trying out new strategies) and exploitation (leveraging known profitable strategies).

4. **Handling Uncertainty:** The stock market is inherently uncertain, with prices influenced by a multitude of factors that are often unpredictable. RL algorithms are well-suited to handle uncertainty by learning probabilistic policies that can account for different possible outcomes and their associated probabilities.

5. **Model-Free Learning:** RL does not require a predefined model of the stock market dynamics, making it suitable for domains where the underlying processes are complex and not fully understood. RL agents learn directly from experience, allowing them to discover patterns and exploit profitable opportunities without relying on explicit models.

Overall, RL offers a flexible and adaptive approach to stock market prediction, enabling traders to develop sophisticated trading strategies that can navigate the dynamic and uncertain nature of financial markets.
- Methodology: Machine learning methods can be broadly classified into: supervised learning, unsupervised learning, and reinforcement learning.

The decision tree model and recurrent neural network are supervised learning models that use known prices to adjust predicted prices, making the model more accurate.

The difference with reinforcement learning is:

There is no supervised signal or label (known price) in the calculation formula. There is only a reward (feedback).
The feedback is delayed and cannot be reflected immediately.
The input during training is time-series related.
The action taken by the agent (decision maker) will affect the subsequent data.
What we are going to do now is:

Obtain an optimal strategy (jumping timing) for a specific problem (jumping as far as possible).
Maximize the reward (score) obtained under this strategy.
Here, the strategy is actually a series of actions (sequence data).

## Conclusion:
Summary of the overall findings and conclusions drawn:

- We can see at which day which stock can be bought and sell at which rate, about total assets and about profit levels.
- Also by plotting output with up and down arrow, it is easy to visualize about prediction.


Future work or improvements to be considered:

- More extensive EDA

## References:
Any external sources or references used during the assignment:

- Kaggle dataset and sample code reference.


**Note:** 
- For any queries or clarifications, feel free to contact shivanshjain3333@gmail.com.
