# Classic-Housing-Price-Challenge
The laboratory from Algorithmic Machine Learning Course at EURECOM

This repository included the Music Recommendation System Laboratory from the Algorithmic Machine Learning Course at EURECOM, which was conducted in a group with DANG Ngoc-Vien (Ngoc-Vien.Dang@eurecom.fr).

Furthermore, the Algorithmic Machine Learning Course was offered by Prof. Pietro Michiardi (http://www.eurecom.fr/~michiard/) at EURECOM. The details of the course can be retrieved in here https://github.com/DistributedSystemsGroup/Algorithmic-Machine-Learning

## Course Description
The goal of this course is mainly to offer data science projects to students to gain hands-on experience. It nicely merges the theoretical concepts students can learn in our courses on machine learning and statistical inference, and systems concepts we teach in distributed systems.

Notebooks require to address several challenges, that can be roughly classified in:
- Data preparation and cleaning
- Building descriptive statistics of the data
- Working on a selected algorithm, e.g., for building a statistical model
- Working on experimental validation

## The Laboratory Description
The first AML challenge for this year is adapted from the well-known 'Zillow's Home Value Prediction' competition on Kaggle. In particular, given a dataset containing descriptions of homes on the US property market, your task is to make predictions on the selling price of as-yet unlisted properties. Developing a model which accurately fits the available training data while also generalising to unseen data-points is a multi-faceted challenge that involves a mixture of data exploration, pre-processing, model selection, and performance evaluation.

### The Goals of this laboratory:
Overview
Beyond simply producing a well-performing model for making predictions, in this challenge we would like you to start developing your skills as a machine learning scientist. In this regard, your notebook should be structured in such a way as to explore the five following tasks that are expected to be carried out whenever undertaking such a project. The description below each aspect should serve as a guide for your work, but you are strongly encouraged to also explore alternative options and directions. Thinking outside the box will always be rewarded in these challenges.

**1. Data Exploration**

The first broad component of your notebook should enable you to familiarise yourselves with the given data, an outline of which is given at the end of this challenge specification. Among others, this section should investigate:
- Data cleaning, e.g. treatment of categorial variables;
- Data visualisation;
- Computing descriptive statistics, e.g. correlation.
- etc.

**2. Data Pre-processing**

The previous step should give you a better understanding of which pre-processing is required for the data. This may include:
- Normalising and standardising the given data;
- Removing outliers;
- Carrying out feature selection, possibly using metrics derived from information theory;
- Handling missing information in the dataset;
- Augmenting the dataset with external information;
- Combining existing features.

**3. Model Selection**

Perhaps the most important segment of this challenge involves the selection of a model that can successfully handle the given data and yield sensible predictions. Instead of focusing exclusively on your final chosen model, it is also important to share your thought process in this notebook by additionally describing alternative candidate models. There is a wealth of models to choose from, such as decision trees, random forests, (Bayesian) neural networks, Gaussian processes, LASSO regression, and so on. There are several factors which may influence your decision:
- What is the model's complexity?
- Is the model interpretable?
- Is the model capable of handling different data-types?
- Does the model return uncertainty estimates along with predictions?
- An in-depth evaluation of competing models in view of this and other criteria will elevate the quality of your submission and earn you a higher grade.

**4. Parameter Optimisation**

Irrespective of your choice, it is highly likely that your model will have one or more parameters that require tuning. There are several techniques for carrying out such a procedure, including cross-validation, Bayesian optimisation, and several others. As before, an analysis into which parameter tuning technique best suits your model is expected before proceeding with the optimisation of your model.

**5. Model Evaluation**

Some form of pre-evaluation will inevitably be required in the preceding sections in order to both select an appropriate model and configure its parameters appropriately. In this final section, you may evaluate other aspects of the model such as:
- Assessing the running time of your model;
- Determining whether some aspects can be parallelised;
- Training the model with smaller subsets of the data.
- etc.
