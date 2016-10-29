# Stock Market Predictor - In Progress
Stock market prediction in this capstone project is treated as a classification problem, where the objective is to predict whether the cumulative returns of a stock over a period of one day will be greater than zero (up) or smaller (down). The final algorithm has to return (1) the predicted label and (2) a confidence level. 

The final classification algorithm will be used in a long/short equity trading strategy. Using a ranking scheme based on both the predicted label and the algorithms confidence the strategy goes long (buys) the top x% of equities of the ranking and goes short (sells) on the bottom x% of the ranking, while maintaining equal dollar volume between the long and short position (Granizo-Mackenzie). The implementation of the machine learning algorithm is out of the scope of this capstone project, yet relevant for the evaluation metric.
## Installation & Contribution
After cloning the repository you can open the Stock Market Prediction v2 Jupyter Notebook. Since this is a personal project for Udacity contributions won't be accepted at this point.
