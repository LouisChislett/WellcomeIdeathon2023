# README
This is a copy of the submission of the "Social Scientists" team submission to the Wellcome Ideathon 2023. I was team leader for this project, which included organising team roles, leading meetings and writing a significant chunk of the code.

The majority of this code consists of a pipeline for building an app which allows for analysis of the sentiments and content of tweets about COVID-19 vaccines, making heavy use of Natural Language Processing (NLP) in python and R. In order to view the app, simply run the [Shiny App](https://github.com/LouisChislett/WellcomeIdeathon2023/blob/main/code/shiny_app.R).

It also contains the associated powerpoint presentation which was made as part of the competition entry.

## What is the prototype?
We have made a public facing app which predicts the probability of tweets being COVID-19 vaccine misinformation, and outputs various visualisations related to where and how this misinformation is occurring for a chosen time period. This is to be treated as an interactive dashboard by policy-makers.
Sentiment Analysis, Named Entity Recognition and Topic Modelling were used to generate an appropriate feature set for subsequent models

We also designed the app to run in parallel to a hypothetical survey on vaccine attitudes among unvaccinated people, such that future attitudes can be predicted from current misinformation.

Credit also goes to:
Yanan Ma - University of Manchester
Jose Benitez Aurioles - University of Manchester
Steven Wambua - University of Birmingham
