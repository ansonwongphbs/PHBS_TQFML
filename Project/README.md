Kobe's Shot prediction
==== 
Team member:
-------
Yiming(Anson) Wang 1701213111

Backgroud
-------
I guess many of you have ever seen NBA Live. And if you have watch, you must know Kobe Bryant marked his retirement from the NBA by scoring 60 points in his final game as a Los Angeles Laker on Wednesday, April 12, 2016. Drafted into the NBA at the age of 17, Kobe earned the sport’s highest accolades throughout his long career.
Using 20 years of data on Kobe's swishes and misses, we can predict which shots will find the bottom of the net. The method used in this model can not only applied to kobe, which is quite meaningful for super Kobe funs, but also can be applied to can tell the live audience if the shots of other players touch the bottome of the net ahead of time. That will add a lot of interest to the watching process. Further more, using this method, the coach and the players can improve their strategies and training process.

Predictor
-------
My project may involve the following questions: Given the remaining time, shoting time, shoting zone, remaining second, period, etc, what the outcome is.
some features I created by myself

'action_type'

'combined_shot_type'

'season'

'opponent'

'home_game'

'loc_x' : horizontal coordinates of the shot location

'loc_y' : vertical coordinates of the shot location

'shot_distance'

'shot_zone_area'

'game_year'	

'game_month'

'is_last_minute' : whether the shot is made at the last minute of the quarter.

'previous_shot_type' : the type of his previous shot attempt

'previous_shot_made' : whether the previous shot is made



Training model 
-------
Try kernel Ridge Regression/SVM/RandomForest/DecisionTree to choose a better model.

Conclusion

The best model for this project is DecisionTree . 


Dataset description
-------
Kaggle https://www.kaggle.com/c/kobe-bryant-shot-selection 
