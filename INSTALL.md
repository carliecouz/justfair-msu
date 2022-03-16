# Project Installations
#### By Team JACT

   Below is the information for Tableau and Pip installations


## Tableau Instructions:

   Tableau Desktop needs to be purchased, but if you have a student email address you can access this product for free for 1 year. If this applies to you, make an account [here](https://www.tableau.com/academic/students). Once you have done that, download the software. After that, you can begin adding data and creating visualizations!
   
   **Note:** If you need a license to simply *view* and not *create*, you need **Tableau Reader**. This will give you access to open and view .twbx files.
   * [Download Tableau Reader](https://www.tableau.com/products/reader)

### Otherwise:

* Here is the link to download and purchase: 

    * [Purchase/Download Tableau](https://buy.tableau.com/?_ga=2.117269891.480212243.1645988593-1028061425.1643919312)

The first thing to do after downloading Tableau is connecting a dataset so you can begin to work with the data. Here is the link for all tutorials and the summary of connecting data to Tableau Desktop.

* [Connecting a Dataset to Tableau](https://help.tableau.com/current/pro/desktop/en-us/basicconnectoverview.html)
    * TLDR: Data connectors that are available to you are listed on the Connect pane, which is the left pane on the Start page. Select the data file you want to use and you're ready to go! 

## Jupyter Notebook Requirements/Installation Instructions:

####  Python installation tutorial if not already installed:

If you do not already have python installed, you will need to visit the website below. Once on the site, scroll to the bottom of the page and will see the section called files. There you can download python (Recommended 64-bit) for windows or MacOS. Next, you can move on to the pip installation information. 

**Note:**  Python version (updated to vers. 3.7) or later is needed

   * [Python Download](https://www.python.org/downloads/release/python-3102/)



#### Pip installation tutorial:

   First you want to search the computer for its command promt on windows or command terminal on Mac OS. 
   
Next,to install Jupyter using pip, we need to check if pip is updated in your system. Use the following command to update and install pip:


```python
python -m pip install --upgrade pip
```

Do this to make sure you have the required version of python for the project:


```python
python --version
```

    Python 3.8.8
    

#### Jupyter Notebook Pip install Instructions:

After updating pip and downloading python, type the following command in the terminal/promt to install Jupyter notebook:


```python
pip install jupyter
```

To launch Jupyter notebook type the following command : 


```python
jupyter notebook
```

That's it! You will be redirected to the juypter notebook page



#### Required Modules/Package Instructions within Jupyter Notebook :

This projects has 5 requirements

The next three require a pip installation along with importing within the juypter notebook you previuosly installed and opened.

* For numpy: Mathmatical arrays and mathmatical operations
      
In the cell (make sure the cell is set to code and not markdown), type in the two instructions below:
```
! pip install numpy
```
```
import numpy as np
```

* For Matplotlib: Data visualization and graphical plotting 

Open a new cell by clicking insert at top of page and select 'Insert cell below'. Make sure the cell is set to code and not markdown. Type in the two instructions below:
```
! pip install matplotlib
```
```
import  matplotlib.pyplot as plt
```

* For Pandas: Python Data Analysis Library

Open a new cell by clicking insert at top of page and select 'Insert cell below'. Make sure the cell is set to code and not markdown. Type in the two instructions below:
```
! pip install pandas
```
```
import pandas as pd
```

Next we will look at json and urllib.request: Transfer data as text over a netwokr and Extensible library for opening URLs

   * Take note that both are a built-in module, you do not need to install either of them with pip just import. Open a new cell by clicking insert at top of page and select 'Insert cell below'. Make sure the cell is set to code and not markdown. Type in the two instructions below:
```
import json
```
```
import urllib.request
```



You now have everything needed to view and explore our project!!
