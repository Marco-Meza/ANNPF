# ANNPF
A code that automatically estimates missing precipitation data in any set of meteorological stations using the most consistent station as a reference, called Artificial Neural Network for Precipitation Filling (ANNPF).

# Initial preparation:
-Install Python:

- 1.- If you don't have Python installed, download it from [python.org](https://www.python.org)  and install it.
- 2.- Install the necessary libraries:
  Open the terminal or command prompt (depending on your operating system) and run the following command to install the required libraries:
  + `pip install pandas numpy scikit-learn matplotlib openpyxl`

 # Steps to run the code from the terminal or command prompt:
1.- Prepare the files:
+ Save the code in a text file with `.py` extension.
+ Make sure you have an Excel file called `Input.xlsx` in the same directory as the `.py` file. This file should have a structure similar to what the code expects.
  
2.- Execute the code:
+ Open the terminal or command prompt.
+ Navigate to the directory where your `.py` and `Input.xlsx` file are located.
+ Type python `filename.py` (replace `filename.py` with the actual name of your Python file) and press `Enter`.
  
3.- Interact with the program:
+ The program will ask you to enter a number, either `1` or `2`, to determine the number of base stations to use.
+ Follow the instructions that appear in the terminal or command prompt depending on the questions the program asks.
# Or You can run this code from Jupyter Lab:
## Steps to run the code in Jupyter Lab:
### Initial preparation:
1.- Install Jupyter Lab:
+ If you don't already have Jupyter Lab installed, you can do so by using pip in your terminal or command prompt with the command:`pip install jupyterlab`
  
2.- Open Jupyter Lab:
+ Open the terminal or command prompt.
+ Navigate to the directory where your `.ipynb` and `Input.xlsx` file is located.
+ Run the `jupyter lab command`. This will open Jupyter Lab in your default web browser.
## Code execution:
3.- Create a new notebook:
+ In Jupyter Lab, click the "New" button and select "Notebook: Python" to create a new notebook.
  
4.- Copy and paste the code:
+ In a cell of the notebook, copy and paste the provided code.
+ 
5.- Execute the code in sections:
+ Divide the code into logical sections (cells). You can do this by separating each block of code with comments indicating sections `#0`, `#1`, `#2`, etc.
+ Click on a cell and press `Shift + Enter` to run that section of code.
  
6.- Interact with the program:
+ When the program prompts for input (as in section `#6`), enter the answer in the appropriate cell and press `Enter`.
  
7.- Observe the results:
+ If there are parts of the code that generate graphs, these will be displayed directly below the corresponding code cells.

8.- Save results (optional):
+ You can save the generated results to files if the part of the code that saves the graphs or data to CSV files has been uncommented.
  
9.- End execution:
+ Continue executing the cells until you have finished using the code.
+ Once finished, close Jupyter Lab or save and close the notebook if you want to resume work later.
