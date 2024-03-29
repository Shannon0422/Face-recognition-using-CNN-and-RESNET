# Face Reognition using CNN and ResNet

**Dataset**: Face Recognition Dataset (https://www.kaggle.com/datasets/vasukipatel/face-recognition-dataset)

**Motivation**: Learn how CNN and ResNet work in identifying multiple people then compare the accuracy rate of each deep learning algorithm.

## Methodology:
### A. Convolutional Neural Network (CNN)
CNNs are a class of deep neural networks consisting of convolutional, pooling, and 
fully connected layers. Convolutional layers are the fundamental building blocks in CNNs. In a single convolutional layer, a kernel or filter defined on some small 
region of the given input is applied to the input through a sliding window and generates a feature map after that. This allows CNN to extract spatio-temporal features 
from the input. Pooling layers are usually inserted between consecutive convolutional layers, which reduce the number of learnable parameters while keeping significant 
features. At the end of a CNN, a fully connected layer integrates all the extracted features to generate an output.

### B. Residual Network (ResNet)
ResNet is a CNN where a residual block is introduced into the architecture. 
Adding more layers could significantly increase the accuracy but at the same time encountering the vanishing gradients problem, 
whereby gradients used to update networks become extremely small or reduced to zero as they backpropagate from the output layers to the earlier layers. 
This would result in slow convergence, low training stability and result in difficulties in capturing long-term dependencies. 
Hence, Residual Network (ResNet) was used to tackle the problem by introducing “skip connections” also known as the residual block, where a bypassing mechanism 
creates extra links from a single layer to a future layer skipping several intermediate layers. So instead of just learning the original function, 
the learned mapping becomes the sum of the original function and an identity mapping. This results in a more direct flow of gradients in the backpropagation process.

## Results and comparison:

