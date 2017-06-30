# Classify MNIST dataset using TensorFlow

Run tf_mnist.py in local conda environment.
```
$ pip install tensorflow
$ az ml execute start -c local tf_mnist.py
```

Run tf_mnist.py in a local Docker container.
```
$ az ml execute start -c docker tf_mnist.py
```

Run tf_mnist.py in a Docker container in a remote machine. Note you need to create/configure myvm.compute.
```
$ az ml execute start -c myvm tf_mnist.py
```
