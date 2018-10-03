# GOM NHÓM TRÊN TẬP DATASET CALTECH256

Link dataset: https://www.kaggle.com/jessicali9530/caltech256

Scripts:

dataset.py:
  + Create Database (train/test):
    $python dataset createDB <id of database> <percent of training>
  + Extract features:
    $python dataset extractfeat <type of features>
  
clustering.py: cluster dataset
  $python clustering.py kmeans <the number of cluster>
  
accuracy.py:  evaluate model
$python accuracy.py <id of dataset>

  
