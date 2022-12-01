# CS 626 Project
This project was the basic implementaion of a [research paper](<https://arxiv.org/pdf/1712.03935.pdf>) as a part of the course project.

## Folder Related Details
The Code folder contains all the jupyter notebooks required for the implementation of the entire project and the Data folder contains all the files required for running the code.

## How to run the Code ?
1. First run the Create_Dataset.ipynb to generate the dataset in a desired format
2. This will create two files namely train_Set.csv and test_Set.csv
3. Then run Neural_Features.ipynb , External_Features.ipynb, Statistical_Features.ipynb and these will require the files train_Set.csv and test_Set.csv
4. This will generate 6 feature files , 2 related each to train and test of a particular type of feature
5. Then using these feature files, one can train the model using Final_Model.ipynb and it will automatically save the model into a pkl file
6. Using the pickled model file, one can test the score and accuracy using Model_Accuracy.ipynb
7. Demo of the implemented code can be done using Model_Demo.ipynb