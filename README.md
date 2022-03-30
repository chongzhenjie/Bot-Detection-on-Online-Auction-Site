# Bot Detection on Online Auction Site - Kaggle
Contributors: [Chong Zhen Kang (Shane)](https://github.com/shaneczk) & [Chong Zhen Jie](https://github.com/chongzhenjie)

<br>
Source: https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot/overview

Notebook shared on Kaggle at: https://www.kaggle.com/chongzhenjie/human-or-robot/notebook
<br>
<br>

### Machine Learning Project: Predict if an online bid is made by a machine or a human

* Analyzed dataset (same dataset used by Facebook in its Kaggle Recruiting Competition) of more than 7 million online auction bids to identify bids placed by robots <br>
* Carried out feature engineering, performed over-sampling on imbalanced data, and built ensemble models to maximize ROC AUC score <br>
* Achieved 0.93488 ROC AUC score on Private Leaderboard, scored on hidden test data <br>
<br>

### Model Validation Summary
![download](https://user-images.githubusercontent.com/77932796/149770234-95b71773-5568-4f9a-b4a5-f0e8d293c5f5.png)

It is evident that hyperparameter tuning reduced the variance of ROC AUC scores as indicated by the spread of the green and red curves. Also, the ROC AUC score for tuned ensemble average of random forests (red vertical line) is more likely to be higher compared to the 3 other models, as seen by the vertical line indicators of their respective peaks.
