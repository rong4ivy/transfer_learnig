# transfer_learnig

# Task: Reading Comprehension (RC) Description
Predict a single, contiguous answer for a question using the context.
The answer is extractive, i.e., it is a part of the context.
Furthermore, your model will be evaluated in a few-shot setting by means of the F1 on the whitespace-split textual answer level. See https://huggingface.co/spaces/evaluate-metric/ squad for more information.


You may use any method e.g., Transfer Learning, Prompting.
Data
• The training data contains context and question as input as well as the textual answers with their start characters in the context in answers.
• Data on which you should do the predictions is missing the labels, i.e, the answers.
• Your predictions should have the exact same format, i.e., a dict containing a list of answers
(with the single prediction) as answers.
