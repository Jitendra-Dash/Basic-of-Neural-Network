# <font color='orange'>What are the things we will learn from this blog.</font>

- Neural network
- Neurons
- Single Neuron
- Perceptron
- Multi layerd perceptron (multiple neurons)
- Training of Multi Layered perceptron with Backpropagation


## In order to understand something We have to ask questions.
### Make sure you should ask relevent questions. 
### <font color = 'red'>What is neural network ? </font>
ANS - collection of neuron form  a network to solve a complex task (lets say a mathametical function)

##### Here is an example where we can use a neural network to detect whether a given image is a Cat or Dog.
![Image detection ](https://miro.medium.com/max/1920/1*oB3S5yHHhvougJkPXuc8og.gif)
source - google.

######  Excited ???? relax In this series of Neural Network we will learn several things in the upcomming time , Like in the above GIF.

Lets get start !!!   

### <font color = 'red'> From where on the earth " Neural Network " came ?</font>       
  
ANS - All these neural network things are inspired by biology .In human body and animals we have something called <font color = 'blue'>Nervous System </font>.      

OK!!!!     

### then <font color = 'red'> what is Nervous System ?</font>     
ANS - Nevous System is Made up of diffrent kind or a special kind of cell in animals or human body which transmit singnals , the cell are called Neurons.     

GOT IT!!!    

### So <font color = 'red'> what are Neurons ?</font>    
Neurons are the primary cell of the nervous system.They are responsible for transmitting electrical signslas to other cells.  
We have diffrent kind of neuron in our body like sensory neuron, motor neuron etc.These are the cell when you touch a hot plate they transmit signals to our spinal cord and brain that "hey thats hot ".   
### This what a neuron look like  
![Neuron](https://upload.wikimedia.org/wikipedia/commons/b/b5/Neuron.svg)  

- Most neurons receive signals via the dendrites and soma and send out signals down the axon. Neurons are connected to each other in various patterns, to allow the output of some neurons to become the input of others  

### <font color = 'red'> How Neural network related to nervous system or neurons ?</font>   
Whenever our eyes saw something the sensor and motor neurons transmit signal to the brain which inform us that we are seeing a cat.Just like that the Artificial Neural network work
### <font color = 'green'>Now we got some familiarity with the neurons(Biological) we can learn about the neurons(neural network)</font>
Here is a comparision where we see can that our neuron from neural network kind of similar to biological neuron.

![comparision artificial and bilogical](https://user-images.githubusercontent.com/46401460/71660260-70c88d00-2d70-11ea-970f-4f05e9e11b22.png)

Lets have a look into our objective "The neuron" of Neural network

![single_neuron1](https://user-images.githubusercontent.com/46401460/71768241-66f28580-2f3a-11ea-960c-18fc5781f279.png)

As we can see in the above picture we can divide a neuron into 3 catagory :
1. Input :- Here the neuron take the data (In our case these are X1,X2,X3,X4)    
Input taken by neurons are nothing but some vectors (these vectors are came from different kind of data it could be image ,text etc.)   

2. cell body :- It has a fuction which tries to learn from the given data (we will learn it later).  
the function look something like this  <img src="https://latex.codecogs.com/gif.latex?function&space;=&space;(W^TX&space;&plus;&space;b)" title="function = (W^TX + b)" />  
Here Wi's are the weight associated with the data Xi's . In biological neuron whenever we learn something the dendrite get some weight   in order to store the information like that the NN neuron also have some weight (wieghts change over time : we will learn this in       backpropagation) , b is a bias.

3. output : After learning the function it generate an output , for example in the above where i gave an example about detecting cat or dog where at the end it saying that picture is a cat. 

###### <font color = 'red'> note : This is not many to one what i mean is we might have sveral input as well as output. which we will see in future. </font>

There is a thing called perceptron.
## <font color = 'red'>Perceptron :-</font>
The perceptron is an algorithm for learning a binary classifier called a threshold function: A function which going to return 1 when <img src="https://latex.codecogs.com/gif.latex?W^TX&space;&plus;&space;b&space;>&space;0" title="W^TX + b > 0" /> else it will return 0.

![image](https://user-images.githubusercontent.com/46401460/71661379-fdc11580-2d73-11ea-9bc3-bbed968902d5.png)








