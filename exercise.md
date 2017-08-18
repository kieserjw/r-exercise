# Exercise

## Introduction
Attached is a reduced set of data, consisting on various tables:

* *dataset_emails*: One row per email, represents an email of a person that signed up to Auth0 on https://auth0.com
* *dataset_pageviews*: One row per combination of url group and email, represents the # of visits of each email to a specific page group.
* *dataset_tenants*: One row per tenant, it's the account entity we use in Auth0 when you signup, other admins (emails) can be invited to the same tenant
* *dataset_relations*: One email can be associated with many tenants, and one tenant with many emails, so this is the relationship table that tells you which tenants are associated with which emails

This is real data from all emails signed up on July, but without any PII involved.

## Requirements

You need to use R to solve this exercise, it's recommended to use R Studio to work on the solution.

Recommended packages:

* dplyr - General data wrangling
* tidyr - Data reshaping
* ggplot2 - One of the best charting libraries, very flexible

To load the data, execute:
load('exerciseData.rda')

## Exercise

We want to analyze our customer data, and better understand them.

Please identify:

* ~~The top 10 countries by active enterprise users~~
* ~~The top 10 operating systems by open and total tickets~~
* ~~The distribution of pageviews per group~~
* ~~The distribution differences on pageviews per login method~~
* ~~What differences do you find between developers and non-developers?~~
* ~~What are the most and least used technologies in tenants?~~
* ~~Please mark any inconsistencies you find in the data that you'd research further if you were working at Auth0~~
* Create at least 3 visualizations using R which you consider interesting for the provided data

Please create an R script which can be re-executed for this exercise, and post any doubts you may have in Slack.
Happy data wrangling!
