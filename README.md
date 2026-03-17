# deep-learning-portfolio
CNN image classifier trained on CIFAR-10 achieving > 85% validation accuracy using Keras, data augmentation, and AdamW optimization.
This porject builds and evaluates a Convolutional Neural Network (CNN) for multiclass image classification using the CIFAR-10 dataset (10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck). 
The model is implemented in Keras and features a two-block convolutional architecture with Batch Normalization, progressive Dropout, and on-the-fly data augmentation (random flips, rotation, and zooms) to prevent overfitting. Additionally, it is compiled witht eh AdamW optimizer and trained with early stopping to further prevent overfitting. The target is >85% validation accuracy within 40 epochs. 
