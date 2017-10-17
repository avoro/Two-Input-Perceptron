# Two-Input-Perceptron

Exercise description:
The vectors in the ordered set defined below were obtained by measuring the weight and ear lengths of toy rabbits and bears in the Fuzzy Wuzzy An- imal Factory. The target values indicate whether the respective input vec- tor was taken from a rabbit (0) or a bear (1). The first element of the input vector is the weight of the toy, and the second element is the ear length.

p1 = [1;4] t1 = 0
p2 = [1;5] t2 = 0
p3 = [2;4] t3 = 0
p4 = [2;5] t4 = 0
p5 = [3;1] t5 = 1
p6 = [3;2] t6 = 1
p7 = [4;1] t7 = 1
p8 = [4;2] t8 = 1

Use MATLAB to test the resulting weight and bias values against the input vectors.

train_network.m

train_network([[1;4],[1;5],[2;4],[2;5],[3;1],[3;2],[4;1],[4;2]],[[0],[0],[0],[0],[1],[1],[1],[1]])

Add input vectors to the training set to ensure that the decision boundary of any solution will not intersect one of the original input vectors (i.e., to ensure only robust solutions are found). Then retrain the network. Your method for adding the input vectors should be general purpose (not designed specifically for this problem).

test_result.m

test_result([[1;4],[1;5],[2;4],[2;5],[3;1],[3;2],[4;1],[4;2]],[[0],[0],[0],[0],[1],[1],[1],[1]])
