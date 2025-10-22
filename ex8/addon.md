import numpy as np
from keras.datasets import fashion_mnist
(X_train, _), (_, _) = fashion_mnist.load_data()
X_train = (X_train.astype(np.float32) - 127.5) / 127.5
X_train = np.expand_dims(X_train, axis=-1)
