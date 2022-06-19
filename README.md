# Tubes AI ~ Face Mask Detection Using Transfer Learning
## About Dataset
In the preparation of this project using a dataset obtained from [Github.com](https://github.com/prajnasb/observations/tree/master/experiments/dest_folder). This dataset is used for Face Mask Detection Classification with images consisting of approximately 1700 images. With directory details:
  1. Test :
     * WithMask : 97 images
     * WithoutMask : 97 images
  2. Train :
     * WithMask : 658 images
     * WithoutMask : 657 images
  3. Validation :
     * WithMask : 71 images
     * WithoutMask : 71 images
## About Project 
This study discusses the classification of facial images using masks and not using masks. This study develops previous research on major journal references using a similar dataset but applying a different proposed method, namely using the transfer learning method with the VGG16 pre-trained architectural model for facial image classification using masks and not using masks with accuracy and values. evaluation which has increased compared to the previous method.
## Research Purposes
This research was conducted with the aim of getting the best final results from the accuracy and evaluation values of previous studies using the transfer learning method with the VGG16 pre-trained architecture model.
## Method
There are several processes, namely at the beginning of data pre-processing in the form of dividing data into training, validation, and testing data, after that the data from training and validation will be augmented. Furthermore, the training dataset will be trained together with the validation set to validate the training performance at the end of each epoch. Meanwhile, the last stage is evaluation where the performance of the model will be evaluated using a testing dataset which is an unseen dataset.
## Deep Learning Techniques
* The model uses the CNN (Convolutional Neural Network) algorithm
* The model uses the Transfer Learning algorithm VGG16
* Models trained using Google Collaboratory
## Reference Journal
* The reference journal for this project is entitled ["Control The COVID-19 Pandemic: Face Mask
Detection Using Transfer Learning"](https://www.mendeley.com/catalogue/33180134-8299-34ea-8f45-c008326f90f6/) Oumina A, El Makhfi N, Hamdi M.
2020 IEEE 2nd International Conference on Electronics, Control, Optimization and Computer Science, ICECOCS 2020 (2020)
## Program Execution Method
* Download file .ipynb
* Open file in the Google Colaboratory

## Authors
Contributors in this project are:
1. Ahmad Junjung Sudrajad
2. Lidya Fankky Oktavia Putri
3. Ulfah Nur Oktaviana
4. Galih Wasis Wicaksono

## Acknowledgments
Inspiration, code snippets, etc.
* [Keras Documentation](https://keras.io/api/applications/vgg/)
