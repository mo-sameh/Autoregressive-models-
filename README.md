# Autoregressive Model
*Disclaimer:* This is a part of a greater project where we experimented with generative models, you can find the complete project at [repo](https://github.com/MRSAIL-Mini-Robotics-Software-AI-Lab/GANVAS-models)

In this repo, I'll introduce my contribution to the project where I implemented pixelCNN and gatedPixelCNN models using pytorch. For 
pixelCNN I've implemented the following architecture:

![PixelCNN architecture](resources/PIXELCNN_ARCH.PNG)



And for the gatedPixelCNN, the main difference is replacing the Relu activation function with a gated function, the architecture mainly consists of gated-Blocks that consist of the following components:

<img src="resources/gated_block.png" alt="drawing" width="800"/>

## Results:
*PixelCNN samples:*

<img src="resources/pixelCNN_shapes.PNG" alt="drawing" width="300"/>

<img src="resources/pixelCNN_coloredShapes.PNG" alt="drawing" width="300"/>

<img src="resources/pixelCNN_binary_mnist.PNG" alt="drawing" width="300"/>




*GatedPixelCNN samples :*




<img src="resources/gated_colored_shapes.PNG" alt="drawing" width="300"/>

<img src="resources/gated_mnist_4bits.PNG" alt="drawing" width="300"/>

<img src="resources/colored_mnist.PNG" alt="drawing" width="300"/>
