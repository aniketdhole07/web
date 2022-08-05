---
title: 'Two Way Sign Language Translate'
date: December 2020
date_display: "December 2020"
featured_image: '/images/trans.png'
excerpt: Desktop App to Translate Sign Language from Voice to Sign and Vice Versa using Computer Vision. 
---

## Inspiration
There are 466 million persons in the world with disabling hearing loss (6.1% of the world's population) , I have created this app for them and their family so that they can communicate easily. This will allow a person with hearing loss and person who doesn't knows Sign language to communicate to each other easily. We were also inspired from Hana's ASL workshop.

## What it does
It can do two things:

1. Take Voice from User and Convert it to Sign Language in form of a GIF
2. It will Take Video from User and convert the Sign Language in Video to Voice using Machine Learning

## How we built it
We divided the project into two parts

### VOICE/TEXT TO SIGN LANGUAGE CONVERSION:
1. Scraping Data from Giphy using Chrome Extension
2. Then filtered the gif files and added names to it
3. Also added gif files of single alphabets
4. Took Voice/Text input from user and split into words and checked if it is present in the GIF filenames. If it is not present then use the Alphabet GIFs for making up words
5. Finally Displayed it onto Tkinter App


![](/images/trans1.png)



### SIGN LANGUAGE TO VOICE/TEXT CONVERSION:
1. Used the ASL Dataset on Kaggle of Alphabets
2. Created a CNN algorithm in Tensorflow and trained the model for small data
3. Used Live Webcam feed of user hand and predicted the Alphabet from a Region of Interest
4. Finally Displayed it onto Tkinter App


![](/images/trans2.png)

## Challenges we ran into
1.Tried using Scrapy and Selenium to scrape the Gif files but were unsuccessful
2. Creating GUI on Tkinter was hard as we were using it for first time

## Accomplishments that we're proud of
1. Successfully created a Multifeatured Desktop App
2. Got Accuracy of 95% in predicting Sign Language

[Project Page](https://devpost.com/software/two-way-sign-language-translate)
