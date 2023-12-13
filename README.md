# Machine Learning Trading Bot

![Decorative image.](Images/14-challenge-image.png)

Now, it's time to take what you've learned about machine learning and apply it to new situations. For this optional assignment, you'll create an algorithmic trading bot that learns and adapts to new data and evolving markets. Be sure to give it your all -- as the skills you hone will become powerful tools in your FinTech tool belt.

## Background

In this Challenge, you’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Your firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, your firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave your firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data.

## What You're Creating

You’ll combine your new algorithmic trading skills with your existing skills in financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets.

In a Jupyter notebook, you’ll do the following:

* Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.

* Adjust the input parameters to optimize the trading algorithm.

* Train a new machine learning model and compare its performance to that of a baseline model.

As part of your GitHub repository’s `README.md` file, you will also create a report that compares the performance of the machine learning models based on the trading predictions that each makes and the resulting cumulative strategy returns.

# What impact resulted from increasing or decreasing the training window?

## Answer:
When increasing the training window to six months it was more accurate with 56% accuracy, 98% recall, and the strategy returns improved to 1.8. The classification report and graph shows a six month training window.


<img width="436" alt="baseline classification report-3month" src="https://github.com/carebear4ever/Machine_Learning_Trading_Bot/assets/141070883/3010f686-b64f-47df-8a02-bf5fda37e531">

<img width="567" alt="base line-3month cumulative return graph" src="https://github.com/carebear4ever/Machine_Learning_Trading_Bot/assets/141070883/8e1468a4-630e-462b-b3bd-4b36ae8bf03e">


# What impact resulted from increasing or decreasing either or both of the SMA windows?

## Answer:
Short window being 4 and increasing the long window to 200 made the accurancy decrease from 56% to 53% and made the strategy returns decrease to 1.4 making actual returns higher. This classification report and graph shows a short window of 4 and a long window of 200.

<img width="431" alt="baseline 4-200 classification report" src="https://github.com/carebear4ever/Machine_Learning_Trading_Bot/assets/141070883/3ad39bf5-8e45-45e1-99ac-c1f7906293b0">

<img width="572" alt="baseline 4-200 graph" src="https://github.com/carebear4ever/Machine_Learning_Trading_Bot/assets/141070883/3418462d-57df-4867-865a-1fdec8354772">

Making the short window 10 and the long window 100 made the accurancy go back to 56%, but this made actual returns higher at 1.6 than strategy returns being at 1.4. This classification report and graph shows a short window of 10 days and a long window of 100 days.

<img width="440" alt="baseline classification report 10-100" src="https://github.com/carebear4ever/Machine_Learning_Trading_Bot/assets/141070883/a9367e04-6554-4c8e-b7ad-cd50534dbb46">

<img width="561" alt="baseline graph 10-100" src="https://github.com/carebear4ever/Machine_Learning_Trading_Bot/assets/141070883/ae693130-bf41-45bc-a09f-302204b87104"> 

# Choose the set of parameters that best improved the trading algorithm returns.

## Answer: 
Increasing the training widow to 6 months showed better results than a training window of 3 months.

# Did the new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?

The logistic regression new model performed worse than the baseline model the strategy returns decreased. This is the classification report and graph for the new model.

<img width="436" alt="new model classification report" src="https://github.com/carebear4ever/Machine_Learning_Trading_Bot/assets/141070883/ae6fc800-a747-49dc-8367-b0bc1f59aeba">

<img width="595" alt="new model graph" src="https://github.com/carebear4ever/Machine_Learning_Trading_Bot/assets/141070883/f86d6e3e-e8a8-4403-bf26-5f0ef66b2d2a"> 

The new model performed worse with 6 month training window. The actual returns and strategy returns did not go higher than 1.6. This is the new models classification report and graph for 6 month training window.

<img width="446" alt="new model classification report 6 months" src="https://github.com/carebear4ever/Machine_Learning_Trading_Bot/assets/141070883/d08da090-ecb4-4a96-90d0-15779373e7a4">

<img width="575" alt="new model graph 6 months" src="https://github.com/carebear4ever/Machine_Learning_Trading_Bot/assets/141070883/165451c7-d76b-410e-824a-7eda9991d5cf">

# Evaluation Report
## Increasing the dateoffset training window to six months with a short window of 4 and a long window of 100 performed the best. The model had the highest accuracy being 56% and the highest strategy returns being 1.8. The overall classification report and graph improved. 

<img width="424" alt="baseline classification report 6 months" src="https://github.com/carebear4ever/Machine_Learning_Trading_Bot/assets/141070883/8ef62474-57bc-4528-8c24-1c5a9b7efb5a">

<img width="595" alt="baseline graph 6 months" src="https://github.com/carebear4ever/Machine_Learning_Trading_Bot/assets/141070883/a1c87d71-539b-424a-af59-506e4f298ea1">
