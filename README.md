# LBP-face-recognition-Confusion-Matrix
OpenCV LBP face recognition with  Confusion Matrix to easly calculate Metrics

you will need open cv and DNN coffee model to work with this code.

1st Step//------------------------------------------\\1st Step 

if you have a database image you have to split it into, trainning part and test part, you have aslo to rename all persons by their names followed by its class number and identification number 
Exemple: Alan Grant.1.1 ----> its the first occurence of the first person in the dataset
         Mac Malone.3.2 ----> its the second occurence of the third person in the dataset

/!\
you can change this formulation by modifing the split into the aprentissage code (Cell number 5)
         
2nd Step//------------------------------------------\\2nd Step 

Now you can start the training, it will show you how much faces the programm trained after its end
Now the model is trained you can start the test, but first to calculate the matrice confusion, we will need the IDs of each person on the test set (cell number 6)
the NAMES list must contain same caracter of the labeled images


3nd Step//------------------------------------------\\3nd Step

Now you can exe the rest of the cells code and it will print the confusion matrix

![Alt text](https://github.com/Altarois/LBP-face-recognition-Confusion-Matrix/blob/master/images/confusion%20matrix.PNG?raw=true "Title")

