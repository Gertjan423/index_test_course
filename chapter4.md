---
title       : Insert the chapter title here
description : Insert the chapter description here
--- type:VideoExercise lang: xp: skills: key:30448b0ca7
## What can go wrong?
Data entry errors can derail your joins. Here are the most  common types and how to search for them: duplicate keys in your data set and missing keys.

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:43a6916d2f
## Spot the key
What is the primary key for this data set?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:MultipleChoiceExercise lang: xp: skills: key:2a7ae92bc1
## Unique keys
Does the primary key uniquely identify each row? (no, you can add your own primary key with add_rownames())

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:5f1e823667
## Too many keys
Join the data sets together. What happens to the duplicate keys?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:f7e85c16e5
## Missing keys
Which rows contain a missing key variable?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang: xp: skills: key:7dae0ba544
## Defining the keys
dplyr gives you a lot of control over how you join rows in data sets. You can rely on dplyr to match up rows automatically, select a subset of keys to join on, or specify a join between keys that have different names.

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:fc06b5c929
## Which keys?
Which keys will dplyr join on if you set by = "NULL" (the default)?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:6a4e7e3f3c
## A subset of keys
Join based on just the x variable. What will happen to the duplicate y and z variables?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:f8bcc2180f
## Mis-matched key names
Join based on just the X$x variable and the Y$y variables

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:9dd049f10f
## More mis-matched names
Join based on these sets of variables

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang: xp: skills: key:81f42fee42
## Joining multiple tables
Joins are always defined as a relationship between two data sets. To join more than two data sets together, join them iteratively with the `purrr::Reduce()` function

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:36c1e29406
## purrr
purrr is a package that does what?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:03652faf49
## Join multiple tables
Join these n tables

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:bd8d8cb81c
## Filter multiple tables
Which observations are common to all n tables?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang: xp: skills: key:b100996435
## Other implementations
Dplyr joins are analagous to other joins you may be doing (or may one day want to do) in other languages. Here we look at how to recreate dplyr joins with the base function merge and SQL.

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:903ae8d5d9
## SQL
TRUE or FALSE, you can recreate each type of SQL join with dplyr

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang: xp: skills: key:1b3b0cfd2e
## One too many
One video exercise too many is no fun...

*** =video_link
