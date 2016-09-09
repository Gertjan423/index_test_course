---
title        : Filtering joins and set operations
description  : Filtering joins and Set operations combine information from data sets without adding new variables. Filtering joins filter the observations of one data set based on whether or not they occur in a second data set. Set operations use combinations of observations from both data sets to create a new data set. 

--- type:VideoExercise lang:python xp: skills: key:1db9500655
## Semi-joins 
Have you ever tried to filter data based on the combination of many variables. You could try to do this with `filter()`, but it will be much easier with a semi-join.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:8c0ce98d1e
## Semi-join 
Return just the rows of X that we have Y information for

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:e60246eaf5
## Semi-join 2 
Do any of the rows in X match any of the rows in Y?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang:python xp: skills: key:927ea6a2f3
## A more precise way to filter? 
We've attempted to rewrite this semi-join as a filter. Will it return the same results?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang:python xp: skills: key:e78c1e283d
## Anti-joins 
Anti-joins do the opposite of semi-joins, they show which rows do not have matches. Anti-joins are a convenient way to check for errors before they occur.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:331999c625
## Anti-join 
Which rows of X do we not have Y information for?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:8464107360
## Anti-Join 2 
Were any of the keys of X mis-entered? Use an anti-join to check

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:754a8479ab
## Which filtering join? 
Use a filtering join to determine how many matches exist between X and Y

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang:python xp: skills: key:96a35d830d
## Set Operations 
Set operations include union(), intersect() and setdiff(). They let you group observations from two data sets into a new data set.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:edf284ec25
## Union 
How many unique observations are there in these two data sets?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:a8cbae7747
## Intersection 
How many observations are shared between these two data sets?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:f45a8d4e73
## Setdiff 
Which observations are in X but not Y?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:9e0a8ff69f
## Operations 
Combine union and setdiff operations to return all of the observations that are in one data set, but not the other.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang:python xp: skills: key:42f84fd7b7
## Unique values 
Will the result of this union statement contain fewer rows than the original data set? That would seem paradoxical.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang:python xp: skills: key:99d5f0843b
## Comparing data sets 
Use setequal or all.equal to check whether two data sets contain of the same observations.

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:84a98bfc2f
## setequal 
Does the second data set contain any new information?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:d2e0ae6716
## setequal 
Write a filtering join that would also check if the second data set contains new information?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct
