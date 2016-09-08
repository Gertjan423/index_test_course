---
title       : Insert the chapter title here
description : Insert the chapter description here
--- type:VideoExercise lang: xp: skills: key:0ddbadf3cb
## Semi-joins
Have you ever tried to filter data based on the combination of many variables. You could try to do this with `filter()`, but it will be much easier with a semi-join.

*** =video_link

--- type:NormalExercise lang: xp: skills: key:5874cf6ad1
## Semi-join
Return just the rows of X that we have Y information for

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:100314b091
## Semi-join 2
Do any of the rows in X match any of the rows in Y?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang: xp: skills: key:44ed09131c
## A more precise way to filter?
We've attempted to rewrite this semi-join as a filter. Will it return the same results?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang: xp: skills: key:841eee3a53
## Anti-joins
Anti-joins do the opposite of semi-joins, they show which rows do not have matches. Anti-joins are a convenient way to check for errors before they occur.

*** =video_link

--- type:NormalExercise lang: xp: skills: key:340d31efa1
## Anti-join
Which rows of X do we not have Y information for?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:25be67bff4
## Anti-Join 2
Were any of the keys of X mis-entered? Use an anti-join to check

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:5d25d91609
## Which filtering join?
Use a filtering join to determine how many matches exist between X and Y

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang: xp: skills: key:ac412039b0
## Set Operations
Set operations include union(), intersect() and setdiff(). They let you group observations from two data sets into a new data set.

*** =video_link

--- type:NormalExercise lang: xp: skills: key:b5dea69973
## Union
How many unique observations are there in these two data sets?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:6a4147d629
## Intersection
How many observations are shared between these two data sets?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:2cea5c3ef0
## Setdiff
Which observations are in X but not Y?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:25bb23a877
## Operations
Combine union and setdiff operations to return all of the observations that are in one data set, but not the other.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang: xp: skills: key:cf87145425
## Unique values
Will the result of this union statement contain fewer rows than the original data set? That would seem paradoxical.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang: xp: skills: key:a1a6565ef9
## Comparing data sets
Use setequal or all.equal to check whether two data sets contain of the same observations.

*** =video_link

--- type:NormalExercise lang: xp: skills: key:116debadcf
## setequal
Does the second data set contain any new information?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:f7662529ae
## setequal
Write a filtering join that would also check if the second data set contains new information?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct
