This project is a from-scratch implementation of a feedforward neural network using only NumPy and Python’s math library. I trained it on the MNIST dataset to predict handwritten digits, achieving >90% accuracy on the dev set. It uses a two-layer architecture with ReLU and softmax activations, powered by backpropagation and gradient descent.

This was a fun challenge that deepened my understanding of AI’s core mechanics—matrix operations, forward/backward propagation, and optimization. No deployment or business application here, just a learning exercise to master the fundamentals.

I’m a strong believer that mathematics, computer science, and statistics are the backbone of artificial intelligence. Check out the code to see how a neural network comes to life without fancy frameworks!

What’s Inside:





Loads and preprocesses MNIST data with NumPy.



Implements a 784-10-10 neural network with ReLU and softmax.



Trains using gradient descent (learning rate 0.3, 2000 iterations).



Evaluates predictions with >90% accuracy.

Note: This is a solo learning project with minimal dependencies. Run main.py with NumPy and pandas to try it. Feedback welcome!
