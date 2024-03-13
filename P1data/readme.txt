Here you will find the weights W^{(1)} through W^{(7)} in the text files W1.txt through W7.txt. In addition, WS.txt contains W^{(s)}, XC.txt contains the compression data, XT.txt contains the test data, and y.txt contains the true labels for the test data. The model gets about 81% accuracy.

For XC and XT each column represents a data point (i.e., a 28 x 28 grayscale image reshaped into a vector of length 784 with values between -1 and 1). The associated labels are encoded as 0 through 9.

All matrices are stored in plain text files with commas delineating columns and newlines delineating rows. For reference (so you can make sure you are reading files correctly), the size of XC should be 784 x 1024 and XT is 784 x 4992. 