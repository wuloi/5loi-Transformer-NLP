Q1
1 point possible (graded)
Which of the following use cases can be framed as a token classification problem?  

Find the grammatical components in a sentence. 

Find the disease(s) mentioned in a sentence. 

Determine if a sentence is grammatically correct or not. 

Find the chunk of words in a sentence that answers a question.
 
 
Q2
1 point possible (graded)
How do we prepare and preprocess data for a token classification problem?  

Inputs and target labels need to have the same length, so padding and truncating may be required. 

Input words can produce several tokens, leading to more tokens than labels. 

Therefore, original labels need to be aligned with the tokens. 

A label is assigned to each input text.
 
 
Q3
1 point possible (graded)
Which of the following use cases can be framed as a text classification problem?  

Determine if the sentiment of a sentence is positive or negative. 

Determine the intent of a sentence. 

Summarize a long paragraph.
 
 
Q4
1 point possible (graded)
How do we prepare and preprocess data for a text classification problem?  

Each input text is paired with a class label. 

Only the inputs need to be tokenized. 

Padding is required for the labels.
 
 
Q5
1 point possible (graded)
Which of the following use cases can be framed as a sequence-to-sequence problem?  

Answer questions about a document. 

Translate a text from one language into another. 

Write short reviews of long documents. 

Determine if a sentence is factual.
 
 
Q6
1 point possible (graded)
How do we prepare and preprocess data for a sequence-to-sequence problem?  

Both the inputs and targets have to be tokenized. 

Only the inputs need to be tokenized. 

Only the targets need to be tokenized.
 
 
Q7
1 point possible (graded)
Which of the following question answering approaches did we use?  

Extractive question answering. 

Generative question answering. 

Rules-based approach.
 
 
Q8
1 point possible (graded)
How do we post-process model results for extractive question answering?  

The model generates the start and end positions of the answer, and we need to match them with the text that has the highest score in context. 

The model generates the start and end positions of the answer, and we have to decode the tokens into text. 

The model generates an answer, and we need to decode it.
 
 
Q9
1 point possible (graded)
When should pre-training a new model be considered?  

When there is no pre-trained model available for a specific language/domain. 

When there are concerns about the potential bias of existing pre-trained models. 

It's always recommended to build a model from scratch to get optimal performance.
 
 
Q10
1 point possible (graded)
What does transfer learning mean?  

It's when you want to fine-tune a pre-trained model on a new dataset so it could make predictions that are adapted for a specific use case. 

It's when you want to transfer knowledge from a pre-trained model to a new model by initializing it with the pre-trained model's weights. 

It's when you want to transfer knowledge from the data to a language model by training it from scratch.
 