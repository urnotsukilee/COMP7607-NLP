## Summary
This is a homework for NLP courses.

## Data
Data consists of thousands of sentences with tagger for each word.

For instances:
```
-DOCSTART- -X- -X- O

SOCCER NN B-NP O
- : O O
JAPAN NNP B-NP B-LOC
GET VB B-VP O
LUCKY NNP B-NP O
WIN NNP I-NP O
, , O O
CHINA NNP B-NP B-PER
IN IN B-PP O
SURPRISE DT B-NP O
DEFEAT NN I-NP O
. . O O
```
The first line is the document start indicator.
All the sentences are seperated by an emply line.
For each line, the first word is an input word of a sentence. The last word is the target tagger.

## Task
The task is to train a model for predicting the related taggers for every word in an input sentence.
