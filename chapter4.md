---
title        : Advanced joining
description  : Now that you have the basics, let's dive deep into the mechanics of joins. This chapter will show you how to spot common join problems; how to join based on multiple, or mis-matched keys; how to join multiple tables; and how you can recreate dplyr's joins with SQL and base R. 

--- type:VideoExercise lang:python xp: skills: key:b7e4b099bd
## What can go wrong? 
Data entry errors can derail your joins. Here are the most  common types and how to search for them: duplicate keys in your data set and missing keys.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:94aa8a0201
## Spot the key 
What is the primary key for this data set?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:MultipleChoiceExercise lang:python xp: skills: key:a31706d551
## Unique keys 
Does the primary key uniquely identify each row? (no, you can add your own primary key with add_rownames())

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang:python xp: skills: key:52b1fd204e
## Too many keys 
Join the data sets together. What happens to the duplicate keys?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:d7eecf083b
## Missing keys 
Which rows contain a missing key variable?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang:python xp: skills: key:804c534d36
## Defining the keys 
dplyr gives you a lot of control over how you join rows in data sets. You can rely on dplyr to match up rows automatically, select a subset of keys to join on, or specify a join between keys that have different names.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:704c8982f6
## Which keys? 
Which keys will dplyr join on if you set by = "NULL" (the default)?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang:python xp: skills: key:f55e26b702
## A subset of keys 
Join based on just the x variable. What will happen to the duplicate y and z variables?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:eb7260fdda
## Mis-matched key names 
Join based on just the X$x variable and the Y$y variables

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:3d4e272d57
## More mis-matched names 
Join based on these sets of variables

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang:python xp: skills: key:469b91dc5b
## Joining multiple tables 
Joins are always defined as a relationship between two data sets. To join more than two data sets together, join them iteratively with the `purrr::Reduce()` function

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:2693cd4f72
## purrr 
purrr is a package that does what?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang:python xp: skills: key:ff4c5fc94d
## Join multiple tables 
Join these n tables

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:e022f3318f
## Filter multiple tables 
Which observations are common to all n tables?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang:python xp: skills: key:ea40f5634f
## Other implementations 
Dplyr joins are analagous to other joins you may be doing (or may one day want to do) in other languages. Here we look at how to recreate dplyr joins with the base function merge and SQL.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:7e62bf1f6d
## SQL 
TRUE or FALSE, you can recreate each type of SQL join with dplyr

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang:python xp: skills: key:340e4b0a4a
## One too many 
One video exercise too many is no fun...

*** =video_link
