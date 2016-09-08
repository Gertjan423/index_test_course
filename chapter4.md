---
title        : Advanced joining
description  : Now that you have the basics, let's dive deep into the mechanics of joins. This chapter will show you how to spot common join problems; how to join based on multiple, or mis-matched keys; how to join multiple tables; and how you can recreate dplyr's joins with SQL and base R.

--- type:VideoExercise lang: xp: skills: key:14d391d107
## What can go wrong?
Data entry errors can derail your joins. Here are the most  common types and how to search for them: duplicate keys in your data set and missing keys.

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:f1727effd8
## Spot the key
What is the primary key for this data set?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:MultipleChoiceExercise lang: xp: skills: key:6a7819899f
## Unique keys
Does the primary key uniquely identify each row? (no, you can add your own primary key with add_rownames())

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:7dc2186b02
## Too many keys
Join the data sets together. What happens to the duplicate keys?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:6018444cd9
## Missing keys
Which rows contain a missing key variable?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang: xp: skills: key:e222b1b152
## Defining the keys
dplyr gives you a lot of control over how you join rows in data sets. You can rely on dplyr to match up rows automatically, select a subset of keys to join on, or specify a join between keys that have different names.

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:3a056a3439
## Which keys?
Which keys will dplyr join on if you set by = "NULL" (the default)?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:21cb9b83f8
## A subset of keys
Join based on just the x variable. What will happen to the duplicate y and z variables?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:cfceeade3b
## Mis-matched key names
Join based on just the X$x variable and the Y$y variables

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:3d1e84b8ac
## More mis-matched names
Join based on these sets of variables

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang: xp: skills: key:e3ed5db31c
## Joining multiple tables
Joins are always defined as a relationship between two data sets. To join more than two data sets together, join them iteratively with the `purrr::Reduce()` function

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:30ba39a6c3
## purrr
purrr is a package that does what?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:e4d10554c0
## Join multiple tables
Join these n tables

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:8638679c6b
## Filter multiple tables
Which observations are common to all n tables?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang: xp: skills: key:2f8f08190b
## Other implementations
Dplyr joins are analagous to other joins you may be doing (or may one day want to do) in other languages. Here we look at how to recreate dplyr joins with the base function merge and SQL.

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:b6e72dc9d0
## SQL
TRUE or FALSE, you can recreate each type of SQL join with dplyr

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang: xp: skills: key:702dc4d15f
## One too many
One video exercise too many is no fun...

*** =video_link
