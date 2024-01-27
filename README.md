# 2024 Winter Natural Language Processing(NLP)
This is a repository for the programming assignments of the NLP study in winter 2024. The course materials are based on [CS224n](https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1214/) of Stanford University.

# Assignment 1
This assignment is demonstrating the basic usage of the pre-implemented NLP model using word vectors. The first half of the assignment are consisted of writing basic methods in python. The later half is a subset of the materials covered in DCCP class.

# Assignment 2
This is for the implementation of the inner workflow of the `Word2Vec` function. We evaluate the gradient of the loss function via the weight matrix and each center vectors. Then the word vector parameters are updated via SGD(Stochastic Gradient Descent). The model overall was trained by 40K iterations, which took around 8700s seconds in total. The result is accessible in `word_vectors.png

# Assignment 3
Now we start to use `pytorch` for implementation. We implement dependency parsing, where a sentence is parsed into a parse tree depending on their dependencies. The way to check which word is dependent to which is ML.
After 10 epochs each consisted of 1848 iterations, the final test `UAS` was 89.22, and average train loss was 0.07 which fits in the desired result.
