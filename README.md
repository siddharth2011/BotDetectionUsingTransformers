# Bot Detection using Transformers


## BERT Classification Approach


## T5 Classification Approach

In this approach, we use the popular T5 model by google and frame the Bot classification problem as a generative task. We maek use of the popular library for instruction tuned T5 modelling ([InstructABSA](https://github.com/kevinscaria/InstructABSA)) which has a T5Classifer inbuilt API. 

As part of the T5Classifier, we insturction tune the model by adding the definition of task followed by 2 positive, negative and neutral examples to every sample in the training set to provide more contextual information. 

The notebook can be found [here](https://github.com/siddharth2011/Bot_Detection/blob/main/T5_Bot_Detection.ipynb).

## Classical ML approach (SVM)

In this approach, we use two models. Logisitc Regression and SVM models. We use TF-IDF to vectorize text data and then convert it into a supervised classification task.  The notebook can be found under SVMClassification. 

Libraries needed to run this are present in requirements.txt
## Model Comparisons
| Model Name  | Accuracy |
| ------------- | ------------- |
| Bert Classifier| 90.86% |
| TkInsturct Classifier| 51.50% |
| SVM Classifier| 70.9%|

## References
<a id="1">[1]</a> 
Scaria, K., Gupta, H., Goyal, S., Sawant, S. A., Mishra, S., & Baral, C. (2023). InstructABSA: Instruction Learning for Aspect Based Sentiment Analysis. arXiv preprint [arXiv:2302.08624](https://arxiv.org/abs/2302.08624).



<a id="2">[2]</a> 
Cheng-Caverlee-Lee September 2009 - January 2010 twitter scrape . Internet Archive. (2010, November 7). Retrieved from https://archive.org/details/twitter_cikm_2010

<a id="3">[3]</a> 
Dukić, D., Keča, D., & Stipić, D. (n.d.). Are you human? detecting bots on Twitter using Bert | IEEE conference ... Retrieved from https://ieeexplore.ieee.org/document/9260074/

<a id="4">[4]</a> 
Feng, S., Wan, H., Wang, N., Luo, M., & Li, J. (2021, August 27). TwiBot-20: A comprehensive twitter bot detection benchmark - arxiv. Retrieved from https://arxiv.org/pdf/2106.13088v4.pdf

