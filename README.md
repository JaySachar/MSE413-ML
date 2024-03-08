## Setting up your virtual environment
I'm using Python 3.11.7, [download here](https://www.python.org/downloads/release/python-3117/). 3.11.8 should work as well. 3.12 had issues with some packages I've downloaded in the past, so I avoided it.

1. **Clone the repo**  
   a) Go to a local path on your machine, and enter command window (ctrl+r, and type "cmd", and navigate to your desired location for the folder)  
   b) `git clone https://github.com/JaySachar/MSE413-ML.git`

2. **Create the virtual Environment**  
   a) Navigate to the repository you cloned in the command window (ie `cd C:/Users/JaySachar/Documents/Github/MSE413-ML`)  
   b) Once in the cloned repo, enter `python -m venv venv` into the command window  
   c) Activate the virtual environment: `cd venv\Scripts`, and on a new line, `activate`  
   d) Navigate to the directory with requirements.txt (`cd ..` takes you up a directory)  
   e) Once in the main directory, run `pip install -r requirements.txt`
3. ** Using the virtual Environment**
   a) Open the .ipynb file in VS Code
   b) On the top right of the editor, below the settings cog, there should be a clickable thing, that'll let you choose the "kernel" for running the file
   c) Click it, and if the virtual environment folder path doesn't show up, click "Select another kernel"
   d) Then click "Python Environment"
   e) Select the virtual environment with the file path "MSE413-ML\venv\Scripts\python.exe"
   
   If the above doesn't work, if you do ctrl+shift+P, search for "Selelct Interpreter" for Python, and then "Enter Interpreter Path". Now you can enter the path to the virtual environment, which will be:
   C:/Users/.../MSE413-ML/venv/Scripts/python.exe
