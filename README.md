## Starbucks

## Introduction
As a part of the couse of [Udacity](https://www.udacity.com/), Data Science Nanodegree, I work on data sets which is kindly given by [Starbucks](https://www.starbucks.com/) for the purpose of this course. This page is a summary of my findingns, if interested, code is [here](https://github.com/wythe0513/Starbucks).

## File Description
1. profile.json

> Rewards program users (17000 users x 5 fields)

> gender: (categorical) M, F, O, or null
age: (numeric) missing value encoded as 118
id: (string/hash)
became_member_on: (date) format YYYYMMDD
income: (numeric)

2. portfolio.json

> Offers sent during 30-day test period (10 offers x 6 fields)

> reward: (numeric) money awarded for the amount spent
channels: (list) web, email, mobile, social
difficulty: (numeric) money required to be spent to receive reward
duration: (numeric) time for offer to be open, in days
offer_type: (string) bogo, discount, informational
id: (string/hash)

3. transcript.json

> Event log (306648 events x 4 fields)

> person: (string/hash)
event: (string) offer received, offer viewed, transaction, offer completed
value: (dictionary) different values depending on event type
offer id: (string/hash) not associated with any "transaction"
amount: (numeric) money spent in "transaction"
reward: (numeric) money gained from "offer completed"
time: (numeric) hours after start of test

## Results

Findings is [here](https://gitpress.io/u/1402/Starbucks)

## Acknoledgements
Must give credit to Sturbacks for this opportunity and data