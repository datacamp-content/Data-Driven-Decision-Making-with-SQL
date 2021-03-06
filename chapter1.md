---
title: 'Template Chapter 1'
description: 'This is a template chapter.'
---

## Introduction to the Course SQL

```yaml
type: VideoExercise
key: 8c8d7f005b
lang: sql
xp: 50
skills: 1
```


---

## A follow-up on the course intro

```yaml
type: PureMultipleChoiceExercise
key: 138621b475
xp: 50
skills: 1
```

This exercise serves as a multiple choice exercise with no coding. We have a hard
limit of five multiple choice exercises throughout the entire course, but instructors
often find it handy to have a multiple choice exercise immediately following
the first video. Note that we do not allow back-to-back multiple choice exercises.
More info on guidelines is [here](https://authoring.datacamp.com/courses/guidelines/content.html).

`@hint`
This should assist students in cutting out some of the distractors.

`@possible_answers`
- A
- B
- [C]
- D

`@feedback`
- This is the reason why A is not the right answer.
- This is the reason why B is not the right answer.
- Correct! C is the right answer here because...
- This is the reason why D is not the right answer.

---

## An exercise title written in sentence case

```yaml
type: NormalExercise
key: 923a0fe951
lang: sql
xp: 100
skills: 1
```

This is the [assignment text](http://authoring.datacamp.com/courses/exercises/normal-exercises/assignment-text.html). 
It should help provide students with the background information needed. 
The instructions that follow should be in bullet point form with clear guidance 
for what is expected.

`@instructions`
- Instruction 1
- Instruction 2
- Instruction 3

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`
```{python}
# Load data bases and set viewable tables here.
# connect('postgresql', 'countries')
# set_options(visible_tables = ['countries',  'economies'])
```

`@sample_code`
```{sql}
-- Your
-- sample
-- code
-- should
-- be
-- ideally
-- 10 lines or less,
-- with a max
-- of 16 lines.
```

`@solution`
```{sql}
-- Answer goes here
-- Make sure to match the comments with your sample code
-- to help students see the differences from solution
-- to given.
```

`@sct`
```{python}
# Update this to something more informative.
Ex().success_msg("Some praise! Then reinforce a learning objective from the exercise.")
```

---

## Update the exercise title

```yaml
type: NormalExercise
key: 215620cd48
lang: r
xp: 100
skills: 1
```

This is the [assignment text](http://authoring.datacamp.com/courses/exercises/normal-exercises/assignment-text.html). 
It should help provide students with the background information needed. 
The instructions that follow should be in bullet point form with clear guidance 
for what is expected.

`@instructions`
- Instruction 1
- Instruction 2
- Instruction 3

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`
```{python}
# Load data bases and set viewable tables here.
# connect('postgresql', 'countries')
# set_options(visible_tables = ['countries',  'economies'])
```

`@sample_code`
```{sql}
-- Your
-- sample
-- code
-- should
-- be
-- ideally
-- 10 lines or less,
-- with a max
-- of 16 lines.
```

`@solution`
```{sql}
-- Answer goes here
-- Make sure to match the comments with your sample code
-- to help students see the differences from solution
-- to given.
```

`@sct`
```{python}
# Update this to something more informative.
Ex().success_msg("Some praise! Then reinforce a learning objective from the exercise.")
```
