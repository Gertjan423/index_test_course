---
title        : Mutating joins yyy
description  : Mutating joins add new variables to one data set from another data set, matching observations across rows in the process. This chapter will explain the various ways you can join data sets together and what happens when you do. 

--- type:VideoExercise lang:python xp: skills: key:ae1a4a254d
## Welcome to the course! 
Introduction. Why use dplyr to join data? Many data sets come in multiple tables, in fact that's the easiest way to store large data. dplyr joins faster are faster than base merges and preserve row order. You can also use them with dplyr's built in SQL backend.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:5786db8b4c
## The advantages of dplyr 
Which is not a reason to use dplyr to join data?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang:python xp: skills: key:4618c75106
## Our data 
Which data set contains the X variable?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang:python xp: skills: key:c60b288f7c
## Keys 
To join two tables you need to identify a pair of keys that connect the tables. Keys are variables whose values are shared across tables. There are two kinds of keys, primary and secondary.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:9fee3f7bb8
## Primary keys 
Examine the data set, what is the primary key for this data set?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:MultipleChoiceExercise lang:python xp: skills: key:dbfbcb198a
## Secondary keys 
Which data sets have a secondary key that matches the primary?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:MultipleChoiceExercise lang:python xp: skills: key:fb12630723
## Multi-variable keys 
In some cases the unique primary key is the interaction of two or more variables. What would be the primary key of this data set?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang:python xp: skills: key:a37f923306
## Joins 
Demonstrate left_join() and right_join().

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:895294af51
## A basic join 
Use pre-code with left_join()

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:f1966aa47e
## A right join 
Use pre-code with right_join()

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang:python xp: skills: key:61dbd3230b
## Right vs. left 
Can you tell the difference between a right and a left join? How many rows will the result have if you right join the two data sets to the right. Each data set contains one unique observation per row. Pre-code should show the nrow() of two data sets and the nrow() of left joining them.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang:python xp: skills: key:8f8a8d74dc
## Variations on joins 
Explain diagram syntax. Demonstrate the differences between left_join(), right_join(), inner_join(), and full_join().

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:b96486f2a8
## Inner joins 
Use pre-code to complete an inner_join()

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:fc530d82a6
## Full joins 
Use pre-code to complete an full_join()

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang:python xp: skills: key:1b5f479549
## Choose a join 
Describe a result and have students choose which of the joins will return it.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang:python xp: skills: key:bff7d12ad2
## Use a join 
Use a dplyr join function to return every row that appears in either data set.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct
