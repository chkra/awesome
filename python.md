# Getting started in Python

A list of Python references for beginners switching from a different language. Collected as teaching material for Students at [HTW Berlin](https://www.htw-berlin.de/). Not intended to be complete - weare aiming to get you started quickly.


## Installing Python

Python can easily be installed on most platforms. There are two options:

* one central installation on your machine, containing ALL the libraries
  * via [python.org](https://www.python.org/downloads/)
  * via [realpython.com](https://realpython.com/installing-python/) (lots of step-by-step guides)
* (recommended) with a manager for virtual environments and a package manager
  * use [venv](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment) or [anaconda](https://docs.anaconda.com/anaconda/install/index.html) as manager for virtual environments
  * venv is a lightweight Python built in tool, anaconda is third-party and more powerful
  * use anaconda if working in data science / ml / ai
  * use pip as package manager

Note: make sure to install python 3.x, not python 2.x! 

## Programming Environments

* IDEs
  * [PyCharm](https://www.jetbrains.com/pycharm/)
  * [Visual Studio Code](https://code.visualstudio.com/)
* CLIs
  * in Windows: anaconda prompt makes live easier sometimes
* [Jupyter Notebook](https://jupyter.org/)
  * HTW hosts a Jupyter Hub
  * anaconda comes with Jupyter (use Anaconda Navigator)
  * for power users: [Jupyter Lab](https://jupyter.org/try)

## Language

* [W3 Schhols](https://www.w3schools.com/python/)
* [detailed Cheatsheet](https://www.pythoncheatsheet.org/)
* [compact Cheat Sheet](https://perso.limsi.fr/pointal/_media/python:cours:mementopython3-german.pdf)


## Libraries

* [comprehensive reference](https://awesome-python.com/) to many libraries

* [pandas](http://pandas.pydata.org/): data analysis and manipulation
* [numpy](http://www.numpy.org/): (large scale) mathemattical data operations
* [matplotlib](http://matplotlib.org/), [seaborn](https://github.com/mwaskom/seaborn): plotting charts & diagrams
* [bokeh](https://github.com/bokeh/bokeh): interactive charts
* [django](https://www.djangoproject.com/), [flask](https://flask.palletsprojects.com/en/2.2.x/): Webserver ( standardised & powerful: Django / lightweight & fast: Flask)
* [scikit-learn](http://scikit-learn.org/): machine learning
* [pytorch](https://github.com/pytorch/pytorch), [TensorFlow](https://github.com/tensorflow/tensorflow): deep learning
* [sqlalchemy](https://www.sqlalchemy.org/): data bases
* [beautyfulsoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): parsing documents (websites, xml etc.)
* os: system functions, paths (see also: pathlib)
* datetime: dates and times (also: see dateutil)


## Best Practices

### Algorithms
* algorithms - Minimal examples of data structures and algorithms.
* python-ds - A collection of data structure and algorithms for coding interviews.
* sortedcontainers - Fast and pure-Python implementation of sorted collections.
* TheAlgorithms - All Algorithms implemented in Python.

## Design Patterns
* PyPattyrn - A simple yet effective library for implementing common design patterns.
* python-patterns - A collection of design patterns in Python.
* transitions - A lightweight, object-oriented finite state machine implementation.

## Courses

* [Step-by-step projects](https://www.jetbrains.com/pages/academy/learn-python)  in PyCharm