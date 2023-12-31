# seoultech_ai
University class practice code

## Machine Learning 2

### 1. Build Model with FashionMNIST Dataset Part1, 2

The FashionMNIST dataset consists of 60,000 training and 10,000 test images, spread across 10 categories of fashion items, offering a more challenging alternative to the classic MNIST dataset.
A model has been constructed and assessed based on this dataset. Part 1 uses only a single linear layer. In Part 2, multiple layers are utilized through nn.Sequential, and each layer is complemented with nn.Linear and nn.ReLU (an activation function). This arrangement allows for more extensive computations and the learning of more complex patterns, thereby enabling an improvement in accuracy.

Part 1 Accuracy: 0.8438  [[code](https://github.com/Kdavid2355/seoultech_ai/blob/main/MachineLearning2/CIFAR_10_PyTorch_Tutorial1.ipynb)]  |  Part 2 Accuracy: 0.8787 [[code](https://github.com/Kdavid2355/seoultech_ai/blob/main/MachineLearning2/CIFAR_10_PyTorch_Tutorial2.ipynb)]



### 2. Build Model with CIFAR-10 Dataset Part1, 2

The CIFAR-10 dataset consists of 60000 32x32 color images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. Unlike the first assignment with FashionMNIST, CIFAR-10 contains RGB images, leading to a three-dimensional data structure. Therefore, using the same model from the FashionMNIST_PyTorch_Tutorial2 for CIFAR-10, as demonstrated in Part 1, results in a reduced accuracy of 0.5485. To improve performance on CIFAR-10, Part 2 employs a Convolutional Neural Network (CNN) structure, which enhances the model's capability.

Part 1 Accuracy: 0.5485  [[code](https://github.com/Kdavid2355/seoultech_ai/blob/main/MachineLearning2/FashionMNIST_PyTorch_Tutorial1.ipynb)]  | Part 2 Accuracy: 0.7176    [[code](https://github.com/Kdavid2355/seoultech_ai/blob/main/MachineLearning2/FashionMNIST_PyTorch_Tutorial2.ipynb)]


## AI System

### 1. Classifying plant leaves and detecting diseases using AI

This project classifies types of plant leaves and the presence of diseases in leaf images. It provided an opportunity to learn about the concepts of CNN (Convolutional Neural Networks) and Transfer Learning.

[[code](https://github.com/Kdavid2355/seoultech_ai/blob/main/AISystem/Classifying_plant_leaves_and_detecting_diseases_using_AI.ipynb)]

### 2. Anomaly Detection on BattleGround Data by AutoEncoder

This is a practice to detect cheaters using 1 million game data records from PUBG. Using a CSV file with 28 columns, an autoencoder model is created to identify the cheaters.

[[code](https://github.com/Kdavid2355/seoultech_ai/blob/main/AISystem/Anomaly_Detection_on_BattleGround_Data_using_Autoencoder.ipynb)]

### 3. VQA Baseline Practice 

VQA, which stands for Vision Question Answering, is one of the most notable topics in recent times. Through this project, it was possible to gain basic knowledge of VQA and observe trends in the related field.

[[code](https://github.com/Kdavid2355/seoultech_ai/blob/main/AISystem/VQA_baseline_final.ipynb)]

### 4. Anime translator 

This project involves using CycleGAN to transform images into animations. Through this exercise, I was able to learn the principles of CycleGAN and experiment with methods of image transformation. The data used was "Selfie2Anime" from Kaggle.

[[code](https://github.com/Kdavid2355/seoultech_ai/blob/main/AISystem/anime_translation_final.ipynb)]
