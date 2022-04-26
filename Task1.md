# Task-1

Following are the few subtasks that will help you run through the python essentials for getting started with AI and ML.

## Q1
File Handling is one of the basic important task when it comes to building machine learning models or neural networks. Building a good model always starts with finding datasets and processing it, for which, file handling acts as a stepping stone.

<br>

#### Write a python program that reads the contents from the given file 'onelinefile.txt'. The file contains a single line which is of the format (int)(string)(float)(string) repeatedly. For e.g. 
```
1Aaa3.5Maths2Bbb4.2Physics3Ccc7.62Chemistry
```
<br>

#### Your main task is to split the contents of the given file based on their format and write it into a .csv file say 'Filename2.csv'. For e.g. the above txt file should be converted into a csv file such that the contents look like this:

```csv
1,Aaa,3.5,Maths
2,Bbb,4.2,Physics
3,Ccc,7.62,Chemistry
```
<br>

### Contents of 'onelinefile.txt'
```
1Aaa3.5Maths2Bbb4.2Physics3Ccc7.62Chemistry4Ddd9.55Biology5Eee4.0Social6Fff7.6English7Ggg3.111Maths8Hhh9.99Physics9Iii1.23Civics
```

<br>

## Q2
### Data formatting
Python libraries represent missing numbers as nan which is short for "not a number". Most libraries (including scikit-learn) will give you an error if you try to build a model using data with missing values. One of the common solution to get around this issue is to impute or fill in the missing value with a number or value of same format. From the given dataset, find the missing values(Nan/NA/-/Nil) and change those values into an appropriate number.

> [Dataset link](https://github.com/cognizance-amrita/AI-Tasks/blob/main/Q2-Dataset.csv)

<br>

## Q3
#### Read the file 'about.txt' and find the words with atleast 6 letters and the most frequently used word.

<br>

Contents of the file 'about.txt':
```
Python has tools for almost every aspect of scientific computing. The Bank of America uses Python to crunch its financial data and Facebook looks upon the Python library Pandas for its data analysis. While there are many libraries available to perform data analysis in Python, here are a few: NumPy, SciPy, Pandas and Matplotlib. 
```

<br>

## Q4
#### Given food name, price, rating(out of 5) and their datatypes, create a structured array using NumPy and sort the array on rating

> [Dataset link](https://github.com/cognizance-amrita/AI-Tasks/blob/main/Q4-Dataset.csv)

<br>

## Q5
#### Let x be the size of houses in sq feet. x can take values between 700 to 2400 and is a multiple of 10. The price of the house (y) is found by the equation y = 10\*x^2 + 2\*x.  
#### Pass the values into a .csv file and plot a graph of the prices against the size of houses. Provide appropriate labels for the axes.


<br><br>

## __Submission Link__
https://forms.gle/Vn5LUBo4k62FFFez6
