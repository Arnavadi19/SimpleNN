Altering the learning rate:

epochs = 25, batch_size = 64, activation_fn = ReLU, loss_fn = crossEntropy
SimpleNN optimal learning rate = 0.001
AlexNet optimal learning rate = 0.0001

Altering the batch_size:
epochs = 25, learning rate= 0.0001, activation_fn = ReLU, loss_fn = crossEntropy
SimpleNN optimal batch_size = 8,16,32 had similar results
AlexNet optimal batch_size = 8

Using different activation functions:
epochs = 25, learning rate= 0.0001, batch size  = 32, loss_fn = crossEntropy
SimpleNN -> GeLU performed the best. ReLU, SeLU and SiLU were comparable and sigmoid was the worst.
AlexNet -> GeLU, SeLU and SiLU gave similar results.

For different number of epochs:
learning rate= 0.0001, activation_fn = ReLU, batch size  = 32, loss_fn = crossEntropy
