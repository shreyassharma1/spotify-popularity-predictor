# spotify-popularity-predictor

Machine learning project that predicts track popularity for hip-hop music. Trained on custom playlist. 
Input features include audio features, segment analysis, and timbre vectors from the Spotify API, web-scraped early life info from wikipedia, and lyrics from MusixMatch API.
Visualizations: correlation heatmap and wordcloud. 
Preprocessing: OneHotEncoding, tested a variety of scalers, and used TF-IDF Vectorizer on textual data. 
Model Selection & Hyperparamater tuning: Tested various models and conducted hp tuning using GridSearchCV. 
Evaluation: Cross-validation as well as predicting popularity of friend's up-and-coming rap song!

Attribution: Co-created this project with my friend Ishvi. 
