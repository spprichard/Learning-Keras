# Learning Keras

## First Attempt
**Model:**

60000 training samples

10000 test samples

### Layer (type), Output Shape, Param #
_________________________________________________________________
dense_1 (Dense), (None, 10), 7850

activation_1 (Activation), (None, 10), 0
_________________________________________________________________

Total params: 7,850
Trainable params: 7,850
Non-trainable params: 0


**Results**

Test Score:  0.277385849932

Test accuracy:  0.9227


## Second Attempt
**Model:**

60000 training samples

10000 test samples

### Layer (type), Output Shape, Param #
dense_1 (Dense), (None, 128), 100480

activation_1 (Activation), (None, 128), 0

dense_2 (Dense), (None, 128), 16512

activation_2 (Activation), (None, 128), 0

dense_3 (Dense), (None, 10), 1290

activation_3 (Activation), (None, 10), 0

Total params: 118,282

Trainable params: 118,282

Non-trainable params: 0
_________________________________________________________________


**Results**

Test Score:  0.18597283092

Test accuracy:  0.9462
