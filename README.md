# CINEMATIC MOVIES PREDICTION SYSTEM
![About-page-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/d6586b48-b571-48c3-8f74-6e57efa0b3bf)
### Download Complete Code Using the Given URL: https://drive.google.com/file/d/1GhrsHxXKL4HDXKjONunWU9_4el7WqSCR/view?usp=sharing 
### (Git LFS is not working due to limited bandwidth size in the free version of GitHub, so I have uploaded the complete project on Google Drive. You can download and run it on your local system.)


# Problem Statement :
The primary objective of this project is to develop a predictive model for movie success based on various factors such as genre, cast, director, budget, release date, and social media buzz. 
By accurately forecasting the success of movies, this predictive model empowers production companies to focus their resources more effectively and increase the likelihood of achieving commercial success.

# DATASET:
The dataset is taken from Kaggle site. You can download the dataset from: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

![Home-page-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/327abfec-6c27-4347-8095-d0b39f9b7f8c)

# APPROACH :
Data is collected from kaggle site. All the required tasks to prepare the data for model buliding such as data cleaning, pre-processing, data exploration,visualisation were done.
##### 1.Data exploration: Exploring the dataset using pandas, numpy, matplotlib, plotly and seaborn.
##### 2.Exploratory Data Analysis : Plotted different graphs to get more insights about dependent and independent variables/features.
##### 3.Feature Engineering : There are numerical and categorical features are present. Scaling was performed on numerical data and encoding of categorical data is done.
```
 import ast 
 ast.literal_eval(obj)
```
##### 4.Model Building : Text Vectorization Process Will Be Done After Filtering All the Dataset.
```
 	 Whichever the strings in tags who are having the closest vector rate they can be considered as similar type of movie which can be recommended
 	 For converting text into vectors their are many methods like:-1)Bag Of Words, 2)tfidf, 3)word to vec
 	 But I will use bag of words which is more simpler compare to other vector methods
 	 In this method I will seperate those tags in which the maximum times particular word is repeated
 	 Finding the 5000 words which is repeated maximum times.
```
##### 5.Stemming Method Using NLTK :  Applying steming method which convert the singular and plural words into one word
```
 Examples
 Before:-["loved","loving","love"]
 After:-["Love","love","love"]
```
##### 6.Distance Metrics: Creating a method to calculate the cosine distance between every movie which get compared
```
 from sklearn.metrics.pairwise import cosine_similarity
 similarity=cosine_similarity(vectors)#this will check the 4806 times similarity between every single movie
 similarity
``` 
##### 7.Pickle File : Selected model as per best RMSE score & R-squared and created pickle file using pickle library.
##### 8.Webpage &Deployment : Created a web application using streamlit API that takes all the necessary inputs from the user & shows the output. Then deployed project on the Heroku Platform.

![Movie-details-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/0cd4de4a-e0f6-42f4-8e52-23f47ef6ada0)
![movie-prediction-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/8d08888c-5deb-4475-a54a-0d095a9db157)
![search-page-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/bf1404bc-dc28-4b40-b691-34a06fa7f36f)
![recursive-recommendation-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/7e7438b9-d8e7-4c62-bb98-b37cfbe33316)
![team-contact-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/38bc0f81-6919-465f-9a86-d9b7780bb1e5)
![chatbot-login-signup-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/c649bd96-bbc3-4071-9b48-6fdd3cff15ca)







# LIBRARIES USED:
1) Pandas
2) Numpy
3) NLTK (Natural Language Toolkit)
4) AST (Abstract Syntax Tree)
5) Pickle, Matplotlib, Seaborn
6) Scikit-Learn


# TECHNICAL ASPECTS:
1) Python with Django Framework 
2) HTML5
3) CSS3
4) JS & jQuery
5) Bootstrap
6) Sqlite
7) Authorization & Authentication Features using login and register
8) Admin panel to handle users




