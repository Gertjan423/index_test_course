---
title        : Advanced joining
description  : Now that you have the basics, let's dive deep into the mechanics of joins. This chapter will show you how to spot common join problems; how to join based on multiple, or mis-matched keys; how to join multiple tables; and how you can recreate dplyr's joins with SQL and base R. 

--- type:VideoExercise lang:python xp: skills: key:0c3ead1b48
## What can go wrong? 
Data entry errors can derail your joins. Here are the most  common types and how to search for them: duplicate keys in your data set and missing keys.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:30bb3788ae
## Spot the key 
What is the primary key for this data set?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:MultipleChoiceExercise lang:python xp: skills: key:80e1b50f0b
## Unique keys 
Does the primary key uniquely identify each row? (no, you can add your own primary key with add_rownames())

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang:python xp: skills: key:0f2e7ae9ec
## Too many keys 
Join the data sets together. What happens to the duplicate keys?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:b42297866a
## Missing keys 
Which rows contain a missing key variable?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang:python xp: skills: key:d7c2d18abd
## Defining the keys 
dplyr gives you a lot of control over how you join rows in data sets. You can rely on dplyr to match up rows automatically, select a subset of keys to join on, or specify a join between keys that have different names.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:c6e7345ed7
## Which keys? 
Which keys will dplyr join on if you set by = "NULL" (the default)?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang:python xp: skills: key:03f5289b5b
## A subset of keys 
Join based on just the x variable. What will happen to the duplicate y and z variables?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:c350a1c215
## Mis-matched key names 
Join based on just the X$x variable and the Y$y variables

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:65f736b29f
## More mis-matched names 
Join based on these sets of variables

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang:python xp: skills: key:677139232c
## Joining multiple tables 
Joins are always defined as a relationship between two data sets. To join more than two data sets together, join them iteratively with the `purrr::Reduce()` function

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:5b91bd8e85
## purrr 
purrr is a package that does what?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang:python xp: skills: key:ba580c965e
## Join multiple tables 
Join these n tables

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:1ee5700478
## Filter multiple tables 
Which observations are common to all n tables?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang:python xp: skills: key:106093dca7
## Other implementations 
Dplyr joins are analagous to other joins you may be doing (or may one day want to do) in other languages. Here we look at how to recreate dplyr joins with the base function merge and SQL.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:9cb3e71a56
## SQL 
TRUE or FALSE, you can recreate each type of SQL join with dplyr

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang:python xp: skills: key:0b53421e41
## One too many 
One video exercise too many is no fun...

*** =video_link
