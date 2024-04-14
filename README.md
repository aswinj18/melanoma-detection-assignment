# Melenoma Detection
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Conclusions
- Build a basic model
	- Architecture:
		- rescaling
		- 2 conv2d with 10 channels with batch normalization after each layer
		- maxpool2d
		- dense layer with 100 neurons with 'ReLU' activation
		- dense layer with 20 neurons with 'ReLU' activation
		- final layer with 9 neurons for the 9 classes, with softmax activation
	- Training accuracy: 99.99%
	- Validaton accuracy: 85%
	- The best model among the 3 models trained
- Build a model same as basic model but with data augmentation layer before the rescaling layer.
	- Training and Validation accuracy same as the Basic model
- Build a model with the same architecture as basic model, but trained on balanced data
	- Worst model among the 3.
	- Training accuracy: 98%
	- Validaton accuracy: 56%

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Contact
Created by [@aswinj18] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->