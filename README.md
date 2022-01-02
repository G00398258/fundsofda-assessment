# Fundamentals of Data Analysis Assessment  
***  
**Student Name:** Gillian Kane-McLoughlin  | **Student Number:** G00398258  


### Description  
***
This repository will contain all components of the assessment for the Fundamentals of Data Analysis module for Winter 2021.  

The contents are as follows:  
- cao.ipynb - this is the Jupyter notebook for the CAO points piece of the assessment  
- pyplot.ipynb - this is the Jupyter notebook for the Pyplot piece of the assessment  
- this README.md file  
- requirements.txt - text file listing all the Python modules & libraries required to run the two notebooks  
- a .gitignore (Python) file  
- data folder containing files used and generated over the course of completing this assessment  


### Software Information
***
The code for this assignment was written in Python (version 3.8.8) and ran in Jupyter Lab.    

Jupyter Version:  
jupyter core : 4.7.1  
jupyter-notebook : 6.3.0  
qtconsole : 5.0.3  
ipython : 7.22.0  
ipykernel : 5.3.4  
jupyter client : 6.1.12  
jupyter lab : 3.0.14  
nbconvert : 6.0.7  
ipywidgets : 7.6.3  
nbformat : 5.1.3  
traitlets : 5.0.5   

Please see the requirements.txt file in this repository for information on the modules and libraries used.  


### How to Run the Notebooks 
***
A Python environment is required to run the two Jupyter notebooks containing the bulk of the submission for this assessment. To ensure that the notebooks run correctly, I would advise that you first install Anaconda on your machine, clone this repository to your device and then open and run the notebooks in Jupyter Lab as per the steps below:  
- Download Anaconda from https://www.anaconda.com/products/individual  
- Install the package  
- Clone this repository to your machine as per the steps outlined [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)    
- Open the command line interface (CLI) on your machine - on Windows, open the Command Prompt tool by selecting Start, searching "cmd" and selecting it from the list. On a Mac, click the Launchpad icon in the Dock, type "Terminal" in the search field, then click Terminal  
- Navigate to the folder where the repository was cloned (above) on the CLI using the cd (Change Directory) command  
- Once in the correct folder, enter command "jupyter lab" to launch the program (note that although Jupter launches in your browser, it is running on your local machine)  
- Select the desired notebook from the left hand pane (cao.ipynb or pyplot.ipynb)  
- **Important:** Select "Kernel" at the top of the notebook and click "Restart Kernel and Run All Cells"  
- To exit Jupyter once finished, close your browser, return to the CLI and enter command CTRL+C  


### What's in the Notebooks? 
***
**CAO Notebook**  
This Jupyter notebook contains an overview of how to load CAO points information from the CAO website into a pandas data frame, a detailed comparison of level 8 CAO points in 2019, 2020, and 2021 and some plots to enhance the viewer experience.    

The notebook is broken down into four sections:  
- Section 1: Loading the CAO Points into Pandas Dataframes  
- Section 2: Creating a Single CAO Points Dataframe Using Concat & Join  
- Section 3: Defining a Function to Perform the Analysis  
- Section 4: Analysing CAO Points  

The results observed in Section 4 show an increase in overall CAO points in 2021 compared to 2020, both in terms of the courses with the highest points and in both the mean and medium points ranges, as shown in the plots generated.  

Throughout the course of compiling this notebook I faced many difficulties, initially with loading the points into dataframes, but particularly in working with the CAO points data, as the information provided was quite messy and not easily comparable. I attempted to tidy this data up as much as possible, but I have to acknowledge that in doing this I did lose some data, resulting in a less accurate analysis. However, despite these difficulties, the analysis undertaken did show an overall increase in CAO points in 2021 across all the measurements observed, which is what I expected to see at the outset of this project.  

**Pyplot Notebook**  
This Jupyter Notebook provides a clear and concise overview of the Matplotlib.Pyplot package in Python, as well as an in-depth explanation of the following plots from the package:    
1. Pie Charts  
2. Scatter Plots  
3. Stack Plots  

In each case, I provide an explanation of what each of these plots are, what they are used for, the syntax and parameters required to plot them, and a practical example of each plot using real world data.  

A different style is used for each plot. Note that you can check what styles are available and change the styles on any of the plots using the following commands: 

``# To check what styles are available``  
``print(plt.style.available)``  

``# To change the style``  
``plt.style.use('style_name')``  

### References & Data Sources  
***
**_CAO Notebook_**  
[1] https://blog.finxter.com/python-regex-start-of-line-and-end-of-line/  
[2] https://www.datacamp.com/community/tutorials/python-regular-expression-tutorial  
[3] https://datatofish.com/dropna/  
[4] https://datatofish.com/replace-values-pandas-dataframe/  
[5] https://discuss.analyticsvidhya.com/t/getting-typeerror-not-supported-between-instances-of-str-and-float/18535/19  
[6] https://docs.python.org/3/library/re.html  
[7] https://www.geeksforgeeks.org/how-to-convert-floats-to-strings-in-pandas-dataframe/  
[8] https://www.geeksforgeeks.org/python-pandas-dataframe-drop_duplicates/  
[9] https://www.kite.com/python/answers/how-to-replace-column-values-in-a-pandas-dataframe-in-python  
[10] https://newbedev.com/pandas-converting-floats-to-strings-without-decimals  
[11] https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.replace.html  
[12] https://stackoverflow.com/questions/13035764/remove-pandas-rows-with-duplicate-indices  
[13] https://stackoverflow.com/questions/18172851/deleting-dataframe-row-in-pandas-based-on-column-value  
[14] http://validator.w3.org/i18n-checker/  
[15] https://www.w3.org/International/questions/qa-html-encoding-declarations  

_**CAO Points Data**_  
2019: http://www.cao.ie/index.php?page=points&p=2019  
2020: https://www.cao.ie/index.php?page=points&p=2020&bb=points  
2021: https://www.cao.ie/index.php?page=points&p=2021&bb=points  

**_Pyplot Notebook_**  
[1] https://dzone.com/articles/types-of-matplotlib-in-python  
[2] https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html  
[3] https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.pie.html  
[4] https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html    
[5] https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.scatter.html  
[6] https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.stackplot.html  
[7] https://matplotlib.org/stable/tutorials/introductory/pyplot.html  
[8] https://realpython.com/visualizing-python-plt-scatter/  
[9] https://stackoverflow.com/questions/6170246/how-do-i-use-matplotlib-autopct  
[10] https://stackabuse.com/matplotlib-stack-plot-tutorial-and-examples/  
[11] https://towardsdatascience.com/scatterplot-creation-and-visualisation-with-matplotlib-in-python-7bca2a4fa7cf  
[12] https://towardsdatascience.com/a-practical-summary-of-matplotlib-in-13-python-snippets-4d07f0011bdf  
[13] https://www.tutorialspoint.com/matplotlib/matplotlib_pie_chart.htm  
[14] https://www.geeksforgeeks.org/graph-plotting-in-python-set-1/  
[15] https://www.geeksforgeeks.org/matplotlib-pyplot-scatter-in-python/  
[16] https://www.geeksforgeeks.org/matplotlib-pyplot-stackplot-in-python/  
[17] https://www.geeksforgeeks.org/plot-a-pie-chart-in-python-using-matplotlib/  
[18] https://www.geeksforgeeks.org/pyplot-in-matplotlib/  
[19] https://www.geeksforgeeks.org/python-matplotlib-an-overview/  
[20] https://www.python-graph-gallery.com/stacked-area-plot/  
[21] https://www.w3schools.com/python/matplotlib_intro.asp  

_**Pie Chart Data**_  
https://covid-19.geohive.ie/pages/vaccinations  

_**Scatter Plot Data**_  
https://gist.githubusercontent.com/curran/a08a1080b88344b0c8a7/raw/639388c2cbc2120a14dcf466e85730eb8be498bb/iris.csv  

_**Stack Plot Data**_  
https://stats.beepbeep.ie/  

# End  
***