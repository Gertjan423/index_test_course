---
title        : Assembling data
description  : This chapter will show you how to build data sets from more basic elements: vectors, lists, and individual data sets that do not require a join. dplyr contains a set of functions for assembling data that work faster and more intuitively that base R's functions. The chapter will also look at when dplyr uses, and when it doesn't use, data type coercion. 

--- type:VideoExercise lang:python xp: skills:
## Binds 
Binds join data sets together in a very simple way; they either add one data set as observations of the other or as variables of the other. Demo of bind_rows() and bind_cols.

*** =video_link

--- type:NormalExercise lang:python xp: skills:
## Which bind? 
Bind these data sets into a single data set. Which bind should you use?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills:
## Bind rows 
Use one command to bind the entire list of data sets into a single data set. Then run the complete code to do something nice.

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills:
## Bind columns 
Use bind cols

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:MultipleChoiceExercise lang:python xp: skills:
## Danger 
What is the biggest risk when using bind cols?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills:
## Build a better data frame 
data_frame() is a trimmed down version of data.frame that never coerces inputs (i.e. strings stay as strings!), never adds row.names, never munges column names, only recycles length 1 inputs, evaluates its arguments lazily and in order, and adds tbl_df class to output. frame_data() does the same thing rowwise

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills:
## data_frame 
Which is not an advantage of data_frame over data.frame?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills:
## Make a data frame 
Turn this columnwise data into a data frame

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills:
## Make another data frame 
Turn this rowwise data into a data frame

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills:
## Make one last data frame 
Turn this list into a data frame

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:VideoExercise lang:python xp: skills:
## Working with data types 
There are several different common data types in R, and sometimes R has to turn one into another, which is known as coercion. Here's how to tell what data types you have and how  (and when) dplyr will coerce them

*** =video_link

--- type:MultipleChoiceExercise lang:python xp: skills:
## Atomic data types 
Which best describes R's coercion rules?

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills:
## Determining type 
Run the code to see the type of X$x. Then write code and determine the type of Y$x

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}

--- type:NormalExercise lang:python xp: skills:
## Results 
Join the data sets together by x with a left join. Then determine the type of the output x.

*** =instructions

*** =hint

*** =pre_exercise_code{python}

*** =sample_code{python}

*** =solution{python}

*** =sct{python}
