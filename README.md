                                                   Project Name:    Melanoma Skin Cancer Detection

1.	Context:
	  The deepest layer of the epidermis, located just above the dermis, contains cells called melanocytes. Melanocytes produce the skin’s pigment or color.
	
	  Melanoma begins when healthy melanocytes change and grow out of control, forming a cancerous tumor. A cancerous tumor is malignant, meaning it can grow and spread to other 		  parts of the body. Sometimes, melanoma develops from a normal mole that a person already has on their skin. When this happens, the mole will undergo changes that usually can be 	  seen, such as changes in shape, size, color, or the border of the mole. Other times, melanoma may develop on skin where there is no existing mole.
	
	  Melanoma can develop anywhere on the body, including the head and neck, the skin under the fingernails, the genitals, and even the soles of the feet or palms of the hands. 
          Melanoma may not be colored like a mole. It may have no color or be slightly red, which is called amelanotic melanoma.
	
	  When found early, melanoma can often be cured with surgery. However, melanoma is one of the most serious forms of skin cancer. It can grow deep into the skin; this is called 
          invasive melanoma. It can also invade blood vessels and spread to lymph nodes and distant parts of the body; this is called metastatic melanoma.

2.	Problem Statement
		In the skin biopsy, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process takes almost a week or more, starting 		from getting a dermatologist appointment to getting a biopsy report. The aims to shorten the current gap to just a couple of days by providing the predictive model. The 		approach uses Convolutional Neural Network (CNN) to classify nine types of skin cancer from outlier lesions images. This reduction of a gap has the opportunity to impact 		millions of people positively.

4.	Benefit
	The primary benefits that drives the project is to use the advanced image classification technology for the well-being of the people. Computer vision has made good progress in 	machine learning and deep learning that are scalable across domains.

6.	Dataset
	This dataset contains 2239 images of malignant diseases which were constructed from ISIC (International Skin Imaging Collaboration)
       		 ![image](https://github.com/parthajitB/Melanoma-Detection/assets/137589244/49f7f3a2-2e53-48ca-917d-35bc86f5a9c9)
  		![image](https://github.com/parthajitB/Melanoma-Detection/assets/137589244/4afd16a6-f788-42f3-a20d-e4fbdfac5bc0)
		 
7.	CNN Architecture

	•	Rescaling Layer - To rescale an input in the [0, 255] range to be in the [0, 1] range.
	•	Convolutional Layer - Convolutional layers apply a convolution operation to the input, passing the result to the next layer. A convolution converts all the pixels in its receptive field into a single value
	•	Pooling Layer - Pooling layers are used to reduce the dimensions of the feature maps. Thus, it reduces the number of parameters to learn and the amount of computation performed in the network.
	•	Dropout Layer - The Dropout layer randomly sets input units to 0 with a frequency of rate at each step during training time, which helps prevent overfitting.
	•	Flatten Layer - Flattening is converting the data into a 1-dimensional array for inputting it to the next layer.
	•	Dense Layer - The dense layer is a neural network layer that is connected deeply, which means each neuron in the dense layer receives input from all neurons of its previous layer.
	•	Activation Function(ReLU) - The rectified linear activation function or ReLU is a piecewise linear function that will output the input directly if it is positive, otherwise, it will output zero.
	•	Activation Function(Softmax) - The softmax function is used as the activation function in the output layer of neural network models that predict a multinomial probability distribution. The main advantage of using Softmax is the output probabilities range. The range will 0 to 1, and the sum of all the probabilities will be equal to one.

6.	Model view
    	 ![image](https://github.com/parthajitB/Melanoma-Detection/assets/137589244/eb755162-edf3-4d05-a95f-7e4cb17c3c22)

7.	Model Evaluation


