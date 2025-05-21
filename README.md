# Profiling-and-Optimisation-in-Python

## Pre-Course Instructions

### Webinar Instructions

To complete this course, you will need to run Jupyter Notebook files on your computer. The easiest way to do this is to ensure you have a Google account. This will allow us to use the online Google Colab tool to run the notebooks on the day.

Alternatively, if you don’t have and don’t want to create a Google account, you may instead install Anaconda on your computer by downloading the appropriate distribution from [here](https://www.anaconda.com/distribution/).

The presentation and the Notebooks may be found [here](https://github.com/coolernato/Profiling-and-Optimisation-in-Python/archive/refs/heads/master.zip). You should download them before the course. However, you do not need to read them before attending.

### Face to Face Course

This course will take place in an ICT computer room and so laptops are not required but you may bring one if you wish. Please make sure it is fully charged. This course will involve the running of Jupyter Notebook files. The easiest way to do this is to ensure you have a Google account. This will allow you to use the online Google Colab tool to run the notebooks on the day.

Alternatively, if you don’t have and don’t want to create a Google account, Imperial computers (including those in the computer rooms) will have Anaconda available to them through the Software Hub which will also allow the running of Jupyter Notebooks. You may also chose to install Anaconda on your personal machine by downloading the appropriate distribution from [here](https://www.anaconda.com/distribution/).

The presentation and the Notebooks may be found [here](https://github.com/coolernato/Profiling-and-Optimisation-in-Python/archive/refs/heads/master.zip) If you want to undertake the course on your own laptop, you may want to download them. However, you do not need to read them before attending.

### Self-Study Instructions

This course can also be completed through self-study from this repository. To do this, you will need to run the Jupyter Notebooks on your computer. The easiest way to do this is to ensure you have a Google account and are logged in on the your browser. Then, you can follow the links in the "Colab Links" section of this file in order from top-to-bottom in order to work through the notebooks. You will need to create a copy of the notebooks by clicking File>Save a Copy in Drive. This will create a copy of the notebook in your Google Drive and allow you to edit it to add notes, run examples and complete exercises. Underneath the code cells left for you to complete each exercise, there will be a code cell saying "Show Code". Clicking on this will show a sample solution to check your answer.

Alternatively, if you don’t have and don’t want to create a Google account, you may instead install Anaconda on your computer by downloading the appropriate distribution from [here](https://www.anaconda.com/distribution/). The presentation and the Notebooks may be downloaded [here](https://github.com/coolernato/Profiling-and-Optimisation-in-Python/archive/refs/heads/master.zip). You can then open the notebooks using Anaconda (open them in the order written in the "Colab Links" section below). You can edit these files to add notes, run examples or write your solutions to the exercises. Under the code cell left blank for you to write your solution to these exercises and the code cell below contains a sample solution for you to compare your answer to.

## Packages

Whether you attend a face-to-face or webinar version of this course or if you intend to self-study, if you intend to run the code in Anaconda, install the following packages in your Python environment before you attend to avoid having to do so during the course:

* ipykernel 
* pympler
* line_profiler
* numba

Alternatively, if you're familiar with requirements files, you may create an environment using the ```requirements.txt``` file in this repository.

## Colab Links

The following are links to the Notebooks which will open in Google Colab. To use these links, you will need to log into a Google account. Once you click the link, you may see a page saying "Connected apps". If Google Colaboratory is in the list, click it to open the notebook. If it's not, click "Connect more apps...", search for "Colab" and connect the app before selecting it.

* [Profiling](<https://colab.research.google.com/github/coolernato/Profiling-and-Optimisation-in-Python/blob/master/Profiling.ipynb>)
* [Algorithm Choice](<https://colab.research.google.com/github/coolernato/Profiling-and-Optimisation-in-Python/blob/master/Optimisation_ Algorithm Choice.ipynb>)
* [Mathematical Optimisation](<https://colab.research.google.com/github/coolernato/Profiling-and-Optimisation-in-Python/blob/master/Optimisation_ Mathematical Optimisation.ipynb>)
* [Caching](<https://colab.research.google.com/github/coolernato/Profiling-and-Optimisation-in-Python/blob/master/Optimisation_ Caching.ipynb>)
* [Optimising Loops](<https://colab.research.google.com/github/coolernato/Profiling-and-Optimisation-in-Python/blob/master/Optimisation_ Optimising Loops.ipynb>)
* [NumPy](<https://colab.research.google.com/github/coolernato/Profiling-and-Optimisation-in-Python/blob/master/Optimisation_ NumPy.ipynb>)
* [Parallelism](<https://colab.research.google.com/github/coolernato/Profiling-and-Optimisation-in-Python/blob/master/Optimisation_ Parallelism.ipynb>)
* [Compilation](<https://colab.research.google.com/github/coolernato/Profiling-and-Optimisation-in-Python/blob/master/Optimisation_Compilation.ipynb>)
* [Exercise](<https://colab.research.google.com/github/coolernato/Profiling-and-Optimisation-in-Python/blob/master/Optimisation_ Exercise.ipynb>)
* [Conclusion](<https://colab.research.google.com/github/coolernato/Profiling-and-Optimisation-in-Python/blob/master/Conclusion.ipynb>)

You do not need to look at these notebooks before the course unless you want to.

## Post-Course Follow-Up: ReCoDE Exemplar
The RCDS team has curated a collection of annotated [exemplar projects](https://imperialcollegelondon.github.io/ReCoDE-home/exemplars/) known as [ReCoDE](https://imperialcollegelondon.github.io/ReCoDE-home/) which demonstrate core research computing and data science principles applied to real problems. Each exemplar is a real project created by an Imperial student based on their research. Each exemplar is accompanied by detailed descriptions of how they work, and the design decisions taken when constructing the code. There are two Fortran exemplars:

* [**Monte Carlo for Fun**](https://recode-mcmcff.readthedocs.io/en/latest/): This exemplar Introduces Markov Chain Monte Carlo in Python, including a [discussion](https://recode-mcmcff.readthedocs.io/en/latest/learning/06%20Speeding%20It%20Up.html) of how to speed it up.
* [**Euler-Maruyama method**](https://imperialcollegelondon.github.io/ReCoDe-Euler-Maruyama/) This exemplar demosntrates how sovle stochastic differential equations in Python, including a [parallel implementation](https://imperialcollegelondon.github.io/ReCoDe-Euler-Maruyama/5-Parallel-Euler-Maruyama-Class/) using joblib.
* [**SPH Solver for 2D Navier-Stokes**](https://imperialcollegelondon.github.io/ReCoDE-SPH-solver-2D-NS/): This exemplar solves the Navier-Stokes equation in 2D using the SPH method. The code is written in C++ but includes a discussion of about [profiling](https://imperialcollegelondon.github.io/ReCoDE-SPH-solver-2D-NS/A3.Profiling/) and [optimisation](https://imperialcollegelondon.github.io/ReCoDE-SPH-solver-2D-NS/8.Efficient_Programming/).
