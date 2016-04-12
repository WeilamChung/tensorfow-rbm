# rbm-ae-tf
Tensorflow implementation of Restricted Boltzman Machine and Autoencoder for layerwise pretraining of Deep Autoencoders with RBM. Idea is to first create RBMs for pretraining weights of autoencoder. In this implementation you can also use tied weights of autoencoder.

More in this paper:

##### https://www.cs.toronto.edu/~hinton/science.pdf

I was inspired with these implementations but need to refactor them and improve them(thanks):
###### https://www.snip2code.com/Snippet/1059693/RBM-procedure-using-tensorflow
###### https://gist.github.com/saliksyed/593c950ba1a3b9dd08d5

I used similar api for RBM and Autoencoder classes to models from official tensorflow/models.

Feel free to make updates, repairs. You can enhance implementation with some tips from:

> https://www.cs.toronto.edu/~hinton/absps/guideTR.pdf

Check test-au.py and test-rbm.py for usages!
