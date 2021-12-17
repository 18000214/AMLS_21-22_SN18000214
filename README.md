# AML
tracking applied machine learning coursework

introduction:
"Task_A_Binary_task_full_code" is the code for Task A, which enables classification of brain with tumor and brain wothout tumor;
"Task_B(Multiclass_task)main" is the code for Task B, which enables classification of different types of tumor in brain;
"data_preprocessing" and "utils" are used with "Task_B(Multiclass_task)main" (should be put in same files), to perform data preprocessing and plotting separatively, also "data_preprocessing" and "utils" should be python file.

organization of the files:
there should be 4 folders named "code", "dataset", "result", & "model", all these 4 folder should be inside one folder;
inside "code" folder, all code mentioned in introduction should be put inside this folder;
inside "dataset" folder, 2 folders should be construct, one of it called "train", the other called "test". Inside "train" folder, put all training image and train label (rename it as "train_label" in excel file) in "train" folder, inside "test" folder, put all testing image and test label (rename it as "test_label" in excel file) in "test" folder

The role of each file:
"code" folder is used to save codes;
"dataset" folder should atore all data set;
"result" folder will store the plot in task_b;
"model" folder will store all trained models.

How to run code:
1. put all folders and files in right path with right name
2. open the files "Task_A_Binary_task_full_code" or "Task_B(Multiclass_task)main" in Jupyter notebook, press run, if any library did not installed, use pip install first, and run again

Necessary packages or header files:
opency-python, torchvision

