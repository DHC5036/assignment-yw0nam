# 1. Why does BERT succeed?

The authors argue that BERT can catch the bidirection feature of setence while previous model only catch left2right or right2left 

# 2. Can we leverage BERT in clinical natural language processing?

In the hospital, human annotators sees and labels a medical examination text.
It is very time-consuming and exhausting for human annotators
Recently, I'm apply bert to label it from the text of the medical examination diagnosis as input.
The model achieve 99.8% accuracy for data with slight preprocessing.
It has a potential being auto labeling system connected with hospital db