# Bot Detection


## BERT Classification Approach


## T5 Classification Approach

In this approach, we use the popular T5 model by google and frame the Bot classification problem as a generative task. We maek use of the popular library for instruction tuned T5 modelling (InstructABSA) which has a T5Classifer inbuilt API. 

As part of the T5Classifier, we insturction tune the model by adding the definition of task followed by 2 positive, negative and neutral examples to every sample in the training set to provide more contextual information. 

The notebook can be found \href{here}{}.
