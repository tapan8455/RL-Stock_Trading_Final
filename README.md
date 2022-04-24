# RL-Stock_Trading_Final
It's implementation of Reinforcement Learning applied to (short-term) stock trading. The model uses n-day windows of closing prices to determine if the best action to take at a given time is to buy, sell or sit.

The code used in the pynb file uses code from various sources.
The Sources are :
1.	https://www.analyticsvidhya.com/blog/2021/01/bear-run-or-bull-run-can-reinforcement-learning-help-in-automated-trading/
2.	https://github.com/edwardhdlu/q-trader
3.	https://github.com/llSourcell/Q-Learning-for-Trading
4.	https://towardsdatascience.com/creating-a-custom-openai-gym-environment-for-stock-trading-be532be3910e
5.	https://github.com/AminHP/gym-anytrading
6.	https://arxiv.org/pdf/1811.07522.pdf?ref=https://githubhelp.com
7.	https://github.com/tatsath/fin-ml/blob/167b1933328992e8de3273996135c99145e68f3e/Chapter%209%20-%20Reinforcement%20Learning/Case%20Study%201%20-%20Reinforcement%20Learning%20based%20Trading%20Strategy/ReinforcementLearningBasedTradingStrategy.ipynb

The training results from the code are good and has not been tested on a new data.
To run the code, you can just download the pynb file and run it.
The window size and the episode count can be changed accordingly.

Problems:
There are much more buy actions than sell actions and the exact reason for this is not known to me.

A much better model is used in the following file:
https://colab.research.google.com/drive/10owEaEzkUFDw5TZkYRLyJTKd0M33BsFd?usp=sharing

