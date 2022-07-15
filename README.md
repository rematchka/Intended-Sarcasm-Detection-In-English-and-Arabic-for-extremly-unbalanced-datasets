# Saracsm-detection-for-extremly-unbalanced-dataset
This repo contains work carried out for SemEval 2022 Task 6: iSarcasmEval: Intended Sarcasm Detection In English and Arabic.

This github is an implementation for accepted manuscript titled `reamtchka at SemEval-2022 Task 6: Investigating the effect of different loss functions for Sarcasm detection for unbalanced datasets`.

## Overview
This repo contains the system implementation used in SemEval-2022 Task 6: Intended Sarcasm Detection
in English and Arabic. Achieving 20th, 3rd places for task A, 16th place for task B, and
10, 6th places for task C on the leaderboard. We proposed a voting classifier between different
Bert-Based KimCNN models which are trained on modified loss functions in order to
improve model performance for an extremely unbalanced dataset and handcrafted features
with machine learning models as SVM. The main contributions of our system are 1) Identifying
appropriate loss functions to help train Bert-Base models and Deep learning models in
presence of extremely unbalanced datasets, 2) Investigating the importance of different layers
in Bert-Base models. 

[Publised paper](https://aclanthology.org/2022.semeval-1.126/).

[Presentation slides, Poster and Video](https://underline.io/events/325/sessions/11192/lecture/55786-reamtchka-at-semeval-2022-task-6-investigating-the-effect-of-different-loss-functions-for-sarcasm-detection-for-unbalanced-datasets).

[Dataset](https://github.com/iabufarha/iSarcasmEval).


If you find code/work useful, please consider citing
```
@inproceedings{abdel-salam-2022-reamtchka,
    title = "reamtchka at {S}em{E}val-2022 Task 6: Investigating the effect of different loss functions for Sarcasm detection for unbalanced datasets",
    author = "Abdel-Salam, Reem",
    booktitle = "Proceedings of the 16th International Workshop on Semantic Evaluation (SemEval-2022)",
    month = jul,
    year = "2022",
    address = "Seattle, United States",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.semeval-1.126",
    pages = "896--906",
    abstract = "This paper describes the system used in SemEval-2022 Task 6: Intended Sarcasm Detection in English and Arabic. Achieving 20th,3rd places with 34{\&} 47 F1-Sarcastic score for task A, 16th place for task B with 0.0560 F1-macro score, and 10, 6th places for task C with72{\%} and 80{\%} accuracy on the leaderboard. A voting classifier between either multiple different BERT-based models or machine learningmodels is proposed, as our final model. Multiple key points has been extensively examined to overcome the problem of the unbalance ofthe dataset as: type of models, suitable architecture, augmentation, loss function, etc. In addition to that, we present an analysis of ourresults in this work, highlighting its strengths and shortcomings.",
}
```


## Results
1. `Different model results for Task A En & Ar on official test-set`
![Alt text](Results/TaskA_En.png?raw=true "Title")
![Alt text](Results/TaskA_Ar.png?raw=true "Title")

2. `Different model results for Task B En  on official test-set`
![Alt text](Results/Task_B.png?raw=true "Title")

3. `Different model results for Task C En & Ar on official test-set`
![Alt text](Results/Task_C.png?raw=true "Title")


