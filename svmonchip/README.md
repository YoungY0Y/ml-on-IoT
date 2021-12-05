### SVM model on audio detection, performed directly on arduino board
The model is implemented through sklearn's svm package with python, then converted into c++ code for 
arduino via micromlgen package.

To run, simply copy the sketch described by the folder on arduino IDE and run on the board.

The model is able to achieve a 75% accuracy on cross-validation training, and has an inference latency of 8ms
