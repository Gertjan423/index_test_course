---
title        : Advanced joining
description  : Now that you have the basics, let's dive deep into the mechanics of joins. This chapter will show you how to spot common join problems; how to join based on multiple, or mis-matched keys; how to join multiple tables; and how you can recreate dplyr's joins with SQL and base R. 

--- type:VideoExercise lang:python xp: skills: key:497ba5e395
## What can go wrong? 
Data entry errors can derail your joins. Here are the most  common types and how to search for them: duplicate keys in your data set and missing keys.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:18513f511f
## Spot the key 
What is the primary key for this data set?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:MultipleChoiceExercise lang:python xp: skills: key:4ef563aeda
## Unique keys 
Does the primary key uniquely identify each row? (no, you can add your own primary key with add_rownames())

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:81f064a9d0
## Too many keys 
Join the data sets together. What happens to the duplicate keys?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:6ca2af7b94
## Missing keys 
Which rows contain a missing key variable?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:482d87d957
## Defining the keys 
dplyr gives you a lot of control over how you join rows in data sets. You can rely on dplyr to match up rows automatically, select a subset of keys to join on, or specify a join between keys that have different names.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:48db825307
## Which keys? 
Which keys will dplyr join on if you set by = "NULL" (the default)?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:10c438b44d
## A subset of keys 
Join based on just the x variable. What will happen to the duplicate y and z variables?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:13b8991829
## Mis-matched key names 
Join based on just the X$x variable and the Y$y variables

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:125b32c62a
## More mis-matched names 
Join based on these sets of variables

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:99905d44be
## Joining multiple tables 
Joins are always defined as a relationship between two data sets. To join more than two data sets together, join them iteratively with the `purrr::Reduce()` function

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:95ab1d15e4
## purrr 
purrr is a package that does what?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:33a849a1db
## Join multiple tables 
Join these n tables

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills: key:f138df5604
## Filter multiple tables 
Which observations are common to all n tables?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:d12fa02c3e
## Other implementations 
Dplyr joins are analagous to other joins you may be doing (or may one day want to do) in other languages. Here we look at how to recreate dplyr joins with the base function merge and SQL.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:e8545c01c7
## SQL 
TRUE or FALSE, you can recreate each type of SQL join with dplyr

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills: key:33887100d5
## One too many 
One video exercise too many is no fun...

*** =video_link
