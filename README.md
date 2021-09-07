# CS224n neural network for question answering (SQuAD2) in Tensorflow

This notebook is based on the [CS224n class](http://web.stanford.edu/class/cs224n/). The notebook implements the neural baseline model in Tensorflow as described in the class [final project (IID SQuAD track)](http://web.stanford.edu/class/cs224n/project/default-final-project-handout-squad-track.pdf). The difference is that the CS224n model is implemented in PyTorch, and here you can see how to build the same neural network but in Tensorflow.

The implementation follows neural design described in Section 4 of the project write up. To prepare and preprocess data run `setup.py` as described in Section 2.2.

The final model has an attention layer and looks as following:

![image](https://user-images.githubusercontent.com/34798874/132378919-52c8e643-65e0-4b5f-acc8-4c7a3adf7bdf.png)
