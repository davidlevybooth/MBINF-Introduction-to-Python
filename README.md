# MBINF-Introduction-to-Python

## MBINF Introduction to Python Workshop 2023

</br>

### Getting Started

This workshop is designed to be used entirely in a Jupyter Notebook environment. There are instructions below to setup Jupyter notebooks in your local environment. To get started without installing anything locally, please follow the `Google Colab` instructions. 

</br>

### Google Colab

Colaboratory, or “Colab” for short, is a product from Google Research. Colab allows anybody to write and execute arbitrary python code through the browser, and is especially well suited to machine learning, data analysis and education. More technically, Colab is a hosted Jupyter notebook service that requires no setup to use, while providing access free of charge to computing resources including GPUs.

Visit the Google Colab site:

```
https://colab.research.google.com/ 
```

Navagate to the `GitHub` tab. Enter the URL for this GitHub respository to get started: 

```
https://github.com/davidlevybooth/MBINF-Introduction-to-Python
```

Select the **MBINF-introduction-to-python.ipynb** link for Part 1. 

Select the **MBINF-introduction-to-pandas-ds.ipynb** link for Part 2. 

</br>

## Running Locally (not recommended for first-time users)

#### Install Python

- Python 3.11.4 is the newest major release of the Python programming language, and it contains many new features and optimizations.
- There are several ways to install Python. The simplest is to navigate to https://www.python.org/ and download the appropriate Python 3.11 installer for your operating system. See https://www.python.org/downloads/release/python-3114/ for more information. 
- Open the downloaded installer and select “Continue” to review the Read Me and License, then select “Install” when prompted. You may have to enter your user password to install new software. 
- Finish the installation and close the installer window. Optionally, remove the installer after installation is complete. 
- For computers managed by your institution, please contact your administrator for assistance. 
- Finally, check that the Python installation is correct by opening a terminal window and typing `python –version`. You should see the output `Python 3.11.4` 

Alternatively, you can install Python through an Anaconda Distribution, although this method is not reviewed in this workshop. 

</br>

### Installing Jupyter Locally

Following the instructions on https://jupyter.org/install:

To install Jupyter Notebook, open a terminal and enter:

```
pip install notebook
```

To run the notebook from the terminal, enter:

```
jupyter notebook
```

The Jupyter Notebook homepage should open in your default web brower. 

</br>

#### Download the workshop material

With `git` installed ([instructions](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)), navagate to a directory using your terminal where you'd like to download the workshop contents. From there, run: 

```
git clone https://github.com/davidlevybooth/MBINF-Introduction-to-Python.git
```

</br>

#### Install VSCode (Optional)
- Visual Studio Code (VSCode) is one of the most popular interactive development environments (IDEs) in the world. It is widely used in industry and academia. 
- Navigate to https://code.visualstudio.com/ and download the appropriate VSCode installer for your operating system. 
- Review setup instructions for:
    - Windows: https://code.visualstudio.com/docs/setup/windows
    - MacOS: https://code.visualstudio.com/docs/setup/mac
    - Linux: https://code.visualstudio.com/docs/setup/linux
- Test that both Python and VSCode are working correctly by running a basic Python command in VSCode:
- Create a new file either with the keyboard shortcut `Ctrl + N` or by selecting `File > New File…` 
- Save the file as `test.py` - note the `.py` extension for Python files.  
- Type `print(‘Hello World’)` into the IDE and save the file using `Ctrl + S`
- Ensure that the correct Python interpreter is selected. This should be Python 3.11.4 if you installed Python using the above instructions, although any Python version > 3.10 should work for this workshop. 
- Open a terminal in VSCode by selected `Terminal > New terminal` and type: `python test.py` into the terminal window. 
- You should see the output `Hello World`
- Congratulations, you’re set up to start the Introduction to Python Workshop!

NOTE: if you encounter an error when working through above steps, try the step-by-step guide in: https://www.datacamp.com/tutorial/setting-up-vscode-python or contact David at dlevybooth@gmail.com. 






 


