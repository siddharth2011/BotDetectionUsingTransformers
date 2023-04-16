# Bot Detection using Transformers


## BERT Classification Approach


## T5 Classification Approach

In this approach, we use the popular T5 model by google and frame the Bot classification problem as a generative task. We maek use of the popular library for instruction tuned T5 modelling ([InstructABSA](https://github.com/kevinscaria/InstructABSA)) which has a T5Classifer inbuilt API. 

As part of the T5Classifier, we insturction tune the model by adding the definition of task followed by 2 positive, negative and neutral examples to every sample in the training set to provide more contextual information. 

The notebook can be found [here](https://github.com/siddharth2011/Bot_Detection/blob/main/T5_Bot_Detection.ipynb).

## Classical ML approach (SVM)

## Model Comparisons
| Model Name  | Accuracy |
| ------------- | ------------- |
| Bert Classifier| 90.86% |
| TkInsturct Classifier| - |
| SVM Classifier| - |

## References
<a id="1">[1]</a> 
Dijkstra, E. W. (1968). 
Go to statement considered harmful. 
Communications of the ACM, 11(3), 147-148.
