import numpy as np
from keras.datasets import fashion_mnist
(X_train, _), (_, _) = fashion_mnist.load_data()
X_train = (X_train.astype(np.float32) - 127.5) / 127.5
X_train = np.expand_dims(X_train, axis=-1)
<img width="1456" height="314" alt="501270122-f5734611-f007-48bc-8add-993ed91ccb3e (1)" src="https://github.com/user-attachments/assets/1d5bf47c-4c99-4f72-b275-4ab3648f2724" />
