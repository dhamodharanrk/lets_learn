---
sort: 1
---

# Introduction

## What is Python in nutshell?

- Python is a general-purpose interpreted, interactive, object-oriented, and high-level programming language.
- It was created by Guido van Rossum during 1985- 1990.
- Python source code is also available under the GNU General Public License (GPL)

## How to download and Setup the environment

Installing Python is pretty simple, Here am going to demonstrate how i have installed Python in my Windows Machine

- Download latest Python Version from Official page [Here](https://www.python.org/downloads/ "Here")

The following page will appear in your browser.

[![python download](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/www_python_org_download.png "python download")](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/www_python_org_download.png "python download")

- Yeah ! download is comleted. Lets start installing. Click the exe file just we downloaded.

- Highlight the Install Now (or Upgrade Now) message, and then click it

[![setup](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/pythonsetup.jpg "setup")](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/pythonsetup.jpg "setup")

Ensure that both the Install launcher for all users (recommended) and the Add Python 3.9 to PATH checkboxes at the bottom are checked: typically only first is checked by default.

- Then, what ever windows asks "yes" or "No". Just press "Yes" simply ! It wont affect anything
- Finally the installation begins

[![Process](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/pythonsetup_2.jpg "Process")](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/pythonsetup_2.jpg "Process")

- Once Installation completes, We get "Setup was successful" message. Just close the window.

[![complete](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/pythonsetup_3.jpg "complete")](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/pythonsetup_3.jpg "complete")

- Ok. now installation is completed. Lets varify the installation.
	- Run > CMD > Python

If the installation is success , the following messgae will be displayed.

[![success](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/pythonsetup_4.jpg "success")](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/pythonsetup_4.jpg "success")

### Bonus

Alternatively, You can download and install distributions such as Anaconda or Miniconda

- You can install Anaconda using following [instructions](https://www.anaconda.com/products/individual "instructions")
	- Its Open source Distribution
	 it is the toolkit that equips you to work with thousands of open-source packages and libraries.
- You can install Miniconda using following [instructions](https://docs.conda.io/en/latest/miniconda.html "instructions")
	- Miniconda is a free minimal installer for conda.
	- It is a small, bootstrap version of Anaconda that includes only conda, Python, the packages they depend on, and a small number of other useful packages, including pip, zlib and a few others.

## Introduction to IDE

According to Wiki, An integrated development environment is a software application that provides comprehensive facilities to computer programmers for software development. An IDE normally consists of at least a source code editor, build automation tools and a debugger.

The following IDEs are more unqiue and efficiant for Python Programming

### Pycharm
PyCharm is an integrated development environment used in computer programming, specifically for the Python language. It is developed by the Czech company JetBrains

[![pycharm](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/pycharm.jpg "pycharm")](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/pycharm.jpg "pycharm")

- All the Python Tools in one place
- A graphical debugger
- An integrated unit tester
- Integration support for version control systems (VCSs)
- Support for data science with Anaconda

You can download and install the community version completly free from [Here](https://www.jetbrains.com/pycharm/download/ "Here")

I am personaly using Pycharm for all of my development works from simple to advanced development works.

### Spyder
Spyder is an open-source cross-platform integrated development environment for scientific programming in the Python language.

[![Spyder](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/spyder.png "Spyder")](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/spyder.png "Spyder")

It can be downloaded and install from [here](https://www.spyder-ide.org/ "here"). I suggest you that, install it along with Anaconda (By Default anaconda includes Spyder)

It has multiple features the most usefull feature i found is,

- Interactive execution which allows you to run line, file, cell, etc."
- Variable Explorer

Along with that it includes other features like,

- Customizable Syntax Highlighting
- Availability of  breakpoints (debugging and conditional breakpoints)
- Supports all the IPython magic commands
- Support for Inline display for graphics produced using Matplotlib

In my experiance its very handly when it comes to developing machine learning or data processing tasks.

### Jupyter
Project Jupyter exists to develop open-source software, open-standards, and services for interactive computing across dozens of programming languages.

[![jupyter](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/jupyter.PNG "jupyter")](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/jupyter.PNG "jupyter")

Some of feature of jupyter is,

- Jupyter supports over 40 programming languages, including Python, R, Julia, and Scala.
- Notebooks can be shared with others using email, Dropbox, GitHub and the Jupyter Notebook Viewer.
- Your code can produce rich, interactive output: HTML, images, videos, LaTeX, and custom MIME types.
- Leverage big data tools, such as Apache Spark, from Python, R and Scala. Explore that same data with pandas, scikit-learn, ggplot2, TensorFlow.

In my exeriance its best for Machine Learning activities , as it has web based intractive interface.

It can be installed via PIP

`pip install jupyterlab`

to run it open your command prompt and type 

`jupyter notebook`

it can be accesed in web browser from using http://localhost:8888/tree

alternatively it can be try online from [here](https://jupyter.org/try "here")

### Google Colab

Colaboratory, or "Colab" for short, allows you to write and execute Python in your browser, with

- Zero configuration required
- Free access to GPUs
- Easy sharing

[![colab](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/colab.PNG "colab")](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/colab.PNG "colab")

Colab notebook that lets you write and execute code.

For example, here is a code cell with a short Python script that computes a value, stores it in a variable, and prints the result:

[![colab_cell](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/colab_cell.PNG "colab_cell")](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/colab_cell.PNG "colab_cell")

Is it deficult to start using Google Colab, No!  its pretty simple, you just need a google account to [start using it](https://colab.research.google.com/ "start using it").

## Creating simple Hello world script and executing it

Ok. Finally we done setting up the environment using  by installing Python and setting up one of your favorite IDE.

Its time to create simple python script and execute it via command prompt.

- Open Pycharm or simply open Note pad (Yes, am saying it) 
- Copy below code and paste it in note pad

```python
print("Hello world, I am Python")
```
- Then save the file as **hello_world.py**
- Yes, you just created a simple Python Script
- Now, lets **execute**
- Open a Command Prompt and type following command

```bash
python hello_world.py
```
[![simple script](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/simple_script.PNG "simple script")](https://raw.githubusercontent.com/dhamodharanrk/lets_learn/main/static_files/simple_script.PNG "simple script")

yes,  we just executed a python script. Congratulations! your journey just started in the world of python.

## Concept of Packages

cwqcqc

## Installing & loading Packages

wvwv

## Python Naming Conventions

cdwcw

