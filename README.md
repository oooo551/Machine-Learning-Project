# Machine-Learning-Project
A classification project to classify 30,000 grey-scale images with 10 labels.Each of the image is in the shape of 28x28.

This jupyter file includes all the code with three methods, OVO of logistic regression, OVA of logistic regression, and knn method.

The code is running from the first console to the last one and the last one before draw the confusion matrix is the main function to decide which model you choose and the optimisation method you use(if required).
  
For the mnist_predicate
(train_set_x, train_set_y, test_set_x, test_set_y, model_name, optimisation_name) function , 
input:train_set_x,train_set_y,test_set_x,test_set_y: preprocessed train x ,y and test x,y separately
the parameter model_name is the model you choose, and optimisation_name is the optimisation method you write in.
you can choose one of the following model method :"OVO","OVA"and "KNN" ,
you can choose the following optimisation method :"Momentum","TNC","gDescent".
hence the composisition could be :
mnist_predicate(train_set_x,train_set_y,test_set_x,test_set_y,"OVO","TNC ") 
mnist_predicate(train_set_x,train_set_y,test_set_x,test_set_y,"OVO","Momentum") 
mnist_predicate(train_set_x,train_set_y,test_set_x,test_set_y,"OVO","gDescent") 
mnist_predicate(train_set_x,train_set_y,test_set_x,test_set_y,"OVA"," ") 
mnist_predicate(train_set_x,train_set_y,test_set_x,test_set_y,"KNN"," ") 

Return : The predicated result of the model and optimisation method chosen
intermediate thing print out for this function : We can see the time used for each binary classification. The total time used and the accuracy at the end.
