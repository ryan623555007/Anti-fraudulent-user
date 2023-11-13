# Anti-fraudulent-user
  Telephone sales are continuously increasing during this pandemic period. Meanwhile, there are more and more harassing calls. I used machine learning algorithms to recognize harassers and push reminders to users’ mobile phones.<br>
  I first used XGBoost to classify harassers, service centers, express-men, and personal users. The training set has 100 million samples and each sample has 200 features including geographic trajectories, personal information and so on. After tuning hyper-parameters, the XGBoost classifier got 90.81 F1 score.<br>
  In order to further improve the performance, I ensembled LGBoost and Random Forest with XGBoost via stacking.<br>
  The experiential result indicated that our ensemble model outperforms single model by 5.72<br>
  In this this solution, I can't upload metadata because it's confidential<br>
