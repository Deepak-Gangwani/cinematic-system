# CINEMATIC MOVIES PREDICTION SYSTEM
![About-page-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/d6586b48-b571-48c3-8f74-6e57efa0b3bf)
### Download Complete Code Using the Given URL: https://drive.google.com/file/d/1GhrsHxXKL4HDXKjONunWU9_4el7WqSCR/view?usp=sharing 
### (Git LFS is not working due to limited bandwidth size in the free version of GitHub, so I have uploaded the complete project on Google Drive. You can download and run it on your local system.)
![Home-page-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/327abfec-6c27-4347-8095-d0b39f9b7f8c)

# Problem Statement :
The primary objective of this project is to develop a predictive model for movie success based on various factors such as genre, cast, director, budget, release date, and social media buzz. 
By accurately forecasting the success of movies, this predictive model empowers production companies to focus their resources more effectively and increase the likelihood of achieving commercial success.

# DATASET:
The dataset is taken from Kaggle site. You can download the dataset from: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
![Movie-details-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/0cd4de4a-e0f6-42f4-8e52-23f47ef6ada0)

# APPROACH :
Data is collected from kaggle site. All the required tasks to prepare the data for model buliding such as data cleaning, pre-processing, data exploration,visualisation were done.
##### 1.Data exploration: Exploring the dataset using pandas, numpy, matplotlib, plotly and seaborn.
![step-1](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/401a3f3e-124d-4840-a0b0-cf6f9a1903d0)

##### 2.Exploratory Data Analysis : Plotted different graphs to get more insights about dependent and independent variables/features.
![step-2](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/84899f2f-e1a9-479b-815d-3c792c6c055f)

##### 3.Feature Engineering : There are numerical and categorical features are present. Scaling was performed on numerical data and encoding of categorical data is done.
```
 import ast 
 ast.literal_eval(obj)
```
![step-3](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/985209b3-9d11-4949-acbc-0e5133d30beb)

##### 4.Model Building : Text Vectorization Process Will Be Done After Filtering All the Dataset.

 	 - Whichever the strings in tags who are having the closest vector rate they can be considered as similar type of movie which can be recommended
 	 - For converting text into vectors their are many methods like:-1)Bag Of Words, 2)tfidf, 3)word to vec
 	 - But I will use bag of words which is more simpler compare to other vector methods
 	 - In this method I will seperate those tags in which the maximum times particular word is repeated
 	 - Finding the 5000 words which is repeated maximum times.

##### 5.Stemming Method Using NLTK :  Applying steming method which convert the singular and plural words into one word
```
 Examples
 Before:-["loved","loving","love"]
 After:-["Love","love","love"]
```
![step-4](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/1fa18214-4331-4268-810e-f3aa72661b06)

##### 6.Distance Metrics: Creating a method to calculate the cosine distance between every movie which get compared
```
 from sklearn.metrics.pairwise import cosine_similarity
 similarity=cosine_similarity(vectors)#this will check the 4806 times similarity between every single movie
 similarity
```
![step-5](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/a0a8fa38-f68b-4614-b13e-4f342a082dd9)

##### 7.Pickle File : Selected model as per best vector points & similarity using distance metrics created pickle file using pickle library.
##### 8.Webpage & Deployment : Created a web application using python with django framework that takes all the necessary inputs from the user & shows the output. The project prototype is in streamlit with the given url repository that is https://cinematic-recommender-system-8r76gvfmxymapuae5dgbru.streamlit.app.

![movie-prediction-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/8d08888c-5deb-4475-a54a-0d095a9db157)

## Search Any Favourite Movie
![search-page-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/bf1404bc-dc28-4b40-b691-34a06fa7f36f)

## Recommendation Inside Recommendation Approach 
![recursive-recommendation-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/7e7438b9-d8e7-4c62-bb98-b37cfbe33316)

## Any Queries Contact US with personal chatbot assistant
![team-contact-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/38bc0f81-6919-465f-9a86-d9b7780bb1e5)

## Authentication and Authorization
![chatbot-login-signup-gif](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/c649bd96-bbc3-4071-9b48-6fdd3cff15ca)

## Admin panel to handle dynamic data and users credentials
![admin-panel](https://github.com/Deepak-Gangwani/iNeuron-internship-project/assets/108722554/57290cbc-b237-4a5d-8543-e59397e915f1)


# LIBRARIES USED:
1) Pandas
2) Numpy
3) NLTK (Natural Language Toolkit)
4) AST (Abstract Syntax Tree)
5) Pickle, Matplotlib, Seaborn
6) Scikit-Learn


# TECHNICAL ASPECTS:
1) Python with Django Framework
2) The MovieDB API
3) Language Selector
4) Attractive Color Palette Theme
5) Real Time Production Level Of Coding
6) HTML5
7) CSS3
8) JS & jQuery
9) Bootstrap
10) Sqlite
11) Authorization & Authentication Features using login and register
12) Admin panel to handle users




