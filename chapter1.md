---
title        : Mutating joins
description  : Mutating joins add new variables to one data set from another data set, matching observations across rows in the process. This chapter will explain the various ways you can join data sets together and what happens when you do. 

--- type:VideoExercise lang:python xp: skills: key:cb5cd86471
## Welcome to the course! 
Introduction. Why use dplyr to join data? Many data sets come in multiple tables, in fact that's the easiest way to store large data. dplyr joins faster are faster than base merges and preserve row order. You can also use them with dplyr's built in SQL backend.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:e31c89d78a
## The advantages of dplyr 
Which is not a reason to use dplyr to join data?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang:python xp: skills: key:3a29726257
## Our data 
Which data set contains the X variable?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang:python xp: skills: key:7b115c7789
## Keys 
To join two tables you need to identify a pair of keys that connect the tables. Keys are variables whose values are shared across tables. There are two kinds of keys, primary and secondary.

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills: key:4cedab8b81
## Primary keys 
Examine the data set, what is the primary key for this data set?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:MultipleChoiceExercise lang:python xp: skills: key:a525e6b60d
## Secondary keys 
Which data sets have a secondary key that matches the primary?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:MultipleChoiceExercise lang:python xp: skills: key:c041d2d5cd
## Multi-variable keys 
In some cases the unique primary key is the interaction of two or more variables. What would be the primary key of this data set?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang:python xp: skills: key:8c4415c818
## Joins 
Demonstrate left_join() and right_join().

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:6d527d656d
## A basic join 
Use pre-code with left_join()

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:1dda536671
## A right join 
Use pre-code with right_join()

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang:python xp: skills: key:66a409eaed
## Right vs. left 
Can you tell the difference between a right and a left join? How many rows will the result have if you right join the two data sets to the right. Each data set contains one unique observation per row. Pre-code should show the nrow() of two data sets and the nrow() of left joining them.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang:python xp: skills: key:0a25eefc42
## Variations on joins 
Explain diagram syntax. Demonstrate the differences between left_join(), right_join(), inner_join(), and full_join().

*** =video_link

--- type:NormalExercise lang:python xp: skills: key:cc3af7773b
## Inner joins 
Use pre-code to complete an inner_join()

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang:python xp: skills: key:a84bbcfdf1
## Full joins 
Use pre-code to complete an full_join()

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang:python xp: skills: key:87b078b4a8
## Choose a join 
Describe a result and have students choose which of the joins will return it.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang:python xp: skills: key:1bea8ce066
## Use a join 
Use a dplyr join function to return every row that appears in either data set.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct
