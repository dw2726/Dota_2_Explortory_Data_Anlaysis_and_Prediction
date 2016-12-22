# Dota_2_Explortory_Data_Anlaysis_and_Prediction

Dataset: downloaded from https://www.kaggle.com/devinanzelmo/dota-2-matches, including hero_names.csv, player_ratings.csv, players.csv, test_play.csv, test_labels.csv, match.csv. 

Codes:

1. Data Cleaning.R attaches label indicating win or lost to the player data. 

2. HeroRecommendation APP.R, Player's Performance APP.R, Prediction App.R integrate hero recommendation, player's performance evaluation and match outcome prediction into a single shiny useful app. 

3. PredictionModelTrain.R trains a model for match outcome prediction in the above app, while the resulting model is stored as prediction_logit.rds in the repo.

4. SynergySuppressionMatrixCompute.R is used to compute the node file and edge files for the IBM System G Visualizer to run.
 

