---
title        : Filtering joins and set operations
description  : Filtering joins and Set operations combine information from data sets without adding new variables. Filtering joins filter the observations of one data set based on whether or not they occur in a second data set. Set operations use combinations of observations from both data sets to create a new data set. 

--- type:VideoExercise lang:python xp: skills: key:9ea13f011f
## Semi-joins 
Have you ever tried to filter data based on the combination of many variables. You could try to do this with `filter()`, but it will be much easier with a semi-join.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:517b1d6a59
## Semi-join 
Return just the rows of X that we have Y information for

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:1a42a5cea0
## Semi-join 2 
Do any of the rows in X match any of the rows in Y?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:MultipleChoiceExercise lang:python xp: skills: key:935e495fa9
## A more precise way to filter? 
We've attempted to rewrite this semi-join as a filter. Will it return the same results?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:77d56b6574
## Anti-joins 
Anti-joins do the opposite of semi-joins, they show which rows do not have matches. Anti-joins are a convenient way to check for errors before they occur.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:5f24562826
## Anti-join 
Which rows of X do we not have Y information for?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:7c5fb0032a
## Anti-Join 2 
Were any of the keys of X mis-entered? Use an anti-join to check

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:34c3fcba02
## Which filtering join? 
Use a filtering join to determine how many matches exist between X and Y

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:863bede8cd
## Set Operations 
Set operations include union(), intersect() and setdiff(). They let you group observations from two data sets into a new data set.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:77752d93e0
## Union 
How many unique observations are there in these two data sets?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:a3c8365020
## Intersection 
How many observations are shared between these two data sets?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:7f0d2c5bca
## Setdiff 
Which observations are in X but not Y?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:0d6c65c303
## Operations 
Combine union and setdiff operations to return all of the observations that are in one data set, but not the other.

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:MultipleChoiceExercise lang:python xp: skills: key:b18a081365
## Unique values 
Will the result of this union statement contain fewer rows than the original data set? That would seem paradoxical.

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:e2ed3129ae
## Comparing data sets 
Use setequal or all.equal to check whether two data sets contain of the same observations.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:1a4449415d
## setequal 
Does the second data set contain any new information?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:acd19c72d4
## setequal 
Write a filtering join that would also check if the second data set contains new information?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}
