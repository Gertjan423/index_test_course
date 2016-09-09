---
title        : Filtering joins and set operations
description  : Filtering joins and Set operations combine information from data sets without adding new variables. Filtering joins filter the observations of one data set based on whether or not they occur in a second data set. Set operations use combinations of observations from both data sets to create a new data set. 

--- type:VideoExercise lang:python xp: skills: key:9ea13f011f
## Semi-joins 
Have you ever tried to filter data based on the combination of many variables. You could try to do this with `filter()`, but it will be much easier with a semi-join.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:79e89c7887
## Semi-join 
Return just the rows of X that we have Y information for

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:731a8d9353
## Semi-join 2 
Do any of the rows in X match any of the rows in Y?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:MultipleChoiceExercise lang:python xp: skills: key:1f15b20011
## A more precise way to filter? 
We've attempted to rewrite this semi-join as a filter. Will it return the same results?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:1c8c7ce220
## Anti-joins 
Anti-joins do the opposite of semi-joins, they show which rows do not have matches. Anti-joins are a convenient way to check for errors before they occur.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:7a7d31130c
## Anti-join 
Which rows of X do we not have Y information for?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:55da73fcf7
## Anti-Join 2 
Were any of the keys of X mis-entered? Use an anti-join to check

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:d97fdc3d80
## Which filtering join? 
Use a filtering join to determine how many matches exist between X and Y

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:cb423e01a9
## Set Operations 
Set operations include union(), intersect() and setdiff(). They let you group observations from two data sets into a new data set.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:81b530815a
## Union 
How many unique observations are there in these two data sets?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:7ba21adec6
## Intersection 
How many observations are shared between these two data sets?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:e26d29b9d6
## Setdiff 
Which observations are in X but not Y?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:6d833e73e8
## Operations 
Combine union and setdiff operations to return all of the observations that are in one data set, but not the other.

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:MultipleChoiceExercise lang:python xp: skills: key:d953441041
## Unique values 
Will the result of this union statement contain fewer rows than the original data set? That would seem paradoxical.

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:153b8a3c49
## Comparing data sets 
Use setequal or all.equal to check whether two data sets contain of the same observations.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:49b6814981
## setequal 
Does the second data set contain any new information?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:eb11403858
## setequal 
Write a filtering join that would also check if the second data set contains new information?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}
