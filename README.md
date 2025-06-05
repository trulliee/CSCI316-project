# CSCI316 Task 1
(10 marks)
Dataset: Dataset: The Superconductivty data
Source: https://archive.ics.uci.edu/ml/datasets/Superconductivty+Data
There are two files in this dataset: (1) train.csv contains 81 features extracted from 21263 superconductors
along with the critical temperature in the last column, (2) unique_m.csv contains the chemical formula broken
up for all the 21263 superconductors from the train.csv file. This task uses the first file.
(Reference: Sathishkumar et al.’s Building Research & Information paper in the above link, which is accessible
in the UOW digital library, i.e., https://www.uow.edu.au/library/)
Objective
The objective of this task is to implement an end-to-end data mining project by using the Python machine
learning library Scikit-Learn. This is a regression problem. The task is to predict critical temperature in the
superconductivity data.
Requirements
(1) Use stratified sampling to select 80% data for training and 20% for testing.
(2) Main steps of the project are (a) “discover and visualise the data”, (b) “prepare the data for machine
learning algorithms”, (c) “select and train models”, (d) “fine-tune the model” and (e) “evaluate the
outcomes”. You can structure the project in your own way. Some steps can be performed more than
once.
(3) In the steps (c) and (d) above, you must work with at least three machine learning algorithms.
(4) In step (b), define at least one new feature by using the User-Defined Transformer. This transformer
includes a parameter indicating whether use the new feature(s) or not. In step (d), fine-tuning step must
use this parameter (as a hyper parameter).
(5) Explanation of each step together with the Python codes must b
