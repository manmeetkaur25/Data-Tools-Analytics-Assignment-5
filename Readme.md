# PROJECT TITLE
Durham College: Data Tools Analytics- Assignment 5
## DESCRIPTION
The aim of the project is to **create a function in Python to calculate the distribution of channel type from the top 1000 records** of the 4000 records in a youtube dataset.

Moreover, we will then **load the top 1000 records of the original 4000 into a separate CSV file called ‘export.csv’** and 
hence, this project will also highlight how to export new csv files using Python codes.
## GETTING STARTED
### Dependencies
* Anaconda navigator
* Jupyter notebook
* Python Libraries: Pandas; NumPy; Seaborn; Matplotlib
### Installing
Original dataset: youtube_dataset[csv file]
## EXECUTION
* The youtube_dataset was imported in jupyter notebook by setting the file path and the variable 'df' is assigned for reading the file. The head function is called to have a preview of the dataset.
* We assigned the variable ‘dataframe’ to read and store **top 1000 records** with head function.
* The next step is defining the function ‘dist_func’ to the dataset with 1000 records(dataframe).
* Value_counts() function counts channel type column and stores it in variable ‘a’. The parameter ‘a’ is then called out to print the output of the function.
* The next code is to extract the top 1000 records in a csv file named ‘export.csv’ Note: We have used index = False and header = True for retaining the header same as the original dataset and to make sure any other index is not added.
## AUTHOR
Manmeet Kaur
### Version
0.1
## Acknowledgements
Durham College-Graduate Certificate in Data Analytics for business decision making
Course: Data Tools Analytics
