**feed-dict** is the slowest possible way to pass data to TensorFlow and it must be avoided. The optimal way to feed data into your models is to use an input pipeline so that the GPU and CPU are utilized properly. Tensorflow **tf.data** API helps to build flexible and efficient input pipelines.

This repo contains scripts for building input pipelines with tensorflow.