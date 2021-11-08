# fundsofda-assessment

This repository will contain all components of the assessment for the Fundamentals of Data Analysis module, due on 19th December 2021.



## CAO Notebook
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