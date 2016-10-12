# googlenet-bn
Added batch normalization to googlenet to solve the slow training problem. 

The original googlenet require non-trivial initialization,
otherwise the training is very slow. 
The error does not reduce after 1~2 epoch.

By adding batch normalization after every convolutional layer, 
the network learns fast, obvious error reduction appears after 1~2 epoch. 
