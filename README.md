Usage
1. prepare the training and testing datasets by following the format in Sample folder
2. run the command "java -jar EvoCleave.jar Sample 16 0" to obtain the result. EvoCleave.jar takes three parameters. The first parameter is the working directory, the second parameter is the value of hyperparameter C and the last one is the kernel type of SVM. Possible values for the kernel types of SVM are listed as below.

* Linear Kernel: 0
* Polynomial Kernel = 1
* Radial Basis Kernel = 2
* Sigmoid Kernel = 3
* Precomputed Kernel = 4

Note: Java SE Runtime Environment 8 should be installed at least before usage.
