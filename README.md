# Crack_Detection_-_Quantization-

When we train a Artificial Neural Network model weights will be in floating points. When the network become huge and we want to run it on simple machine we will try to reduce the parameters of Neural Network. So we will convert the values of weight from float to integer.
There are many numbers of layers in Deep Neural Network where we have weight (w) values in float. Since this is floating point number we have to represent in 32 bit memory. Like which we have many number of weight.
If we represent the same weight in integer. We can represent most of the integer in 8 bit which will help us to reduce the memory required.
That’s how we make the model to work on small machine and to make inference faster. We are reducing the size of each weight by which Quantization helps.
