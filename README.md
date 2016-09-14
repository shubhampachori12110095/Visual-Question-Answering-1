# Visual Question Answering implementations in Keras

Various implementations of Visual Question Answering problem in keras. Current implementation only supports yes/no type questions. Currrently following models are implemented:

1. MLP + BoW model : VGGnet (pre-trained) for image embedding and Bag Of Words model (avg. of word vectors) for question embedding with a MLP on top of it for classifying response of question as yes/no

# Requirements

1. Theano/Tensorflow
2. Keras
3. Numpy
4. VQA Api


