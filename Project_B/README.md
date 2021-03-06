# ECE1512 – Project B Knowledge Distillation for Building Lightweight Deep Learning Models in Visual Classification Tasks

This project aims to implement knowledge distillation on two datasets, MNIST and MHIST. When training the student model using the teacher model, we need to consider the effect of hyperparameters alpha and temperature on knowledge distillation. A better model can be obtained by tune these two hyperparameters. Also, we need to compare the difference between student model with KD and student model without KD to understand the role of KD. We also use XAI methods to help understand the performance of the model. Based on the original KD, we also learn the further KD approach of TAKD and compare the student model obtained by KD and TAKD.

We used RISE as our XAI Methods to explane all the models and we use TAKD as our state-of-the-arts KD algorithm.





TASK 1: KNOWLEDGE DISTILLATION IN MNIST DATASET  => Project_B_Supp/Task1_final.ipynb

(The model statement of task 1 is saved in Project_B_Supp/model_state_task1.)

TASK 2: KNOWLEDGE DISTILLATION IN MHIST DATASET  => Project_B_Supp/Task2_final.ipynb

(The model statement of task 2 is saved in Project_B_Supp/model_state_task2.)


