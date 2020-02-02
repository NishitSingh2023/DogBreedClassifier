# DogBreedClassifier
![Image](https://github.com/NishitSingh2023/DogBreedClassifier/blob/master/images/Labrador_retriever_06457.jpg)

## It's a classifier that detects dog breed given a pic of dog

This is project given to us at Udacity that detects a picture passes it through a ` CNN ` And checks whether the given input is dog or a human, Based on a model called VGG16 which is trained on __[ImageNet](https://www.image-net.org/)__
In this project, I have learned how to build a pipeline to process real-world, user-supplied images. Given an image of a dog, my algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. Along with exploring state-of-the-art CNN models for classification, I have made important design decisions about the user experience for our app. By completing this lab, I understood the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.

## Project Instructions

### Instructions

-  Clone the repository
- Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip) Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
- Download the [human_dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip) Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
- Make sure you have already installed the necessary Python packages according to the README in the program repository.
- Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
  ```
		jupyter notebook dog_app.ipynb
	```


### What will model do:-

__If a dog is detected__:
>The output will be detected breed of the dog.

__If a human is detected__:
>The output will be most resembling breed of dog to face of that human.

__Else if none is detected__:
>The output will be `neither`

## (Optionally) Accelerating the Training Process 

If your code is taking too long to run, you will need to either reduce the complexity of your chosen CNN architecture or switch to running your code on a GPU.  If you'd like to use a GPU, you can spin up an instance of your own:

#### Amazon Web Services

You can use Amazon Web Services to launch an EC2 GPU instance. (**Warning: This costs money**)

