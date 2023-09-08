---
layout: archive
title: "Personal Projects"
permalink: /personal-projects/
author_profile: true
---

## Sports Betting Predictor Model

![Model logo](/images/nba-model-pic.PNG){:width="350px" height="200px"} 

### Project Overview
I developed a machine learning sports betting predictor focused on optimizing player bet predictions based on past game performances. This project was primarily to assess the model's theoretical performance rather than for profit generation.

Currently, there exists a wide disparity between the casual fans betting on players and betting sportsbooks that derive live betting lines from a variable number of parameters kept undisclosed to the public eye, positioning these betting firms to win more money from bettors. Hence, my aim was to harness data to sharpen these edges by optimizing bet predictions. 

### Data Collection & Preprocessing
I aggregated expert predictions from sports betting websites that publish daily predictions using their proprietary analyzers and harnessed their outputs as inputs to my optimizer, further capitalizing on their existing backed predictions. With past game statistics from the ongoing season scraped from online box scores, I conducted extensive data processing and cleaning to develop a `daily statistics evaluator` for determining whether a player achieved the bet prop's threshold and a `real-time prediction scraper` to produce my model's insights before game times.

### Model Optimization
To optimize the predictions:

1. **Ensemble Learning**: I employed diverse ML models (logistic regression, LDA, KNN, Gaussian NB, SVM, MLP, decision trees and forests, AdaBoost, gradient boosting) to create an ensemble based on expert predictions. This considered features like past expert success rate, specified stat type, betting odds, and more.
2. **Multiplicative Weights Algorithm**: I integrated the multiplicative weights algorithm where each ML model (MLP, DNN, RF, XGB, LSTM, and the aforementioned Online Experts Ensemble Learning) acts as its own expert. They predict player stats using advanced features, and these predictions are weighted based on their past accuracy, rewarding the “model experts” closer to the true player performance and penalizing those that are not and ensuring adaptive, data-driven decisions that combine the collective intelligence of all models.

### Results
While an "educated" bettor generally achieves around a 50% success rate on NBA bets to truly generate a profit (and casual bettors having even lower success rates), my model demonstrated an overall best accuracy of 61% for the 2022-23 NBA season with other varying strategies spanning from 54-60% accuracy. It's important to note, however, that these results come with the underlying consideration of variability with the volume of bets.

[🏀 2022-23 NBA Season Model](https://github.com/arnavsinghvi11/NBA_Betting_Model)

------------------------------------------------------------------------------------------------------------------------

MLB betting is a unique challenge. In a sport where a batter is considered exceptional hitting once every three at-bats, there's inherent unpredictability throughout the 162-game season. Even professional bettors often achieve success rates of around 40% but can still turn a profit. For the 2023 season, my updated MLB framework has a peak accuracy rate of 49%. However, this current model doesn't yet include the multiplicative weights algorithm, which is in development and offers the possibility of even greater accuracy.

[⚾ 2023 MLB Season Model](https://github.com/arnavsinghvi11/MLB_Betting_Model)

------------------------------------------------------------------------------------------------------------------------

Stay tuned for the upcoming 🏈 2023-24 NFL Season Model!