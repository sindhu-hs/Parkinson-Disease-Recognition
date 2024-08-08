## Parkinson's Disease Recognition

### Aim
To recognize if the person has Parkinson's Disease or not given a hand-drawn spiral or wave image.

### Flow of Execution
Dowload the data folder as the first step before execution.
1. PDD SPIRAL MODEL.ipynb
2. PDD WAVE MODEL.ipynb
3. SpiralGUI.py
4. WaveGUI.py

### Data
Our aim is create seperate training model and gui for spiral images and wave images.
1. Both spiral and wave image category are divided into train and test images.
2. With train and test they are divided into "Healthy" & "Disease" classes.

### PDD SPIRAL MODEL.ipynb & PDD WAVE MODEL.ipynb
In these files the foolowing tasks are performed:
1. Due to lack of data available for training (only36 in each class), data augmentation is done.
2. Classic Convolutional Neural Netwrok is used for training.
3. The trained weights are stored as json file, which can be loaded for use in future
   wothout having the need to train the model again.

### SpiralGUI.py & WaveGUI.py
1. These files are used to create user interface where the user can insert a hand-drawn spiral or
   wave image as input and get the correspond recognition as output.
2. PyQt is used for creating the user interface.
