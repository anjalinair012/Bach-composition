# Bach-composition
The project aims at completing the bach composition using Machine learning. We use the hidden markov model, a statistical approach in performing this task.
Two approaches have been taken.Approach 1 is a theme based approach and approach 2 is a chord based one. The results from our models are presented as mp3 files. 
Around 25 second of the composition has been predicted.
F.txt-dataset
Themes_approach.py - model 1 based on themes
model_themes.mid/model_theme.mp3 - music file for model 1 predictions
model_themes.csv - the predictions made by model 1
model2 - model 2 based on chords
model2_highRand.mid/model2_highRand.mp3 - music file for model 2 prediction for a run with high Randomness
model2_mediumRand.mid/model2_mediumRand.mp3 - music file for model 2 prediction for a run with medium Randomness
model2_lowRand.mid/model2_lowRand.mp3 - music file for model 2 prediction for a run with low Randomness
In case of model 2 , we have high low and medium randomness. These indicate how random the prediction for V4 is.
