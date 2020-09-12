# AmazonFromSpace

## Multi-Label Classification of Satellite Photos of the Amazon Rainforest

### Developed a convolutional neural network to classify satellite photos of the Amazon tropical rainforest.

Data and Final Model- https://drive.google.com/drive/folders/1KQFLV1c4kgdHW4fBCt6ZyqIyKnHZZMxR?usp=sharing

Main Guide- https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-to-classify-satellite-photos-of-the-amazon-rainforest/

Description
The competition involved classifying small squares of satellite images taken from space of the Amazon rainforest in Brazil in terms of 17 classes, such as “agriculture“, “clear“, and “water“. Given the name of the competition, the dataset is often referred to simply as the “Planet dataset“.

The color images were provided in both TIFF and JPEG format with the size 256×256 pixels. A total of 40,779 images were provided in the training dataset and 40,669 images were provided in the test set for which predictions were required.

I strongly encourage you to run the tutorial on an Amazon EC2 instance with sufficient RAM and access to a GPUs, such as the affordable p3.2xlarge instance on the Deep Learning AMI (Amazon Linux) AMI, which costs approximately $3 USD per hour.

We use the VGG-16 transfer learning, fine-tuning, and data augmentation as the final model.

Order of Notebooks 
  1. Planet Understanding the Amazon from Space
  2. Planet part 2
  3. Planet part 3
  4. Planet part 4
  5. Planet part 5 # To save the model 
  6. Planet part 6 # To run the model and predict
  
Summary 
* Prepared satellite photos of the Amazon tropical rainforest for modeling.
* Developed a convolutional neural network for photo classification from scratch and improve model performance.
* Develop a final model and use it to make ad hoc predictions on new data.
