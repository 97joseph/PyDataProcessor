# PyDataProcessor

 Data pipeline

# PA 3: Association Analysis - Apriori Algorithm

**Student
Details**

Student Name and ID:

## Submission Instructions

Step 1: Rename this file to 'yourNetID_PA3.ipnyb' and the
report file to 'yourNetID_PA3.pdf'

Step 2: Upload all the document separately onto canvas

**Not in a zip file. 20 points will be deducted if you don't follow the
instruction** Note: Your submission should include ONLY the following
files:

* apriory.py  `<br>`
* yourNetID_PA3.ipynb  `<br>`
* yourNetID_PA3.pdf  `<br>`
* yourNetID_PA3.doc.
  `<br>`
* dataset.csv  `<br>`
* toyDS.csv
  `<br>`

## Programming Assignment Details Before you start: - Note

that this is a group assignment. - Be familiar with the algorithm and with the
dataset. - If you use external sources make sure that you cite them, and be
specific! - Make sure that your code is running before you upload your
submission file. TA will not debug your code. - Start early! For this
assignment, you will have to use: * Jupyter notebook, * the 'Random Shopping
cart' dataset [01], * and the Apriori Algorithm (apriory.py)[02]. Note that the
apriory.py file is modified to run with Python 3.

**Do Not
Delete the Above Cell  **

10 points will be deducted if the instructions are not
followed

![](file:///C:/Users/97jos/AppData/Local/Temp/msohtmlclip1/01/clip_image002.gif)

### Task 1: DataSet Preprocess

Before you start you need to modify your dataset
'dataset_group.csv' to look like the toyDS.csv. Each transaction is at one line
with a variable length. Discard the date attribute (1st attribute) from your
dataset. For example, in your dataset transaction#4 should look like:

cereals,juice,lunch meat,soda,toilet
paper,all-purpose

Export your modified dataset in a file named 'dataset.csv'.

Use pandas to Read and Print the first 7 transactions of
the 'dataset.csv'.

![](file:///C:/Users/97jos/AppData/Local/Temp/msohtmlclip1/01/clip_image003.gif)

![](file:///C:/Users/97jos/AppData/Local/Temp/msohtmlclip1/01/clip_image005.gif)

### Task 2: Run apriory.py and Evaluate Results

In this task, you have to find how you will be able to
execute and print apriory results by making use of only the apriory.py. In
other words "DO NOT USE ANY OTHER LIBRARY FOR TASK 2!!!".

(*) For those that are not familiar with python and coding
this could be a quite demanding task.

You will have to execute apriori algorithm "3"
times for different combinations of support and confidence. Print the results
of apriory for 'dataset.csv' by making use ONLY the provided methods.

Do not forget to add your reasoning (explain the result
outcome) at the top of each case in a nice and readable way.

You are allowed to use the python print method to print
your results. DO NOT add your reasoning as comments.

![](file:///C:/Users/97jos/AppData/Local/Temp/msohtmlclip1/01/clip_image006.gif)In [7]: print ('# # # # # # # # #
Code for Task 2, Case:1 # # # # # # # # #')  print ('Case 1 (minimum support=XX and minimum
confidence=YY)') print ('Case 1 Reasoning:') print ('Case 1 Output:')

# # # # # # # # #  Code for Task 2, Case:1 # # # # # # # #

Case 1 (minimum support=XX and minimum confidence=YY)

Case 1 Reasoning: Case 1 Output:

![](file:///C:/Users/97jos/AppData/Local/Temp/msohtmlclip1/01/clip_image007.gif)In [8]: print ('# # # # # # # # #
Code for Task 2, Case:2 # # # # # # # # #')  print ('Case 2 (minimum support=XX and minimum
confidence=YY)')  print ('Case 2 Reasoning:') print ('Case 2 Output:')

# # # # # # # # #  Code for Task 2, Case:2 # # # # # # # #

Case 2 (minimum support=XX and minimum confidence=YY)

Case 2 Reasoning: Case 2 Output:

![](file:///C:/Users/97jos/AppData/Local/Temp/msohtmlclip1/01/clip_image008.gif)In [9]: print ('# # # # # # # # #
Code for Task 2, Case:3 # # # # # # # # #')  print ('Case 3 (minimum support=XX and minimum
confidence=YY)') print ('Case 3 Reasoning:') print ('Case 3 Output:')

# # # # # # # # #  Code for Task 2, Case:3 # # # # # # # #

Case 3 (minimum support=XX and minimum confidence=YY)

Case 3 Reasoning:

Case 3 Output:

## Report

(separately in pdf/doc)

Take a small dataset (it can be any dataset). Show 3
support and confidence for the small dataset. Show the rules for all the 3
cases using the formula. Provide references where ever necessary.

# References

[01][https://www.ka](https://www.kaggle.com/acostasg/random-shopping-cart)[gg](https://www.kaggle.com/acostasg/random-shopping-cart)[le.com/acostas](https://www.kaggle.com/acostasg/random-shopping-cart)[g](https://www.kaggle.com/acostasg/random-shopping-cart)[/random-shoppin](https://www.kaggle.com/acostasg/random-shopping-cart)[g](https://www.kaggle.com/acostasg/random-shopping-cart)[-cart ](https://www.kaggle.com/acostasg/random-shopping-cart)[(](https://www.kaggle.com/acostasg/random-shopping-cart)[https://www.ka](https://www.kaggle.com/acostasg/random-shopping-cart)[gg](https://www.kaggle.com/acostasg/random-shopping-cart)[le.com/acostas](https://www.kaggle.com/acostasg/random-shopping-cart)[g](https://www.kaggle.com/acostasg/random-shopping-cart)[/randomshoppin](https://www.kaggle.com/acostasg/random-shopping-cart)[g](https://www.kaggle.com/acostasg/random-shopping-cart)[-cart)](https://www.kaggle.com/acostasg/random-shopping-cart)

[02][https://](https://github.com/asaini/Apriori)[g](https://github.com/asaini/Apriori)[ithub.com/asaini/Apriori
](https://github.com/asaini/Apriori)[(](https://github.com/asaini/Apriori)[https://](https://github.com/asaini/Apriori)[g](https://github.com/asaini/Apriori)[ithub.com/asaini/Apriori)](https://github.com/asaini/Apriori)

# Rubric

![](file:///C:/Users/97jos/AppData/Local/Temp/msohtmlclip1/01/clip_image009.gif)[02
points] - Student Details

[08 points] - Comply with submission instructions

[30 points] - DataSet Preprocess

[30 points] - Run apriory.py

[5 points] - Evaluate Results

[25 points] - Report
