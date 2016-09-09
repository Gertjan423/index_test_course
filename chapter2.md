---
title        : Filtering joins and set operations
description  : Filtering joins and Set operations combine information from data sets without adding new variables. Filtering joins filter the observations of one data set based on whether or not they occur in a second data set. Set operations use combinations of observations from both data sets to create a new data set. 

--- type:VideoExercise lang:python xp: skills: key:90c106b0dc
## Semi-joins 
Have you ever tried to filter data based on the combination of many variables. You could try to do this with `filter()`, but it will be much easier with a semi-join.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:e9505445a0
## Semi-join 
Return just the rows of X that we have Y information for

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:28cb9f4df2
## Semi-join 2 
Do any of the rows in X match any of the rows in Y?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:MultipleChoiceExercise lang:python xp: skills: key:ed06bcad37
## A more precise way to filter? 
We've attempted to rewrite this semi-join as a filter. Will it return the same results?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:df16ce99d6
## Anti-joins 
Anti-joins do the opposite of semi-joins, they show which rows do not have matches. Anti-joins are a convenient way to check for errors before they occur.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:0f4ee75fee
## Anti-join 
Which rows of X do we not have Y information for?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:ccb09dc5f9
## Anti-Join 2 
Were any of the keys of X mis-entered? Use an anti-join to check

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:5525a41e08
## Which filtering join? 
Use a filtering join to determine how many matches exist between X and Y

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:febe9bd6f7
## Set Operations 
Set operations include union(), intersect() and setdiff(). They let you group observations from two data sets into a new data set.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:087ed0b134
## Union 
How many unique observations are there in these two data sets?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:c0043e0e5d
## Intersection 
How many observations are shared between these two data sets?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:b255819b6c
## Setdiff 
Which observations are in X but not Y?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:fc99895349
## Operations 
Combine union and setdiff operations to return all of the observations that are in one data set, but not the other.

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:MultipleChoiceExercise lang:python xp: skills: key:5e11aa4feb
## Unique values 
Will the result of this union statement contain fewer rows than the original data set? That would seem paradoxical.

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:9ef0c0f297
## Comparing data sets 
Use setequal or all.equal to check whether two data sets contain of the same observations.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:b16226b84d
## setequal 
Does the second data set contain any new information?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:843b69ff09
## setequal 
Write a filtering join that would also check if the second data set contains new information?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}
