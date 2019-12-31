# <font color='orange'>What are the things we will learn from this blog.</font>

- Neural network
- Neurons
- Single Neuron
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

### <font color = 'red'> how Neural network related to nervous system or neurons ?</font>   
Whenever eye sees something the sensor and motor neurons transmit signal to the brain which inform us that we are seeing a cat.Just like that the Artificial Neural network work
### <font color = 'green'>Now we got some familiarity with the neurons(Biological) we can learn about the neurons(neural network)</font>
Here is a comparision where we see can that our neuron from neural network kind of similar to biological neuron.

![comparision artificial and bilogical](https://user-images.githubusercontent.com/46401460/71612493-cb25ea00-2bc6-11ea-8b38-6d3509113aec.png)

lets dig into our objective "The neuron" of Neural network

![single_neuron1](https://user-images.githubusercontent.com/46401460/71612699-1a204f00-2bc8-11ea-8e82-37d2544180cb.png)

As we can see in the above picture we can divide a neuron into 3 catagory :
1. Input :- Here the neuron take the data    
Input take by nerons are nothing but some vectors (these vectors are came from different kind of data it could be image ,text etc.)   

2. cell body :- It consist a sum and a fuction which do some mathematics (we will learn it later).  

it consist a function :<img src="https://latex.codecogs.com/gif.latex?f&space;=&space;(W^TX&space;&plus;b)" title="f = (W^TX +b)" />    
Here W's are the weight associated with the data X's . In biological neuron whenevr we learn something the dendrite get some weight in order to store the information like that the NN neuron also have some weight (wieght change over time : we will learn this in backpropagation) , b is a bias.

3. output : After solving the math it produced some result. 

#### <font color = 'red'> This is not many to one what i mean is we might have sveral input as well as output. which we will see in future. </font>










