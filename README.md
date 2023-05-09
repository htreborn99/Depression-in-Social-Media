# IS460 G1T2 Source Code Readme

## Team Members

[Evelyn PEH Ting Yu]

[KOH Pei Ling]

[LAU Wei Ting]

[LYE Jian Yi]

[LUQMAN Juzaili Bin Muhammad Najib]

[SONG Yu Xiang]

## "Source Code" Folder Content

We divided our source code into 5 files based on the dependencies required by the deep learning model and language model combinations implemented, to ensure that the notebooks can be executed to completion without the need of restarting the kernel or changing versions in between. We also have a folder that stores the best models.

- ["models" folder]
    - This folder contains the best model saved based on the lowest validation loss for Deep Learning Implementations that have this feature, which is useful to ensure that the test data is passed to the model that uses the best weights from training. This will ensure that the test accuracy and loss will be optimal. 
    - Our team has saved the best model for the following implementations: All Bert and language model combinations, GPT with CNN & RNN, and ELMo with CNN. 
    - With these models, we can bypass running the training from scratch and can conveniently run the test cell with this models to obtain the test results.

- [Detecting Depression (BERT)_FINAL_EDIT.ipynb]
    - This file contains all the code for loading the raw Twitter dataset, data preprocessing, and EDA to obtain the cleaned dataset to be used in our Machine Learning and Deep Learning models.
    - This file contains all the BERT language model code implementations, including: BERT word embeddings, BERT with Traditional Classifiers (SVM, Gradientboost, Logistic Regression, Random Forest, Gaussian NB, and Decision Tree Classifier), BERT with RNN, Bert with CNN, BERT with LSTM, and BERT with Bi-LSTM
    - Feel free to comment/uncomment code cells wherever necessary to execute the file 
    - The file should be able to execute completely without error

- [Detecting Depression (ELMo)_FINAL_EDIT.ipynb]
    - This file contains all the code for loading the raw Twitter dataset, data preprocessing, and EDA to obtain the cleaned dataset to be used in our Machine Learning and Deep Learning models.
    - This file contains all the ELMo language model code implementations, including: ELMo word embeddings, ELMo with Traditional Classifiers (SVM, Gradientboost, Logistic Regression, Random Forest, Gaussian NB, and Decision Tree Classifier), ELMo with RNN, ELMo with CNN, ELMo with LSTM, and ELMo with Bi-LSTM
    - Feel free to comment/uncomment code cells wherever necessary to execute the file 
    - The file should be able to execute completely without error

- [Detecting Depression (GPT + LSTM & BiLSTM)_FINAL_EDIT.ipynb]
    - This file contains all the code for loading the raw Twitter dataset, data preprocessing, and EDA to obtain the cleaned dataset to be used in our Machine Learning and Deep Learning models.
    - This file contains the GPT language model code implementations specifically for GPT word embeddings, GPT with LSTM, and GPT with Bi-LSTM
    - Feel free to comment/uncomment code cells wherever necessary to execute the file 
    - The file should be able to execute completely without error

- [Detecting Depression (GPT + Traditional, CNN and RNN)_FINAL_EDIT.ipynb]
    - This file contains all the code for loading the raw Twitter dataset, data preprocessing, and EDA to obtain the cleaned dataset to be used in our Machine Learning and Deep Learning models.
    - This file contains the GPT language model code implementations specifically for GPT word embeddings, GPT with Traditional Classifiers (SVM, Gradientboost, Logistic Regression, Random Forest, Gaussian NB, and Decision Tree Classifier), GPT with RNN, and GPT with CNN
    - Feel free to comment/uncomment code cells wherever necessary to execute the file 
    - The file should be able to execute completely without error

- [Detecting Depression (Word2Vec)_FINAL_EDIT.ipynb]
    - This file contains all the code for loading the raw Twitter dataset, data preprocessing, and EDA to obtain the cleaned dataset to be used in our Machine Learning and Deep Learning models.
    - This file contains all the Word2Vec language model code implementations, including: Word2Vec with Traditional Classifiers (SVM, Gradientboost, Logistic Regression, Random Forest, Gaussian NB, and Decision Tree Classifier), Word2Vec with RNN, Word2Vec with CNN, Word2Vec with LSTM, and Word2Vec with Bi-LSTM
    - Feel free to comment/uncomment code cells wherever necessary to execute the file 
    - The file should be able to execute completely without error
