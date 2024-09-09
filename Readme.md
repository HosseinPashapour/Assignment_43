# Assignment 43
# Machine learning
##  KNN🐟

## 1.Finding Nemo

I use KNN algorithm for two classes which include nemo and background.
I use a picture of nemo for training. 
At first, In this picture, I use opencv library to separate nemo pixels from its background.
Then I use nemo pixels as first class and background pixels as second class and I made a trainng data with these two class.
The features are Hue, Sturation and Value of each pixel.

In the next step I made a label matric for training data.


Then I fit KNN with train data.

After that I give a new picture of nemo family to my algorithm and the out put of algorithm is a picture that inculde just the family member of nemo without background.

At the end I made a finding nemo class that get a family member of nemo and return that picture include family member of nemo without background.

## How to Install
Run following commend :
```
pip install -r requirments.txt
```

## How to Run
```
Run Finding_Nemo.ipynb file in jupyter notebook
```

## Input

<img src="Input\Mynemo.jpg" width="550">
<img src="Input\Abjie-nemo.jpg" width="550">

## Results

The Diagram of fruits with new three data:


<img src="Output\White_Mask.png" width="550">
<img src="Output\Black_Mask.png" width="550">
<img src="Output\Orange_Mask.png" width="550">
<img src="Output\Final_Result.png" width="550">
<img src="Output\Final_Mask.png" width="550">

-----------------------------------------

## 2.Finding Dori

I use KNN algorithm for two classes which include dori and background.
I use a picture of dori for training. 
At first, In this picture, I use opencv library to separate dori pixels from its background.
Then I use dori pixels as first class and background pixels as second class and I made a trainng data with these two class.
The features are Hue, Sturation and Value of each pixel.

In the next step I made a label matric for training data.


Then I fit KNN with train data.

After that I give a new picture of dori family to my algorithm and the out put of algorithm is a picture that inculde just the family member of dori without background.

At the end I made a finding dori class that get a family member of dori and return that picture include family member of dori without background.
## How to Install
Run following commend :
```
pip install -r requirments.txt
```

## How to Run
```
Run Finding_Dori.ipynb file in jupyter notebook
```

## Input

<img src="Input\Dori.jpg" width="550">
<img src="Input\Abji_Dori.jpeg" width="450">

## Results

The Diagram of fruits with new three data:


<img src="Output\Dory_Blue Mask.png" width="550">
<img src="Output\Dory_Yellow_Mask.png" width="550">
<img src="Output\Result_of_train_image.png" width="550">
<img src="Output\Dory_Final_Mask.png" width="550">
<img src="Output\Dory_Final_Result.png" width="450">


-----------------------------------------

## 3.IRIS Dataset

We have 3 classes:
- Setosa
- Versicolour
- Virginica

Features are:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

## How to Install
Run following commend :
```
pip install -r requirments.txt
```

## How to Run
```
Run Iris.ipynb file in jupyter notebook
```


## Scores of different n_neighbors
   | k  | Accuracy of ``scikit-learn KNN algorithm`` (%) | 
   |----|--------------|
   | 3  |  [0.9333] |
   | 5  |  [0.9666] |
   | 7  |  [1.0] |
   | 9  |  [1.0] |
   | 11  |  [0.9666] |

## Confusion matrix of test dataset:

<img src="Output\Confusion_Matrix.png" width="450">


-----------------------------------------

## 4.Breast Cancer Dataset From Sklearn

I use this dataset to solve an Breast tumor classification.
At first we shoud create train and test dataset.
then fit the algorithm with trainig data.

The Knn algorithm has a parameter which name is K.
I set K to 3,5,7,9,11.

and then use test data to evaluate the algorithm with different K. 

In the result part you can see the table of Accuracy for different K.


## How to Install
Run following commend :
```
pip install -r requirments.txt
```

## How to Run
```
Run Breast_Cancer.ipynb file in jupyter notebook
```

#### Breast Cancer dataset
  | k | Accuracy |
  | --------- |:---:|
  |  1 |  0.921053 |
  |  3 |  0.929825 |
  |  5 |  0.938596 |
  |  7 |  0.947368 |
  |  9 |  0.947368 |
  | 11 |  0.947368 |
  | 13 |  0.947368 |
  | 15 |  0.938596 |
  

## Confusion matrix of test dataset:

<img src="Output\Confusion_Matrix_Breast_Cancer.png" width="450">

-----------------------------------------


