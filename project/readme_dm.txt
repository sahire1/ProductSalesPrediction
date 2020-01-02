Name: Snehal anil ahire
This program is done in R that takes input as 2 files(product_distribution_training_set.txt, key_product_IDs.txt) given in project folder.
Inorder to get output ,run file name "finalfinal.R" and get output in output.txt file . I have run this on R studio and coded with the help of R language.
You may need to install the required libraries from R in this command on console:
install.packages('forecast', dependencies = TRUE)
replace forecast by any package that is needed to download.
you can say no to a dialog box that appears on the install command of lattice and ggplot2.

The method used is auto.arima and neural networks. Basic steps in algorithm:
1. Read the input file 
2. create an output matrix 
3. for entry from 1 to 101
4. convert to time series
5. fit fourier transform
6. fir neural network and arima model
7. select the one that is most accurate
8. copy the answer to output matrix