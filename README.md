![166883947-24571cd0-a806-47d9-9a00-87f76cd015f9](https://github.com/KushalChakraborty1995/Ted-Talk-Prediction/assets/114491920/638dfebc-8118-4299-8817-323c71be5ca3)

## Ted-Talk-Prediction

## Introduction:-
TED stands for Technology, Entertainment and Design.

A TED talk refers to a recorded public-speaking presentation that was originally given at the main TED (technology, entertainment and design) annual event or one of its many satellite events around the world. TED is a nonprofit devoted to spreading ideas, usually in the form of short, powerful talks, often called "TED talks." These could be a motivational video, awareness, technical, Science entertainment, or any other genre.

TED is devoted to spreading powerful ideas on just about any topic. Founded in 1984 by Richard Salman as a nonprofit organization that aimed at bringing experts from the fields of Technology, Entertainment, and Design together, TED Conferences have gone on to become the Mecca of ideas from virtually all walks of life. As of 2015, TED and its sister TEDx chapters have published more than 2000 talks for free consumption by the masses and its speaker list boasts of the likes of Al Gore, Jimmy Wales, Shahrukh Khan, and Bill Gates.

## Objective:-
The main objective is to build a predictive model, which could help in predicting the views of the videos uploaded on the TEDx website.

## Data description:-
This Dataset consists of following Attributes:

talk_id : Talk identification number provided by TED

title : Title of the talk

speaker_1 : First speaker in TED's speaker list

speakers : Speakers in the talk

occupations : Occupations of the speakers

about_speakers : Blurb about each speaker

views(Dependent Variable) : Count of views

recorded_date : Date the talk was recorded

published_date : Date the talk was published to TED.com

event : Event or medium in which the talk was given

native_lang : Language the talk was given in

available_lang : All available languages (lang_code) for a talk

comments : Count of comments

duration : Duration in seconds

topics : Related tags or topics for the talk

related_talks : Related talks (key='talk_id', value='title')

url URL of the talk

description : Description of the talk

transcript : Full transcript of the talk

## Python Libraries used:-

### Datawrangling and manipulation:

Numpy
Pandas

### Visualization:

Matplotib
Seaborn

### Machine learning Models:

Scikit-Learn

### Others:

datetime
warnings

### Models:-
In this project we are implementing 7 machine learning algorithms to predict the target variable and then we'll apply optimization techniques on the one that gives best resulting accuracy out of all.

Following algorithms have been used for predictions:-

Linear Regression
Lasso Regression
Ridge Regression
Elastic Net Regression
Decision Tree
Random Forest Regression
XGB Regression
## Notable Findings:-

In all these models our errors have been in the range of 2,00,000 which is around 10% of the average views. The model has been able to correctly predict views 90% of the time. After hyper parameter tuning, we have prevented overfitting and decreased errors by regularizing and reducing learning rate. Given that only have 10% errors, our models have performed very well on unseen data due to various factors like feature selection, correct model selection.

After evaluating the performance of all the models, the best model is Random Forest Regressor based on MAE because MAE is linear and robust to outliers.

![istockphoto-1132817705-612x612](https://github.com/KushalChakraborty1995/Ted-Talk-Prediction/assets/114491920/3d07057a-c502-4ac6-b29b-d9594e6fb313)

