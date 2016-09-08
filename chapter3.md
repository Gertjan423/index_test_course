---
title       : Insert the chapter title here
description : Insert the chapter description here
--- type:VideoExercise lang: xp: skills: key:29117fc487
## Binds
Binds join data sets together in a very simple way; they either add one data set as observations of the other or as variables of the other. Demo of bind_rows() and bind_cols.

*** =video_link

--- type:NormalExercise lang: xp: skills: key:4075723482
## Which bind?
Bind these data sets into a single data set. Which bind should you use?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:7e8d9f4aa6
## Bind rows
Use one command to bind the entire list of data sets into a single data set. Then run the complete code to do something nice.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:311fa74453
## Bind columns
Use bind cols

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang: xp: skills: key:bd95f415f1
## Danger
What is the biggest risk when using bind cols?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang: xp: skills: key:8e8e315707
## Build a better data frame
data_frame() is a trimmed down version of data.frame that never coerces inputs (i.e. strings stay as strings!), never adds row.names, never munges column names, only recycles length 1 inputs, evaluates its arguments lazily and in order, and adds tbl_df class to output. frame_data() does the same thing rowwise

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:7ffbb2ca15
## data_frame
Which is not an advantage of data_frame over data.frame?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:130ecc4761
## Make a data frame
Turn this columnwise data into a data frame

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:17e4048c31
## Make another data frame
Turn this rowwise data into a data frame

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:a2123ef1e5
## Make one last data frame
Turn this list into a data frame

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang: xp: skills: key:f063a13d17
## Working with data types
There are several different common data types in R, and sometimes R has to turn one into another, which is known as coercion. Here's how to tell what data types you have and how  (and when) dplyr will coerce them

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:cfa018d9c3
## Atomic data types
Which best describes R's coercion rules?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:a4faf5507a
## Determining type
Run the code to see the type of X$x. Then write code and determine the type of Y$x

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:4ce2d8b476
## Results
Join the data sets together by x with a left join. Then determine the type of the output x.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct
