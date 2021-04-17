To get started open the *cnn.ipynb*, that will be the jupyter-notebook used for this CNN with all the code. <br>
Most of the beginning of the jupyter-notebook is created by Tensorflow's Keras. <br>
You can find the it here https://keras.io/examples/vision/mnist_convnet/ . <br>
I have only deleted the first cell of the notebook. <br>

The structure of the CNN can be found in the file *mnist_convnet_summary.png* and *mnist_convnet.png*.

After you got the basic idea of the structure of this CNN, learn about the other files in this directory below!

# Description of the Different Types of Files in this directory

#### Starter (no visualization) Files

* *cnn.ipynb* -- the jupyter-notebook used for this CNN with all the code
* *mnist_convnet_summary.png* and *mnist_convnet.png* -- You alreadly know (structure of the CNN)

* *my_model.h5* -- My Trained Tensorflow Model.

### Visualization of Weights and Biases in Convolutional Layers

* *weights1_biases1.png* -- Weights and Biases of First Convolutional Layer
* *weights2_biases2.png* -- Weights and Biases of Second Convolutional Layer

### Visualization of Weights and Biases in the Dense Layer
* The bias is in the file *bias3.png*. <br>
* The weights are in the **templates** sub_directory of this directory. <br>
* In the templates folder there are 10 files (one for each class). <br>
* Each of those files contain 1600 flatten weights. <br>
* For example, *0.png* contains the first row of the 1600 weights, *1.png* contains the second row of the 1600 weights, and so on to the last row of the 1600 weights would be *9.png* <br>
* This might sound confusing so feel free to create an issue on this topic and I will try my best to explain it better.


### Visualization of a Input and Final Output of CNN
* *input_img.png* is the single Input Example
* *final_out.png* is the final output of the CNN

### Visualization of Outputs from Convolutional Layers and Maxpool

* *out_conv2d.png* -- This is the output of the first Convolutional Layer
* *out_max_pooling2d.png* -- This is the output of the first Maxpool Layer
* *out_conv2d_1.png* -- This is the output of the second Convolutional Layer
* *out_max_pooling2d_1.png** -- This is output of second Maxpool Layer

### Visualization of Outputs from Flatten and Dropout Layer
* *last_outpus.png* -- This is the output of the Flatten and Dropout Layer.
* Since Tenserflow does Inverted Dropout (No Dropout during test time), the result of Flatten and Droupout is the same. Also, this is the same thing as the second Maxpooling output but flattened.

<br><br>
## The End, good luck and have fun!  :)

