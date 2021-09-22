# Starbucks Project
The purpose of this project to identify how demographic groups correlates to specific offer types. Based on this knowledge, create a ML model to predict how existing offer types suits for customer needs.

## Installations
In oder to use this ode, please install python libraries:

`pip install numpy`  
`pip install pandas`  
`pip install matplotlib`  
`pip install pickle`  
`pip install sklearn`  
`pip install plotly`
`pip install seaborn`

If you are using Udacity Conda platform, please update environment in terminal: `conda create -n myenv python=3.6`

## Project Motivation
In this day and age, the customers' satisfaction score is #1 for a good business performance. It is especially interesting case for me, because I can be either a customer or a business owner. As a customer want to know how modern technologies could satisfy my needs. As business owner, I will know how to predict customers needs and provide them good offers..

## Data Dictionary
* profile.json - Rewards program users (17000 users x 5 fields)
gender: (categorical) M, F, O, or null
age: (numeric) missing value encoded as 118
id: (string/hash)
became_member_on: (date) format YYYYMMDD
income: (numeric)

* portfolio.json - Offers sent during 30-day test period (10 offers x 6 fields)
reward: (numeric) money awarded for the amount spent
channels: (list) web, email, mobile, social
difficulty: (numeric) money required to be spent to receive reward
duration: (numeric) time for offer to be open, in days
offer_type: (string) bogo, discount, informational
id: (string/hash)

* transcript.json - Event log (306648 events x 4 fields)
person: (string/hash)
event: (string) offer received, offer viewed, transaction, offer completed
value: (dictionary) different values depending on event type
offer id: (string/hash) not associated with any "transaction"
amount: (numeric) money spent in "transaction"
reward: (numeric) money gained from "offer completed"
time: (numeric) hours after start of test

## Story
You can read my artickle about this project on [Medium.com](https://best-mahogany-dolphin-856.medium.com/starbucks-project-18d8fb8dd85)

## Contact:
LinkedIn: https://www.linkedin.com/in/alexey-smirnov-4339322b
