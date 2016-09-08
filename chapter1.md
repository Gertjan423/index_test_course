---
title       : Insert the chapter title here
description : Insert the chapter description here
--- type:VideoExercise lang: xp: skills: key:173ec58765
## Welcome to the course!
Introduction. Why use dplyr to join data? Many data sets come in multiple tables, in fact that's the easiest way to store large data. dplyr joins faster are faster than base merges and preserve row order. You can also use them with dplyr's built in SQL backend.

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:2a0545c90d
## The advantages of dplyr
Which is not a reason to use dplyr to join data?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:759f07fd65
## Our data
Which data set contains the X variable?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang: xp: skills: key:56db475351
## Keys
To join two tables you need to identify a pair of keys that connect the tables. Keys are variables whose values are shared across tables. There are two kinds of keys, primary and secondary.

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:dd0132be6c
## Primary keys
Examine the data set, what is the primary key for this data set?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:MultipleChoiceExercise lang: xp: skills: key:491c9e2862
## Secondary keys
Which data sets have a secondary key that matches the primary?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:MultipleChoiceExercise lang: xp: skills: key:0b6e614699
## Multi-variable keys
In some cases the unique primary key is the interaction of two or more variables. What would be the primary key of this data set?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang: xp: skills: key:053533ccf0
## Joins
Demonstrate left_join() and right_join().

*** =video_link

--- type:NormalExercise lang: xp: skills: key:0a8a66e57e
## A basic join
Use pre-code with left_join()

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:37fd0a087d
## A right join
Use pre-code with right_join()

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang: xp: skills: key:c515a67b50
## Right vs. left
Can you tell the difference between a right and a left join? How many rows will the result have if you right join the two data sets to the right. Each data set contains one unique observation per row. Pre-code should show the nrow() of two data sets and the nrow() of left joining them.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang: xp: skills: key:692d0e0a3c
## Variations on joins
Explain diagram syntax. Demonstrate the differences between left_join(), right_join(), inner_join(), and full_join().

*** =video_link

--- type:NormalExercise lang: xp: skills: key:acf538584e
## Inner joins
Use pre-code to complete an inner_join()

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:86ad7db8ea
## Full joins
Use pre-code to complete an full_join()

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang: xp: skills: key:40d1c732c7
## Choose a join
Describe a result and have students choose which of the joins will return it.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:f1ecccb396
## Use a join
Use a dplyr join function to return every row that appears in either data set.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct
