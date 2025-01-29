# About
This is a repository containing my implementation of various problems and data structure implementations from NeetCode in Python. My instructions apply only to Mac and Linux users - Windows users are unfortunately on their own in getting this code to run on their machines!
I am assuming you have Homebrew installed, as well as both pyenv and swig installed via Homebrew. 

## Instruction
1. Navigate to a folder on your computer where you would like to clone this project via the command line and run the following command:<br>
   ```git clone https://github.com/Pirate-Hunter-Zoro/Deep-Q-Learning.git```<br>
This will create a folder called "Deep-Q-Learning" in your current folder. 
2. Navigate into this folder.<br>
   ```cd Deep-Q-Learning```
3. Create a python virtual environment named "deep-q-env" (or whatever you want to call it) via the following commands:<br>
   ```pyenv install 3.10```
4. Create a python environment with said python version:<br>
   ```pyenv virtualenv 3.10 deep-q-env```
5. Activate the virtual environment:<br>
   ```pyenv activate deep-q-env```
6. Install the necessary Python libraries:<br>
   ```pip install -r requirements.txt```<br>
   (If that doesn't work, ensure you have installed swig:<br>```brew install swig```)
7. At this point, you should be able to open a notebook in VSCode and select the correct Python interpretter (the virtual environment you just created).

## Useful Note
To write all of the requirements in the Python virtual library into "requirements.txt", run the following command:<br>
```pip freeze > requirements.txt```