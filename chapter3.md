---
title       : Insert the chapter title here
description : Insert the chapter description here
--- type:VideoExercise lang: xp: skills: key:87c00cd670
## Binds
Binds join data sets together in a very simple way; they either add one data set as observations of the other or as variables of the other. Demo of bind_rows() and bind_cols.

*** =video_link

--- type:NormalExercise lang: xp: skills: key:1431365def
## Which bind?
Bind these data sets into a single data set. Which bind should you use?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:6069a86257
## Bind rows
Use one command to bind the entire list of data sets into a single data set. Then run the complete code to do something nice.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:1972462c60
## Bind columns
Use bind cols

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:MultipleChoiceExercise lang: xp: skills: key:14df8402e5
## Danger
What is the biggest risk when using bind cols?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:VideoExercise lang: xp: skills: key:723750e1ad
## Build a better data frame
data_frame() is a trimmed down version of data.frame that never coerces inputs (i.e. strings stay as strings!), never adds row.names, never munges column names, only recycles length 1 inputs, evaluates its arguments lazily and in order, and adds tbl_df class to output. frame_data() does the same thing rowwise

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:47570ab3bf
## data_frame
Which is not an advantage of data_frame over data.frame?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:6a38c920c8
## Make a data frame
Turn this columnwise data into a data frame

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:daad035a74
## Make another data frame
Turn this rowwise data into a data frame

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:ddb615557f
## Make one last data frame
Turn this list into a data frame

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:VideoExercise lang: xp: skills: key:75ca117211
## Working with data types
There are several different common data types in R, and sometimes R has to turn one into another, which is known as coercion. Here's how to tell what data types you have and how  (and when) dplyr will coerce them

*** =video_link

--- type:MultipleChoiceExercise lang: xp: skills: key:5438acbc68
## Atomic data types
Which best describes R's coercion rules?

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sct

--- type:NormalExercise lang: xp: skills: key:47c60277df
## Determining type
Run the code to see the type of X$x. Then write code and determine the type of Y$x

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct

--- type:NormalExercise lang: xp: skills: key:81b2955092
## Results
Join the data sets together by x with a left join. Then determine the type of the output x.

*** =instructions

*** =hint

*** =pre_exercise_code

*** =sample_code

*** =solution

*** =sct
