# Fundamentals of Data Analysis Assessment  
***  
**Student Name:** Gillian Kane-McLoughlin  | **Student Number:** G00398258  


### Description  
This repository will contain all components of the assessment for the Fundamentals of Data Analysis module for Winter 2021.    
The contents are as follows:  
- **cao.ipynb** - this is the Jupyter notebook for the CAO points piece of the assessment  
- **pyplot.ipynb** - this is the Jupyter notebook for the pyplot piece of the assessment  
- README.md (which you are currently reading)  
- requirements.txt - text file listing all the Python modules & files used in the two notebooks  
- .gitignore (Python) file  
- Data folder containing data files used and generated over the course of completing this assessment  


### Software Information
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


### How to Run the Notebooks  
A Python environment is required to run the two Jupyter notebooks containing the bulk of the submission for this assessment. One possible suggestion is to first install Anaconda on your machine and then open the notebooks in Jupyter Lab as per the steps below:  
- Download Anaconda from ...  
- Install the package  
- Open the command line interface (CLI) on your machine - on Windows, open the Command Prompt tool by selecting Start, searching "cmd" and selecting it from the list. On a Mac, click the Launchpad icon in the Dock, type "Terminal" in the search field, then click Terminal  
- Navigate to the folder containing the Jupyter notebooks on the CLI using the cd (Change Directory) command  
- Once in the correct folder, enter "jupyter lab" to launch the program (note that although Jupter launches in your browser, it is running on your local machine)  
- Select the desired notebook from the left hand pane (cao.ipynb or pyplot.ipynb)  
- **Important** Select "Kernel" at the top of the notebook and click "Restart Kernel and Run All Cells"  
- To exit Jupyter once finished, close your browser, return to the CLI and click CTRL+C  


### What's in the Notebooks?  
CAO  
Pyplot  


### Results  
CAO points up... down...  
Can edit parameters in pyplot.ipynd and see the results...  


### CAO Notebook  
I found how to check the encoding declaration on the CAO website at w3.org [1] and used their Internationalization Checker [2] to confirm that I needed to decode the response with the expression line.decode('iso-8859-1').

22/10 - manually checked the cao courses CSV file and I'm getting 949 courses, so some are not being captured by the code Ian used in the lectures. Trying to capture all courses with a different RE compilation. Researching the Python documentation [3] to find out how to do this.

08.11 - checked the length of the 2021 course titles in Excel and the maximum seems to be 53 characters. I've refined my RE to match this and am happy now that it is pulling in the data I want and splitting it out into 4 columns, so I should be good to go.

# References  
[1] https://www.w3.org/International/questions/qa-html-encoding-declarations  
[2] http://validator.w3.org/i18n-checker/  
[3] https://docs.python.org/3/library/re.html  
[4] https://blog.finxter.com/python-regex-start-of-line-and-end-of-line/  
[5] https://www.datacamp.com/community/tutorials/python-regular-expression-tutorial  
[6] https://stackoverflow.com/questions/34091877/how-to-add-header-row-to-a-pandas-dataframe  