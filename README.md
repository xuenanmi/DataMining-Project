# DataMining-Project
Required package:

import deepchem as dc,   https://github.com/deepchem/deepchem#installation
import numpy as np
import pandas as pd
from sklearn.ensemble import RandomForestClassifier
from sklearn.svm import SVC

Run “clean-data.ipynb” to clean the original data set “CehmokineReceptor.csv”, generate the final input file “Input_Pos10Neg10.csv”, and split “Input_Pos10Neg10.csv” into “train_dataset” and “test_dataset” (because I have generate the train set and test set, and put them in folder, you can use them directly to run models)

Base method1 –Random Forest “Base1-RandomForest.ipynb”

Base method2 –SVM “Base2-SVM.ipynb”

Proposed framework  “Proposed-method.ipynb” 
