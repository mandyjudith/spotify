# Spotify Music Genre Classification
![Screenshot 2021-05-17 at 3 56 16 PM](https://user-images.githubusercontent.com/77132971/118453053-5efb4600-b729-11eb-8dbc-1700e6a724f0.png)

## Project Overview
Spotify is the world’s biggest music streaming platform by a significant proportion 
Among the goals for our project, we want to create a new genre that softens the boundary between existing genres - allowing customers from fringe groups to transition into listening to a broader choice of music.
From analyzing the data we have gathered on the more niche genres of music streamed by our customers: 
we have made a proposition in diversifying existing genres and again attracting  people with all kinds of music preferences.

## Data Collection & Preprocessing
### Dataset of songs in Spotify

The [Dataset of songs in Spotify](https://www.kaggle.com/mrmorj/dataset-of-songs-in-spotify) contains the full list of genres included in the CSV are Trap, Techno, Techhouse, Trance, Psytrance, Dark Trap, DnB (drums and bass), Hardstyle, Underground Rap, Trap Metal, Emo, Rap, RnB, Pop and Hiphop.

![countplot](https://user-images.githubusercontent.com/77132971/118456072-cc0fdb00-b72b-11eb-9f13-f9979ba46b82.png)
![heatmap](https://user-images.githubusercontent.com/77132971/118458551-76d4c900-b72d-11eb-8557-a6564bf5623b.png)


Data Preprocess:
1. CHECK FOR MISSING DATA & VISUALIZATION
2. DROP UNNECESSARY COLUMNS
3. REMOVE THE OUTLIER
4. HANDLING WITH THE IMBALANCED DATA
5. FEATURE SCALING
6. SPLIT TRAIN / TEST DATA

<img src="https://user-images.githubusercontent.com/77132971/118458865-bbf8fb00-b72d-11eb-96a4-975d2d1733f3.jpg" width="400"/> <img src="https://user-images.githubusercontent.com/77132971/118458967-d6cb6f80-b72d-11eb-9017-eeaa6e6b48ce.jpg" width="350"/> 


## Models Creation
### Find out the important features
![Treevisualization](https://user-images.githubusercontent.com/77132971/118460628-750c0500-b72f-11eb-826c-6ba90b038b8a.jpg)

![features](https://user-images.githubusercontent.com/77132971/118460892-b13f6580-b72f-11eb-9e0e-e1e4dd81f413.png)

## Model Evaluation
We have adopted 6 machine learning models for training and predicting the genre.
XGBoost give out the best performance.


![comparison](https://user-images.githubusercontent.com/77132971/118459455-59542f00-b72e-11eb-907e-9db5f043a8ad.png)


## Model Tunning
1. SMOTE - for imbalance data handling
2. Drop/add value
3. Hyperparameter Tuning




## Conclusion
All of the model are showing an average accuracy of 60-70%.
It gives us an opportunity to give the genre a bigger spectrum.



