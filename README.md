# Machine-Learning-and-Statistics-GMIT2020
Repository for my Machine Learning and Statistics module assignments.
Ian Wafer

29/11/2019

G00376322

Assignments
This is an assignment set out by Ian Mcloughin for the Machine Learning Module of the Data Analytics higher diploma by GMIT. The 4 assignments given where as follows- 
1. October 5th, 2020: Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code shoul not depend on any module from the standard library1 or otherwise. You should research the task first and include references and a description of your algorithm.

2. November 2nd, 2020: The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example , stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.
|           | A   | B  | C   | D   | Total |
|-----------|-----|----|-----|-----|-------|
| White     | 90  | 60 | 104 | 95  | 349   |
| Blue      | 30  | 50 | 51  | 20  | 151   |
| No Collar | 30  | 40 | 45  | 35  | 150   |
| Total     | 150 | 15 | 200 | 150 | 650   |

3. November 16th, 2020: The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) . However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x) . Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence.

4. November 30th, 2020: Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.

The instructions issued can be found here- link

How to download this repository
Go to Github profile located here- link[https://github.com/IanWafer]
Click repository labeled IanWafer/Machine-Learning-and-Statistics-GMIT2020.
Click the download button or clone the repository to your own Github account.
How to run the code.
Install a python code client (Anaconda recommended. See here for installer- link[https://www.anaconda.com/])
Run a command line client (cmder recommended. See here for installer- link[https://cmder.net/])
Ensure you are in the correct directory where .ipynb is located using the cd command to navigate.
To open the descriptions and code type Jupyter Notebook in the command window.
Your default browser window should be open now in the Jupyter interface. Select Tasks For Machine Learning & Statistics Module to open the file.
To run all of the code click the cell button from the menu at the top of the browser window and select Run All.
To test any of the scripts within the notebook double click the cell to enter the edit mode and press shift+enter to run the code.