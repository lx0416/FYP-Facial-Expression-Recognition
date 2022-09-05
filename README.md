# FYP-Facial-Expression-Recognition
Reference: Deep Learning with Python (DWLP)

Other files were unable to be uploaded as the file sizes were too big. Such files include the fer2013 dataset, the saved models and the directory containing the process of hyperparameter tuning, as well as many others. The files with the extension .h5 are the saved models that could be uploaded. test.csv and train.csv are files which were saved in Notebook 1.

Dataset can be acquired from Kaggle at https://www.kaggle.com/datasets/msambare/fer2013

## Overview
### Notebook 1_Models A, B and C.ipynb
This notebook should be the first to run. It contains data preparation of which certain files will be saved and then loaded in other notebooks. Some files that were created from the execution of the codes in this notebook were unable to be loaded due to their large file size. Notebook 1 also contains the definition of Models A, B and C, which were implemented to test the hypothesis of more complex machine learning models will perform better.

### Notebook 2_Optimisation and Model D.ipynb
This notebook is a continuation from Notebook 1, to clearly distinguish the purpose of the notebooks, which is to test each of the hypotheses stated in the report. Notebook 2 contains the process of hyperparameter tuning and Model D. In addition, Model D was compared to a supplementary model to test the effects of data augmentation. Model D was then compared to the winning model from Notebook 1 to test the second hypothesis: transforming the data to make up for the small dataset will improve the generalizability of the model. Unfortunately, the directory of results from hyperparameter tuning had files that were too large to be uploaded.

### Notebook 3_Transfer learning and Model E.ipynb
This notebook is a continuation from Notebook 2, incorporating transfer learning to test the third hypothesis: Transferring of knowledge over related tasks will overcome the shortcomings of a small training set and improve the accuracy of the model. Notebook 3 contains the utilization of 5 different pretrained convolutional neural networks and the selection of the best performing one will be represented as Model E. Model E will be compared to all other models to decide on the final model. Unfortunately, all of the models that were saved in this notebook could not be uploaded due to their large files size. However, there is a live demonstration which was carried out to compare the predictions of Models D and E. 
