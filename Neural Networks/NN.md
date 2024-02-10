# Fundamentals of Neural Networks

**Artificial Neurons** mimic the behavior of biological neurons (nerve cells) in the body.<br>

- In other words, with certain inputs there are generated outputs. 

Each neuron receives :
- multiple products of **inputs and random weights**
- **static bias** (unique to each neuron layer) is added
- appropriate **activation function** then decides the final value given out of the neuron, i.e., switches the neuron on or off.<br> There exist a variety of different activation functions available per nature of input values.
    - Mathematical or computational formular that helps neuron switch on or off.<br>

As each input enters node<br>
it gets multiplied by a weight value<br>
and the resulting output is either 
- observed or
- passed on to the next layer in the network. 

There is also:<br>
- a **Loss function** (input vs output) that must be calculated, once the output is generated and<br> 
- **Backpropagation** is then performed whereby weights are adjusted to minimize the losses. 

An **Artificial Neural Network** (or **Neural Network**) consists of layers of interconnected artificial neurons powered by activation functions that switch them either on or off. Each of the neurons performs a mathematical function that upon receiving inputs produces outputs. Neural Networks (NN) can be viewed as a set of algorithms that recognize hidden patterns and correlation in raw data, cluster, and classify it, while continuously learning and improving.<br> As in the case of traditional machine learning algorithms, there is a training phase, as well, with neural networks. 



<img src="https://www.w3schools.com/ai/img_neural_networks.jpg" 
alt="IBM Neural Network image"
width="300"
height="300"/>


**W<sup>3</sup> Neural Network Image**

The input data (Yellow) are processed against a hidden layer(Blue) and against an additional hidden layer (Green) to yield a final ouput (Red).

The series of hidden layers in the neural network applies transformations to input data.<br>
Within the nodes of hidden layers, the weights are applied<br>
Neural networks randomize weights and bias
- As the training continues, both parameters adjust toward desired values and correct output.

The **goal** is to find the optimal values of the weights. 

**Weights and Bias**

The weights self-adjust based on the difference between predicted outputs and training inputs.
**Bias and weights** have different influence on the input data
- **Bias**
    - Addresses how far off predictions are from intended value
    - Makes up the difference between function's output and intended input
    - Low Bias  
        - Network makes more assumptions about the output
    - High Bias
        - Less assumptions are made about the output.
- **Weights**
    - Viewed as strength of connection
    - affects the amount of influence change of input has on output
    - Low Weight   
        -No change on output
    - Large Weight        
        - Significant change on output.
- **Input layer**
    - Dimensions of input vector
- **Hidden layer**      
    - Intermediary nodes that divide the input space into regions with (soft) boundaries
    - Takes in set of weighted input and produces output through an activation function
- **Output layer**  
    - Output of neural network. 

# Perceptron: The simplest Neural Network

The **Perceptron** is the smallest representation of a neural network that enables feature detection in the input data. It accepts weighted inputs and obtains the output by applying the application function. The **Perceptron**
is also known as the **TLU**(threshold logic unit).<br>





<img src="https://www.w3schools.com/ai/img_perceptron.jpg" />


**W<sup>3</sup> Convolutional Neural Network**

The **Perceptron** is a **supervised learning algorithm** that classifies data into two categories, i.e., it is a **binary classifier**.

**Advantage**
- Can Implement Logic Gates

**Disadvantage**
- Can only learn linearly separable problems.

# Feedforward Neural Networks

The **simplest** form of neural networks where hidden layers may not be present and input data travels in only one direction, passing through the input nodes to the output nodes.<br>
Feedbforward Neural Networks have **uni-directional forward propagation** but **not backward propagation**.

**Advantage**
- Easy to design and maintain; less complex
- Speedy and Fundamentals
- Highly responsive to noisy data.

**Disadvantages**
- Cannot be used for deep learning 

# Recurrent Neural Networks
    - commonly used for natural language processing and speech recognition

# Convolutional Neural Network (CNN)


<img src="https://miro.medium.com/max/1400/1*uAeANQIOQPqWZnnuH-VEyw.jpeg"
alt="Convolutional Neural Network Example"
width="300"
height="300"/>


**Convolutional Neural Network Image**

**Convolution**
- A mathematical operation that expresses the "overlap" of one function as it is shifted over another function. It "blends" one function with another.
- An important operation in image and signal processing, whereby one input signal (or image) operates on image (kernel),<br> produces an output image.
- Designed for processing structured arrays of data, such as images.

**CNN Applications**
 - Image Processing
 - Computer Vision
 - Speech Recognition
 - Machine Translation

 There are 3 types of layers in a convolutional neural network, including: 
 - **Convolutional layer**
    - Convolve the input and forward the corresponding results to the next Layer
    - The **operation** that **convolution layers** apply is the **sliding scalar product calculation**
 - **Pooling layer**
    - The pooling layer reduces the dimensions of feature maps, i.e., reduces number of paramters required to learn and    amount of computation.
    - Operates on each feature map (channel) independently
    - Involves sliding 2-D filter over each channel of feature map and summarizing the features in region covered by the<br>
      filter
    - The **purpose of the Pooling Layer** is to reduce the dimensions of the hidden layer by combining the outputs of the<br>      neuron clusters at the previous layer into a single neuron in the next layer.
    - Two types of Pooling layers   
        -  Max Pooling  
            - Most commonly used because they work so well in convolutional neural networks by helpinig networks detect
            features more efficiently after down-sampling an input representation 
        - Average Pooling       
            - Less used

 - **Fully-Connected layer**
    - Layer in which all inputs from one layer are connected to every activation unit of the next layer
    - Such layers compile the data extracted by the previous layers to form the final output
    - It is the second most time consuming layer, second only to the Convolutional layer

 Contains 3-D arrangement of neurons instead of the standard 2-D array. The first layer is called the **convolutional layer**. Each neuron in the convolutional layer only processes the information from a small part of the visual field. Input features are taken in batch-wise like a filter. The network understand the images in parts and can computer the operations multiple times to complete the full image processing, which involves converting an image from RGB or H/SI scale to grey-scae. Further changes in the pixel value will help detect the edges and images.<br>

 Propagation is a single direction and CNNs contain one or more convolutional layers followed by pooling and bidrectional layers wherein the output of the convolutional layer goes to a fully connected neural network for classifying the images. Filters are used to extract certain parts of the image. Convolution uses RELU and MLP activation functions followed by Softmax. Convolution neural networks show promising results in image and video recognition and semantic parsing. 

 **Advantages**
 - Deep learning with few parameters
 - Less parameters to learn as compared to fully connected layer

 **Disadvantages**
 - Comparatively complex to desing and maintain
 - Comparatively slow.


