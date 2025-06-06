# Comparative-Analysis-of-Classical-ML-and-Neural-Network-Models-for-Pig-Weight-Prediction

Obiajulu Emenike Ositanwosu1,2,5, Qiong Huang1,2*, Chukwunonso Henry Nwokoye3,5*, Yun Liang1,2, Chukwunonso O. Ositanwosu4

1. College of Mathematics and Informatics, South China Agricultural University, Guangzhou 510642, China.   ositanwosuobiajulu@yahoo.com ; qhuang@scau.edu.cn 
2. Guangzhou Key Laboratory of Intelligent Agriculture, South China Agricultural University, Guang-zhou, 510642, China. yliang@scau.edu.cn  
3. Trustworthy AI Lab, Ontario Tech University, Canada; chinonsonwokoye@gmail.com ; HenryChukwunonso.Nwokoye@ontariotechu.ca 
4. Department of Agricultural Economics & Extension, Nnamdi Azikiwe University, P.M.B. 5025, Awka, Nigeria. chynon24@yahoo.com 
5. Department of Computer Science, Nnamdi Azikiwe University, P.M.B. 5025, Awka, Nigeria


Abstract: 
Given the importance of pork and the intricacies of pig breeding in modern life, this study is aimed at predicting the body weight (BW) of pigs using two popular LSTM versions, machine learning, and ensemble algorithms. Additionally, the study evaluated the models' performances using several notable metrics. With the dataset of Duroc pigs, the study performed several experiments so as to address the bias resulting from feature selection, i.e., the impact of using a subset of data or using all input parameters. Additionally, K-fold cross-validation experiments were used to check the consistencies of results across the models. Based on several experiments alongside K-fold cross-validation, the bidirectional LSTM models (with Adam-ReLU optimizer and activation function pair) had higher R² and lower MSE values compared to the vanilla LSTM models. For boosting algorithms, the CatBoosting regressor performed well with 4 input features, while XGBoost and LightGBM regressors showed remarkable test R² values for all input features. For ensemble models, the stacking regressor gave somewhat better generalization (high test R² scores); bagging regressors are exceptional in performance during training while incurring the huge costs for training time and memory usage. The voting regressor offers an excellent compromise between computation time and memory efficiency and performance, as confirmed by K-fold experiments on the ensemble models. Finally, the essentiality of bias was discussed in view of the study outcomes and literature. Moreover, explainability techniques were used to highlight feature contributions and impact.


Note that the k-fold cross-validation for the ensemble models was done with cross_val_score on a separate notebook after it continued to run endlessly with the manual looping. 

# Code Availability 
The custom code used for the pig weight estimation experiments, including implementations of classical machine learning and neural network models, is openly available on GitHub and archived on Zenodo with the following DOI: 10.5281/zenodo.15605858. This ensures long-term accessibility and version control of the exact codebase described in this publication. The repository contains all necessary scripts, preprocessing steps, and instructions for replication.
