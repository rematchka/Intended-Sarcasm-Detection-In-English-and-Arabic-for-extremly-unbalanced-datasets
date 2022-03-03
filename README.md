# Saracsm-detection-for-extremly-unbalanced-dataset
This repo contains work carried out for SemEval 2022 Task 6: iSarcasmEval: Intended Sarcasm Detection In English and Arabic,

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


## Results
1. `Different model results for Task A En & Ar on official test-set`
![Alt text](Results/TaskA_En.png?raw=true "Title")
![Alt text](Results/TaskA_Ar.png?raw=true "Title")
2. `Different model results for Task B En  on official test-set`
![Alt text](Results/Task_B.png?raw=true "Title")
3. `Different model results for Task C En & Ar on official test-set`
![Alt text](Results/Task_C.png?raw=true "Title")


