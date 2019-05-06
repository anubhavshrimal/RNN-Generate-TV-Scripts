## Project Overview

This project is done as a part of the Udacity's [Deep Learning Nanodegree](https://eu.udacity.com/course/deep-learning-nanodegree--nd101). The Long Short Term Memory Networks, a type of RNN, is trained over Seinfeld TV scripts from 9 seasons. The trained model is then able to generate new "fake" tv scripts similar to Seinfeld.

LSTMs are implemented using PyTorch framework.

Fake generated tv script by the project can be found in [generated_script_1.txt](generated_script_1.txt)


## Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/anubhavshrimal/RNN-Generate-TV-Scripts.git
		cd RNN-Generate-TV-Scripts/
	```
2. Install required dependencies using:
```
		pip install -r requirements.txt
```
3. Open a terminal window and navigate to the project folder. Open the notebook using the bellow command and follow the instructions given in the notebook.
	
	```
		jupyter notebook dlnd_tv_script_generation.ipynb
	```


## Accelerating the Training Process 

If your code is taking too long to run, you will need to switch to running your code on a GPU.  If you'd like to use a GPU, you can use [Google Colab](https://colab.research.google.com/). 

**Note:** Colab is a free service and the data is not persistent. It is suggested to download whatever data you need once your session is idle otherwise you may lose the progress.

You can use Amazon Web Services to launch an EC2 GPU instance which will be persistent. (This costs money)
