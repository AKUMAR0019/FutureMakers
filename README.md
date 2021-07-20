Responses:
=========

Day 1:
---------
One new thing I learned today was how to set up Jupyter Notebooks. I normally use PyCharm to code, and it was very interesting to see how Jupyter runs each line of code when you type it as opposed to going from start to finish as you run it. 

I hope to learn more about how to code AI using modules like TensorFlow, because while I do know how to use scikit-learn and other machine learning tools, I do not know enough about AI. My hope is that I can then use my knowledge to aid in the field of neuroscience. I really can't wait to get started :)!

Day 2:
---------
Today, I learned how to tell a story about myself that comes from the heart, a story that shows my motivations and my challenges, and how I moved past hurdles. I learned that the world may have problems, but the way to take action on those problems is to combine both heart and head to create unique solutions. I learned that I am a leader, because a leader motivates others so that a community can together solve a problem. Today was amazing, and I'm so glad I got the opportunity to attend this session.

Day 3:
---------
Today, I learned how validation is different from testing, which was very helpful, as I didn't understand the distinction until today.

i. In supervised learning, training data already has labels, and the idea is to learn from feedback and predict the outcome. In unsupervised learning, the training data has no labels, so there's no feedback and one learns from the patterns.

ii. It is false because scikit-learn is built on other modules like NumPy, SciPy, IPython, Sympy, pandas, and matplotlib. It does data mining and data analysis, but to collect that data or display that data, it requires other libraries. 

Day 4:
---------
Today, I learned what the TPU is. I had no idea that there was such a thing as a Tensor Processing Unit which can speed up AI processing. 

The dataset I found is a dataset on breast cancer metastases in whole-slide images of histological lymph node sections. The link is here: https://drive.google.com/drive/folders/0BzsdkU4jWx9Bb19WNndQTlUwb2M?resourcekey=0-FREBAxB4QK4bt9Zch_g5Mg. To use deep learning on this algorithm, I would use pattern recognition (computer vision algorithm), especially to identify which slides have evidence of cancer. 

Days 5 & 6:
---------
The weekend.

Day 7:
---------
Today, I more about tensors and actually coded a ML algorithm using TensorFlow. 

To answer the questions in text format: A tensor is basically a multidimensional array used to generalize scalars, vectors, and matrices. A single-dimensional tensor is a vector, a two-dimensional one, a matrix. Tensors are used in ML because machines cannot learn without data, and modern data is multi-dimensional. Using tensors allows the coder to encode that multi-dimensional data, making it easier to solve problems that involve huge datasets, common in ML. 

The computations I ran were complicated. They tended to involve multiple steps to encode the data followed by the training of a dataset through hundreds of thousands of iterations. Calculations involved splitting a dataset into train and test datasets, encoding them, and then completing prediction and fitting. An optimizer and cost function were both important in tuning the code, as was the overall accuracy. Weights, biases, and lambdas also had to be encoded. It is difficult to understand the math behind it fully, but the concept behind multidimensional arrays and matrices is a part of linear algebra. 

Day 8:
---------
Today, I learned more about the different types of neural networks, especially how a neural network operates in terms of neurons, synapses, and activation functions.

Day 9:
---------
Today, I learned more about what a CNN is. Its applications to images are very important, and very useful. In addition, I learned more about how to use convolution, an activation layer (reLU, usually), and pooling operations to increase the usability of CNNs. 

Day 10:
---------
Today, I learned about the 5-step plan to setting goals. I also learned how to get past insecurities in order to succeed.

Day 11:
---------
Today, I learned more about the fully connected layer and also 3D filters. 

In a FCNN, all layers are fully connected, meaning each neuron in a layer is connected to each neuron in another layer. The advantage of this setup is that there is no need to assume anything about the input (structurally agnostic), making them applicable to a broad set of problems. However, they perform worse than other networks with more specified purposes. They are less useful for feature extraction and have a larger number of weights to train, which makes them take longer to run.

A CNN assumes that all inputs are images, so you can encode properties in the model setup. A CNN is a sequence of layers, just like FCNN, but these layers have different purposes. There is the convolutional layer, the activation layer, and the pooling layer, and these transform the data multiple times when running a CNN. These run faster, and are meant specifically for image datasets. 

Days 12 & 13:
---------
The weekend. 

Days 14:
---------
Today, I learned more about the different types of loss functions, especially which ones apply to regression as opposed to classification. 

Days 15:
---------
Today, I learned more about the best activation functions to use for different NNs. I also learned the math behind the sigmoid and softmax functions. 

My answer to the prompt on ReLU is as follows: ReLU outputs the result of max(0,x). This means for any value below 0 (negative numbers), the function outputs 0. For x=0 and above, it outputs x. ReLU is one of the most common activation functions for a hidden layer. Like all other activation functions, it adds nonlinear elements to the model so it can model data more complex than a line.

The advantages ReLU presents are as follows: ReLU is less computationally expensive than other activation functions like tanh and sigmoid because it involves simpler math operations. In addition, at any given moment, only a few neurons are activated because of the 0 output for negative numbers. This makes the network sparse, which makes it efficient and easy for computation. ReLU learns much faster than sigmoid and tanh, which presents another advantage. Finally, ReLU overcomes the vanishing gradient problem, which allows models to learn faster and perform better. ReLU is often used in the hidden layers of MLPs and CNNs due to these advantages. 

In deep neural networks, there is a need to use stochastic gradient descent with a backpropagation of errors in order to train. In this case, the activation function needed is one that looks and acts like a linear function, but is a nonlinear one in order to allow complex relationships in the data to be learned. It has to be more sensitive to the activation sum input and avoid easy saturation. Sigmoid and tanh can't do that because large values either translate to 1.0 or -1 or 0 for tanh and sigmoid respectively. Both are also hugely sensitive to changes around the midpoint (0.5 for sigmoid, 0.0 for tanh). ReLU has provided the solution, making it ideal to use. That doesn't mean it's perfect, of course. You do not want to use it in RNNs, for example. But in CNNs and MLPs, it is the best function to use.

Reflections:
=========

Days 1-9:
---------
No reflections. See responses.

Day 10:
---------
1. The AI hiring and firing decisions were likely made by a ML algorithm. When I made my selections in the beginning, that data was inputted into the model as training data, which resulted in the hiring patterns found in the machine-controlled decisions. Just like the Amazon hiring algorithm, my past decisions affected how the AI selected newer members, not just by looking at skills or ambition, but also by looking at other characteristics. 

2. I learned very recently that the motion-detection soap dispensers run on ML algorithms, which explains why they don't work for me half the time. It is biased towards paler skin, so when a brown person sticks her hand underneath, it doesn't recognize the hand as a human hand, and soap is not dispensed. To make it more inclusive, you would need to train it on a larger dataset of hands, not just white ones, but brown ones too. The dataset isn't diverse enough. The reason I selected this one as opposed to other ones that concern me like Amazon's hiring algorithm (which automatically removed women, even when gender wasn't specified by IDing women's colleges, sports, and fraternities and removing people with those) or recidivism risk algorithms (say black people have a much higher risk of recidivism) is because this one personally affects me all the time. I always thought it was a glitch. Now I know differently. While the Amazon algorithm bothers me the most, I did want to provide more information on an algorithm few people reall;y know about.
