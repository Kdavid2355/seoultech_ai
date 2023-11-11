# seoultech_ai
University class practice code

### 1. Build Model with FashionMNIST Dataset Part1, 2

The FashionMNIST dataset consists of 60,000 training and 10,000 test images, spread across 10 categories of fashion items, offering a more challenging alternative to the classic MNIST dataset.
A model has been constructed and assessed based on this dataset. Part 1 uses only a single linear layer. In Part 2, multiple layers are utilized through nn.Sequential, and each layer is complemented with nn.Linear and nn.ReLU (an activation function). This arrangement allows for more extensive computations and the learning of more complex patterns, thereby enabling an improvement in accuracy.

Part 1 Accuracy: 0.8438  [[code](https://github.com/Kdavid2355/seoultech_ai/blob/main/FashionMNIST_PyTorch_Tutorial1.ipynb)]  |  Part 2 Accuracy: 0.8787 [[code](https://github.com/Kdavid2355/seoultech_ai/blob/main/FashionMNIST_PyTorch_Tutorial2.ipynb)]

### 2. Build Model with CIFAR-10 Dataset Part1, 2

The CIFAR-10 dataset consists of 60000 32x32 color images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. Unlike the first assignment with FashionMNIST, CIFAR-10 contains RGB images, leading to a three-dimensional data structure. Therefore, using the same model from the FashionMNIST_PyTorch_Tutorial2 for CIFAR-10, as demonstrated in Part 1, results in a reduced accuracy of 0.5485. To improve performance on CIFAR-10, Part 2 employs a Convolutional Neural Network (CNN) structure, which enhances the model's capability.

Part 1 Accuracy: 0.5485  [[code](https://github.com/Kdavid2355/seoultech_ai/blob/2112c3811646cccfc5d93fcf882e322b7e95a378/CIFAR_10_PyTorch_Tutorial1.ipynb)]  | Part 2 Accuracy: 0.7176    [[code](https://github.com/Kdavid2355/seoultech_ai/blob/2112c3811646cccfc5d93fcf882e322b7e95a378/CIFAR_10_PyTorch_Tutorial1.ipynb)]



