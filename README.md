# Single-Sided-Hindi-braille-into-corresponding-text-
In this project, a picture of the embossed Braille characters would be fed as an input and a series of techniques in Image pre-processing, Segmentation, Character Extraction, Character Recogni- tion and Text Conversion will be applied to it resulting in an output image that will be the corresponding Hindi format of that braille text image. The Braille text image processing and translation is done by various methods of Digital image processing and Convolutional Neural Network. With advancements in the field of Artificial Intelligence the conversion of the braille image to its natural language character can be done effectively in python environment.

## Getting Started
Download the following files and folders
- requirements.txt
- preprocessing
- segmentation
- character translation


## Prerequisites
Things needed to install the software and dependencies  
- install latest version of python from [python website](https://www.python.org/downloads/) and set environment variables
- install jupyter notebook using `pip install notebook` in your command prompt(for windows) or terminal(for macOS or linux) command
- install all the required dependencies using this command `pip install -r /path/to/requirements.txt` in command prompt or terminal
- Set the path of each of the input and output in the order of execution of code where each each code's output is the input of the next code

> another way is to use Anaconda environment for executing the code. Download and set up for code execution through [Anaconda wesite](https://www.anaconda.com/)


## Running the tests
A sample input image is present in the preprocessing folder with the name:
> inputImage.jpg  
Use this image by setting the path in the file:  
> grayScaleConversion.ipynb  
The output of this code will act as input of the next code  
> and repeat until the last code in execution order.

Run the code in the following order:  
a. Preprocessing
   1. grayScaleConversion.ipynb
   2. shadow.ipynb
   3. light.ipynb
   4. gamma.ipynb
   5. bitPlaneSlicing.ipynb
   6. threshold.ipynb
   7. erosion.ipynb
   8. dilation.ipynb
   9. centroidDetection.ipynb
   
b. Segmentation
   1. rowWise_segmentation.ipynb
   2. wordWise_segmentation.ipynb
   3. blackImage.ipynb
   4. charWise_segmentation.ipynb  
   > use the image saved from _blackImage.ipynb_ as the template for adding the dots on  

c. characterTranslation
   1. modelTraining.ipynb  
   > use this code for training the model. A sample model is included in the foler _characterTranslation_, which can be used directly for predicting the output
   2. predictBrailleChars.ipynb  
   > use the output saved from _charWise_segmentation.ipynb_ as the input to this code and set the model path(which is alread present in the same folder) to execute and predict the output of the image.
   
   
   
   
## Project Details
- Title: Single-Sided braille into corresponding text
- Batch ID: CSE06530721
- Student Author:  
          Abhishek Kumar – RA1611003010653  Bipasha Biswas – RA1611003010721
- Guide name and Designation:  Dr. A.Pandian, Associate professor




