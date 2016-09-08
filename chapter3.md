---
title       : Insert the chapter title here
description : Insert the chapter description here
--- type:VideoExercise lang: xp: skills: key:ca68c8792c
## Binds
Binds join data sets together in a very simple way; they either add one data set as observations of the other or as variables of the other. Demo of bind_rows() and bind_cols.

*** =video_link

--- type:NormalExercise lang: xp: skills: key:85a18e4f21
## Which bind?
Bind these data sets into a single data set. Which bind should you use?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:c15d81e6e7
## Bind rows
Use one command to bind the entire list of data sets into a single data set. Then run the complete code to do something nice.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:d1a84b9eaf
## Bind columns
Use bind cols

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang: xp: skills: key:b04c120c0b
## Danger
What is the biggest risk when using bind cols?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang: xp: skills: key:82afa2264f
## Build a better data frame
data_frame() is a trimmed down version of data.frame that never coerces inputs (i.e. strings stay as strings!), never adds row.names, never munges column names, only recycles length 1 inputs, evaluates its arguments lazily and in order, and adds tbl_df class to output. frame_data() does the same thing rowwise

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:d20d26818d
## data_frame
Which is not an advantage of data_frame over data.frame?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:d4011861cc
## Make a data frame
Turn this columnwise data into a data frame

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:ab77b9b972
## Make another data frame
Turn this rowwise data into a data frame

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:04b6c623b2
## Make one last data frame
Turn this list into a data frame

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang: xp: skills: key:150804759c
## Working with data types
There are several different common data types in R, and sometimes R has to turn one into another, which is known as coercion. Here's how to tell what data types you have and how  (and when) dplyr will coerce them

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:707bd3f7ae
## Atomic data types
Which best describes R's coercion rules?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:8d44f3b6e0
## Determining type
Run the code to see the type of X$x. Then write code and determine the type of Y$x

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:ca4d987e04
## Results
Join the data sets together by x with a left join. Then determine the type of the output x.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct
