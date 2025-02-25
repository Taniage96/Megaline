# Megaline Plan Recommendation Project

## Project Description

Megaline, a mobile carrier company, is dissatisfied with the number of its customers using legacy plans. They aim to develop a model that can analyze customer behavior and recommend one of the new Megaline plans: Smart or Ultra.

You have access to subscriber behavior data from customers who have already switched to the new plans (from the Statistical Data Analysis sprint project). For this classification task, you need to build a model that selects the correct plan. Since you've already processed the data, you can dive straight into model creation.

Develop a model with the highest possible accuracy. In this project, the accuracy threshold is 0.75. Use the dataset to check the accuracy.

## Data Description

Each observation in the dataset contains monthly behavior information about a user. The provided information is as follows:

* `calls` — number of calls
* `minutes` — total call duration in minutes
* `messages` — number of text messages
* `mb_used` — Internet traffic used in MB
* `is_ultra` — plan for the current month (Ultra - 1, Smart - 0)
